# prettier-config-joshingmachine

A shareable version of my Prettier configuration file.

**Note:** This package is a work in progress and likely won't work until 1.x.x

## Usage

### Per project
Install the package and its peer depedency `prettier` as dev dependencies. 

```bash
# npm
npm install prettier-config-joshingmachine prettier --save-dev --save-exact
# yarn
yarn add prettier-config-joshingmachine prettier --dev --exact
```

Then create a new file named `.prettierrc.js` or `prettier.config.js` to the relevant directory/directories of your project and add the following line.

```js
module.exports = require('prettier-config-joshingmachine')
```

Now Prettier will apply the options in this configuration file when used on any file that resolves to it [as explained in the Prettier docs](https://prettier.io/docs/en/configuration.html).

> The configuration file will be resolved starting from the location of the file being formatted, and searching up the file tree until a config file is (or isn't) found.


### Global
Todo
