# @backstage/plugin-catalog-graph

## 0.1.3

### Patch Changes

- 81a41ec249: Added a `name` key to all extensions in order to improve Analytics API metadata.
- Updated dependencies
  - @backstage/core-components@0.6.1
  - @backstage/core-plugin-api@0.1.10
  - @backstage/plugin-catalog-react@0.5.2
  - @backstage/catalog-model@0.9.4
  - @backstage/catalog-client@0.5.0

## 0.1.2

### Patch Changes

- Updated dependencies
  - @backstage/core-plugin-api@0.1.9
  - @backstage/core-components@0.6.0
  - @backstage/plugin-catalog-react@0.5.1

## 0.1.1

### Patch Changes

- c0eb1fb9df: Make zooming configurable for `<CatalogGraphCard>` and disable it by default.
  This resolves an issue that scrolling on the entity page is sometimes captured
  by the graph making the page hard to use.
- Updated dependencies
  - @backstage/core-components@0.5.0
  - @backstage/catalog-client@0.4.0
  - @backstage/plugin-catalog-react@0.5.0
  - @backstage/catalog-model@0.9.3
