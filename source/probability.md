---
title: "確率の話"
tags: ["math"]
---

### 同様に確かにらしい
「同様に確からしい」とは事象がすべて同じ確率で起こるという仮定。

例：トランプからカードを引く場面を考える。スペードのエースを引く確率は1/52
である。決して引くor引かないかの1/2

ではない。 一枚一枚のカードは引く確率に偏りがなくどれも同じ確率で引くことになる設定のことを、「同様に確からしい」と表現する。 極端な例として宝くじがある。1等賞が非常に珍しいのはくじを選ぶ確率が同様に確からしいから。

### 条件付き確率

「条件付き確率」とはある事象が起こるという条件のもとで、別のある事象が起こる確率のこと。

事象Bが起こるという条件のもとで事象Aが起こる場合、この条件付き確率は$P(A|B)$
と表され次のように計算できる。

$$
P(A|B)=\frac{P(A\cap B)}{P(B)}  
$$

表記に注意が必要。$A \to B$ではなく、$A \leftarrow B$が正しい。 