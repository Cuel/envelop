# @envelop/apollo-tracing

## 1.2.1

### Patch Changes

- b1a0331: Properly list `@envelop/core` as a `peerDependency` in plugins.

  This resolves issues where the bundled envelop plugins published to npm had logic inlined from the `@envelop/core` package, causing `instanceof` check of `EnvelopError` to fail.

- Updated dependencies [b1a0331]
  - @envelop/core@1.6.1

## 1.2.0

### Minor Changes

- 090cae4: GraphQL v16 support

## 1.1.0

### Minor Changes

- 04120de: add support for GraphQL.js 16

## 1.0.3

### Patch Changes

- 452af8f: Update dependencies of graphql-tools to latest

## 1.0.2

### Patch Changes

- 94db02d: Update usage of plugins to use the correct `isAsyncIterable` and new helper `handleStreamOrSingleExecutionResult`

## 1.0.1

### Patch Changes

- 8021229: fix ESM graphql import

## 1.0.0

### Major Changes

- 40bc444: v1 major release for envelop packages

## 0.2.1

### Patch Changes

- 28ad742: Improve TypeScript types

## 0.2.0

### Minor Changes

- eb6f53b: ESM Support for all plugins and envelop core

## 0.1.0

### Minor Changes

- 2fba0b4: Initial version bump

## 0.0.2

### Patch Changes

- b1333b0: Initial packages release

## 0.0.1

### Patch Changes

- c499ae8: First bump as envelop
- 2cfc726: Fixes
