## 1.0.0 (2022-05-24)

### Perf

- **import**: Import urllib3 only if needed (#81)

### Fix

- importlib-metadata requirement
- **patched**: re-enable --config cli arg
- **formatters**: use another plugin name colour
- **plugins**: increase max violation code length

### Feat

- Configurable cache timeout (#46)
- Use relative path (#41)

### Refactor

- drop support for flake8-strict

### BREAKING CHANGE

- Users should replace flake-strict rules with flake8-black

## 0.11.1 (2022-01-26)

### Fix

- **plugins**: use new pylint api
