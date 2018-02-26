# @yours/nyc-config

Handy default configuration for instrumenting @Yoursco projects
with test coverage using [nyc](https://github.com/istanbuljs/nyc).

First install the dependencies:

`yarn add --dev yoursco/yours-nyc-config`

Then write a `.nycrc` that looks something like this:

```json
{
  "extends": "yoursco/yours-nyc-config"
}
```
