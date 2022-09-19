# Change Log

## v2.0.0 (2022-09-20)

### Enhancements

- [#186](https://github.com/tiennguyendang/task-manager-api/issues/186) Refactor success response and error response format
  - Wrap success response data with `data` property
  - Wrap pagination links property with meta property
  - Return only fields that are updated with new values when doing `ListOperator`
  - Refactor login response data format
  - Simplify error response format by returning only `name` and `message`

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
