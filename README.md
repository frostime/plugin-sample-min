# SiYuan plugin sample (minimum)

A minimum sample/template for SiYuan plugin development.

## Package contents

The tag release workflow creates `package.zip` with the files required by the SiYuan community bazaar:

- `plugin.json`
- `index.js` and `index.css`
- `i18n/*` (using BCP 47 locale names such as `en.json` and `zh-CN.json`)
- `icon.png` and `preview.png`
- `README*.md`

About the `siyuan` module, see [Petal](https://github.com/siyuan-note/petal).

## Release

Push a tag such as `v0.1.0`. GitHub Actions creates a release and uploads `package.zip`. The package manifest version must match the release version without the `v` prefix.

For bazaar submission and manifest details, see the [official plugin sample](https://github.com/siyuan-note/plugin-sample) and [bazaar documentation](https://github.com/siyuan-note/bazaar).
