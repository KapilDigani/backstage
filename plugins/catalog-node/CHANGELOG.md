# @backstage/plugin-catalog-node

## 1.1.1-next.1

### Patch Changes

- Updated dependencies
  - @backstage/catalog-client@1.1.1-next.1
  - @backstage/backend-plugin-api@0.1.3-next.1
  - @backstage/catalog-model@1.1.2-next.1
  - @backstage/errors@1.1.2-next.1
  - @backstage/types@1.0.0

## 1.1.1-next.0

### Patch Changes

- Updated dependencies
  - @backstage/catalog-model@1.1.2-next.0
  - @backstage/backend-plugin-api@0.1.3-next.0
  - @backstage/catalog-client@1.1.1-next.0
  - @backstage/errors@1.1.2-next.0
  - @backstage/types@1.0.0

## 1.1.0

### Minor Changes

- 9743bc788c: Added refresh function to the `EntityProviderConnection` to be able to schedule refreshes from entity providers.

### Patch Changes

- 7d7d947352: Adds experimental `catalogServiceRef` for obtaining a `CatalogClient` in the new backend system.
- 409ed984e8: Updated usage of experimental backend service APIs.
- 62788b2ee8: The experimental `CatalogProcessingExtensionPoint` now accepts multiple providers and processors at once.
- Updated dependencies
  - @backstage/backend-plugin-api@0.1.2
  - @backstage/catalog-client@1.1.0
  - @backstage/catalog-model@1.1.1
  - @backstage/errors@1.1.1

## 1.1.0-next.2

### Minor Changes

- 9743bc788c: Added refresh function to the `EntityProviderConnection` to be able to schedule refreshes from entity providers.

### Patch Changes

- 409ed984e8: Updated usage of experimental backend service APIs.
- Updated dependencies
  - @backstage/backend-plugin-api@0.1.2-next.2
  - @backstage/catalog-client@1.1.0-next.2
  - @backstage/catalog-model@1.1.1-next.0
  - @backstage/errors@1.1.1-next.0

## 1.0.2-next.1

### Patch Changes

- 7d7d947352: Adds experimental `catalogServiceRef` for obtaining a `CatalogClient` in the new backend system.
- Updated dependencies
  - @backstage/backend-plugin-api@0.1.2-next.1
  - @backstage/catalog-client@1.0.5-next.1

## 1.0.2-next.0

### Patch Changes

- 62788b2ee8: The experimental `CatalogProcessingExtensionPoint` now accepts multiple providers and processors at once.
- Updated dependencies
  - @backstage/backend-plugin-api@0.1.2-next.0

## 1.0.1

### Patch Changes

- 0599732ec0: Refactored experimental backend system with new type names.
- 56e1b4b89c: Fixed typos in alpha types.
- Updated dependencies
  - @backstage/backend-plugin-api@0.1.1

## 1.0.1-next.0

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.1.1-next.0

## 1.0.0

### Major Changes

- 9a6aba1d85: This package houses stable types from the `@backstage/plugin-catalog-backend` package and is intended for creation of catalog modules. Prefer importing from this package over the `@backstage/plugin-catalog-backend` package.

### Minor Changes

- 91c1d12123: Added alpha exports for the new experimental backend system.

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.1.0
  - @backstage/catalog-model@1.1.0
  - @backstage/errors@1.1.0

## 1.0.0-next.0

### Major Changes

- 9a6aba1d85: This package houses stable types from the `@backstage/plugin-catalog-backend` package and is intended for creation of catalog modules. Prefer importing from this package over the `@backstage/plugin-catalog-backend` package.

### Minor Changes

- 91c1d12123: Added alpha exports for the new experimental backend system.

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.1.0-next.0
  - @backstage/catalog-model@1.1.0-next.3
