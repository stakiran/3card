# 3card
Idea creation tool with 3 cards.

![demo_3card](https://user-images.githubusercontent.com/23325839/66474667-b4db2700-eacc-11e9-90be-ea73f6f40b19.gif)

## Overview
3card とは、カードリストから 3 枚のカードを次々に(自分のペースで)表示させることでアイデア創出を支援するフレームワークです。

以下でパソコン用ツールを公開しています（スマホは非対応）。

→ [https://stakiran.github.io/3card/](https://stakiran.github.io/3card/)

## How to use
まずはカードをつくります。

- 1: カードエリアにカードを **一行一記述** で追加します
- 2: カードエリアからフォーカスを外します(クリックや Tab キー等)

すると下部にカードがずらりと並びますので、以下のようにして 3 card を組み合わせていきます。

- 1: スロット選択
  - スロット 1～3 のうち、カードを置きたいものをクリックする(青色が選択の目印です)
  - キーボードの <kbd>1</kbd> <kbd>2</kbd> <kbd>3</kbd> でも可
- 2: カードセット
  - スロットに置きたいカードをマウスカーソルでなぞる
  - キーボードの <kbd>Left</kbd> や <kbd>Right</kbd> でも可
- 3: スロットロック
  - スロットの内容を固定したい場合、<kbd>Space</kbd> キーで固定できます(赤枠がロックの目印です)

## Keyboard Shortcuts
:warning: ただしフォーカスがカードエリア(テキストボックス)に入っている間は効きません。

| Key | Action |
| --- | ------ |
| <kbd>1</kbd> | スロット 1 を選択 |
| <kbd>2</kbd> | スロット 2 を選択 |
| <kbd>3</kbd> | スロット 3 を選択 |
| <kbd>Esc</kbd> | 選択中のスロットをクリア |
| <kbd>Delete</kbd> | すべてのスロットをクリア |
| <kbd>Space</kbd> | 選択中のスロットをロック or ロック解除(Lキーは離れていて押しづらい) |
| <kbd>L</kbd> | 選択中のスロットをロック or ロック解除 |
| <kbd>Left</kbd> | 一つ前のカードを選択(選択中のスロットにセット) |
| <kbd>Right</kbd> | 一つ後のカードを選択(選択中のスロットにセット) |

## License
[MIT License](LICENSE)

## Author
[stakiran](https://github.com/stakiran)
