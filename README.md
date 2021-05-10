# 🥞 Frogg UIkit

Frogg UIkit is a set of React components and hooks used to build pages on Frogg's apps. It also contains a theme file for dark and light mode.

## Setup

### Theme

Before using Frogg UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@froggswap/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@froggswap/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.
