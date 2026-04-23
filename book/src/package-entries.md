# package entries
[example](https://github.com/koibtw/nvrs/blob/main/nvrs.toml#L12-L15)

package entries are custom entries in the main config file. they contain values such as:

| name          | description                                                                     | type   | required | custom |
|---------------|---------------------------------------------------------------------------------|--------|----------|--------|
| `source`      | see [sources](https://github.com/koibtw/nvrs?tab=readme-ov-file#sources)        | string | ✔️       | ❌     |
| source name   | the "target". eg. repo path for `github`                                        | string | ✔️       | ✔️     |
| `host`        | domain name the source is hosted on                                             | string | ❌       | ❌     |
| `prefix`      | the prefix used in releases / tags<br>example: `v` for tags like `v0.1.0`       | string | ❌       | ❌     |
| `use_max_tag` | use max git tag instead of the latest release                                   | bool   | ❌       | ❌     |
| `url`         | url to check for source type `regex`                                            | string | ❌       | ❌     |
| `regex`       | regex to search url for source type `regex`                                     | bool   | ❌       | ❌     |
