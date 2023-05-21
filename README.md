# ESLint-Security-Rules
Security Rules created for the ThunderHorse plugin in the context of our Master Thesis.  In collaboration with Fabian Harlang.
# ThunderHorse plugin:
https://www.npmjs.com/package/eslint-plugin-thunderhorse?activeTab=readme
# Rules path:
lib/rules
# eslint-plugin-react-weblint

<h2>Installation</h2>

```npm i eslint-plugin-secure-access```

<h2>Recommended configuration: </h2>

```
module.exports = {
    "env": {
        "browser": true,
        "es2021": true
    },
    "extends": ["plugin:secure-access/recommended"],
    "overrides": [
    ],
    "parserOptions": {
        "ecmaVersion": "latest",
        "sourceType": "module"
    },
    "plugins": ["secure-access"],
    "rules": {
    }
};

