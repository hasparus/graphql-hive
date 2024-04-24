# @graphql-hive/envelop

## 0.33.0

### Minor Changes

- [#4573](https://github.com/kamilkisiela/graphql-hive/pull/4573) [`06d465e`](https://github.com/kamilkisiela/graphql-hive/commit/06d465e882b569b6d0dbd5b271d2d98aafaec0b1) Thanks [@kamilkisiela](https://github.com/kamilkisiela)! - Break `@graphql-hive/client` into library-specific packages:

  - `@graphql-hive/core` - Core functionality
  - `@graphql-hive/apollo` - Apollo Client integration
  - `@graphql-hive/yoga` - Yoga Server integration
  - `@graphql-hive/envelop` - Envelop integration

  Migration steps are available in the README of each package.

- [#4494](https://github.com/kamilkisiela/graphql-hive/pull/4494) [`c5eeac5`](https://github.com/kamilkisiela/graphql-hive/commit/c5eeac5ccef9e2dcc3c8bb33deec0fb95af9552e) Thanks [@kamilkisiela](https://github.com/kamilkisiela)! - 🚨 BREAKING CHANGE 🚨 Requires now Node v16+

- [#4573](https://github.com/kamilkisiela/graphql-hive/pull/4573) [`06d465e`](https://github.com/kamilkisiela/graphql-hive/commit/06d465e882b569b6d0dbd5b271d2d98aafaec0b1) Thanks [@kamilkisiela](https://github.com/kamilkisiela)! - **Migration**

  Migration steps are available in the README.

  ```diff
  - import { useHive } from '@graphql-hive/client';
  + import { useHive } from '@graphql-hive/envelop';
  ```

### Patch Changes

- Updated dependencies [[`06d465e`](https://github.com/kamilkisiela/graphql-hive/commit/06d465e882b569b6d0dbd5b271d2d98aafaec0b1), [`c5eeac5`](https://github.com/kamilkisiela/graphql-hive/commit/c5eeac5ccef9e2dcc3c8bb33deec0fb95af9552e)]:
  - @graphql-hive/core@0.3.0