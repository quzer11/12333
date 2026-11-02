# 双子星

郭智淳 × 顾景豪，一张网页里的双主角展示。

打开或刷新网页就会播放约六秒的双人片头。03、02、01 倒数过后，两颗粉蓝彗星带出郭智淳的香肠头和顾景豪的火柴头海报，最后亮出“双子星”片名。

## 打开

直接用浏览器打开 `index.html`、`双子星.html` 或 `沪深股票1443.html`。三个入口内容相同；后者保留原先指定的文件名。
下载仓库后请保留同目录的 `assets` 文件夹。

需要本地服务器时，在仓库目录运行：

```sh
python3 -m http.server 8000
```

访问 `http://localhost:8000`。无需安装任何依赖。

## 交互

- 在后台标签页打开时，片头等到切换至该页再播放。可以点击跳过或按 Esc，也可以在首页重播。
- 开启系统“减少动态效果”时直接进入首页。
- 两位主角都有单人舞台出场动画。
- 暂停特效、系统减少动态效果适配、手机布局。
- 顾景豪的人像/火柴头特效切换，以及查看原始特效截图。
- 七张 AI 海报支持放大和下载，其中郭智淳四张，顾景豪三张。

## 素材

- `assets/portrait.jpg`：郭智淳的原照片。
- `assets/poster-stage.png`、`poster-cyber.png`、`poster-comic.png`：郭智淳的 AI 创意海报。
- `assets/poster-sausage.png`：郭智淳的 AI 香肠头特效海报。
- `assets/gu-jinghao-portrait.jpg`：顾景豪的人像照片。
- `assets/gu-jinghao-effect.jpg`：用户提供的顾景豪特效截图。
- `assets/gu-poster-star.png`、`gu-poster-neon.png`、`gu-poster-match.png`：顾景豪的蓝色星光、霓虹出场和火柴头 AI 海报。
- `assets/intro-guo.jpg` 和 `assets/intro-gu.jpg`：片头先加载的两张轻量海报。
- `创作与使用说明.txt`：使用说明与七张海报的生成提示词。

原照片未做生成式修改。AI 海报属于创意画面，不表示真实拍摄场景。
