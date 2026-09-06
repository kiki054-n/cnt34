# 参加のしかた / Contributing

*[日本語](#日本語) ・ [English](#english)*

---

<a id="日本語"></a>
# 日本語

## はじめに — 賛成は参加の条件ではありません

三四式（TTT理論）は完成した理論ではありません。**招いているのは理論への同意ではなく、問いへの関心です。**

「ここは間違っている」「この式は成立しない」「この対応づけは根拠がない」——こうした指摘は、賛同と同じか、それ以上に歓迎します。反証は理論の敵ではなく、理論が生きている証拠です。

このプロジェクトには中心となる正解者がいません。**中心は空っぽです。** 著者を含め、誰の主張も同じラベル体系の下に置かれます。

---

## 1. まず読むもの（10分）

1. [`README.md`](README.md) — 全体像
2. [`01_FOUNDATION/definitions.md`](01_FOUNDATION/definitions.md) — 記号の意味と、**いま空いている問い（O-1〜O-6）**
3. [`01_FOUNDATION/00-dual-pole.md`](01_FOUNDATION/00-dual-pole.md) — すべての出発点

急いでいる方は、2番だけで構いません。未決項目の一覧が、そのまま「やることリスト」です。

---

## 2. 確からしさのラベル — このプロジェクトの中心ルール

**このリポジトリのすべての主張には、確からしさのラベルが付きます。** 寄与を出すときは、自分の主張がどのラベルかを書いてください。これが三四式のいちばん大事な作法です。

| ラベル | 意味 |
| :---: | :--- |
| **D** | **定義** — 「そう呼ぶ」と決めたもの。真偽を問えない |
| **A** | **借用** — 確立された数学・物理から借りたもの。**出典必須** |
| **B** | **命題** — 定義と借用から導けるが、まだ導出を書き下していない |
| **E** | **対応** — 現実の事例・観察との対応づけ |
| **C** | **仮説** — 主張だが、導出も検証もまだない |
| **O** | **未決** — 問いとして開いている |
| **F** | **反証済み** — 誤りと確認されたもの。**消さずに残す** |

### なぜラベルを付けるのか

主張が全部同じ声の大きさで並んでいると、読む人は何を信じてよいか分かりません。**「まだ分かっていない」と書いてあることが、この理論の信頼性を支えます。**

> **未決を未決と書いた寄与は、断定した寄与より価値が高い。**

### 3つの原則

1. **構成の産物は発見ではない。** 定義から自動的に出てくるものを「導いた」と言わない
2. **単位で変わる量は不変量ではない。** 目盛りを変えたら消える一致は、一致ではない
3. **後から黙って直さない。** 誤りは **F** として残し、訂正の履歴を書く

---

## 3. 参加の3つのレーン

### 🔢 レーン1: 数学・物理

未決項目 **O-1 〜 O-3, O-6** が空いています（[definitions.md §3](01_FOUNDATION/definitions.md#3-未決項目--いま空いている問い)）。

- **O-1**: $U,V,W$ と $R,I,J$ の対応写像を書き下す（最優先。ここが理論の最大の隘路）
- **O-2**: $XYZ\pi=1$ の「積」がどのような演算か定義する
- **O-3**: 位置側のπとエネルギー側のπの非対称を解消するか、必然性を示す
- **O-6**: $R,I,J$ に正規化拘束を課すかを決める

**「この式は数学的に成立しない」という結論も、完全な寄与です。** その場合 **F** ラベルを付けて Issue に書いてください。

### 💻 レーン2: 実装・可視化

未決項目 **O-4** は、**実装だけで決着がつく唯一の項目**です。

「位置に方向の相互作用が加わると、系は自律的に7節点・4辺のテンセグリティ構造を形成する」——これがTTTの中心的な主張ですが、まだ数値実験がありません。

寄与の形:

- $N$ 個の点＋規則を時間発展させ、構造に収束するかを見るコード（Python / JS どちらでも）
- 既存の [`TTT_theory_simulation.html`](02_MATHEMATICS/TTT_theory_simulation.html) の改良
- 理論ドキュメントの図解・3D可視化

⚠️ **数値の主張には、必ず帰無対照を添えてください。**

規則をランダム化したとき、同じ構造に何％の割合で到達するか。ランダムでも同じくらい到達するなら、それは理論の成果ではありません。**「〇〇%で収束した」だけの報告は受け付けられません。「規則ありで82%、ランダムで31%」の形にしてください。**

### 🎨 レーン3: 思想・芸術・翻訳

三四式は、幾何学の言葉で書かれた調和論でもあります。

- 理論ドキュメントの**英訳**（現在ほとんどが日本語のみ。最も需要の高い寄与のひとつ）
- [`2-to-5.md`](01_FOUNDATION/2-to-5.md) と [`cell-division.md`](04_LIFE/cell-division.md) — 中身が空です。書ける方を探しています
- この世界観からの創作（詩・絵・音楽・立体）。[`gratitude.yml`](.github/ISSUE_TEMPLATE/gratitude.yml) の Issue テンプレートから
- 4つの柱（労働論）への異論・別の分類の提案 → [`QUESTIONS.md`](06_GOVERNANCE/pillars/QUESTIONS.md)

**哲学的な違和感の表明も寄与です。** 「感謝をエネルギーと呼ぶのは無理がある」といった指摘は、Issue に書いてください。

---

## 4. Issue と Pull Request の作法

### Issue

用途別のテンプレートがあります（[`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE/)）。迷ったら [custom](.github/ISSUE_TEMPLATE/custom.md) で構いません。

タイトルの先頭にラベルを付けると助かります。例:

```
[O-1] U,V,W → R,I,J の対応写像の候補
[F] XYZπ=1 は次元解析で成立しない
[C] 7節点構造は正20面体の部分構造ではないか
```

### Pull Request

- **1つのPRで1つの主張**。「ついでの修正」は別PRに分けてください
- 変更した主張のラベルを PR 本文に書いてください
- リンクは**相対パス**で（`../02_MATHEMATICS/XYZ-pi.md` のように）
- 各理論ドキュメントの末尾にある「*この文書は仮説であり、完成された結論ではない*」の一文は、削除しないでください

### ⚠️ GitHub Web UI からのアップロードについて

ブラウザの "Add files via upload" で既存ファイルと同名のファイルを上げると、上書きではなく **`ファイル名_1.md` が新規作成されます。** その結果、正規の名前のファイルに古い版が残り、新しい版が誰からも参照されない状態になります。

**このリポジトリでは実際にこれが起きています**（`01-basic-equation_1.md` 等）。ファイルを更新するときは、Web UI の**鉛筆アイコン（Edit）**か、`git push` を使ってください。

---

## 5. 反証したときは

**反証は歓迎されるだけでなく、記録として残されます。**

誤りが確認された主張は、削除せずに **F** ラベルを付けて残し、いつ・誰が・どういう根拠で反証したかを書きます。消してしまうと、同じ誤りが数年後にまた繰り返されるからです。

反証してくださった方のお名前は、そのまま記録に残ります。

---

## 6. ライセンスについて

寄与していただいた内容は、次のライセンスで公開されます。PRを送る時点で、これに同意したものとみなします。

- **コード**（スクリプト・シミュレーション）→ [MIT License](LICENSE)
- **文章・図版** → [CC BY-NC-SA 4.0](LICENSE-CONTENT.md)

理論そのもの（数式・アイデア）は著作権の対象外です。ライセンスが及ぶのは、公開された具体的な文章・コードであって、発想自体を独占するものではありません。

---

## 7. この場のふるまいについて

三四式は「感謝の交換」を社会の基本単位と考える理論です。この場自体も、その原則で運営します。

- **人ではなく主張を検討する。** 「あなたは分かっていない」ではなく「この式のここが成立しない」
- **分からないと言ってよい。** このプロジェクトには、著者自身が分かっていないことが山ほどあります
- **専門でなくても発言してよい。** 数学が読めなくても、「ここは日本語として意味が通らない」という指摘は立派な寄与です
- **同意を強要しない。同意を求められない。** 誰も、三四式を信じる必要はありません

---

<a id="english"></a>
# English

## Agreement is not a condition of participation

TTT Theory (Sanshi-shiki, 三四式) is not a finished theory. **What is invited here is interest in the questions, not assent to the answers.**

"This is wrong," "this equation doesn't hold," "this correspondence has no basis" — such contributions are as welcome as agreement, often more so. Refutation is not the enemy of a theory; it is evidence that the theory is alive.

There is no central authority on correctness here. **The center is empty.** Every claim, including the author's, sits under the same labeling system.

## 1. Read first (10 minutes)

1. [`README_en.md`](README_en.md) — the big picture
2. [`01_FOUNDATION/definitions.md`](01_FOUNDATION/definitions.md) — symbols, and the **currently open questions (O-1 … O-6)**. Japanese, but the symbol tables and the open-item list are readable with minimal Japanese
3. [`00-dual-pole.md`](01_FOUNDATION/00-dual-pole.md) — the starting point

## 2. Confidence labels — the central rule

**Every claim in this repository carries a confidence label.** When you contribute, state which label your claim has.

| Label | Meaning |
| :---: | :--- |
| **D** | **Definition** — something we decided to call by a name. Cannot be true or false |
| **A** | **Borrowed** — taken from established mathematics or physics. **Citation required** |
| **B** | **Proposition** — derivable from definitions and borrowings, but the derivation is not yet written out |
| **E** | **Correspondence** — a mapping onto real cases or observations |
| **C** | **Hypothesis** — a claim with neither derivation nor verification yet |
| **O** | **Open** — a question we do not have an answer to |
| **F** | **Refuted** — confirmed wrong. **Kept, not deleted** |

> **A contribution that marks an open question as open is worth more than one that asserts.**

Three principles:

1. **A product of construction is not a discovery.** Do not say you "derived" what follows automatically from a definition
2. **A quantity that changes with units is not an invariant.** An agreement that disappears when you change the scale was never an agreement
3. **Never silently fix things afterwards.** Errors stay, labeled **F**, with the correction history written down

## 3. Three lanes

### 🔢 Lane 1 — Mathematics & physics

Open items **O-1 … O-3, O-6** in [definitions.md](01_FOUNDATION/definitions.md).

- **O-1** (highest priority): write down the correspondence map between $U,V,W$ and $R,I,J$
- **O-2**: define what kind of operation the "product" in $XYZ\pi = 1$ actually is
- **O-3**: resolve the asymmetry between the positional $\pi$ and the energetic $\pi$, or show why it is necessary
- **O-6**: decide whether $R,I,J$ carry a normalization constraint

**"This does not hold mathematically" is a complete contribution.** File it as an Issue with label **F**.

### 💻 Lane 2 — Implementation & visualization

**O-4 is the one item that implementation alone can settle.** The claim that a system "autonomously forms a stable 7-node, 4-edge tensegrity structure" has never been tested numerically.

⚠️ **Every numerical claim must come with a null control.** Randomize the rule: what fraction of runs reach the same structure? If random rules do just as well, the result is not evidence for the theory. Report as "82% with the rule, 31% randomized" — never as a single number.

### 🎨 Lane 3 — Thought, art, translation

- **Translation of the theory documents into English** — most are Japanese-only. One of the most valuable contributions available right now
- [`2-to-5.md`](01_FOUNDATION/2-to-5.md) and [`cell-division.md`](04_LIFE/cell-division.md) are empty stubs. We are looking for someone to write them
- Creative work from this worldview — poetry, images, music, sculpture
- Objections to the Four Pillars model of labor → [`QUESTIONS.md`](06_GOVERNANCE/pillars/QUESTIONS.md)

**Philosophical discomfort is a contribution too.** "Calling gratitude a form of energy is a stretch" belongs in an Issue.

## 4. Issues and Pull Requests

Prefix your Issue title with a label where you can:

```
[O-1] A candidate correspondence map for U,V,W → R,I,J
[F] XYZπ=1 fails dimensional analysis
[C] Is the 7-node structure a substructure of the icosahedron?
```

For PRs: **one claim per PR**; state the label in the PR body; use **relative paths** for links; and please keep the "*this document is a hypothesis, not a settled conclusion*" line at the foot of each theory document.

⚠️ **Do not use GitHub's "Add files via upload" to update an existing file** — it creates `filename_1.md` instead of overwriting, leaving the stale version under the canonical name. This has already happened in this repository. Use the pencil (Edit) button or `git push`.

## 5. Licensing of contributions

By opening a PR you agree that your contribution is published under:

- **Code** → [MIT License](LICENSE)
- **Prose and figures** → [CC BY-NC-SA 4.0](LICENSE-CONTENT.md)

The theory itself — the equations and ideas — is not copyrightable, and neither license claims ownership of the idea.

## 6. Conduct

TTT treats the exchange of gratitude as the basic unit of society. This space runs on the same principle.

- **Examine claims, not people.** Not "you don't understand," but "this step in the equation does not hold"
- **You may say you don't know.** There is a great deal the author does not know either
- **You do not have to be a specialist.** "This sentence does not parse" is a real contribution
- **No one is required to believe any of this**

---

*質問は Issue へ。日本語・英語どちらでも構いません。 / Questions welcome in Issues, in Japanese or English.*
