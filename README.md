# grommet-hpe-css

Created to use [grommet](https://github.com/grommet/grommet) with [create-react-app](https://github.com/facebookincubator/create-react-app). Grommet needs `scss` preprocessor and unless you `eject` there is no way to easily use with `create-react-app`.

## Usage
### As is
```bash
npm install --save grommet-hpe-css
# or
yarn install --save grommet-hpe-css
```

in `App.js`
```js
import '../node_modules/grommet-hpe-css'
```

### Custom
You can also fork this repo, make changes like including a different default grommet style in `index.scss` or tweaking grommet scss variables.

grommet-hpe-css using grommet version 1.11.0

#### Production
Update the name in `package.json`, run `npm build`, then run `npm publish`

#### Development
Use `npm link`  to link your fork to your main repo and `npm start` to watch for changes.
