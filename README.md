# eslint-config-sunset-nodejs

Default eslint configuration for nodejs services

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint eslint-plugin-import eslint-plugin-node eslint-plugin-promise eslint-config-google --save-dev
```

Next, install `eslint-config-sunset-nodejs`:

```
$ npm i git+https://git@github.com/SunsetRiders/eslint-config-sunset-nodejs.git --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must
also install `eslint-config-sunset-nodejs` globally.

## Usage

Add `sunset-nodejs` to the extends section of your `.eslintrc` configuration
file. You can omit the `eslint-config-` prefix:

```json
{
    "extends": [
        "sunset-nodejs"
    ]
}
```
