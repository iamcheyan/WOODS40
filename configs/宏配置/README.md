## 宏配置说明（WOODS40_BASE / LAYOUT_45）

本文档基于 WOODSKB 官方配置工具与 Wiki 整理，用于指导你创建、导入与维护宏配置。

- 官方配置工具：[`https://woodskb.com/config/#/WOODS40_BASE/LAYOUT_45`](https://woodskb.com/config/#/WOODS40_BASE/LAYOUT_45)
- 官方 Wiki（含“配置宏”与常见问题）：[`https://woodskb.com/wiki/`](https://woodskb.com/wiki/)

### 支持与建议

- 支持常见宏类型：文本输入、组合键（如 Ctrl+Alt+X）、延时（毫秒）、多步骤序列等。
- 建议将常用操作（层切换、媒体键、窗口管理、代码片段）抽象为命名良好的宏，便于复用与分享。

### 导入与绑定步骤

1. 打开官方配置工具页面（见上方链接）。
2. 在“宏”或“宏配置”入口导入本目录下的 JSON 文件。
3. 在“键位设置”中，将宏绑定到目标键位或组合层键位（如 Fn 层）。
4. 写入键盘并在实机上测试触发效果。

### 文件放置与命名约定

- 放置路径：`configs/WOODS40_BASE/LAYOUT_45/宏配置/`
- 建议命名：`macros_<用途或层>_<版本>.json`，例如：`macros_media_v1.json`
- 若包含多套方案，建议用子目录区分：`宏配置/办公/`、`宏配置/开发/`

### 维护建议

- 小步迭代：每次调整新增一个小版本，方便回滚。
- 配置与键位图同步：更新宏后建议在 `图片/` 下同步更新示意图。
- 兼容性：升级固件后如宏异常，优先对照 Wiki 的“固件升级/常见问题”。

以上内容基于官方资源汇总与经验整理，更多细节以官方页面为准：
- `https://woodskb.com/config/#/WOODS40_BASE/LAYOUT_45`
- `https://woodskb.com/wiki/`


