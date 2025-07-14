# snakeV1（C++）

這是使用 C++ 製作的貪食蛇遊戲，支援即時鍵盤操作、碰撞與結束判斷以及長度判斷。

## 功能特色

- 終端畫面輸出（使用 `ncurses` 函式庫）
- 蛇可上下左右移動
- 吃食物會使蛇長縮短
- 撞牆或自撞即結束遊戲
- 鍵盤控制蛇身移動

## 關於此遊戲

- 語言：C++
- 函式庫：`ncurses.h`
- 編譯器：`g++`
### 安裝 ncurses（Linux/macOS）與編譯

```bash
sudo apt install libncurses5-dev    # Ubuntu / Debian
brew install ncurses                # macOS
g++ main.cpp -lncurses -o snake

