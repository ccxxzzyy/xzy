# 项目规则

## 命名规范
- 所有 CSS 类名必须以 `xzy_` 开头（如 `.xzy_box`、`.xzy_container`）
- 所有 HTML id 名必须以 `xzy_` 开头（如 `id="xzy_demo"`）
- 所有 JavaScript 变量和函数必须以 `xzy_` 开头（如 `let xzy_count = 0`、`function xzy_init() {}`）

## HTML 注释规范
每个 HTML 页面顶部必须包含以下格式的注释：
```html
<!--
姓名：夏志远
日期：YYYY-MM-DD
功能：功能名称描述
-->
```

## 技术栈
- 使用原生 HTML、CSS 和 JavaScript 实现，不使用任何第三方库或 CDN（包括但不限于 jQuery、Bootstrap、Vue、React、CDN 上的字体图标等）
- 图标使用本地 `font/font_5244859_igt0lytephh/` 目录下的 iconfont 图标
- 获取服务器端数据统一使用原生 `fetch` API

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
