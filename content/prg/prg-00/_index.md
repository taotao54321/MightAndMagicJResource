+++
title = "PRG 0"
+++

論理アドレス `$8000-$9FFF` にマップされるセグメント。

以下のマップのイベント処理を行う:

* ポートスミスの町
* アルガリーの町
* ダスクの町
* エルキューンの町

## メモリマップ

| アドレス | 内容 |
| -- | -- |
| `$8000` | (エクスポート) ルーチン `$800C` を呼ぶ |
| `$8003` | (エクスポート) ルーチン `$854B` を呼ぶ |
| `$8006` | (エクスポート) ルーチン `$89E8` を呼ぶ |
| `$8009` | (エクスポート) ルーチン `$8F28` を呼ぶ |
| `$800C` | イベントルーチン: ポートスミスの町 |
| | {% todo() %}TODO{% end %} |
| `$854B` | イベントルーチン: アルガリーの町 |
| | {% todo() %}TODO{% end %} |
| `$89E8` | イベントルーチン: ダスクの町 |
| | {% todo() %}TODO{% end %} |
| `$8F28` | イベントルーチン: エルキューンの町 |
| | {% todo() %}TODO{% end %} |
| `$94FF-$9FEC` | メッセージデータ |
| `$9FED-$9FFF` | (未使用) |
