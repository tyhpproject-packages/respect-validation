<!-- tyhp-readme:start -->
# tyhpdef/respect-validation

Tyhp type definitions for `respect/validation` `3.1.2`.

```bash
composer require --dev tyhpdef/respect-validation:3.1.2
```

This is a metapackage. Composer also installs `tyhpdef/respect-validation-impl` (type files).
Require **this** name, not `tyhpdef/respect-validation-impl`.

See https://tyhplang.com.

## Maintain `respect/validation`? Ship the types yourself

If you are a Packagist maintainer of `respect/validation`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/respect-validation-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `respect/validation` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/respect-validation": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `respect/validation` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `respect/validation` with a real constraint,
   `"replace": { "tyhpdef/respect-validation": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `respect/validation` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/respect-validation` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
