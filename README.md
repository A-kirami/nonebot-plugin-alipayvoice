<div align="center">
  <a href="https://v2.nonebot.dev/store"><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo"></a>
  <br>
  <p><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>

<div align="center">

# nonebot-plugin-alipayvoice

_✨ 支付宝到账0.5元（ ✨_


<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/A-kirami/nonebot-plugin-alipayvoice.svg" alt="license">
</a>
<a href="https://pypi.python.org/pypi/nonebot-plugin-alipayvoice">
    <img src="https://img.shields.io/pypi/v/nonebot-plugin-alipayvoice.svg" alt="pypi">
</a>
<img src="https://img.shields.io/badge/python-3.8+-blue.svg" alt="python">

</div>

## 📖 介绍

发送支付宝到账语音, 支持金额范围为0.01~999999999999.99

## 💿 安装

<details>
<summary>使用 nb-cli 安装</summary>
在 nonebot2 项目的根目录下打开命令行, 输入以下指令即可安装

    nb plugin install nonebot-plugin-alipayvoice

</details>

<details>
<summary>使用包管理器安装</summary>
在 nonebot2 项目的插件目录下, 打开命令行, 根据你使用的包管理器, 输入相应的安装命令

<details>
<summary>pip</summary>

    pip install nonebot-plugin-alipayvoice
</details>
<details>
<summary>pdm</summary>

    pdm add nonebot-plugin-alipayvoice
</details>
<details>
<summary>poetry</summary>

    poetry add nonebot-plugin-alipayvoice
</details>
<details>
<summary>conda</summary>

    conda install nonebot-plugin-alipayvoice
</details>

打开 nonebot2 项目的 `bot.py` 文件, 在其中写入

    nonebot.load_plugin('nonebot_plugin_alipayvoice')

</details>


## 🎉 使用
### 指令表
| 指令 | 说明 |
|:-----:|:----:|
| 支付宝到账 + 金额 | 发送对应金额到账的支付宝语音 |

