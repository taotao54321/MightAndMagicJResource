+++
title = "マップ各種フラグ配列"
+++

マップの各マスは周囲 4 方向に対する通行不可フラグや、その他諸々のフラグを持っている。ここではこれらを「各種フラグ」と呼ぶことにする。

各種フラグは 1 バイトに pack された値である。この pack されたバイトを `16 * 16 = 256` 個並べた配列を「マップ各種フラグ配列」と呼ぶ。

マップ各種フラグ配列のバイト内の pack 形式は以下の通り:

| bit | 意味         |
| --  | --           |
| 7   | イベントあり |
| 6   | 北が通行不可 |
| 5   | 暗闇         |
| 4   | 東が通行不可 |
| 3   | 休息禁止     |
| 2   | 南が通行不可 |
| 1   | 魔法禁止     |
| 0   | 西が通行不可 |

マップ各種フラグの並び順は row-major で、y, x ともに昇順。つまり座標 (0, 0), (1, 0), ..., (15, 0), (1, 0), ... のように並んでいる。たとえばオフセット 19 は座標 (3, 1) に対応する。

マップ各種フラグ配列は `$6300-$63FF` にロードされる。イベントにより動的に書き換わる場合もある。
