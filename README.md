# eslint-config-platzi

## Installation

The default export contains all default Airbnb ESLint rules and the configurations recommended by the Platzi team.

Install the package:

 ```sh
npm install eslint-config-platzi --save-dev
```

## Usage

Now add the config to either your `package.json`:

```json
{
  "eslintConfig": {
    "extends": "eslint-config-platzi"
  }
}
```

to your `.eslintrc`:

```json
{
  "extends": "eslint-config-platzi"
}
```

 or `.eslintrc.js`:

```js
module.exports ={
  "extends": "eslint-config-platzi"
}
```

## LICENCE

[MIT](LICENCE)