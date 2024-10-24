# DDEV SPX

Provides the [SPX](https://github.com/NoiseByNorthwest/php-spx) extension for PHP.

For DDEV v1.23.5 or above run

```sh
ddev add-on get fullfatthings/ddev-spx
```

For earlier versions of DDEV run

```sh
ddev get fullfatthings/ddev-spx
```

After installation:

- Run `ddev restart` - this should install the addons into php
- To enable, run `ddev spx on` and to disable run `ddev spx off`.
- Once enabled, browse to `https://example.ddev.site/?SPX_KEY=dev&SPX_UI_URI=/`
