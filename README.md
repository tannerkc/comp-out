# comp-out

> Simple React Component Library

[![NPM](https://img.shields.io/npm/v/comp-out.svg)](https://www.npmjs.com/package/comp-out) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save comp-out
```

## Usage

```jsx
import React, { Component } from 'react'

import { CompCard as Card, CompAppointment as Appt, CompProfile as Profile} from 'comp-out'
import 'comp-out/dist/index.css'

class App extends Component {
  render() {
    return (
        <Card
          img = 'example.png'
          title = 'Hello World'
          content = 'lorum ipsum'
        />

        <Appt
          time = '12 Jan 2020, 8am - 10am'
          requesterImg = 'example.png'
          requesterName = 'Vision'
          requesterTitle = 'Synthozoid'
        />

        <Profile
          img = 'example.png'
          name = 'Vision'
          title = 'Synthozoid'
        />
      )
  }
}
```

## License

MIT © [tannerkc](https://github.com/tannerkc)
