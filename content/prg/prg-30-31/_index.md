+++
title = "PRG 30-31"
+++

論理アドレス `$C000-$FFFF` にマップされるセグメント。

固定バンクであり、汎用的なコード/データを含む。

## メモリマップ

| アドレス | 内容 |
| -- | -- |
| | {% todo() %}TODO{% end %} |
| `$DF04` | IRQ 割り込みハンドラ (ポインタ `$0204` が指すルーチンへ飛ぶ) |
| | {% todo() %}TODO{% end %} |
| `$FA93-$FAA4` | (未使用) |
| | {% todo() %}TODO{% end %} |
| `$FF6D-$FF6F` | (未使用) |
| `$FF70` | RESET 割り込みハンドラ (ソフトウェアから呼ばれる場合もある) |
| `$FFE6` | {% todo() %}TODO{% end %} |
| `$FFEF` | NMI 割り込みハンドラ (ポインタ `$067E` が指すルーチンへ飛ぶ) |
| `$FFF2-$FFF9` | (未使用) |
| `$FFFA` | 割り込みベクタ |