# Rc-UI

UI component library built with React Hooks.

## Install

```bash
# use npm
npm install @ks/rc-ui

# or use yarn
yarn add @ks/rc-ui
```

## Usage

```js
// introduce components on demand
import { Button } from '@ks/rc-ui';

const App = () => <Button type="primary">CLICK ME</Button>;

// and import style manually
import '@ks/rc-ui/dist/index.css';
```

## Development scripts

```bash
# verify the code format and syntax in the project.
yarn lint

# launches the test runner in the interactive watch mode.
yarn test

# write a more friendly commit message
yarn commit
```

## License

[MIT](https://github.com/storybookjs/storybook/blob/master/LICENSE)
