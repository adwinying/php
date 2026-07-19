# php

Fetches PHP binaries from [crazywhalecc/static-php-cli](https://github.com/crazywhalecc/static-php-cli) and organize them into Github Releases. No fumbling with dependencies, no builds required.

## What's in the box?

This repo uses [crazywhalecc/static-php-cli](https://github.com/crazywhalecc/static-php-cli?tab=readme-ov-file#direct-download) [bulk](https://dl.static-php.dev/static-php-cli/bulk/) variant for macOS and Linux, and [spc-max](https://dl.static-php.dev/static-php-cli/windows/spc-max/) variant for Windows to ensure max compatibility.

## Usage

I recommend using [mise-en-place](https://github.com/jdx/mise) to install the binaries:

```bash
mise use github:adwinying/php@8.1
```
