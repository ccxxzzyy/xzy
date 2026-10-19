# 项目规则

## 命名规范
- 所有 CSS 类名必须以 `xia` 开头（如 `.xia-box`、`.xia-container`）
- 所有 HTML id 名必须以 `xia` 开头（如 `id="xia-demo"`）
- 所有 JavaScript 变量必须以 `xia` 开头（如 `let xiaCount = 0`）

## 提示词记录
每次执行任务前，将本次提示词追加写入 `xia_prompt.md`，不覆盖之前的内容。
追加内容包含以下信息：
- 时间：`yyyy-mm-dd-hh-mm` 格式
- 使用的模型
- 提示词内容（用户原始消息）

示例格式：
```
---
## 2026-10-12-14-30
**模型**: longcat-2.5-preview-free
**提示词**: 新建11-1.html展示web前端的长度变化
```

## 页面导航
- 所有新建的 HTML 文件必须包含返回首页 `index.html` 的超链接
