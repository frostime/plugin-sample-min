# 思源插件样例（最简版）

思源插件开发的最简模板。

## 包内容

推送类似 `v0.1.0` 的标签后，GitHub Actions 会创建 `package.zip`，其中包含思源社区集市要求的文件：

- `plugin.json`
- `index.js` 和 `index.css`
- `i18n/*`（使用 BCP 47 语言名称，例如 `en.json` 和 `zh-CN.json`）
- `icon.png` 和 `preview.png`
- `README*.md`

关于 `siyuan` 模块的 API，请参考 [Petal](https://github.com/siyuan-note/petal)。

## 发布

GitHub Actions 会创建 Release 并上传 `package.zip`。清单中的 `version` 必须与版本标签一致，但不包含 `v` 前缀。

集市提交流程和清单字段说明请参考[官方插件样例](https://github.com/siyuan-note/plugin-sample)及[集市文档](https://github.com/siyuan-note/bazaar)。
