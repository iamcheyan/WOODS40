## WOODS40 键盘配置共享（WOODS40_BASE / LAYOUT_45）

本仓库用于公开与分享我的 WOODS40 客制化键盘配置（基于 `WOODS40_BASE`，布局 `LAYOUT_45`）。你可以直接下载并导入到 WOODSKB 官方配置工具中使用，或参考作为自己的客制化基础。

### 官方资源

- 配置工具链接：[`https://woodskb.com/config/#/WOODS40_BASE/LAYOUT_45`](https://woodskb.com/config/#/WOODS40_BASE/LAYOUT_45)
- 使用帮助 / Wiki：[`https://woodskb.com/wiki/`](https://woodskb.com/wiki/)

以上链接来源：
- `https://woodskb.com/config/#/WOODS40_BASE/LAYOUT_45`
- `https://woodskb.com/wiki/`

### 目录结构

```
configs/
  WOODS40_BASE/
    LAYOUT_45/
      键位配置/        # 放置从配置工具导出的键位布局文件（如 JSON）
      宏配置/          # 放置宏配置文件（如 JSON/TXT），命名清晰便于识别
      固件/            # 可选：对应版本的固件文件（从官网下载）
      图片/            # 截图与示意图（例如键位图、层说明），便于预览
      文档/            # 补充文档，如版本变更、兼容性说明
```

### 使用说明

1. 打开 WOODSKB 配置工具：[`https://woodskb.com/config/#/WOODS40_BASE/LAYOUT_45`](https://woodskb.com/config/#/WOODS40_BASE/LAYOUT_45)
2. 在配置工具中导入本仓库 `键位配置` 或 `宏配置` 下的文件（通常为 JSON）。
3. 根据需要在工具中进行微调（如层切换、Fn 组合、宏触发）。
4. 参考 `图片` 目录下的示意图了解各层功能；如需刷写固件，前往 `固件` 目录或官方 `固件下载` 页面。
5. 实机验证无误后，建议备份你的个性化版本到 `文档` 目录并注明变更点。

### 命名约定（建议）

- 键位配置文件：`layout_<日期/版本>.json`（例如：`layout_v1.0.json`）
- 宏配置文件：`macros_<用途/层>_<版本>.json`（例如：`macros_media_v1.json`）
- 图片：`层X_功能说明.png`、`整体布局预览.png`
- 文档：`CHANGELOG.md`、`兼容性说明.md`

### 贡献与反馈

- 欢迎通过 Issue 或 PR 反馈与改进建议。
- 若你的键位方案基于此仓库二次定制，欢迎在 `文档` 目录下新增说明并提交 PR。

### 版权与致谢

- 本仓库仅分享个人使用的配置方案，版权归原作者所有。
- 感谢 WOODSKB 官方提供的配置平台与文档支持。


