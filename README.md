# 烧脑日历

[简体中文](#简体中文) · [English](#english) · [English README](README.en.md)

## 简体中文

一个无需构建工具、直接在浏览器中运行的 H5 日历拼图小游戏。玩家通过拖动、旋转和翻转连通拼块，露出目标月份、日期和星期以获得胜利。

<video src="https://raw.githubusercontent.com/willldx-git/brain-calendar-puzzle/main/assets/brain-calendar-demo.mov" controls muted playsinline width="100%"></video>

[播放游戏演示视频（MOV，约 6 秒）](assets/brain-calendar-demo.mov)

### 在线体验

仓库启用 GitHub Pages 后，可通过项目主页访问游戏。

### 本地运行

直接用浏览器打开 `index.html` 即可，无需安装依赖或启动构建工具。

### 操作方式

- 拖动拼块到棋盘，靠近格子时会自动吸附。
- 单击拼块可拿起并让它跟随鼠标；滚轮旋转、右键翻转，在棋盘上左键放置。也可继续使用拖动方式。
- 点击已放置的拼块进行选中，再使用旋转或翻转按钮调整方向。
- 将拼块拖出棋盘后松开，可将它放回待选区。
- 可以撤销上一步。拼成后棋盘会锁定，可重开或更换日期开始新挑战。
- 新局棋盘为空时可使用“首块提示”，之后“继续提示”还可放置一块；

### 项目文件

- `index.html`：游戏页面、样式和交互逻辑。
- `assets/brain-calendar-demo.mov`：约 6 秒的游戏演示视频，画面根据当前游戏界面和拼块定义制作。
- `design-options/`：早期界面风格方案。
- `设计稿-木质玩具风格.svg`、`2026-10-21-拼图摆放图.svg`：设计参考图。

### 许可

本项目以 MIT License 发布，详见 [LICENSE](LICENSE)。

### 作者

By Will

## English

A browser-based H5 calendar puzzle game with no build tools or dependencies. Drag, rotate, and flip connected polyomino pieces to uncover the target month, day, and weekday.

### Run locally

Open `index.html` in a modern browser. No installation or build step is required.

### How to play

- Drag a piece onto the board; it snaps to nearby cells.
- Select a placed piece, then use Rotate or Flip to change its orientation.
- Drag a piece outside the board and release it to return it to the tray.
- Use Undo to reverse your last move. Completing the puzzle locks the board. Use Restart or Change date to start another challenge.
- On a fresh, empty board, “First-piece hint” places one randomly selected piece correctly; one more actual placement is available through “Continue hint”. If you place a piece manually first, only one actual hint placement is available. When two or more pieces are already on the board, clicking “Continue hint” shows “Only hint when fewer than 2 pieces are placed”. After the hint allowance is used up, clicking again opens the recharge-code or text-entry dialog. Each round allows at most two hinted pieces; undoing or moving pieces does not restore uses. Restarting or changing the date resets the count.
- Completing a puzzle shows your elapsed time, hints used, and total completions today. The timer starts when a hint places a piece or when you first place a piece successfully. Zero hours and minutes are omitted.

### Project files

- `index.html`: the game UI, styles, and interaction logic.
- `design-options/`: early visual style explorations.
- `设计稿-木质玩具风格.svg` and `2026-10-21-拼图摆放图.svg`: design reference images.

### License

Released under the MIT License. See [LICENSE](LICENSE).

### Author

By Will
