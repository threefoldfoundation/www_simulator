# WWW Simulator

## Contents

- [Build new release](#Build-new-release)

### Build new release

1. Clone Farming calculator weblet

```sh
git clone https://github.com/threefoldtech/tf-farming-calculator.git
```

```sh
cd tf-farming-calculator
```

2. Install dependencies

```sh
yarn install
```

3. Build Web components (weblets)

```sh
yarn build
```

4. Clone WWW_Simulator

```sh
git clone git@github.com:threefoldtech/www_simulator.git
```

5. Repleace `farmingcalculator.wc.js` with the one from `tf-farming-calculator/dist/farmingcalculator.wc.js`
