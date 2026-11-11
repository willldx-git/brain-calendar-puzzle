# Brain Calendar Puzzle

[English](#english) · [简体中文](#简体中文) · [中文 README](README.md)

## English

A browser-based H5 calendar puzzle game with no build tools or dependencies. Drag, rotate, and flip connected polyomino pieces to uncover the target month, day, and weekday.

<video src="https://raw.githubusercontent.com/willldx-git/brain-calendar-puzzle/main/assets/brain-calendar-demo.mov" controls muted playsinline width="100%"></video>

[Watch the short gameplay video (MOV, about 6 seconds)](assets/brain-calendar-demo.mov)

### Run locally

Open `index.html` in a modern browser. No installation or build step is required.

### How to play

- Drag a piece onto the board; it snaps to nearby cells.
- Select a placed piece, then use Rotate or Flip to change its orientation.
- Drag a piece outside the board and release it to return it to the tray.
- Use Undo, Restart, or Change date to start another challenge.
- On a fresh, empty board, “First-piece hint” places one randomly selected piece correctly; one more actual placement is available through “Continue hint”. If you place a piece manually first, only one actual hint placement is available. When two or more pieces are already on the board, clicking “Continue hint” shows “Hints are available only with fewer than 2 pieces placed”. After the hint allowance is used up, clicking again opens the recharge-code or text-entry dialog. Each round allows at most two hinted pieces; undoing or moving pieces does not restore uses. Restarting or changing the date resets the count.
- Completing the target reveals a celebration animation, elapsed time, and hint count. The timer starts with the first hint click or first successful placement and is shown as HH:MM:SS.

### Project files

- `index.html`: the game UI, styles, and interaction logic.
- `assets/brain-calendar-demo.mov`: a short gameplay video using the current game interface and piece definitions.
- `design-options/`: early visual style explorations.
- `设计稿-木质玩具风格.svg` and `2026-10-21-拼图摆放图.svg`: design reference images.

### License

Released under the MIT License. See [LICENSE](LICENSE).

### Author

By Will

## 简体中文

这是一个无需构建工具、直接在浏览器中运行的 H5 日历拼图小游戏。拖动、旋转和翻转连通拼块，露出目标月份、日期和星期。

### 本地运行

直接用现代浏览器打开 `index.html` 即可，无需安装依赖或构建。

### 操作方式

- 将拼块拖到棋盘，靠近格子时会自动吸附。
- 选中棋盘上的拼块后，使用“旋转”或“翻转”调整方向。
- 将拼块拖出棋盘后松开，可放回待选区。
- 使用“撤销”“重开”或“换日期”开始新挑战。
- 新局棋盘为空时可使用“首块提示”，之后“继续提示”还可放置一块；如果先手动放置拼块，则只提供一次实际提示。棋盘上已放置两块或更多拼块，或提示额度用完后，点击“继续提示”会打开充值码或输入文字弹窗，不会增加提示次数。每局最多放置两块提示拼块，撤销或移动拼块不会恢复次数，重开本局或更换日期后重置。
- 拼出目标后会显示庆祝动画、用时和提示次数；计时从首次点击提示或首次成功落子开始，格式为时:分:秒。

### 许可

本项目以 MIT License 发布，详见 [LICENSE](LICENSE)。

### 作者

By Will