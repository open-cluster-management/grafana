---
keywords:
  - grafana
  - schema
title: Preferences kind
---
> Both documentation generation and kinds schemas are in active development and subject to change without prior notice.

# Preferences kind

## Maturity: merged
## Version: 0.0

## Properties

| Property           | Type                                              | Required | Description                                                                     |
|--------------------|---------------------------------------------------|----------|---------------------------------------------------------------------------------|
| `homeDashboardUID` | string                                            | No       | UID for the home dashboard                                                      |
| `language`         | string                                            | No       | Selected language (beta)                                                        |
| `queryHistory`     | [QueryHistoryPreference](#queryhistorypreference) | No       |                                                                                 |
| `theme`            | string                                            | No       | light, dark, empty is default                                                   |
| `timezone`         | string                                            | No       | The timezone selection<br/>TODO: this should use the timezone defined in common |
| `weekStart`        | string                                            | No       | day of the week (sunday, monday, etc)                                           |

## QueryHistoryPreference

### Properties

| Property  | Type   | Required | Description                                 |
|-----------|--------|----------|---------------------------------------------|
| `homeTab` | string | No       | one of: '' &#124; 'query' &#124; 'starred'; |


