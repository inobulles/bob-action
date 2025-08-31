# bob-action

GitHub action to bootstrap [Bob the Builder](https://github.com/inobulles/bob).

You can use this action for projects which use Bob as their build system.

## Usage

### Inputs

|Input    |Description               |Default |
|---------|--------------------------|--------|
|`version`|Version of Bob to install.|`latest`|

### Outputs

|Output       |Description                                                                  |
|-------------|-----------------------------------------------------------------------------|
|`bob-version`|The version of Bob that was installed. Useful when input version is `latest`.|

### Basic

```yaml
- uses: inobulles/bob-action@v1
```

### With version

```yaml
- uses: inobulles/bob-action@v1
  with:
    version: v0.2.18
```
