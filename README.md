# GA-H81M-H-Hackintosh

## 电脑配置
| 规格     | 详细信息                       |
| -------- | ------------------------------ |
| 主板型号 | 技嘉 GA-H81M-H               |
| 操作系统 | macOS High Sierra 10.13        |
| 处理器   | 英特尔 酷睿 i5 - 4460          |
| 内存     | 8GB x 1 1600MHz         |
| 硬盘     | 120G SSD |
| 显卡1    | Intel HD Graphics 4600 Haswell |
 
| 显示器   | 23 英寸 FHD 1920x1080     |
| 声卡     | 瑞昱 Realtek ALC887            |
| 网卡     |  瑞昱 RTL8111               |
- 因 Acidanthera 开发组的驱动不再对 Clover 做兼容性测试 , 放弃 Clover , 使用 OpenCore 引导方案
- 由于主板只有 VGA 接口 , Nvidia 的 WebDriver 驱动 只支持到 10.13 , 所以暂时无缘更高的版本
- [EFI Releases 下载](https://github.com/xlivans/GA-H81M-H-Hackintosh/releases)
- [更新日志](Changelog.md)
## 鸣谢
- **宪武** 提供 [OC-little](https://github.com/daliansky/OC-little)
- **Acidanthera** 提供 [OpenCore](https://github.com/acidanthera/OpenCorePkg) 和 [相关驱动](https://github.com/acidanthera)

