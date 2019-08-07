# useKeyPress

> React hook to detect key press

> **Note:** This is using the new [React Hooks API](https://reactjs.org/docs/hooks-intro.html)
>
> You'll need to install `react`, `react-dom`, etc at `^16.8.0` or above

## Install

```sh
yarn add @alobato/use-key-press
```

## Usage

```js
import useKeyPress from '@alobato/use-key-press'
...
const escPress = useKeyPress('Escape') 
if (escPress) handleExit()
```
