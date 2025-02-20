# @pnpm/plugin-commands-deploy

## 1.0.9

### Patch Changes

- 107d01109: `pnpm deploy` should inject local dependencies of all types (dependencies, optionalDependencies, devDependencies) [#5078](https://github.com/pnpm/pnpm/issues/5078).
  - @pnpm/cli-utils@0.7.22
  - @pnpm/directory-fetcher@3.0.8
  - @pnpm/plugin-commands-installation@10.4.1

## 1.0.8

### Patch Changes

- 0569f1022: `pnpm deploy` should not modify the lockfile [#5071](https://github.com/pnpm/pnpm/issues/5071)
- 0569f1022: `pnpm deploy` should not fail in CI [#5071](https://github.com/pnpm/pnpm/issues/5071)
- Updated dependencies [0569f1022]
  - @pnpm/plugin-commands-installation@10.4.0
  - @pnpm/cli-utils@0.7.21

## 1.0.7

### Patch Changes

- 31e73ba77: `pnpm deploy` should include all dependencies by default [#5035](https://github.com/pnpm/pnpm/issues/5035).
- Updated dependencies [406656f80]
  - @pnpm/plugin-commands-installation@10.3.10
  - @pnpm/cli-utils@0.7.20

## 1.0.6

### Patch Changes

- @pnpm/plugin-commands-installation@10.3.9
- @pnpm/cli-utils@0.7.19

## 1.0.5

### Patch Changes

- @pnpm/plugin-commands-installation@10.3.8

## 1.0.4

### Patch Changes

- @pnpm/cli-utils@0.7.18
- @pnpm/plugin-commands-installation@10.3.7

## 1.0.3

### Patch Changes

- Updated dependencies [b55b3782d]
  - @pnpm/plugin-commands-installation@10.3.6

## 1.0.2

### Patch Changes

- Updated dependencies [5f643f23b]
  - @pnpm/cli-utils@0.7.17
  - @pnpm/directory-fetcher@3.0.7
  - @pnpm/plugin-commands-installation@10.3.5

## 1.0.1

### Patch Changes

- f4248b514: Changes deployment directories to be created recursively
  - @pnpm/plugin-commands-installation@10.3.4

## 1.0.0

### Major Changes

- 7922d6314: A new experimental command added: `pnpm deploy`. The deploy command takes copies a project from a workspace and installs all of its production dependencies (even if some of those dependencies are other projects from the workspace).

  For example, the new command will deploy the project named `foo` to the `dist` directory in the root of the workspace:

  ```
  pnpm --filter=foo deploy dist
  ```

### Patch Changes

- Updated dependencies [7922d6314]
  - @pnpm/fs.indexed-pkg-importer@1.0.0
  - @pnpm/plugin-commands-installation@10.3.3
