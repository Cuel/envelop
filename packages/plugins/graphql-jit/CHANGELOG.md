# @envelop/graphql-jit

## 1.3.1

### Patch Changes

- b1a0331: Properly list `@envelop/core` as a `peerDependency` in plugins.

  This resolves issues where the bundled envelop plugins published to npm had logic inlined from the `@envelop/core` package, causing `instanceof` check of `EnvelopError` to fail.

- Updated dependencies [b1a0331]
  - @envelop/core@1.6.1

## 1.3.0

### Minor Changes

- 090cae4: GraphQL v16 support

## 1.2.0

### Minor Changes

- 04120de: add support for GraphQL.js 16
- 3bb3df0: feat(graphql-jit): subscription support

## 1.1.1

### Patch Changes

- abae5a2: Allow `enableIf` to return Promise

## 1.1.0

### Minor Changes

- cc71515: Added `enableIf` config flag to allow flexibility on jit executor

## 1.0.0

### Major Changes

- 40bc444: v1 major release for envelop packages

## 0.2.1

### Patch Changes

- d82e2d0: Adjustments for new TypeScript beta version
- 28ad742: Improve TypeScript types

## 0.2.0

### Minor Changes

- eb6f53b: ESM Support for all plugins and envelop core

## 0.1.1

### Patch Changes

- e7f43f4: Fix issues with executor and caching

## 0.1.0

### Minor Changes

- 2fba0b4: Initial version bump

## 0.0.2

### Patch Changes

- b1333b0: Initial packages release
