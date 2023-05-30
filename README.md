Reference: https://levelup.gitconnected.com/building-a-react-component-library-e4eb7985ff5d


npm install -g create-react-library

create-react-library header-custom

-- Build 
npm build

-- Login with NPM Credentials
npm login

-- Publish code to NPM
npm publish 


Published Location: https://www.npmjs.com/package/header-custom

Compiled files for reference: https://github.com/bpolimetla/header-custom/tree/main/dist
Same can be deployed to web server or CDN and share those details with clients

#-------------------------
Run these commands in demo folder
npm install -g live-server // Install globally via npm
live-server                // Run in the html's directory



# header-custom

> custom header library

[![NPM](https://img.shields.io/npm/v/header-custom.svg)](https://www.npmjs.com/package/header-custom) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save header-custom
```

## Usage

```jsx
import React, { Component } from 'react'

import MyComponent from 'header-custom'
import 'header-custom/dist/index.css'

class Example extends Component {
  render() {
    return <MyComponent />
  }
}
```

## License

MIT © [bpolimetla](https://github.com/bpolimetla)
