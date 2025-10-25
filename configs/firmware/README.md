## 固件获取与刷写指南（WOODS40_BASE / LAYOUT_45）

出于安全性与版本一致性考虑，固件请从 WOODSKB 官方渠道下载，并严格按官方“固件升级”指引进行刷写。

- 官方 Wiki（含“固件升级”与“常见问题”）：[`https://woodskb.com/wiki/`](https://woodskb.com/wiki/)
- 官方配置工具入口：[`https://woodskb.com/config/#/WOODS40_BASE/LAYOUT_45`](https://woodskb.com/config/#/WOODS40_BASE/LAYOUT_45)

### 下载固件

1. 前往官方站点，在“固件下载”/“固件升级”页面获取与你键盘型号与布局匹配的固件文件（通常为 `.bin`/`.hex` 等）。
2. 将文件保存至本目录：`configs/WOODS40_BASE/LAYOUT_45/固件/`
3. 建议重命名为：`firmware_<版本>_<日期>.<ext>`，例如：`firmware_v1.0_2025-01-01.bin`

### 刷写步骤（概述）

1. 使用数据线连接键盘与电脑，准备进入刷机/升级模式（进入方式以 Wiki 为准）。
2. 打开官方工具或对应升级程序，选择上一步下载的固件文件。
3. 开始刷写并等待完成，完成后键盘会自动重启或按提示手动复位。
4. 验证键位与宏功能是否正常，如异常请参考 Wiki 的“常见问题”。

### 完整性校验（可选）

为避免传输损坏，建议在下载后校验文件哈希：

```
shasum -a 256 firmware_xxx.bin
```

如哈希不一致，请重新下载。更多升级细节、注意事项与回退方案，请以官方 Wiki 为准：
- `https://woodskb.com/wiki/`


