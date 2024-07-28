# Coyote-Majsoul 雀魂自动开电

## 介绍

此项目基于 [majsoul-analyser](https://github.com/HomeArchbishop/majsoul-analyser) ，借助 [DG-Lab-Coyote-Streaming-Widget](https://github.com/hyperzlib/DG-Lab-Coyote-Streaming-Widget) 实现雀魂郊狼小游戏

## 支持平台

- Windows Steam 雀魂
- 网页版雀魂

## 基本使用

从 [Release](https://github.com/hyperzlib/Coyote-Majsoul/releases) 下载最新版本，解压后运行 ```coyote-majsoul.exe``` 即可。

如果需要在网页版雀魂中使用，请安装 **[Tampermonkey](https://www.tampermonkey.net/)** 插件，然后 **[点击这里安装脚本 (通过GreasyFork)](https://greasyfork.org/zh-CN/scripts/502006-%E9%9B%80%E9%AD%82%E9%83%8A%E7%8B%BC%E7%9B%91%E5%90%AC%E5%99%A8)**。

### Windows Steam 雀魂

安装依赖，推荐使用 PNPM，为了兼容性，以下示例仍使用 NPM：

```bash
npm install
```

下载 **[proxinject](https://github.com/PragmaTwice/proxinject/releases)**，解压后放在 ```bin/proxinject``` 目录下。（如果不需要使用Windows Steam 雀魂，可以跳过）

运行以下命令启动服务：

```bash
npm run start
```

### 网页版雀魂

```bash
npm install
npm run build:user
```

在浏览器中安装 **[Tampermonkey](https://www.tampermonkey.net/)** 插件，然后安装 ```dist/majsoul-analyser.user.js``` 脚本。

运行以下命令启动服务：

```bash
npm run start
```

待更新
