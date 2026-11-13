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
- Click a piece to pick it up and attach it to the cursor. Use the wheel to rotate, right-click to flip, and left-click the board to place it. Drag and drop still works too.
- Select a placed piece, then use Rotate or Flip to change its orientation.
- Drag a piece outside the board and release it to return it to the tray.
- Use Undo to reverse your last move. Completing the puzzle locks the board. Use Restart or Change date to start another challenge.
- On a fresh, empty board, “First-piece hint” places one randomly selected piece correctly; one more actual placement is available through “Continue hint”. If you place a piece manually first, only one actual hint placement is available. When two or more pieces are already on the board, clicking “Continue hint” shows “Hints are available only with fewer than 2 pieces placed”. After the hint allowance is used up, clicking again opens the recharge-code or text-entry dialog. Each round allows at most two hinted pieces; undoing or moving pieces does not restore uses. Restarting or changing the date resets the count.
- Completing a puzzle shows your elapsed time, hints used, and total completions today. The timer starts when a hint places a piece or when you first place a piece successfully. Zero hours and minutes are omitted.
- Daily totals cover all target dates and start at local midnight. The dialog shows a time improvement when you beat your previous time for the same target that day. On the first completion of a target that day, it also shows the total hints and restarts if you used both. Daily progress is stored in the current browser.
- The victory dialog and piece tray show how many solutions the target date has and how many you have found. Each layout counts once, and progress is stored in the current browser for each target date. Hints lead to undiscovered solutions until you find them all. The final new solution triggers a special victory dialog.

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
- 可以撤销上一步。拼成后棋盘会锁定，可重开或更换日期开始新挑战。
- 新局棋盘为空时可使用“首块提示”，之后“继续提示”还可放置一块；如果先手动放置拼块，则只提供一次实际提示。棋盘上已有两块或更多拼块时，点击“继续提示”会提示“只有摆放2块以下时方可提示”；提示额度用完后再次点击则打开充值码或输入文字弹窗。每局最多放置两块提示拼块，撤销或移动拼块不会恢复次数，重开本局或更换日期后重置。
- 拼成后显示本局用时、提示次数和今日累计拼成次数。用时从首次获得提示或首次成功落子开始，省略为零的小时和分钟。
- 今日次数按电脑本地时间从午夜起累计，包含所有目标日期。同一目标当天再次拼成且比上一次更快时，弹窗会显示快了多少。当天首次拼成某个目标时，如果实际获得过提示且重开过，也会显示累计提示和重开次数。当天进度保存在当前浏览器中。
- 胜利弹窗和待选区会显示目标日期的拼法总数和已拼出的种数。每种摆法只计一次，进度按目标日期保存在当前浏览器中。集齐前，提示只引导到尚未完成的拼法。拼出最后一种时会触发特别胜利弹窗。

### 许可

本项目以 MIT License 发布，详见 [LICENSE](LICENSE)。

### 作者

By Will
