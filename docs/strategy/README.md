# OneWay 戦略OS — Enterprise AI Architecture Company

> **OneWay株式会社のエンタープライズAI事業に関する、戦略の一次情報を集約したナレッジベースです。**
> 新しい戦略を考えるとき、提案書を作るとき、価格を決めるとき、採用を判断するとき — まずここを開いてください。

| 項目 | 内容 |
|---|---|
| 対象事業 | OneWay Enterprise AI Platform |
| 最終更新 | 2026-08-29 |
| 管理者 | 高橋宏明（OneWay株式会社 代表） |

---

## 1. ワンページ・サマリー

| 問い | 答え |
|---|---|
| **何の会社か** | **Enterprise AI Architecture Company**。企業のAI活用における設計と標準を定義し、エコシステムを保有する会社です。開発会社ではありません |
| **誰に売るか** | **売上30〜500億円 / 従業員100〜2,000名**の中堅企業。ホワイトカラー業務が大量にあり、AI専門部署が弱い企業。接触は**経営層に限定**します |
| **何を売るか** | **Level 0〜5 の6階建てラダー**。Briefing（50〜100万）→ Assessment（300万）→ PoV（500〜800万）→ Dept Platform（1,000〜2,000万）→ Ent Platform（3,000〜8,000万）→ Ent Agreement（年3,000〜8,000万×3年） |
| **どう儲けるか** | **固定年間契約 + 従量課金（AI Capacity）+ オプション（Agent / Support）**。顧客のAI利用が増えるほど売上が増える構造 |
| **何で勝つか** | 技術ではありません。**業種別の型 × ガバナンス × 経営可視化 × エコシステム（標準・パートナー・認定・市場）** |
| **5年後の姿** | **従業員25名・総売上10.5億円・ARR 8.0億円・企業価値40〜64億円**。デリバリーの55%はパートナーが担います |
| **最大のリスク** | **顧客ごとにコードを書いてしまい、受託会社に逆戻りすること** |

---

## 2. 【最重要】3つの「階層」を混同しないこと

OneWay の戦略には、性質の異なる3つの階層構造が同時に存在します。**取り違えると議論が噛み合わなくなります。**

| 呼称 | 何の階層か | 記号 | 定義文書 |
|---|---|---|---|
| **事業エコシステム** | 会社が保有する事業レイヤー | **EL1〜EL6** | [05-ecosystem-model.md](05-ecosystem-model.md) |
| **商品ラダー** | 顧客の契約単価を上げる段階 | **Level 0〜5** | [03-product-ladder.md](03-product-ladder.md) |
| **技術アーキテクチャ** | プロダクトの技術スタック | **T1〜T7** | [04-architecture.md](04-architecture.md) |

```
【事業エコシステム】          【商品ラダー】              【技術アーキテクチャ】
EL1 AI Strategy      ──売る──▶ Level 0 Briefing
                              Level 1 Assessment
                              Level 2 PoV
EL2 AI Platform      ──売る──▶ Level 3 Dept Platform ──実装──▶ T1 Control Center
                              Level 4 Ent Platform            T2 AI Agent Layer
                              Level 5 Ent Agreement           T3 Workflow Layer
EL3 Agent Library    ──売る──▶ 追加Agent（月5〜20万）         T4 Knowledge Layer
EL4 Partners                                                 T5 AI Gateway/Governance
EL5 Certification                                            T6 Enterprise Systems（接続のみ）
EL6 Marketplace                                              T7 AI/Cloud（作らない）
```

---

## 3. ドキュメント一覧

| # | 文書 | 内容 | こんなときに開く |
|---|---|---|---|
| **01** | [positioning](01-positioning.md) | 会社としての名乗り・建築設計事務所アナロジー・判断基準 | 会社紹介を書くとき / 案件を受けるか迷ったとき |
| **02** | [icp-target](02-icp-target.md) | ターゲット企業定義・業種別攻略・意思決定者マップ | リストを作るとき / 商談前 |
| **03** | [product-ladder](03-product-ladder.md) | Level 0〜5 の商品定義・Land & Expand | 商品を決めるとき / 提案の組み立て |
| **04** | [architecture](04-architecture.md) | 技術7層・最初に作る4プロダクト・作らないもの | 開発の優先順位を決めるとき |
| **05** | [ecosystem-model](05-ecosystem-model.md) | EL1〜EL6・フライホイール・失敗パターン | 中長期の打ち手を考えるとき |
| **06** | [revenue-model](06-revenue-model.md) | 課金構造・価格・財務モデル・値引きルール | 価格を決めるとき / 値引きを求められたとき |
| **07** | [gtm-playbook](07-gtm-playbook.md) | 営業手順・禁句・数字の作り方・想定問答 | **商談の直前** |
| **08** | [execution-plan](08-execution-plan.md) | 5年ロードマップ・最初の90日・KPI | 月次レビュー / 計画を立てるとき |
| **09** | [strategy-reference](09-strategy-reference.md) | プラットフォーム戦略・認定経済・参照事例の理論 | 新しい打ち手を考えるとき |
| **10** | [decision-log](10-decision-log.md) | 決めたことと理由・**未決事項** | 「なぜこうしたんだっけ」となったとき |
| **11** | [open-questions](11-open-questions.md) | 一次情報の要確認・要実測・検証中の仮説 | **提案書・対外資料を作る前** |

---

## 4. 使い方（場面別）

| 場面 | 読む順序 |
|---|---|
| **商談の前** | 07（禁句と4問）→ 02（意思決定者マップ）→ 03（提案するLevel） |
| **提案書を作る** | 11（要確認事項）→ 03 → 06 → 01（4.4 New Opportunity） |
| **価格を決める / 値引きを求められた** | 06（第9章 値引きルール） |
| **開発の優先順位を決める** | 04 → 08（開発ロードマップ） |
| **中長期の打ち手を考える** | 05 → 09 → 10（未決事項） |
| **月次の経営レビュー** | 08（第10章 KPI）→ 11（B欄 実測値の更新） |
| **新しい案件を受けるか迷った** | 01（第6章 4つの判断基準） |

---

## 5. 絶対に守る5つのルール

これだけは、どの文書よりも優先します。

| # | ルール | 破ったときに起きること |
|---|---|---|
| **1** | **顧客ごとにコードを書かない** | 受託会社に戻ります。EL3以降が永久に始まりません |
| **2** | **現場担当を窓口にしない。経営層に限定する** | ツール比較・価格競争に落ちます |
| **3** | **無料提案・無料PoCをしない** | 商品ラダー全体が崩壊します |
| **4** | **1期に着手する事業レイヤーは1つまで** | 少人数で全部が中途半端になります |
| **5** | **未確認の数字を対外資料に書かない** | 一度の誤りで、この価格帯の信頼は戻りません |

---

## 6. 更新プロトコル

**この戦略OSは「書いて終わり」ではありません。実データで毎月更新します。**

| 頻度 | やること | 対象文書 |
|---|---|---|
| **随時** | 戦略・価格・商品・組織の決定をした日のうちに記録 | [10-decision-log.md](10-decision-log.md) |
| **随時** | 商談で有効だった / 無効だった論法を記録 | [07-gtm-playbook.md](07-gtm-playbook.md) / [09-strategy-reference.md](09-strategy-reference.md) |
| **商談10件ごと** | 想定問答の更新 | [07-gtm-playbook.md](07-gtm-playbook.md) |
| **月次** | 実績数値の反映（ARR / 転換率 / 原価率） | [06-revenue-model.md](06-revenue-model.md) / [08-execution-plan.md](08-execution-plan.md) |
| **実測が出るたび** | 仮置き値を実測値に差し替え | [11-open-questions.md](11-open-questions.md) B欄 |
| **Phase完了時** | 合否判定と次Phaseの計画更新 | [08-execution-plan.md](08-execution-plan.md) |
| **年次** | ポジショニングと5年計画の再検証 | [01-positioning.md](01-positioning.md) / [05-ecosystem-model.md](05-ecosystem-model.md) |

**各文書の冒頭にある「最終更新 / ステータス / 更新トリガー」を必ず更新してください。** 古い数字が残っている文書は、無い文書より危険です。

---

## 7. 関連する既存資産

| 資産 | 関係 |
|---|---|
| `oneway-marketing-os` スキル | ブランソン三部作ベースの戦略OS。**B2C/教育事業側**。本戦略との対応関係は [09-strategy-reference.md](09-strategy-reference.md) 第9章 |
| `oneway-proposal` スキル | 提案書テンプレート（.pptx）。**Enterprise モジュールの追加が Phase 0 のタスク** |
| ブランドボイス | 結論ファースト / 断言調 / 具体数値 / 「完璧より完了」「消費者から事業者へ」 |

---

## 8. 現在地（2026-08-29 時点）

```
Phase 0（型づくり）  ← ★いまここ
  └ 開始予定：2026年9月
  └ 完了目標：2026年11月
  └ 90日後の合格ライン：Assessment 3件受注（900万円）

未決の最優先事項：
  U-001  Level 4 と Level 5 の価格整合（→ Phase 0 W1で決着）
  U-002  最初に密度を作る2業種の選定（→ Phase 0 完了時）
```

**次にやること：** [08-execution-plan.md](08-execution-plan.md) 第7章「最初の90日アクションプラン」の Month 1 / Week 1。
