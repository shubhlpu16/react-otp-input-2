# react-otp-input-2

> Updated  version of react-otp-input with bug fixes.

[![NPM](https://img.shields.io/npm/v/react-otp-input-2.svg)](https://www.npmjs.com/package/react-otp-input-2) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save react-otp-input-2
```

## Usage

```jsx
import React, { Component } from 'react';
import OtpInput from 'react-otp-input';

export default class App extends Component {
  state = { otp: '' };

  handleChange = (otp) => this.setState({ otp });

  render() {
    return (
      <OtpInput
        value={this.state.otp}
        onChange={this.handleChange}
        numInputs={6}
        separator={<span>-</span>}
      />
    );
  }
}
```

## License

MIT © [shubhlpu16](https://github.com/shubhlpu16)
