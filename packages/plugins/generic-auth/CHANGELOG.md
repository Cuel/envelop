# @envelop/generic-auth

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

### Patch Changes

- 9f63dac: Add `skipAuth` directive to `protect-all` auth option

## 1.0.1

### Patch Changes

- 546db6c: Fix issue with inaccessible directiveNode

## 1.0.1

### Patch Changes

- Fix issue with inaccessible directiveNode

## 1.0.0

### Major Changes

- 40bc444: v1 major release for envelop packages

## 0.2.0

### Minor Changes

- 83b2b92: Extend plugin errors from GraphQLError.

## 0.1.1

### Patch Changes

- 28ad742: Improve TypeScript types

## 0.1.0

### Minor Changes

- eb6f53b: ESM Support for all plugins and envelop core

## 0.0.2

### Patch Changes

- 5fc65a4: Improved type-safety for internal context

## 0.0.1

### Patch Changes

- 55a13bd: NEW PLUGIN!
