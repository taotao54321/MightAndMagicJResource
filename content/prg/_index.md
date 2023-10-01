+++
title = "PRG-ROM"
+++

本作はマッパー 4 ([MMC3](https://www.nesdev.org/wiki/MMC3)) であり、PRG-ROM は 0x2000 バイト単位のバンク 32 個からなる。ここでは PRG バンクIDを 0-based (`0..=31`) で扱う。

CPU メモリマップは以下の通り:

| 論理アドレス | 内容 |
| -- | -- |
| `$6000-$7FFF` | Save RAM |
| `$8000-$9FFF` | 可変バンク領域 |
| `$A000-$BFFF` | 可変バンク領域だが、PRG 29 がマップされていることが多い |
| `$C000-$FFFF` | 固定バンク領域。常に PRG 30, 31 がマップされる |

Save RAM は起動直後から常時有効化されている。

基本的には 1 つのセグメントが 1 つのバンク領域に対応するが、例外もある:

* PRG 21 は A, B の 2 つに分かれており、
  -  PRG 21-A (バンク内範囲 `0..=0x1A7F`) は PRG 15 と組み合わせてオーディオドライバセグメントを構成する。
  -  PRG 21-B (バンク内範囲 `0x1A80..=0x1FFF`) は独立したセグメント。
* PRG 23, 24 は連続した 1 セグメントであり、`$8000-$BFFF` にマップされる。

セグメント一覧は以下の通り (各セグメントの詳細はリンク先を参照):

| セグメント | 論理アドレス | 内容 |
| -- | -- | -- |
| [PRG  0](@/prg/prg-00/_index.md)                | `$8000-$9FFF` | イベント処理 (ポートスミスの町, アルガリーの町, ダスクの町, エルキューンの町) |
| [PRG  1](@/prg/prg-01/_index.md)                | `$8000-$9FFF` | イベント処理 (ソーピガルの地下, ノーザンバリアー洞穴, ポートスミスの地下, エルキューンの地下, ダスクの地下, コリンブルッフ洞穴) |
| [PRG  2](@/prg/prg-02/_index.md)                | `$8000-$9FFF` | イベント処理 (ボルカノ神殿, 鷹の目洞穴, ホワイトウルフ洞穴, バーン地上A1, バーン地上A2, バーン地上A3, バーン地上A4) |
| [PRG  3](@/prg/prg-03/_index.md)                | `$8000-$9FFF` | イベント処理 (バーン地上B1, バーン地上B2, アラマーの城, バーン地上B3, バーン地上B4, バーン地上C1) |
| [PRG  4](@/prg/prg-04/_index.md)                | `$8000-$9FFF` | イベント処理 (バーン地上C2, バーン地上C3, バーン地上C4, バーン地上D1, バーン地上D2, バーン地上D3, エルドラド地下2) |
| [PRG  5](@/prg/prg-05/_index.md)                | `$8000-$9FFF` | |
| [PRG  6](@/prg/prg-06/_index.md)                | `$8000-$9FFF` | イベント処理 (バーン地上E1, バーン地上E2, バーン地上E3, バーン地上E4, デュームの城) |
| [PRG  7](@/prg/prg-07/_index.md)                | `$8000-$9FFF` | イベント処理 (ホワイトウルフの城, ブラックリッジノース, ブラックリッジサウス, ドラガデューンの城) |
| [PRG  8](@/prg/prg-08/_index.md)                | `$8000-$9FFF` | イベント処理 (ドラガデューン地下1, ドラガデューン地下2, ドラガデューン地下3, 魔法の砦地下1, 魔法の砦地下2, バーン地上D4) |
| [PRG  9](@/prg/prg-09/_index.md)                | `$8000-$9FFF` | イベント処理 (森のあばら屋地下1, 森のあばら屋地下2, レイバン砦地下1, レイバン砦地下2, エルドラド地下1) |
| [PRG 10](@/prg/prg-10/_index.md)                | `$8000-$9FFF` | イベント処理 (エルドラド地下3, エルドラド地下4, アストラル世界, イドの迷宮, ソーピガルの町) |
| [PRG 11](@/prg/prg-11/_index.md)                | `$8000-$9FFF` | |
| [PRG 12](@/prg/prg-12/_index.md)                | `$8000-$9FFF` | |
| [PRG 13](@/prg/prg-13/_index.md)                | `$8000-$9FFF` | |
| [PRG 14](@/prg/prg-14/_index.md)                | `$8000-$9FFF` | |
| [PRG 15 + PRG 21-A](@/prg/prg-15-21a/_index.md) | `$8000-$BA7F` | オーディオドライバ |
| [PRG 16](@/prg/prg-16/_index.md)                | `$8000-$9FFF` | |
| [PRG 17](@/prg/prg-17/_index.md)                | `$8000-$9FFF` | 戦闘関連 |
| [PRG 18](@/prg/prg-18/_index.md)                | `$8000-$9FFF` | 魔法関連 |
| [PRG 19](@/prg/prg-19/_index.md)                | `$8000-$9FFF` | |
| [PRG 20](@/prg/prg-20/_index.md)                | `$8000-$9FFF` | |
| [PRG 21-B](@/prg/prg-21b/_index.md)             | `$9A80-$9FFF` | |
| [PRG 22](@/prg/prg-22/_index.md)                | `$8000-$9FFF` | |
| [PRG 23-24](@/prg/prg-23-24/_index.md)          | `$8000-$BFFF` | |
| [PRG 25](@/prg/prg-25/_index.md)                | `$8000-$9FFF` | マップデータ ([マップID](@/map/_index.md) `1..=16`) |
| [PRG 26](@/prg/prg-26/_index.md)                | `$8000-$9FFF` | マップデータ ([マップID](@/map/_index.md) `17..=32`) |
| [PRG 27](@/prg/prg-27/_index.md)                | `$8000-$9FFF` | マップデータ ([マップID](@/map/_index.md) `33..=48`) |
| [PRG 28](@/prg/prg-28/_index.md)                | `$8000-$9FFF` | マップデータ ([マップID](@/map/_index.md) `49..=55`), マップメタデータテーブル |
| [PRG 29](@/prg/prg-29/_index.md)                | `$A000-$BFFF` | 汎用的なコード/データ |
| [PRG 30-31](@/prg/prg-30-31/_index.md)          | `$C000-$FFFF` | 汎用的なコード/データ |