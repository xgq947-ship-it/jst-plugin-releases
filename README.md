# 聚水潭执行插件 · 版本发布

这里发布供 PDD AI客服 使用的聚水潭执行插件安装包和中文更新说明。

## 安装与更新

在 AI客服「设置 → 聚水潭插件 → 远程更新」点击「检查更新」，查看说明后点击「更新到 1.0.0」（后续会显示当时的最新版本）。

新版 AI客服 已预设更新地址；旧版如需填写，只需设置一次：

```text
https://raw.githubusercontent.com/xgq947-ship-it/jst-plugin-releases/main/latest.json
```

首次安装也可以前往 [最新版本](https://github.com/xgq947-ship-it/jst-plugin-releases/releases/latest) 下载 `.pddplugin`，在 AI客服 中安装，然后登录聚水潭并配置店铺对照。

支持 macOS 和 Windows；需要 AI客服 具备插件安装能力，远程更新需要对应的控制台和后台接口。Windows 真机安装和业务执行尚未验收。

## 更新说明

参见 [更新说明](CHANGELOG.md) 或每个 [Release](https://github.com/xgq947-ship-it/jst-plugin-releases/releases) 的说明。

安装包包含运行所需插件代码，并经过签名与文件校验。不包含账号、Cookie、登录存档、店铺对照、私钥或本机配置。更新保留本机登录和店铺对照；需要人点击才安装。

本仓库只用于版本分发；开发仓库保持私有。
