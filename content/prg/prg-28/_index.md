+++
title = "PRG 28"
+++

論理アドレス `$8000-$9FFF` にマップされるセグメント。

マップメタデータテーブル、および以下のマップデータを格納している:

* レイバン砦地下2
* エルドラド地下1
* エルドラド地下2
* エルドラド地下3
* エルドラド地下4
* アストラル世界
* イドの迷宮

## メモリマップ

| アドレス | 内容 |
| -- | -- |
| `$8000` | レイバン砦地下2 [マップ境界配列](@/data-structure/place-boundarys/_index.md) |
| `$8100` | レイバン砦地下2 [マップ各種フラグ配列](@/data-structure/place-flags/_index.md) |
| `$8200` | エルドラド地下1 [マップ境界配列](@/data-structure/place-boundarys/_index.md) |
| `$8300` | エルドラド地下1 [マップ各種フラグ配列](@/data-structure/place-flags/_index.md) |
| `$8400` | エルドラド地下2 [マップ境界配列](@/data-structure/place-boundarys/_index.md) |
| `$8500` | エルドラド地下2 [マップ各種フラグ配列](@/data-structure/place-flags/_index.md) |
| `$8600` | エルドラド地下3 [マップ境界配列](@/data-structure/place-boundarys/_index.md) |
| `$8700` | エルドラド地下3 [マップ各種フラグ配列](@/data-structure/place-flags/_index.md) |
| `$8800` | エルドラド地下4 [マップ境界配列](@/data-structure/place-boundarys/_index.md) |
| `$8900` | エルドラド地下4 [マップ各種フラグ配列](@/data-structure/place-flags/_index.md) |
| `$8A00` | アストラル世界 [マップ境界配列](@/data-structure/place-boundarys/_index.md) |
| `$8B00` | アストラル世界 [マップ各種フラグ配列](@/data-structure/place-flags/_index.md) |
| `$8C00` | イドの迷宮 [マップ境界配列](@/data-structure/place-boundarys/_index.md) |
| `$8D00` | イドの迷宮 [マップ各種フラグ配列](@/data-structure/place-flags/_index.md) |
| `$8E00` | 各[マップメタデータ](@/data-structure/place-metadata/_index.md)へのポインタテーブル |
| `$8E6E` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ソーピガルの町 |
| `$8EBC` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ポートスミスの町 |
| `$8F0A` | [マップメタデータ](@/data-structure/place-metadata/_index.md): アルガリーの町 |
| `$8F58` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ダスクの町 |
| `$8FA6` | [マップメタデータ](@/data-structure/place-metadata/_index.md): エルキューンの町 |
| `$8FF4` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ソーピガルの地下 |
| `$9042` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ノーザンバリアー洞穴 |
| `$9090` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ポートスミスの地下 |
| `$90DE` | [マップメタデータ](@/data-structure/place-metadata/_index.md): エルキューンの地下 |
| `$912C` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ダスクの地下 |
| `$917A` | [マップメタデータ](@/data-structure/place-metadata/_index.md): コリンブルッフ洞穴 |
| `$91C8` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ボルカノ神殿 |
| `$9216` | [マップメタデータ](@/data-structure/place-metadata/_index.md): 鷹の目洞穴 |
| `$9264` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ホワイトウルフ洞穴 |
| `$92B2` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上A1 |
| `$9300` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上A2 |
| `$934E` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上A3 |
| `$939C` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上A4 |
| `$93EA` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上B1 |
| `$9438` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上B2 |
| `$9486` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上B3 |
| `$94D4` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上B4 |
| `$9522` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上C1 |
| `$9570` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上C2 |
| `$95BE` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上C3 |
| `$960C` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上C4 |
| `$965A` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上D1 |
| `$96A8` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上D2 |
| `$96F6` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上D3 |
| `$9744` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上D4 |
| `$9792` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上E1 |
| `$97E0` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上E2 |
| `$982E` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上E3 |
| `$987C` | [マップメタデータ](@/data-structure/place-metadata/_index.md): バーン地上E4 |
| `$98CA` | [マップメタデータ](@/data-structure/place-metadata/_index.md): デュームの城 |
| `$9918` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ホワイトウルフの城 |
| `$9966` | [マップメタデータ](@/data-structure/place-metadata/_index.md): アラマーの城 |
| `$99B4` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ブラックリッジノース |
| `$9A02` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ブラックリッジサウス |
| `$9A50` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ドラガデューンの城 |
| `$9A9E` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ドラガデューン地下1 |
| `$9AEC` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ドラガデューン地下2 |
| `$9B3A` | [マップメタデータ](@/data-structure/place-metadata/_index.md): ドラガデューン地下3 |
| `$9B88` | [マップメタデータ](@/data-structure/place-metadata/_index.md): 魔法の砦地下1 |
| `$9BD6` | [マップメタデータ](@/data-structure/place-metadata/_index.md): 魔法の砦地下2 |
| `$9C24` | [マップメタデータ](@/data-structure/place-metadata/_index.md): 森のあばら屋地下1 |
| `$9C72` | [マップメタデータ](@/data-structure/place-metadata/_index.md): 森のあばら屋地下2 |
| `$9CC0` | [マップメタデータ](@/data-structure/place-metadata/_index.md): レイバン砦地下1 |
| `$9D0E` | [マップメタデータ](@/data-structure/place-metadata/_index.md): レイバン砦地下2 |
| `$9D5C` | [マップメタデータ](@/data-structure/place-metadata/_index.md): エルドラド地下1 |
| `$9DAA` | [マップメタデータ](@/data-structure/place-metadata/_index.md): エルドラド地下2 |
| `$9DF8` | [マップメタデータ](@/data-structure/place-metadata/_index.md): エルドラド地下3 |
| `$9E46` | [マップメタデータ](@/data-structure/place-metadata/_index.md): エルドラド地下4 |
| `$9E94` | [マップメタデータ](@/data-structure/place-metadata/_index.md): アストラル世界 |
| `$9EE2` | [マップメタデータ](@/data-structure/place-metadata/_index.md): イドの迷宮 |
| `$9F30-$9FFF`| (未使用) |
