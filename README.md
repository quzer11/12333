# 双子星

郭智淳 × 顾景豪，一张网页里的双主角展示。

郭智淳使用粉色舞台配色，顾景豪使用蓝色星光配色。两位主角都能单独出场，也能一起登场；顾景豪还可以切换人像与 AI 火柴头特效海报。

## 打开

直接用浏览器打开 `index.html`、`双子星.html` 或 `沪深股票1443.html`。三个入口内容相同；后者保留原先指定的文件名。
下载仓库后请保留同目录的 `assets` 文件夹。

需要本地服务器时，在仓库目录运行：

```sh
python3 -m http.server 8000
```

访问 `http://localhost:8000`。无需安装任何依赖。

## 交互

- 舞台出场、聚光灯、姓名与彩纸，支持跳过和 Escape。
- 暂停特效、系统减少动态效果适配、手机布局。
- 顾景豪的人像/火柴头特效切换，以及查看原始特效截图。
- 两位主角各三张 AI 海报，支持放大和下载。

## 素材

- `assets/portrait.jpg`：郭智淳的原照片。
- `assets/poster-stage.png`、`poster-cyber.png`、`poster-comic.png`：郭智淳的 AI 创意海报。
- `assets/gu-jinghao-portrait.jpg`：顾景豪的人像照片。
- `assets/gu-jinghao-effect.jpg`：用户提供的顾景豪特效截图。
- `assets/gu-poster-star.png`、`gu-poster-neon.png`、`gu-poster-match.png`：顾景豪的蓝色星光、霓虹出场和火柴头 AI 海报。
- `创作与使用说明.txt`：使用说明与此前海报的生成提示词。

原照片未做生成式修改。AI 海报属于创意画面，不表示真实拍摄场景。
