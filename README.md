# GA-H81M-H-Hackintosh

## 电脑配置
| 规格      | 详细信息                        |  
| -------- | ------------------------------ |
| 主板型号 | 技嘉 GA-H81M-H  BISO F2          |  
| 操作系统 | macOS Catalina 10.15.5        |
| 处理器   | 英特尔 i5 - 4460   3.2 GHz, 4 cores  |
|Architecture|Haswell |
 |Chipset |Intel H81  |
| 内存     | 8GB x 1 1600MHz DDR3        |
| 硬盘     | 120G SSD |
| 显卡    | Intel HD Graphics 4600 Haswell |
| 显示器   | 23 英寸 FHD 1920x1080   |
| 声卡     | 瑞昱 Realtek ALC887     |
| 板载网卡  |  瑞昱 RTL8111           |
| USB无线网卡 | TP-LINK TL-WDN7200H |
- 因 Acidanthera 开发组的驱动不再对 Clover 做兼容性测试 , 放弃 Clover , 使用 OpenCore 引导方案
- 参考 [opencore-i5-4460-h81m-k](https://github.com/wargodz009/opencore-i5-4460-h81m-k/)
- 参考 [GA-H81M-H-Hackintosh](https://github.com/xlivans/GA-H81M-H-Hackintosh/)
- 驱动 声卡的 Layout_ID 选择，看你的声音输出插口颜色，根据自己的颜色排序来定位ID
  
  LayoutID = 11 : 3 ports supported (Pink, Green, Blue) (Note : without auto-switch , you have to manually select between output/input device's) Codec Address : 0
  
  LayoutID = 13 : 5/6 ports supported (Grey, Black, Laranja, Pink, Green, Blue) Codec Address : 0
  
  LayoutID = 17 : 5/6 ports supported (Grey, Black, Laranja, Pink, Green, Blue) Codec Address : 2
  
  LayoutID = 18 : 5/6 ports supported (Grey, Black, Laranja, Pink, Green, Blue) Codec Address : 2
  
- 注意 VGA 接口 没有正常驱动  
## 鸣谢
- **宪武** 提供 [OC-little](https://github.com/daliansky/OC-little)
- **Acidanthera** 提供 [OpenCore](https://github.com/acidanthera/OpenCorePkg) 和 [相关驱动](https://github.com/acidanthera)

