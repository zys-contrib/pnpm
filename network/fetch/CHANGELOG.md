# @pnpm/fetch

## 1000.2.3

### Patch Changes

- Updated dependencies [1a07b8f]
- Updated dependencies [1ba2e15]
  - @pnpm/types@1000.7.0
  - @pnpm/fetching-types@1000.2.0
  - @pnpm/core-loggers@1001.0.2

## 1000.2.2

### Patch Changes

- 09cf46f: Update `@pnpm/logger` in peer dependencies.
- Updated dependencies [09cf46f]
- Updated dependencies [5ec7255]
  - @pnpm/core-loggers@1001.0.1
  - @pnpm/types@1000.6.0

## 1000.2.1

### Patch Changes

- Updated dependencies [8a9f3a4]
- Updated dependencies [5b73df1]
  - @pnpm/core-loggers@1001.0.0
  - @pnpm/logger@1001.0.0
  - @pnpm/types@1000.5.0

## 1000.2.0

### Minor Changes

- 750ae7d: Export `CreateFetchFromRegistryOptions` type.

### Patch Changes

- Updated dependencies [750ae7d]
- Updated dependencies [750ae7d]
  - @pnpm/types@1000.4.0
  - @pnpm/core-loggers@1000.2.0

## 1000.1.6

### Patch Changes

- Updated dependencies [5f7be64]
- Updated dependencies [5f7be64]
  - @pnpm/types@1000.3.0
  - @pnpm/core-loggers@1000.1.5

## 1000.1.5

### Patch Changes

- Updated dependencies [a5e4965]
  - @pnpm/types@1000.2.1
  - @pnpm/core-loggers@1000.1.4

## 1000.1.4

### Patch Changes

- Updated dependencies [8fcc221]
  - @pnpm/types@1000.2.0
  - @pnpm/core-loggers@1000.1.3

## 1000.1.3

### Patch Changes

- Updated dependencies [b562deb]
  - @pnpm/types@1000.1.1
  - @pnpm/core-loggers@1000.1.2

## 1000.1.2

### Patch Changes

- Updated dependencies [9591a18]
  - @pnpm/types@1000.1.0
  - @pnpm/core-loggers@1000.1.1

## 1000.1.1

### Patch Changes

- Updated dependencies [516c4b3]
  - @pnpm/core-loggers@1000.1.0

## 1000.1.0

### Minor Changes

- b0f3c71: The `fetch` function accepts a `method` option now.

### Patch Changes

- Updated dependencies [b0f3c71]
  - @pnpm/fetching-types@1000.1.0

## 8.0.7

### Patch Changes

- Updated dependencies [d500d9f]
  - @pnpm/types@12.2.0
  - @pnpm/core-loggers@10.0.7

## 8.0.6

### Patch Changes

- Updated dependencies [7ee59a1]
  - @pnpm/types@12.1.0
  - @pnpm/core-loggers@10.0.6

## 8.0.5

### Patch Changes

- Updated dependencies [cb006df]
  - @pnpm/types@12.0.0
  - @pnpm/core-loggers@10.0.5

## 8.0.4

### Patch Changes

- Updated dependencies [0ef168b]
  - @pnpm/types@11.1.0
  - @pnpm/core-loggers@10.0.4

## 8.0.3

### Patch Changes

- Updated dependencies [dd00eeb]
- Updated dependencies
  - @pnpm/types@11.0.0
  - @pnpm/core-loggers@10.0.3

## 8.0.2

### Patch Changes

- Updated dependencies [13e55b2]
  - @pnpm/types@10.1.1
  - @pnpm/core-loggers@10.0.2

## 8.0.1

### Patch Changes

- Updated dependencies [45f4262]
  - @pnpm/types@10.1.0
  - @pnpm/core-loggers@10.0.1

## 8.0.0

### Major Changes

- 43cdd87: Node.js v16 support dropped. Use at least Node.js v18.12.

### Minor Changes

- 7733f3a: Added support for registry-scoped SSL configurations (cert, key, and ca). Three new settings supported: `<registryURL>:certfile`, `<registryURL>:keyfile`, and `<registryURL>:ca`. For instance:

  ```
  //registry.mycomp.com/:certfile=server-cert.pem
  //registry.mycomp.com/:keyfile=server-key.pem
  //registry.mycomp.com/:cafile=client-cert.pem
  ```

  Related issue: [#7427](https://github.com/pnpm/pnpm/issues/7427).
  Related PR: [#7626](https://github.com/pnpm/pnpm/pull/7626).

### Patch Changes

- Updated dependencies [7733f3a]
- Updated dependencies [43cdd87]
- Updated dependencies [730929e]
  - @pnpm/types@10.0.0
  - @pnpm/fetching-types@6.0.0
  - @pnpm/core-loggers@10.0.0

## 7.0.7

### Patch Changes

- @pnpm/core-loggers@9.0.6

## 7.0.6

### Patch Changes

- @pnpm/core-loggers@9.0.5

## 7.0.5

### Patch Changes

- @pnpm/core-loggers@9.0.4

## 7.0.4

### Patch Changes

- @pnpm/core-loggers@9.0.3

## 7.0.3

### Patch Changes

- @pnpm/core-loggers@9.0.2

## 7.0.2

### Patch Changes

- @pnpm/core-loggers@9.0.1

## 7.0.1

### Patch Changes

- 8228c2cb1: Patch node-fetch to fix an error that happens on Node.js 20 [#6424](https://github.com/pnpm/pnpm/issues/6424).

## 7.0.0

### Major Changes

- eceaa8b8b: Node.js 14 support dropped.

### Patch Changes

- Updated dependencies [eceaa8b8b]
  - @pnpm/fetching-types@5.0.0
  - @pnpm/core-loggers@9.0.0

## 6.0.6

### Patch Changes

- 673e23060: Fail with a meaningful error message when cannot parse a proxy URL.
- 9fa6c7404: The `strict-ssl`, `ca`, `key`, and `cert` settings should work with HTTPS proxy servers [#4689](https://github.com/pnpm/pnpm/issues/4689).

## 6.0.5

### Patch Changes

- @pnpm/core-loggers@8.0.3

## 6.0.4

### Patch Changes

- a9d59d8bc: Update dependencies.

## 6.0.3

### Patch Changes

- @pnpm/core-loggers@8.0.2

## 6.0.2

### Patch Changes

- Updated dependencies [804de211e]
  - @pnpm/fetching-types@4.0.0

## 6.0.1

### Patch Changes

- @pnpm/core-loggers@8.0.1

## 6.0.0

### Major Changes

- 043d988fc: Breaking change to the API. Defaul export is not used.
- f884689e0: Require `@pnpm/logger` v5.

### Patch Changes

- Updated dependencies [f884689e0]
  - @pnpm/core-loggers@8.0.0

## 5.0.10

### Patch Changes

- Updated dependencies [3ae888c28]
  - @pnpm/core-loggers@7.1.0

## 5.0.9

### Patch Changes

- @pnpm/core-loggers@7.0.8

## 5.0.8

### Patch Changes

- @pnpm/core-loggers@7.0.7

## 5.0.7

### Patch Changes

- @pnpm/core-loggers@7.0.6

## 5.0.6

### Patch Changes

- e018a8b14: Some HTTP errors should not be retried [#4917](https://github.com/pnpm/pnpm/pull/4917).

## 5.0.5

### Patch Changes

- @pnpm/core-loggers@7.0.5

## 5.0.4

### Patch Changes

- @pnpm/core-loggers@7.0.4

## 5.0.3

### Patch Changes

- 9d5bf09c0: Use @pnpm/network.agent instead of @pnpm/npm-registry-agent.
  - @pnpm/core-loggers@7.0.3

## 5.0.2

### Patch Changes

- Updated dependencies [d5730ba81]
  - @pnpm/npm-registry-agent@6.1.0
  - @pnpm/core-loggers@7.0.2

## 5.0.1

### Patch Changes

- @pnpm/core-loggers@7.0.1

## 5.0.0

### Major Changes

- 542014839: Node.js 12 is not supported.

### Patch Changes

- Updated dependencies [542014839]
  - @pnpm/core-loggers@7.0.0
  - @pnpm/fetching-types@3.0.0
  - @pnpm/npm-registry-agent@6.0.0

## 4.2.5

### Patch Changes

- @pnpm/core-loggers@6.1.4

## 4.2.4

### Patch Changes

- @pnpm/core-loggers@6.1.3

## 4.2.3

### Patch Changes

- @pnpm/core-loggers@6.1.2

## 4.2.2

### Patch Changes

- @pnpm/core-loggers@6.1.1

## 4.2.1

### Patch Changes

- Updated dependencies [ba9b2eba1]
  - @pnpm/core-loggers@6.1.0

## 4.2.0

### Minor Changes

- f1c194ded: Add `fetchWithAgent()`.

## 4.1.6

### Patch Changes

- 12ee3c144: HTTP requests should be retried when the server responds with on of 408, 409, 420, 429 status codes.

## 4.1.5

### Patch Changes

- @pnpm/core-loggers@6.0.6

## 4.1.4

### Patch Changes

- @pnpm/core-loggers@6.0.5

## 4.1.3

### Patch Changes

- 782ef2490: Default options should not be overriden by undefined options.
- Updated dependencies [3c7e5eced]
  - @pnpm/npm-registry-agent@5.0.2

## 4.1.2

### Patch Changes

- Updated dependencies [6c50af201]
- Updated dependencies [0beffc2a0]
  - @pnpm/npm-registry-agent@5.0.1

## 4.1.1

### Patch Changes

- bab172385: The Node.js process should not silently exit on some broken HTTPS requests.
- Updated dependencies [bab172385]
  - @pnpm/fetching-types@2.2.1

## 4.1.0

### Minor Changes

- eadf0e505: New optional option added: compress.

### Patch Changes

- Updated dependencies [eadf0e505]
  - @pnpm/fetching-types@2.2.0

## 4.0.2

### Patch Changes

- @pnpm/core-loggers@6.0.4

## 4.0.1

### Patch Changes

- @pnpm/core-loggers@6.0.3

## 4.0.0

### Major Changes

- e7d9cd187: Do not use fetch does not support unix requests.
- eeff424bd: strictSSL option renamed to strictSsl.

### Patch Changes

- Updated dependencies [eeff424bd]
  - @pnpm/npm-registry-agent@5.0.0
  - @pnpm/core-loggers@6.0.2

## 3.1.0

### Minor Changes

- 05baaa6e7: Add new option: timeout.

### Patch Changes

- Updated dependencies [05baaa6e7]
  - @pnpm/fetching-types@2.1.0
  - @pnpm/core-loggers@6.0.1

## 3.0.0

### Major Changes

- 97b986fbc: Node.js 10 support is dropped. At least Node.js 12.17 is required for the package to work.

### Patch Changes

- Updated dependencies [97b986fbc]
- Updated dependencies [90487a3a8]
  - @pnpm/core-loggers@6.0.0
  - @pnpm/fetching-types@2.0.0
  - @pnpm/npm-registry-agent@4.0.0

## 2.1.11

### Patch Changes

- Updated dependencies [dd12cf6ec]
  - @pnpm/npm-registry-agent@3.1.2

## 2.1.10

### Patch Changes

- @pnpm/core-loggers@5.0.3

## 2.1.9

### Patch Changes

- Updated dependencies [dc5a0a102]
  - @pnpm/npm-registry-agent@3.1.1

## 2.1.8

### Patch Changes

- 263f5d813: Import node-fetch-unix correctly.

## 2.1.7

### Patch Changes

- @pnpm/core-loggers@5.0.2

## 2.1.6

### Patch Changes

- @pnpm/core-loggers@5.0.1

## 2.1.5

### Patch Changes

- Updated dependencies [86cd72de3]
  - @pnpm/core-loggers@5.0.0

## 2.1.4

### Patch Changes

- 3981f5558: Update node-fetch to v2.6.1.

## 2.1.3

### Patch Changes

- Updated dependencies [46128b5b0]
  - @pnpm/npm-registry-agent@3.1.0

## 2.1.2

### Patch Changes

- Updated dependencies [9a908bc07]
- Updated dependencies [9a908bc07]
  - @pnpm/core-loggers@4.2.0

## 2.1.1

### Patch Changes

- Updated dependencies [7b98d16c8]
  - @pnpm/npm-registry-agent@3.0.1

## 2.1.0

### Minor Changes

- 71aeb9a38: fetchFromRegistry() added.

### Patch Changes

- Updated dependencies [c3796a71d]
- Updated dependencies [71aeb9a38]
  - @pnpm/npm-registry-agent@3.0.0
  - @pnpm/fetching-types@1.0.0

## 2.0.2

### Patch Changes

- @pnpm/core-loggers@4.1.2

## 2.0.1

### Patch Changes

- @pnpm/core-loggers@4.1.1

## 2.0.0

### Major Changes

- 2ebb7af33: Print a warning when request fails and a retry will happen. Breaking changes in the programmatic API of `@pnpm/fetch`.

### Patch Changes

- Updated dependencies [2ebb7af33]
  - @pnpm/core-loggers@4.1.0

## 1.0.4
