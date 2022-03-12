# milingui

> buttons with different styles

[![NPM](https://img.shields.io/npm/v/milingui.svg)](https://www.npmjs.com/package/milingui) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save milingui
```

## Usage

```jsx
import React, { Component } from 'react'

import MyComponent from 'milingui'
import 'milingui/dist/index.css'

class Example extends Component {
  render() {
    return (
      <>
        <Button type='primary' text='Primary Button 😄' />
        <Button type='dashed' text='Dashed Button 😄' />
        <Button type='link' text='Link Button 😄' />
      </>
    )
  }
}
```

## License

MIT © [elifdiril](https://github.com/elifdiril)
