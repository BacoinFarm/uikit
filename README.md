# 🥞 Bacoin UIkit

[![Version](https://img.shields.io/npm/v/@bacoin/uikit)](https://www.npmjs.com/package/@bacoin/uikit) [![Size](https://img.shields.io/bundlephobia/min/@bacoin/uikit)](https://www.npmjs.com/package/@bacoin/uikit)

Bacoin UIkit is a set of React components and hooks used to build pages on Bacoin's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @bacoin/uikit`

## Setup

### Theme

Before using Bacoin UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@bacoin/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@bacoin/uikit'
...
<ResetCSS />
```
