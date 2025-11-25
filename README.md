# 爱心大作战 ❤️

一个浪漫的HTML5小游戏，通过左右滑动小熊接住爱心，收集爱意值。

## 游戏说明

- 左右滑动（或鼠标移动）控制小熊移动
- 接住 ❤️ 爱心、🍬 糖果、🌹 玫瑰增加爱意值
- 躲避 💣 炸弹和 🥦 西兰花
- 收集满100%爱意值即可获胜

## 部署说明

### 通过 GitHub Pages 部署

1. 在 GitHub 上创建一个新仓库
2. 将代码推送到仓库：
   ```bash
   git remote add origin <你的仓库URL>
   git branch -M main
   git push -u origin main
   ```
3. 在仓库设置中启用 GitHub Pages：
   - 进入 Settings > Pages
   - Source 选择 `main` 分支
   - 保存后，你的游戏将在 `https://<你的用户名>.github.io/<仓库名>/love_game.html` 访问

### 或者使用 index.html

如果想直接通过根URL访问，可以将 `love_game.html` 重命名为 `index.html`，这样访问 `https://<你的用户名>.github.io/<仓库名>/` 即可。

