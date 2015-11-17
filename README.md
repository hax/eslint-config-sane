# Sane - ESLint Shareable Config

**An ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for [JavaScript Standard Style](https://github.com/feross/standard)**

## Install

```sh
npm install eslint-config-sane
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the JavaScript Standard Style shareable config, first run this:

```bash
npm install eslint-config-sane
```

Then, add this to your .eslintrc file:

```json
{
  "extends": "standard"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.

## License

![WTFPL](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-1.png) © 2015 [HE Shi-Jun](http://johnhax.net/).
