# gongju

小工具合集。

## 鱼鱼找鸡（coser-image-search）

给一张图，反查这人是谁、账号在哪。多引擎（谷歌 Lens / SauceNAO / trace.moe / IQDB / 百度），
零 npm 依赖，可当命令行用，也可以挂到 QQ 机器人上。

**下载**：[`鱼鱼找鸡-插件-v1.1.0.zip`](./鱼鱼找鸡-插件-v1.1.0.zip)（解压即用，看包里的 README.md）

```bash
node bin/fish.mjs 图片.jpg          # 命令行查图
node host.mjs                       # 挂 QQ 机器人（要先配 host.config.json）
```
