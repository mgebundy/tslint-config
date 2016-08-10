## tslint-ssense-config

The [tslint](http://palantir.github.io/tslint/) config we use at **SSENSE** for all TypeScript projects. It's a combination of base rules provided by tslint as well as rules from [tslint-microsoft-contrib](https://github.com/Microsoft/tslint-microsoft-contrib).

#### Installation

1. Install the package
    * `npm install --save-dev tslint @ssense/tslint-ssense-config`
2. Create a file named *tslint.json* in your project root
    * `touch tslint.json`
3. Add the contents referenced in the section below to *tslint.json*
4. Run **tslint**
    * `./node_modules/.bin/tslint`

#### tslint.json

```json
{
    "extends": "@ssense/tslint-config"
}
```
