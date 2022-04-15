# Floppy based on CH331A

⭐ 基于 CH331A 的模拟软盘 ⭐

[![pipeline status](https://gitlab.soraharu.com/XiaoXi/Floppy-based-on-CH331A/badges/master/pipeline.svg)](https://gitlab.soraharu.com/XiaoXi/Floppy-based-on-CH331A/-/commits/master)
[![Latest Release](https://gitlab.soraharu.com/XiaoXi/Floppy-based-on-CH331A/-/badges/release.svg)](https://gitlab.soraharu.com/XiaoXi/Floppy-based-on-CH331A/-/releases)

🔗 [GitLab (Homepage)](https://gitlab.soraharu.com/XiaoXi/Floppy-based-on-CH331A) | 🔗 [OSHWHub](https://oshwhub.com/yanranxiaoxi/Floppy-based-on-CH331A) | 🔗 [GitHub](https://github.com/yanranxiaoxi/Floppy-based-on-CH331A)

![实拍图](https://downloadserver.soraharu.com:7000/Floppy%20based%20on%20CH331A/Image/Product_quality_5.jpg)

## 🤔 这是什么

这是一个基于 CH331A 的模拟软盘，使用 [立创 EDA](https://lceda.cn/) 进行开发。

本作品采用 CH331A 芯片作为主控，24C256 作为存储芯片，可以提供~~高达~~ 32KiB 的存储空间。提供板载写保护开关，有效保护软盘的数据安全。

## 🍭 使用说明

将 24C256 替换为 24C512 可以简单地将存储空间提升至 64KiB。请注意，需要选用 SOP-8 封装的存储芯片，而不是更为常见的 TSSOP-8 封装。

本 PCB 设计已通过完整功能性测试，且已添加 [嘉立创](https://www.jlc.com/) SMT 定位孔，可直接进行 SMT 贴片生产。但请注意，本设计完整开源并遵循 [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/) 开源协议，开源作者不对作品的安全性、完整性作任何承诺，且不对因此产生的任何损失承担后果。

你可以使用本项目的 [焊接助手](https://interactivehtmlbom.soraharu.com/Floppy-based-on-CH331A.html) 有效地提升手工焊接效率，本助手通过 [InteractiveHtmlBom](https://gitlab.soraharu.com/XiaoXi/InteractiveHtmlBom) 流水线自动化生成。

## 🛠️ 生产电路板

本项目的 Gerber 文件可以从 [Releases](https://gitlab.soraharu.com/XiaoXi/Floppy-based-on-CH331A/-/releases) 页面获取，并允许在开源许可范围内的商业目的使用。

*建议使用 [嘉立创](https://www.jlc.com/) 生产高品质电路板。

*It is recommended to use [JLCPCB](https://jlcpcb.com/) to produce high-quality circuit boards.

## ⚙️ 部署至 EasyEDA

1. 克隆本项目 [源代码](https://gitlab.soraharu.com/XiaoXi/Floppy-based-on-CH331A/-/archive/master/Floppy-based-on-CH331A-master.zip) 到本地
2. 在立创 EDA 标准版编辑器中选择 `文件` -> `打开` -> `立创EDA...`
3. 选择本项目源代码中的 `/EasyEDA/*.json` 文件并分别导入

## 🔤 字体

警告：本项目包含仅个人使用（禁止商用）的字体素材，虽然本设计授权用户在开源许可范围内的商业目的使用，但是项目所使用的字体库并不包含在该授权范围内，商业使用时请注意处理版权风险。

- SAO UI Regular | [下载](https://www.deviantart.com/darkblackswords/art/Sword-Art-Online-Font-Download-426603647) | [官方](https://www.deviantart.com/darkblackswords/art/Sword-Art-Online-Font-342305125) | Only for Personal Use, Not for Commercial Use

## 📜 开源许可

基于 [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/) 许可进行开源。

本设计已在 [中国版权保护中心](https://www.ccopyright.com.cn/) 登记注册。
