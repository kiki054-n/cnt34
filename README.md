# cnt34 Code Name Type ３４ 三四式

〜 位置（3）と方向（4）がつむぐ、より良き世界へのオープンソース研究イニシアチブ 〜

[![Code License: MIT](https://img.shields.io/badge/Code_License-MIT-green.svg)](./LICENSE)
[![Content License: CC BY-NC-SA 4.0](https://img.shields.io/badge/Content_License-CC_BY--NC--SA_4.0-lightgrey.svg)](./LICENSE-CONTENT.md)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19704117.svg)](https://doi.org/10.5281/zenodo.19704117)

[![Author](https://img.shields.io/badge/Author-川上真潔-f39c12?style=for-the-badge)](https://orcid.org/0009-0009-2972-6511)

📄 [紹介ページ](https://kiki054-n.github.io/cnt34/CNT34_TriTetra_Introduction.html) ・ 📖 [記号と用語の定義](01_FOUNDATION/definitions.md) ・ 🤝 [参加のしかた](CONTRIBUTING.md) ・ 🌐 [English](./README_en.md)

---

# 三四式（TTT理論 / Triple-Tetra Theory）

> **〜 位置（3）と方向（4）がつむぐ、より良き世界へのオープンソース研究イニシアチブ 〜**

## 📛 名前の由来 — 「三四式」とは

明治〜昭和初期、日本軍は制式採用年（元号や皇紀の下2桁）を「式」に冠して兵器を命名しました（三八式歩兵銃、零式艦上戦闘機など）。

CNT34の「三四式」は、この命名法を踏まえつつ、まったく別の意味を重ねています。Tri-Tetra Theory（TTT）の頭文字と、理論の中核「位置3 + 方向4」を縮約した象徴的な名称です。

兵器が「対立と殺戮」の象徴であったように、三四式は「接続と調和」の象徴を目指します。この理論が、幾何学の言葉で描く平和論であり、日本文化に根ざした「中心のない調和」のモデルであることは、[`four-gods-and-tensegrity.md`](06_GOVERNANCE/four-gods-and-tensegrity.md) で詳しく扱っています。

## 🌟 プロジェクトのビジョン

自然界や生命、そして宇宙に宿る「幾何学的な調和」を読み解くための、新しい思考の枠組み——それが「三四式（TTT理論）」です。

異なる要素や次元が結合することで、新しい「自律したシステム（10・細胞・立体）」が生まれ、世界へと広がっていく——。

このリポジトリは、単なる数学や物理の計算式を置く場所ではありません。科学、医療、情報、芸術、そして人間社会がより調和した世界を、世界中の人々と共に描くための、開かれたキャンバスです。

---

## 💡 三四式（TTT理論）とは？

「3（空間位置）」と「4（方向・回転）」の相互作用に着目し、位置ベクトルと配向ベクトルを統合した状態空間モデルです。

$$P = xX + yY + zZ + uU + vV + wW$$

* **位置の3次元**（$xX, yY, zZ$）: どこに物質があるか
* **方向の3次元**（$uU, vV, wW$）: どちらを向いているか（極性・回転・場の傾き）

「位置」に「方向」の相互作用が加わることで、系は自律的に安定したテンセグリティ構造や膜を形成し、生命のように自発的な対称性の破れを起こします。

### 「三」と「四」の数え方

名称の「4」は、この式の成分数ではありません。方向側の3軸（$U, V, W$）に、それらを束ねて閉じる回転軸 $\pi$ を加えたものが「4」です。

$$XYZ\pi = 1 \qquad OOO\pi = 1$$

つまり **位置3軸＋方向3軸＝6成分**、そして **各系を閉じる回転軸 $\pi$ を数えて「三と四」** となります。詳細は [`XYZ-pi.md`](02_MATHEMATICS/XYZ-pi.md)（空間側）と [`OOO-pi.md`](02_MATHEMATICS/OOO-pi.md)（エネルギー側）を参照してください。

### 記号 $U,V,W$ と $R,I,J$ について

方向の3成分には、本リポジトリ内で2通りの表記が現れます。**同じ3成分の別表記**であり、別の量ではありません。

| 表記 | 使う場面 | 出典 |
| :--- | :--- | :--- |
| $uU + vV + wW$ | 幾何学的な導入（双極から軸が生まれる話） | [`00-dual-pole.md`](01_FOUNDATION/00-dual-pole.md) |
| $rR + iI + jJ$ | 各成分に具体的な意味を与える定式化 | [`01-basic-equation.md`](01_FOUNDATION/01-basic-equation.md) |

対応関係の厳密な導出は**未決**です（[`definitions.md`](01_FOUNDATION/definitions.md) の未決項目 O-1）。

---

## 🚀 期待される応用分野

* 🧬 **人工生命・バイオテクノロジー**: 人工合成セルの自律分裂・自己組織化シミュレーション
* 🤖 **自律分散ロボティクス**: 群制御やスウォームインテリジェンス
* 🌌 **新素材・建築トポロジー**: テンセグリティ構造・メタマテリアル
* 💻 **次世代AI・ベクトル表現**: 高次元埋め込み表現

いずれも**構想段階**であり、実装・検証はこれからです。ここに書かれていることは「できたこと」ではなく「やってみたいこと」です。

---

## 🤝 共に良い夢を見よう（Contribution）

この理論を完結したものとは考えていません。むしろ、ここからがスタートです。

**三四式に賛成することは、参加の条件ではありません。** 招いているのは理論への同意ではなく、問いへの関心です。反証・別解釈・「ここは間違っている」という指摘は、賛同と同じか、それ以上に歓迎します。

* **数学・物理が好き:** 数式アプローチや四元数との厳密な定式化
* **プログラマー:** Pythonや3D可視化シミュレーションコード作成
* **思想・アート・詩人:** このモデルがもたらす新しい世界観の議論・文書化

はじめての方は [**CONTRIBUTING.md**](CONTRIBUTING.md) をご覧ください。いま空いている問い（未決項目）と、寄与に付ける「確からしさのラベル」について書いてあります。

> **「一人で見ようとする夢はただの夢。みんなで見ようとする夢は現実となる。」**

---

## 📍 現在地 — どこまで書けているか

このプロジェクトは、**書けている部分と、まだ穴が空いている部分を、同じ大きさの文字で示す**方針を取ります。

| 状態 | 意味 | 該当 |
| :--- | :--- | :--- |
| ✅ 記述済み | 一通り読める形になっている | 00-dual-pole, 01-basic-equation, 02-dynamic-model, 03-cosmic-sphere-model, 04-genesis-and-time, 05-lattice-and-existence, XYZ-pi, OOO-pi, euler-connection, 4つの柱, governance |
| 🚧 準備中 | 見出しだけがあり、中身はこれから | [`2-to-5.md`](01_FOUNDATION/2-to-5.md), [`cell-division.md`](04_LIFE/cell-division.md) |
| ❓ 未決 | 理論の中で、まだ答えが出ていない問い | [`definitions.md`](01_FOUNDATION/definitions.md) の「未決項目」節（O-1 〜 O-5） |

特に [`cell-division.md`](04_LIFE/cell-division.md) は、他の9か所の文書から参照されている**最大の空白**です。ここを書ける方を探しています。

---

## 🏛️ 三四式ガバナンス・モデル

> ３つのものを４で考えてみる、５つになって誕生する。５になると分裂する。

三四式（TTT理論）を社会制度に適用した章です。

- **思想の核**: [`governance.md`](06_GOVERNANCE/governance.md) - 3権 + 国民主権 + AI = 第5の自律体「検証可能な合意細胞」
- **実装設計図**: [`5W1H.md`](06_GOVERNANCE/5W1H.md) - 5W1Hで展開する合意細胞の設計
- **インタラクティブデモ**: [Governance-5w1h.html](https://kiki054-n.github.io/cnt34/06_GOVERNANCE/Governance-5w1h.html) - 膜の誕生と分裂を可視化
- EN: [`Governance-En.md`](06_GOVERNANCE/Governance-En.md) / [`5W1H-En.md`](06_GOVERNANCE/5W1H-En.md)

[![Open in Browser](https://img.shields.io/badge/Demo-Governance%20Cell-blue?style=for-the-badge)](https://kiki054-n.github.io/cnt34/06_GOVERNANCE/Governance-5w1h.html)

### 5W1H対応表

| 5W1H | 三四式 | 役割 |
| :--- | :--- | :--- |
| Where, What, When | xX, yY, zZ | 位置 - 事実の座標 |
| Why, How | uU, vV, wW | 方向 - 国民主権とAI知の場 |
| Who | P5 | 自律体 - 検証可能な合意細胞 |

---

## 📚 理論ドキュメント

双極（2）→ 位置（3）→ 方向（4）→ 顕在化した自律体（5）という数の並びを、1つずつ辿ります。

### 01_FOUNDATION — 土台

- [`00-dual-pole.md`](01_FOUNDATION/00-dual-pole.md) — 双極の原理。なぜ「1」ではなく「2」から始まるのか。00という最小の区別から、次元と手のひらの幾何学が生まれる
- [`01-basic-equation.md`](01_FOUNDATION/01-basic-equation.md) — 基本方程式。$P=xX+yY+zZ+rR+iI+jJ$ という6次元ベクトル方程式と、クォータニオンとの異同
- [`definitions.md`](01_FOUNDATION/definitions.md) — 記号・用語の定義と、未決項目の一覧
- [`2-to-5.md`](01_FOUNDATION/2-to-5.md) 🚧 — 「2」から「5」への展開

### 02_MATHEMATICS — 数理

- [`XYZ-pi.md`](02_MATHEMATICS/XYZ-pi.md) — 空間単位系。位置の3軸と、それを閉じる回転軸πによる単位条件 $XYZ\pi=1$
- [`OOO-pi.md`](02_MATHEMATICS/OOO-pi.md) — エネルギー単位系。3つのスピンと $OOO\pi=1$。4つの柱のエネルギーと対応する
- [`euler-connection.md`](02_MATHEMATICS/euler-connection.md) — オイラー公式との接続。$e^{i\pi}=-1$ を双極の誕生、$e^{i\cdot 2\pi}=1$ を顕在化の周期として読み解く
- [`02-dynamic-model.md`](02_MATHEMATICS/02-dynamic-model.md) — 動的記述。物理（$p$軌道）と精神（$d/f$軌道）の対応、テンソル積による時間発展方程式
- [TTT_theory_simulation.html](https://kiki054-n.github.io/cnt34/02_MATHEMATICS/TTT_theory_simulation.html) — インタラクティブ・シミュレーション（[EN](https://kiki054-n.github.io/cnt34/02_MATHEMATICS/TTT_theory_simulation_en.html)）

### 03_PHYSICS — 物理

- [`03-cosmic-sphere-model.md`](03_PHYSICS/03-cosmic-sphere-model.md) — 全体均衡モデル。境界づけられた球体と、零点収束の公理

### 04_LIFE — 生命

- [`04-genesis-and-time.md`](04_LIFE/04-genesis-and-time.md) — 時間の起源。双極の運動から事後的に定義される時間
- [`four-gods-and-tensegrity.md`](04_LIFE/four-gods-and-tensegrity.md) — 四神とテンセグリティ。中心のない調和のモデル
- [`cell-division.md`](04_LIFE/cell-division.md) 🚧 — 細胞分裂の幾何学。メタン分子（5 → 15 → 30 → 15+15）と「2・3・4・5」

### 05_AI — 情報

- [`05-lattice-and-existence.md`](05_AI/05-lattice-and-existence.md) — ラティスと存在。$\pi$（軌道）がラティスの基であること
- [`AIの正体.md`](05_AI/AIの正体.md) — AIを三四式の枠組みで読む

### 06_GOVERNANCE / 07_WCCC — 社会

- [`governance.md`](06_GOVERNANCE/governance.md) ・ [`5W1H.md`](06_GOVERNANCE/5W1H.md) ・ [`社会システム設計.md`](06_GOVERNANCE/社会システム設計.md)
- [`gratitude.md`](07_WCCC/gratitude.md) — 感謝の循環プロトコル

---

## 🏛️ 4つの柱と感謝の循環

三四式を人の役割・労働に適用した章です。図解版は [TTT_4pillars_repository.html](https://kiki054-n.github.io/cnt34/06_GOVERNANCE/pillars/TTT_4pillars_repository.html) をご覧ください。

- [`pillar-01-create.md`](06_GOVERNANCE/pillars/pillar-01-create.md) — 第1柱・作る労働（u軸のスピン）
- [`pillar-02-support.md`](06_GOVERNANCE/pillars/pillar-02-support.md) — 第2柱・支える労働（v軸のスピン）
- [`pillar-03-govern.md`](06_GOVERNANCE/pillars/pillar-03-govern.md) — 第3柱・管理労働（w軸のスピン）
- [`pillar-04-invent.md`](06_GOVERNANCE/pillars/pillar-04-invent.md) — 第4柱・創造労働（回転軸 $\pi$ そのもの）
- [`QUESTIONS.md`](06_GOVERNANCE/pillars/QUESTIONS.md) — 4つの柱に対する問い
- [`gratitude.md`](07_WCCC/gratitude.md) — 感謝の循環プロトコル

---

## 📜 ライセンス

本プロジェクトは、コードと文章とで異なるライセンスを採用しています。

* **コード**（シミュレーションHTML/JS、検証スクリプトなど）: [MIT License](./LICENSE) — 自由に使い、改変し、検証・実装に組み込んでいただいて構いません。三四式（TTT理論）を実際に使い、検証・証明につなげてもらうことを最優先しています。
* **理論の解説文・論文等**（本READMEの本文、Zenodo等で公開している論文類）: [CC BY-NC-SA 4.0](./LICENSE-CONTENT.md) — 出典を明記した引用・議論・非営利利用は歓迎します。商用利用や、同一条件でない形での二次配布はご遠慮ください。

理論そのもの（数式・アイデア）は著作権の対象外のため、いずれのライセンスも「このテキスト・コードの複製や再配布」に関するルールであり、TTT理論という発想自体を独占するものではありません。

---

### GitHub Pages 有効化手順（1分）

1. GitHubで cnt34 リポジトリ > Settings > Pages
2. Source: Deploy from a branch
3. Branch: main / root を選択して Save
4. 1分後に https://kiki054-n.github.io/cnt34/ でトップページ（index.html）が公開されます
