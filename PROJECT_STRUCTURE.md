# Provisional Project Structure

このファイルはTBI2027 repositoryの将来構成を記録する。

現段階では仮構成であり、すべてのディレクトリ・ファイルを直ちに作成する必要はない。

```text
TBI2027/
├── README.md
├── STATUS.md
│
├── 00-project/
│   ├── purpose.md
│   ├── success-criteria.md
│   └── decision-log.md
│
├── 01-plan/
│   ├── roadmap.md
│   ├── calendar.md
│   ├── event-plan.md
│   └── fitness-plan.md
│
├── 02-preparation/
│   ├── checklist.md
│   ├── entry-and-logistics.md
│   ├── budget.md
│   └── documents.md
│
├── 03-bike/
│   ├── baseline.md
│   ├── modifications.md
│   ├── navigation.md
│   ├── suspension.md
│   ├── wheels-tires-mousse.md
│   ├── luggage.md
│   └── maintenance/
│       ├── README.md
│       ├── maintenance-log.md
│       └── maintenance-plans.md
│
├── 04-equipment/
│   ├── rider-gear.md
│   ├── bike-carried-equipment.md
│   ├── tools-and-spares.md
│   └── packing-list.md
│
├── 05-training/
│   ├── riding.md
│   ├── navigation.md
│   ├── fitness.md
│   ├── sessions/
│   └── events/
│       ├── sser/
│       ├── jncc/
│       ├── jec/
│       └── other/
│
├── 06-tbi2027/
│   ├── pre-start-checklist.md
│   ├── daily-log/
│   ├── incidents.md
│   └── results.md
│
├── 07-review/
│   ├── vehicle-review.md
│   ├── equipment-review.md
│   ├── rider-review.md
│   └── lessons-learned.md
│
└── 08-rally-mongolia-2028/
    ├── carry-over.md
    ├── open-issues.md
    └── next-test-plan.md
```

## Directory roles

### `00-project`

プロジェクトの目的、成功条件、重要な判断とその理由を記録する。

### `01-plan`

将来の計画を管理する。

対象には以下を含む。

- TBIまでのロードマップ
- 他SSERイベント
- JNCC
- JEC
- その他イベント
- 体力作り

### `02-preparation`

TBI参戦そのものに必要な準備を管理する。

### `03-bike`

KOVE 450 Rally MY2024の仕様、艤装、変更、タイヤ、サスペンション、積載方法およびメンテナンスを管理する。

### `04-equipment`

ライダー装備、工具、スペア、携行品を管理する。

### `05-training`

実際に行った練習・イベント・体力トレーニングを記録する。

`01-plan` を計画、`05-training` を実績として分離する。

### `06-tbi2027`

TBI 2027本番の記録を管理する。

### `07-review`

TBI終了後の評価を管理する。

### `08-rally-mongolia-2028`

TBIで得られた知見のうち、Rally Mongolia 2028へ引き継ぐ内容を管理する。

## Current policy

初期段階では必要なファイルだけを作成する。

Gitは空ディレクトリを管理しないため、仮構成を実現する目的だけで `.gitkeep` を大量に作成しない。

必要になった時点で、この構成を基準として各ディレクトリ・ファイルを追加する。

構成自体も固定せず、実運用上必要な場合は変更する。
