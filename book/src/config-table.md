# `__config__` table
this configures the behavior of nvrs. see the [example config](https://github.com/koibtw/nvrs/blob/main/nvrs.toml#L7-L10).

available fields:

| name      | description                                                          | type   | required |
|-----------|----------------------------------------------------------------------|--------|----------|
| `oldver`  | path to the `oldver` file                                            | string | ✔️       |
| `newver`  | path to the `newver` file                                            | string | ✔️       |
| `keyfile` | path to a keyfile (see [keyfile structure](/keyfile-structure.html)) | string | ❌       |
