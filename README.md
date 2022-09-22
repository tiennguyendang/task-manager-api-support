# Change Log

## v2.0.2 (2022-09-22)

### Bug fixes

- Fix cached `node_modules` when installing packages for new application

## v2.0.1 (2022-09-22)

### Bug fixes

- [#206](https://github.com/tiennguyendang/task-manager-api/issues/206) Return only updated fields when performing `UpdateOperation`
  - AsIs: When request body has at least one field that have new value, return `request body` with `updatedAt` field
  - ToBe: When request body has at least one field that have new value, return `updated fields` with `updatedAt` field
- [#207](https://github.com/tiennguyendang/task-manager-api/issues/207) Do not hash new password when performing `UpdateUserOperation`

## v2.0.0 (2022-09-20)

### Enhancements

- [#186](https://github.com/tiennguyendang/task-manager-api/issues/186) Refactor success response and error response format
  - Wrap success response data with `data` property
  - Wrap pagination links property with meta property
  - Return only fields that are updated with new values when doing `UpdateOperation`
  - Refactor login response data format
  - Simplify error response format by returning only `name` and `message`

## v1.4.3 (2022-09-17)

### Bug fixes

- Delete all containers and images created by up commands in ApplicationStop hook

## v1.4.2 (2022-09-16)

### Bug fixes

- Create script for ValidateService hook to cache build result

## v1.4.1 (2022-09-16)

### Bug fixes

- [#203](https://github.com/tiennguyendang/task-manager-api/issues/203) Anyone can list all tasks

## v1.4.0 (2022-09-16)

### Enhancements

- [#202](https://github.com/tiennguyendang/task-manager-api/issues/202) Refactor paginate operation
- [#201](https://github.com/tiennguyendang/task-manager-api/issues/201) Insert query into pagination links
- [#200](https://github.com/tiennguyendang/task-manager-api/issues/200) Allow specifying sortField when querying
- [#199](https://github.com/tiennguyendang/task-manager-api/issues/199) Implement users querying
- [#198](https://github.com/tiennguyendang/task-manager-api/issues/198) Implement tasks searching
- [#197](https://github.com/tiennguyendang/task-manager-api/issues/197) Implement categories searching
