## `@envelop/graphql-jit`

This plugins replaces the original `execute` of GraphQL with [`graphql-jit`](https://github.com/zalando-incubator/graphql-jit).

## Getting Started

```
yarn add @envelop/graphql-jit
```

## Usage Example

```ts
import { envelop } from '@envelop/core';
import { useGraphQlJit } from '@envelop/graphql-jit';

const getEnveloped = envelop({
  plugins: [
    // ... other plugins ...
    useGraphQlJit(
      {
        // your compiler options here. See https://github.com/zalando-incubator/graphql-jit#compiledquery--compilequeryschema-document-operationname-compileroptions
      },
      {
        onError: (e: Error) => { ... } // custom error handler
      }
    ),
  ],
});
```

## Conditional Execution

If you wish to conditionally use the JIT executor based on the incoming request, you can use `enableIf` config flag and return a `boolean` based on the `ExecutionArgs`:

```ts
import { envelop } from '@envelop/core';
import { useGraphQlJit } from '@envelop/graphql-jit';

const getEnveloped = envelop({
  plugins: [
    // ... other plugins ...
    useGraphQlJit(
      {
        // your compiler options here. See https://github.com/zalando-incubator/graphql-jit#compiledquery--compilequeryschema-document-operationname-compileroptions
      },
      {
        enableIf: executionArgs => executionArgs.contextValue.shouldUseJit,
      }
    ),
  ],
});
```

## Notes

You can find more details here: https://github.com/zalando-incubator/graphql-jit
