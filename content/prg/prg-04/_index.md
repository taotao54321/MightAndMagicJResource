+++
title = "PRG 4"
+++

論理アドレス `$8000-$9FFF` にマップされるセグメント。

以下のマップのイベント処理を行う:

* バーン地上C2
* バーン地上C3
* バーン地上C4
* バーン地上D1
* バーン地上D2
* バーン地上D3
* エルドラド地下2

## メモリマップ

| アドレス | 内容 |
| -- | -- |
| `$8000` | (エクスポート) ルーチン `$8015` を呼ぶ |
| `$8003` | (エクスポート) ルーチン `$8344` を呼ぶ |
| `$8006` | (エクスポート) ルーチン `$85A7` を呼ぶ |
| `$8009` | (エクスポート) ルーチン `$8800` を呼ぶ |
| `$800C` | (エクスポート) ルーチン `$8A7B` を呼ぶ |
| `$800F` | (エクスポート) ルーチン `$8DC0` を呼ぶ |
| `$8012` | (エクスポート) ルーチン `$9119` を呼ぶ |
| `$8015` | イベントルーチン: バーン地上C2 |
| | {% todo() %}TODO{% end %} |
| `$8344` | イベントルーチン: バーン地上C3 |
| | {% todo() %}TODO{% end %} |
| `$85A7` | イベントルーチン: バーン地上C4 |
| | {% todo() %}TODO{% end %} |
| `$8800` | イベントルーチン: バーン地上D1 |
| | {% todo() %}TODO{% end %} |
| `$8A7B` | イベントルーチン: バーン地上D2 |
| | {% todo() %}TODO{% end %} |
| `$8DC0` | イベントルーチン: バーン地上D3 |
| | {% todo() %}TODO{% end %} |
| `$9119` | イベントルーチン: エルドラド地下2 |
| | {% todo() %}TODO{% end %} |
| `$9395-$9E17` | メッセージデータ |
| `$9E18-$9FFF` | (未使用) |
