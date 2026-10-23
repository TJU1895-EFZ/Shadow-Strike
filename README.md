# 暗影突袭 · SHADOW STRIKE

一款基于 Three.js 的浏览器第一人称射击（FPS）生存游戏。单文件实现，无需构建，打开即玩。

击退一波波来袭的敌人，尽可能活下去。

## 在线游玩

GitHub Pages：https://tju1895-efz.github.io/Shadow-Strike/

## 操作

| 按键 | 功能 |
| --- | --- |
| `W` `A` `S` `D` | 移动 |
| 鼠标 | 瞄准 / 射击 |
| `Shift` | 疾跑 |
| `空格` | 跳跃 |
| `R` | 装填 |

## 玩法

- 敌人按波次刷新，波数越高，敌人越强
- 击杀敌人积累分数，屏幕右上角显示击杀信息
- 生命值显示在左下角，血量归零游戏结束

## 技术

- 纯 HTML / CSS / JavaScript，单文件 `index.html`
- 3D 渲染：[Three.js](https://threejs.org/) r158（通过 jsDelivr CDN 引入）
- 包含电影级滤镜：暗角、颗粒、遮幅黑边、色彩分级、受击闪红等效果

## 本地运行

直接用浏览器打开 `index.html`，或在目录中启动任意静态服务器：

```bash
python -m http.server 8000
# 然后访问 http://localhost:8000
```

> 需要联网加载 Three.js CDN。
