# vtuber

[![CI](https://github.com/YunYouJun/vtuber/actions/workflows/ci.yml/badge.svg)](https://github.com/YunYouJun/vtuber/actions/workflows/ci.yml)
[![GitHub deployments](https://img.shields.io/github/deployments/YunYouJun/vtuber/production?label=vercel&logo=vercel&logoColor=white)](https://vercel.com/yunyoujun/vtuber)

从一开始的 Vtuber。

> 为什么是从「一」开始，因为「零」已经有人用了，此外因为个人能力有限，过程中应该会可能尽可能使用一些已有的轮子。那么「一」便代表前辈们吧。（~~没有任何特殊含义~~）

- [奇怪的指南](https://docs.vtuber.yunyoujun.cn)
- [在线示例](https://vtuber.yunyoujun.cn)

![Preview](./docs/public/gif/preview-1.gif)

目前正在进行的工作：尽管 Three.js 的使用十分广泛，但从代码质量与类型提示上来看，我更喜欢 [Babylon.js](https://github.com/BabylonJS/Babylon.js)，因此我会将其图形渲染部分逐渐使用 Babylon 进行重构。（Please `packages/client/src/pages/babylon.vue`）

## Usage

```bash
# install dependencies
pnpm i

# dev
pnpm run dev
```

## Dev

### Docs

```bash
# 构建文档
pnpm docs:build
# docs/.vitepress/dist
```

## Base

- ~~[face-api.js](https://github.com/justadudewhohacks/face-api.js/)~~
- [google/mediapipe](https://github.com/google/mediapipe)
  - [Holistic](https://google.github.io/mediapipe/solutions/holistic.html)
- [kalidokit](https://github.com/yeemachine/kalidokit)

## Thanks

- [Alicia Solid | VRoid Hub](https://hub.vroid.com/characters/515144657245174640/models/6438391937465666012)
  - 利用条件: アバターOK/暴力表現OK/性的表現OK/法人OK/個人商用OK - 同人OK/改変OK/再配布OK/クレジット表記不要
- [Kizuna AI official website](https://kizunaai.com/): 非商业模型免费使用
