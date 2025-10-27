#🎓 生徒の学力に影響を与える要因分析

〜家庭環境や学習支援が成績に与える影響を探る〜

---

##🎯 目的（Purpose）

この分析では、「生徒の学力（数学・読解・ライティング）」に影響を与える要因を探る。\
特に、**親の学歴・学習支援コースの有無・性別**に注目して分析する。

---

##💡 仮説（Hypothesis）

* 親の学歴が高いほど、平均スコアが高い。

* 学習支援コースを受講した生徒は平均スコアが高い。

* 性別による学力差はほとんどない。

---

##🧮 使用データ（Dataset）

* 出典：Students Performance in Exams (Kaggle)

* データ件数：1000件

* 主なカラム

| カラム名 |	説明 |
|----------|-------|
|gender|	性別（male / female）|
|parental level of education	|親の最終学歴
|lunch	|昼食の種類（standard / free/reduced）
|test preparation course	|学習支援コースの有無（none / completed）
|math score	|数学スコア
|reading score	|読解スコア
|writing score	|ライティングスコア

---

##📊 分析手法（Methods）

1. pandasでデータを読み込み・整形
2. seabornで可視化（箱ひげ図・棒グラフなど）
3. 要因ごとのスコア分布を比較し、仮説を検証

---

##📈 主な可視化（Visualizations）

* 性別 × 平均スコア → 箱ひげ図
* 親の学歴 × 平均スコア → 棒グラフ
* 学習支援コース × 平均スコア → 箱ひげ図
* 相関ヒートマップ → 各スコアの関連性を確認

---

##🧾 結果（Results）

* 親の学歴が高いほど、平均スコアも高い傾向が見られた。

* 学習支援コースを受けた生徒は、スコアが全体的に高い。

* 性別による大きな差はなかった。

---

##💬 考察（Discussion）

教育支援や家庭環境が学力に与える影響は小さくない。\
特に、家の経済的余裕や親の教育水準が子どもの学力にポジティブな影響を与えている\
可能性が高い。

---

##🚀 結論（Conclusion）

教育格差の一因は家庭環境や経済状況にあると考えられる。\
教育支援制度や補助を通じて、多くの生徒が公平に学べる仕組みを整えることが重要。

---

###✍️ 作成者（Author）

Name: ScarNam0818

Skills: Python / pandas / seaborn / matplotlib

Goal: データ分析を通じて社会課題を理解し、より良い教育環境を提案する。

---

## 🧰 使用ライブラリ
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
