# Generic function

This project contains a few simple generic functions.

## Installation

```bash
npm install --save @gmjs/generic-functions
```

## API

```ts
function emptyFn(): void;
function identityFn<T>(value: T): T;
function alwaysTruePredicate(): boolean;
function alwaysFalsePredicate(): boolean;
```
