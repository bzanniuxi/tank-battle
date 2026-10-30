# 坦克大战 · Tank Battle

一个用纯 HTML5 Canvas + JavaScript 写的经典《坦克大战》小游戏，单文件、零依赖，浏览器打开即玩。

## 在线试玩

GitHub Pages 地址（部署后）：

```
https://<你的用户名>.github.io/tank-battle/
```

也可以直接把 `index.html` 拖进浏览器本地打开。

## 玩法

- **移动**：方向键 / `WASD`
- **射击**：空格 / `J`
- **暂停**：`P` / `Esc`
- 手机/触屏设备会自动显示屏幕方向键和开火按钮

## 规则

- 守住屏幕底部的**金色基地**，别让它被敌方坦克摧毁
- 消灭本关所有敌方坦克即可过关，敌人会逐关变多
- 你有 3 条命，被击中会重生
- 砖墙（`#`）可被子弹摧毁，钢墙（`@`）打不穿

## 本地运行

无需安装任何东西：

```bash
# 方式一：直接双击 index.html
# 方式二：起一个本地静态服务
python3 -m http.server 8000
# 然后浏览器访问 http://localhost:8000
```

## 部署到 GitHub Pages

在仓库 **Settings → Pages** 里把 Source 选为 `main` 分支根目录（`/ (root)`），保存后等一分钟即可访问。
