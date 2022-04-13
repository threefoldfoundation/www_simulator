# WWW Simulator

## Contents
- [Build new release](Build-new-release)

### Build new release

1. Clone weblets

```sh
git clone git@github.com:threefoldtech/grid_weblets.git
```
```sh
cd grid_weblets
```

2. Install dependencies

```sh
yarn install
```
```sh
cd easy-docs && yarn install
```

3. Build Web components (weblets)
```sh
yarn build:app
```

4. Clone WWW_Simulator
```sh
git clone git@github.com:threefoldtech/www_simulator.git
```

5. Repleace `farmingcalculator.wc.js` with the one from `grid_weblets/docs/build/elements/farmingcalculator.wc.js`

