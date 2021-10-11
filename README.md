# Arduino Uno Development Board based on LGT8Fx8P & ATMEGAx8PB

⭐ 基于 LGT8Fx8P 与 ATMEGAx8PB 系列单片机的 8051 Uno 开发板 ⭐

🔗 [GitLab (Homepage)](https://gitlab.soraharu.com/XiaoXi/Arduino-Uno-Development-Board-based-on-LGT8Fx8P-and-ATMEGAx8PB) | 🔗 [OSHWHub](https://oshwhub.com/yanranxiaoxi/Arduino-Uno-Development-Board-based-on-LGT8Fx8P-and-ATMEGAx8PB)

![实拍图](https://downloadserver.soraharu.com:7000/Arduino%20Uno%20Development%20Board%20based%20on%20LGT8Fx8P%20and%20ATMEGAx8PB/Image/Product_quality_5.jpg)

## 🤔 这是什么

这是一个基于 LGT8Fx8P 与 ATMEGAx8PB 系列单片机的 8051 Uno 开发板 ，使用 [立创 EDA](https://lceda.cn/) 进行开发。

建议使用 LGT8F328P 国产 AVR 单片机，该单片机拥有改善的性能，高达 32MHz 的时钟速度，是传统 Arduino Uno 的两倍。关于该单片机使用 Arduino IDE 进行开发的方式，请参阅 [久治明千树汐/LGT8Fx](https://gitlab.soraharu.com/XiaoXi/LGT8Fx) 项目。

你可以使用本项目的 [焊接助手](https://htmlpreview.soraharu.com/?https://gitlab.soraharu.com/XiaoXi/Arduino-Uno-Development-Board-based-on-LGT8Fx8P-and-ATMEGAx8PB/-/raw/master/InteractiveHtmlBom/index.html) 有效地提升手工焊接效率，本助手通过 [InteractiveHtmlBom](https://gitlab.soraharu.com/XiaoXi/InteractiveHtmlBom) 自动生成。

## 🛠️ 生产电路板

本项目的 Gerber 文件可以从 [Releases](https://gitlab.soraharu.com/XiaoXi/Arduino-Uno-Development-Board-based-on-LGT8Fx8P-and-ATMEGAx8PB/-/releases) 页面获取，并允许在开源许可范围内的商业目的使用。

*建议使用 [嘉立创](https://www.jlc.com/) 生产高品质电路板。

*It is recommended to use [JLCPCB](https://jlcpcb.com/) to produce high-quality circuit boards.

## ⚙️ 部署至 EasyEDA

1. 克隆本项目 [源代码](https://gitlab.soraharu.com/XiaoXi/Arduino-Uno-Development-Board-based-on-LGT8Fx8P-and-ATMEGAx8PB/-/archive/master/Arduino-Uno-Development-Board-based-on-LGT8Fx8P-and-ATMEGAx8PB-master.zip) 到本地
2. 在立创 EDA 标准版编辑器中选择 `文件` -> `打开` -> `立创EDA...`
3. 选择本项目源代码中的 `/EasyEDA/1-*.json` 文件并分别导入

## 🔤 字体

- NotoSerifCJKsc-Medium | [下载](https://github.com/googlefonts/noto-cjk/raw/main/Serif/NotoSerifCJKsc-Medium.otf) | [官方](https://github.com/googlefonts/noto-cjk) | [SIL Open Font License 1.1](https://choosealicense.com/licenses/ofl-1.1/)

## 📄 支持 MCU

本项目 MCU 为 LQFP-32 封装，以下所有支持 MCU 均需选用其 LQFP-32 封装版本。

| Model       | Test   | Remark    |
| ----------- | ------ | --------- |
| LGT8F88P    |        |           |
| LGT8F168P   |        |           |
| LGT8F328P   | Tested | Recommend |
| ATMEGA48PB  |        |           |
| ATMEGA88PB  |        |           |
| ATMEGA168PB |        |           |
| ATMEGA328PB |        | Recommend |

## 📜 开源许可

基于 [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/) 许可进行开源。

本设计已在 [中国版权保护中心](https://www.ccopyright.com.cn/) 登记注册。
