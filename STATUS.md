# TBI2027 Status / ToDo

Last updated: 2026-09-04

このファイルは、TBI 2027に向けて実行・確認が必要なToDoを一元管理する。

詳細な仕様、判断理由、装備方針等は各Source文書を正本とし、この表では「次に何をする必要があるか」とその進行状態を管理する。

## Status definitions

- `未着手`: 実行可能だが、まだ開始していない
- `進行中`: 確認、相談、作業等を開始している
- `待ち`: 外部条件、前提作業、レギュレーション公開等を待っている
- `完了`: ToDoとして完了した
- `保留`: 意図的に実行判断を保留している

## Assignees

- `新堀`: 本人が実施・判断する項目
- `うなぎさん`: 石原商店。既存文書では「石原商店」と「うなぎさん」の表記揺れを許容する
- `DecaPlus`: デカール製作依頼先

## Source labels

- `Mods`: [車両艤装・変更](03-bike/modifications.md)
- `Carried`: [車載携行品](04-equipment/bike-carried-equipment.md)
- `Spares`: [工具・予備品](04-equipment/tools-and-spares.md)

## ToDo

| ID | 分類 | ToDo | 担当 | Status | 期限 / Trigger | メモ | Source |
|---|---|---|---|---|---|---|---|
| T001 | ナビ | ICO Rallye MAX GをKTM 500 EXC-Fから移植 | うなぎさん | 未着手 | TBI前 |  | [Mods](03-bike/modifications.md) |
| T002 | ナビ | N-System ICO用スイッチを購入・施工 | うなぎさん | 購入に進む | TBI前 | MAX G用 | [Mods](03-bike/modifications.md) |
| T003 | 電装 | 計器電源の冗長化方法を決定・施工 | うなぎさん | 未着手 | TBI前 | 増設用に追加する | [Mods](03-bike/modifications.md) |
| T004 | 電装 | 所有済みBaja Designsライトを追加施工 | うなぎさん | 未着手 | TBI前 | 4灯を入れる[案](https://www.kovemotousa.com/latest-news/baja-1000-win-2024)あり | [Mods](03-bike/modifications.md) |
| T005 | ガード | ガード類の追加要否・構成を相談・決定 | 新堀 / うなぎさん | 購入に進む | TBI前 | ブーツが当たるところを追加（[Acerbis](https://images.squarespace-cdn.com/content/v1/645001d75ffea600703d8d92/eefcb44c-bc7d-48a1-a9c0-eeed8a6d31f1/ac.jpg?format=1000w)） | [Mods](03-bike/modifications.md) |
| T006 | ホイール | 前後予備ホイールを購入 | うなぎさん | 予約済 | TBI前 | 石原商店で購入予定:Batonさんの中古で確定 | [Mods](03-bike/modifications.md), [Spares](04-equipment/tools-and-spares.md) |
| T007 | 操安 | KOVE純正ステアリングダンパー購入・施工 | うなぎさん | 購入に進む | TBI前の走行時 | まずKOVE純正を試し、使用感を評価するため | [Mods](03-bike/modifications.md) |
| T008 | サス | サスペンション仕様について相談・確認 | 新堀 / うなぎさん | 進行中 | TBI仕様決定前 | うなぎさんが知人に確認中（2026/08/24〜）。テクニクスサスに換装する場合、STD用サスのAssy購入ではなく、パーツの追加購入でモディファイ可能かを要確認。 | [Mods](03-bike/modifications.md) |
| T009 | サス | TBI前にサスペンション変更するか決定 | 新堀 | 待ち | T008および事前走行後 | 交換によって性能が向上すること自体は認識済み。TBI前に変更するかを判断する。テクニクスサスは一般ツーリング向けなので柔らかく、ラリー向きではない。 | [Mods](03-bike/modifications.md) |
| T010 | 外装 | TBI用デカールを製作 | DecaPlus | 未着手 | TBI前 | 純正デカールは熱で縮み、不格好になったため交換予定 | [Mods](03-bike/modifications.md) |
| T011 | タイヤ | 使用済みムースの状態を確認し、再利用可否を判断 | 新堀 | 未着手 | TBI装着前 | モンゴルで使用したムースを再利用予定 | [Mods](03-bike/modifications.md), [Spares](04-equipment/tools-and-spares.md) |
| T012 | スペア | 予備レバーを購入 | うなぎさん | 購入に進む | TBI前 |  | [Spares](04-equipment/tools-and-spares.md) |
| T013 | スペア | 予備ペダルを購入 | うなぎさん | 購入に進む | TBI前 |  | [Spares](04-equipment/tools-and-spares.md) |
| T014 | スペア | 予備ブレーキパッド前後を購入 | うなぎさん | 購入に進む | TBI前 |  | [Spares](04-equipment/tools-and-spares.md) |
| T015 | 必携品 | TBI 2027レギュレーションから正式必携品を確定 | 新堀 | 待ち | 2027年版レギュレーション公開後 | 現時点の候補リストを正式必携品とは扱わない | [Carried](04-equipment/bike-carried-equipment.md) |
| T016 | 積載 | 必携品の実物・重量・寸法を確認 | 新堀 | 待ち | T015後 |  | [Carried](04-equipment/bike-carried-equipment.md) |
| T017 | 積載 | 工具・必携品の車体搭載位置を決定 | 新堀 / うなぎさん | 待ち | T016後 | 重量位置、防水、振動、脱落防止、転倒時損傷、アクセス性を考慮 | [Carried](04-equipment/bike-carried-equipment.md), [Spares](04-equipment/tools-and-spares.md) |
| T018 | 積載 | 工具類の搭載方法を相談・施工 | 新堀 / うなぎさん | 待ち | 搭載候補整理後 | 工具自体は一通り揃っており、課題は車体上の搭載位置・固定方法 | [Spares](04-equipment/tools-and-spares.md) |
| T019 | 積載 | 実走で脱落・振動・重量バランス・取り出しやすさを評価 | 新堀 | 待ち | 艤装完成後 | 必携品と工具を含む最終積載状態で評価する | [Carried](04-equipment/bike-carried-equipment.md) |
| T020 | 操安 | グリップ交換 | 新堀 | 未着手 |  | スポンジ or ProTaper | [Mods](03-bike/modifications.md) |
| T021 | 操安 | メインキー交換 |  | 未着手 |  | Suzuki製のメインキーに交換？ | [Mods](03-bike/modifications.md) |
| T022 | 操安 | ABSケーブル撤去/維持 |  | 未着手 |  | ケーブル削減により故障可能性を下げるが、車検で通るかどうかに不安あり（なお、ABS設定はOff/Onを覚えている） | [Mods](03-bike/modifications.md) |
| T023 | 吸排気 | マフラー交換 |  | 未着手 |  | 重さとキャタライザーによる熱問題を軽減 | [Mods](03-bike/modifications.md) |
| T024 | 操安 | スロットルパイプ |  | 購入に進む |  | グリップ交換用 | [Mods](03-bike/modifications.md) |

## Operating policy

- 新しい具体的な実行項目が発生したら、この表へ追加する
- 詳細仕様や判断理由はSource文書側へ記録し、ToDo表へ過度に重複させない
- 完了項目は削除せず、原則として`完了`へ変更して履歴を残す
- IDは既存項目を参照するための識別子とし、今後は原則として再採番しない
