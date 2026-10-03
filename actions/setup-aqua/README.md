# setup-aqua

Install [aqua](https://aquaproj.github.io/) and tools declared in `aqua.yaml`.

```yaml
steps:
  - uses: 'actions/checkout@v6'
  - uses: 'attakei/devkit/actions/setup-aqua@main'
```

| Input               | Default   | Description                                                   |
| ------------------- | --------- | ------------------------------------------------------------- |
| `aqua_version`      | `v2.55.0` | Version of aqua to install                                    |
| `policy_allow`      | `true`    | Run `aqua policy allow` for the policy file of the repository |
| `working_directory` | (empty)   | Directory to run aqua (where `aqua.yaml` can be found)        |

