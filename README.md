# Arduino Uno Development Board based on LGT8Fx8P & ATMEGAx8PB

⭐ 基于 LGT8Fx8P 与 ATMEGAx8PB 系列单片机的 Arduino Uno 开发板 ⭐

🔗 [GitLab (Homepage)](https://gitlab.soraharu.com/XiaoXi/Arduino-Uno-Development-Board-based-on-LGT8Fx8P-and-ATMEGAx8PB) | 🔗 [OSHWHub](https://oshwhub.com/yanranxiaoxi/Arduino-Uno-Development-Board-based-on-LGT8Fx8P-and-ATMEGAx8PB)

![实拍图](https://downloadserver.soraharu.com:7000/Arduino%20Uno%20Development%20Board%20based%20on%20LGT8Fx8P%20and%20ATMEGAx8PB/Image/Product_quality_5.jpg)

## 🤔 这是什么

这是一个基于 LGT8Fx8P 与 ATMEGAx8PB 系列单片机的 Arduino Uno 开发板 ，使用 [立创 EDA](https://lceda.cn/) 进行开发。

建议使用 LGT8F328P 国产 AVR 单片机，该单片机拥有改善的性能，高达 32MHz 的时钟速度，是传统 Arduino Uno 的两倍。

本 PCB 设计已通过完整功能性测试，且已添加 [嘉立创](https://www.jlc.com/) SMT 定位孔，可直接进行 SMT 贴片生产。但请注意，本设计完整开源并遵循 [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/) 开源协议，开源作者不对作品的安全性、完整性作任何承诺，且不对因此产生的任何损失承担后果。

你可以使用本项目的 [焊接助手](https://htmlpreview.soraharu.com/?https://gitlab.soraharu.com/XiaoXi/Arduino-Uno-Development-Board-based-on-LGT8Fx8P-and-ATMEGAx8PB/-/raw/master/InteractiveHtmlBom/index.html) 有效地提升手工焊接效率，本助手通过 [InteractiveHtmlBom](https://gitlab.soraharu.com/XiaoXi/InteractiveHtmlBom) 自动生成。

## 📝 配置 Arduino IDE

以下配置方式以 LGT8F328P 为例：

1. 参阅 [久治明千树汐/LGT8Fx](https://gitlab.soraharu.com/XiaoXi/LGT8Fx) 项目配置并安装开发板资源包
2. 选中 `工具` -> `开发板` -> `Logic Green Arduino AVR Compatible Boards (LGT8Fx Boards)` -> `LGT8F328`
3. 选中 `工具` -> `Variant` -> `328P-LQFP32 (e.g. MiniEVB nano-style and WAVGAT)`

如若发现有部分延时或与速度有关的功能工作不正常，可能是因为 LGT8F328P 芯片改善了部分逻辑所占用的时钟周期并提升了一倍的时钟速度，可以尝试选中 `工具` -> `Clock` -> `16 MHz` 以对齐原版 Arduino Uno 的时钟速度。

## 🛠️ 生产电路板

本项目的 Gerber 文件可以从 [Releases](https://gitlab.soraharu.com/XiaoXi/Arduino-Uno-Development-Board-based-on-LGT8Fx8P-and-ATMEGAx8PB/-/releases) 页面获取，并允许在开源许可范围内的商业目的使用。

*建议使用 [嘉立创](https://www.jlc.com/) 生产高品质电路板。

*It is recommended to use [JLCPCB](https://jlcpcb.com/) to produce high-quality circuit boards.

## ⚙️ 部署至 EasyEDA

1. 克隆本项目 [源代码](https://gitlab.soraharu.com/XiaoXi/Arduino-Uno-Development-Board-based-on-LGT8Fx8P-and-ATMEGAx8PB/-/archive/master/Arduino-Uno-Development-Board-based-on-LGT8Fx8P-and-ATMEGAx8PB-master.zip) 到本地
2. 在立创 EDA 标准版编辑器中选择 `文件` -> `打开` -> `立创EDA...`
3. 选择本项目源代码中的 `/EasyEDA/*.json` 文件并分别导入

## 🔤 字体

- NotoSerifCJKsc-Medium | [下载](https://github.com/googlefonts/noto-cjk/raw/main/Serif/NotoSerifCJKsc-Medium.otf) | [官方](https://github.com/googlefonts/noto-cjk) | [SIL Open Font License 1.1](https://choosealicense.com/licenses/ofl-1.1/)

## 📄 支持 MCU

本项目 MCU 为 LQFP-32 封装，以下所有支持 MCU 均需选用其 LQFP-32 封装版本。

| Model          | Test                                              | Remark    |
| -------------- | ------------------------------------------------- | --------- |
| LGT8F88P       |                                                   |           |
| LGT8F168P      |                                                   |           |
| LGT8F328P      | Tested                                            | Recommend |
| ATMEGA48PB     |                                                   |           |
| ATMEGA88PB     |                                                   |           |
| ATMEGA168PB    |                                                   |           |
| ATMEGA328PB    |                                                   | Recommend |
| ATMEGA328PU-TH | Tested by [@ARES001](https://oshwhub.com/ARES001) |           |

## 📜 开源许可

基于 [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/) 许可进行开源。

本设计已在 [中国版权保护中心](https://www.ccopyright.com.cn/) 登记注册。
