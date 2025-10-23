# Number Formatter

[![publish](https://github.com/balboacodes/number-formatter/actions/workflows/publish.yml/badge.svg)](https://github.com/balboacodes/number-formatter/actions/workflows/publish.yml)

## About

Number Formatter is a TypeScript port of [Laravel's](https://github.com/laravel/laravel) number helpers. It aims to bring a small dose of the expressive and elegant syntax Laravel is known for to the TypeScript community. It has no third-party dependencies, is fully-typed, and includes all of Laravel's tests ported to [Vitest](https://github.com/vitest-dev/vitest).

## Installation

`npm i @balboacodes/number-formatter`

## Usage

Number Formatter consists of one class, `NumberFormatter`, that provides methods via a static interface.

```ts
import { NumberFormatter } from '@balboacodes/number-formatter';

const number = NumberFormatter.abbreviate(1000);

// 1K
```

## Documentation

Documentation for the methods can be found on Laravel's [Helpers documentation](https://laravel.com/docs/12.x/helpers#numbers-method-list) page. Just translate PHP's syntax to JS like shown above.

## Related

If you like this package and are looking for other helpers, be sure to check out our [other packages](https://www.npmjs.com/~balboacodes).
