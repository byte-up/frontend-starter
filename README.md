# Frontend starter

## Detailed Content

- Typescript
- React JS (16.9+ - [github :link:](https://github.com/facebook/react))
- Redux (_as you application grows managing state will be a serious concern, save pain with Redux_)
- React-Redux (_Redux is not specific to ReactJS, you could easily use it with Angular2 for instance_)
- redux-devtools-extension ([github :link:](https://github.com/zalmoxisus/redux-devtools-extension#redux-devtools-extension))
- connected-react-router 4 ([github :link:](https://github.com/supasate/connected-react-router))
- react-router (4.x- [github :link:](https://github.com/reactjs/react-router))
- Bootstrap (4.x - [github :link:](https://github.com/twbs/bootstrap))
- reactstrap ([github :link:](https://github.com/reactstrap/reactstrap))
- loadable-components - work with reactsnap for better static website performance - (_stuck to pre v2.2.3+ breakings changes, waiting for a new solution see [PR](https://github.com/stereobooster/react-snap/pull/338/commits/adf107b4bff212a854a93e2d90f89d369433a807)_)
- font-awesome ([github :link:](https://github.com/FortAwesome/Font-Awesome))
- animate.css ([github :link:](https://github.com/daneden/animate.css))
- classnames ([github :link:](https://github.com/JedWatson/classnames))
- react-motion ([github :link:](https://github.com/chenglou/react-motion))
- Webpack 4.x ([github :link:](https://github.com/webpack/webpack))
- axios ([github :link:](https://github.com/mzabriskie/axios) _Why: simple, complete, isomorphic ..._)

**Tool chain:**

- Typescript
- eslint
- webpack 4
- hot reload
- loaders
  - `ts` / `tsx`
  - css
  - json
  - images formats
  - svg and fonts formats

**tests:**

- Jest
- enzyme

## Usage

### Install

```bash
# from root directory:
cd front && yarn install
```

### bundle dev mode (_+ redux-devtools_)

```bash
# from root directory:
cd front && yarn run dev
```

### dev : hot reload mode (_+ redux-devtools_)

```bash
# from root directory:
cd front && yarn run start
```

### tests

```bash
# from root directory:
cd front && yarn run test
```

### bundle production mode

```bash
# from root directory:
cd front && yarn run prod
```