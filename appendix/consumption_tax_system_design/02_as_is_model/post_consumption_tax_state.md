# 💴 post_consumption_tax_state.md

## 📌 概要

本ドキュメントは、1989年に導入された消費税制度が社会・経済・制度構造に及ぼした影響を、アーキテクチャ的観点から記録する。  
制度導入時のTO-BEモデル（理想設計）に対し、現実の運用がどのような構造に収束したかを明らかにするものである。

## 🗓️ 状態発生のトリガー

- **制度投入**：消費税法（1988年公布、1989年施行）
- **設計目的**：広く薄い負担による社会保障財源の安定化、公平性・透明性の確保
- **導入時税率**：3%
- **初期状態**：物品税を廃止し、事業者ベースの付加価値課税モデルへ移行

---

## 🧠 構造的に現れたAS-ISの状態

| 項目 | AS-ISの構造的現象 | コメント |
|------|-------------------|----------|
| 財源構造 | 社会保障目的の建前とは裏腹に、国債返済・財政再建に消費税収が流用される | 目的と実態の乖離 |
| 税負担構造 | 逆進性が露呈、低所得者層の相対的負担が拡大 | 軽減税率等は後年の対症療法 |
| 制度理解 | 「預かり金」としての誤解が根強く、納税者意識が分断される | 制度教育の不足と設計透明性の限界 |
| 事業者の実務負担 | 記帳・申告・控除計算など複雑化し、中小事業者に大きな圧力 | 「簡素性」目標との乖離 |
| 社会的印象 | 「福祉目的」の顔で導入されたが、増税の口実装置に変質 | 信頼性の低下と制度的嫌悪感の蓄積 |

---

## 🔍 実装構造としての問題点（1989〜2012）

- 税率上昇（3%→5%）が制度設計の再構築を伴わずに実施され、制度構造が旧設計のまま負荷のみ増加した
- 税負担が所得に関係なく一律であったため、逆進性（低所得層の実質負担増）が社会問題化
- 社会保障財源という建前が維持されながらも、実際の使途が明示されず、制度への信頼が低下
- 制度への国民的理解が進まないまま、「税率だけが動く制度」として定着し、制度疲労が蓄積された

---

## 🔗 関連TO-BE設計とのリンク

- [`consumption_tax_spec.md`](../03_to_be_model/consumption_tax_spec.md)
- [`consumption_tax_diff.md`](../04_diff_analysis/consumption_tax_diff.md)

