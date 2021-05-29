# react-dark-mode-toggle

A super cutesy dark mode toggle button for [React](https://github.com/facebook/react). Inspired by [overreacted.io](https://overreacted.io/).

<a href="#badge">
    <img alt="code style: prettier" src="https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square"></a>

<p align="center">
  <img src="./assets/title.gif" width="300" height="300" />
</p>

## 🚀 Getting Started

##### [`npm`]():

```bash
npm i react-dark-mode-toggle
```

##### [`yarn`]():

```bash
yarn add react-dark-mode-toggle
```

## ✨ Usage

#### TypeScript

```typescript jsx
import React from "react";
import { DarkModeToggle } from "react-dark-mode-toggle";

export const SomeComponent = () => {
  const [isDarkMode, setIsDarkMode] = React.useState<boolean>(false);
  
  return (
    <DarkModeToggle onChange={setIsDarkMode} checked={isDarkMode} />
  );
};
```

#### JavaScript

```javascript
import React from "react";
import { DarkModeToggle } from "react-dark-mode-toggle";

export const SomeComponent = () => {
  const [isDarkMode, setIsDarkMode] = React.useState(false);
  
  return (
    <DarkModeToggle onChange={setIsDarkMode} checked={isDarkMode} />
  );
};
```

## 📌 Props

Prop                  | Type     | Default                   | Required
--------------------- | -------- | ------------------------- | --------
`onChange`|func|`value => null`|No
`checked`|boolean|`false`|No
`size`|number (defaults to `px`) or a string containing a number+unit (e.g `"10px"`, `"2em"`, `"4.5rem"`, `"100%"`, etc). These units may also have a space between them (e.g. `"10 px"`, `"2 em"`, etc).|`85`|No
`speed`|number|`1.3`|No
`className`|string|`null`|No|

> **Note**, this is _not_ a dark mode theme implementation; it's just a button! You'll need to mix this with a management solution such as [use-dark-mode](https://github.com/donavon/use-dark-mode).

## ✌️ License
[MIT](https://opensource.org/licenses/MIT)

<p align="center">
  <a href="https://www.buymeacoffee.com/cawfree">
    <img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy @cawfree a coffee" width="232" height="50" />
  </a>
</p>


