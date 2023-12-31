+++
title = "エンカウント発生後の流れ"
+++

エンカウント発生後の処理の概略を記す。

まず[敵編成処理](@/encounter/composition/_index.md)により敵軍の全個体を確定させる。具体的には、マップごとの制約や彼我の強さを考慮した上でランダム敵を追加できるだけ追加する。

次に自軍/敵軍の[先制判定/処理](@/encounter/preemptive/_index.md)を行う。自軍先制の場合、敵に気付かれず戦闘を回避できる可能性がある。敵軍先制の場合は直ちに戦闘に突入する。自軍が先制して戦闘を回避した場合はここで終了処理を行う。

戦闘を回避しておらず、かつ敵軍先制でなければ[戦闘前フェイズ](@/encounter/pre-battle/_index.md)を実行する。ここで「おくりもの」「にげる」「こうさん」コマンドにより戦闘を回避した場合は終了処理を行う。戦闘回避に失敗するか、もしくは「たたかう」を選んだ場合は戦闘に突入する。
