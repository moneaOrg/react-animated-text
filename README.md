# react-animated-text

## Installation

```shell
npm install --save react-animated-text
```

## Documentation

Full docs along with examples can be found here:<br />
[Coming soon...](http://www.react-animated-text.com)

### A couple quick examples

```javascript
import React from 'react';
import { Wave } from 'react-animted-text';

const ExampleOne = () => (
  <Wave
    text="EXAMPLE TEXT"
    waveIteration="infinite"
    effect="stretch"
    effectChange={1.5}
);
```

```javascript
import React from 'react';
import { Random } from 'react-animted-text';

const ExampleTwo = () => (
  <Random
    text="EXAMPLE TEXT"
    effect="jump"
    effectChange={2.0}
);
```

## Licence

[MIT](LICENCE) - Copyright (c) 2018, Greg Burger
