# cnt34 に追加するREADMEセクション（コピペ用）

README.md の「🌐 English」の上あたりにこれを追記してください：

---

## 🏛️ 三四式ガバナンス・モデル

> ３つのものを４で考えてみる、５つになって誕生する。５になると分裂する。

三四式（TTT理論）を社会制度に適用した新しい章を公開しました。

- **思想の核**: [`docs/Governance/governance.md`](docs/Governance/governance.md) - 3権 + 国民主権 + AI = 第5の自律体「検証可能な合意細胞」
- **実装設計図**: [`docs/Governance/5W1H.md`](docs/Governance/5W1H.md) - 5W1Hで展開する合意細胞の設計
- **インタラクティブデモ**: [`docs/Governance/simulations/governance_5w1h.html`](docs/Governance/simulations/governance_5w1h.html) - 膜の誕生と分裂を可視化

[![Open in Browser](https://img.shields.io/badge/Demo-Governance%20Cell-blue?style=for-the-badge)](https://kiki054-n.github.io/cnt34/docs/Governance/simulations/governance_5w1h.html)

### 5W1H対応表

| 5W1H | 三四式 | 役割 |
| :--- | :--- | :--- |
| Where, What, When | xX, yY, zZ | 位置 - 事実の座標 |
| Why, How | uU, vV, wW | 方向 - 国民主権とAI知の場 |
| Who | P5 | 自律体 - 検証可能な合意細胞 |

---

### GitHub Pages 有効化手順（1分）

1. GitHubで cnt34 リポジトリ > Settings > Pages
2. Source: Deploy from a branch
3. Branch: main / root を選択して Save
4. 1分後に https://kiki054-n.github.io/cnt34/docs/Governance/simulations/governance_5w1h.html でデモが公開されます

### 置くべきファイル構成

```
cnt34/
├─ README.md (上記セクションを追記)
├─ docs/
│  └─ Governance/
│     ├─ governance.md (前に作ったファイル)
│     ├─ 5W1H.md (前に作ったファイル)
│     └─ simulations/
│        └─ governance_5w1h.html (下記HTMLファイル)
```

全ての理論MDは CC BY-NC-SA 4.0、 simulations/*.html は MIT ライセンスです。
