# 2024aug-taikenkai
2024 年度「中学生の科学実験教室」(https://kagaku.isee.kyushu-u.ac.jp/) の準備用レポジトリ
参考: https://learn.adafruit.com/welcome-to-circuitpython

## プログラム
- btn_oled: SECCON2023のボード上の赤、緑、青、白ボタンを押すとOLEDディスプレイ上に対応した色の名前が表示されるプログラム
- pingpong: Ping-Pongゲームのプログラム
- pingpong_optimized: pingpongの改良版で、ディスプレイの更新を少なくして高速化している

## 手順
### ボードにCircuitPythonをインストール
参考: https://learn.adafruit.com/welcome-to-circuitpython/installing-circuitpython

### ライブラリバンドルをダウンロード 
参考: https://learn.adafruit.com/welcome-to-circuitpython/circuitpython-libraries

### 以下のライブラリをボードの`/lib`フォルダに入れる 
- `adafruit_displayio_ssd1306.mpy` 
- `adafruit_framebuf.mpy` 
- `adafruit_ssd1306.mpy` 

### ボードの`/code.py`にプログラムを書き込む