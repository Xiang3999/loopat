# 巴厘岛追海豚游戏 · three.js 视觉研究

用 three.js 复原 Lovina(巴厘岛北部)清晨出海追海豚场景的概念验证。
全部素材程序化生成,无外部资源依赖。

- `dawn.html` — 第一版:日出天空(Sky)+ 海面(Water + 程序化法线贴图)+ 船只剪影
- `lovina.html` — 复原版:程序化海豚(圆弧脊柱 + 背鳍/尾鳍/胸鳍)、jukung 翘首船、
  第一人称坐船视角(船头入画)、水花、远山、晨雾

## 运行

```bash
npm install three
npx serve .   # 或任意静态服务器(ES module 不能用 file:// 直接打开)
```

打开 `lovina.html` 即可。渲染单帧,供视觉参数调试用。
