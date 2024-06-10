# Animation Programming Challenge 2024

概要: アニメーションプログラミングチャレンジは、キャラクタアニメーション分野を広く理解するための講義である。

## Lecture 1: Motion Data

- Date: 2024.05.23
- 概要: BVHデータの構造を知ろう。
  - Recursive function(再帰関数)
  - Depth-first search(深さ優先探索)
  - BVH data structure
  - Forward Kinematics(FK)
  - (Advanced) Inverse Kinematics(IK)
- Challenges
  - [x] 1.1 Load/Export BVH data
    - [x] Done on 2024.05.30 [ [code](/animation_lecture/5-30/) ]
  - [x] 1-2 Visualize BVH data (FK)
    - [x] Done on 2024.06.06 [ [code](/animation_lecture/6-6/) ]

- References
  - 「オイラー角と固定角は逆順の関係にあるらしい」 [ [Web](https://space-denpa.jp/2021/05/04/relationship-euler-fix/) ]

## Lecture 2: Mesh Animation

- Date: 2024.06.06
- 概要: 様々なメッシュのアニメーション手法を知ろう。
  - Mesh structure (.obj, .ply)
  - Blendshape animation
  - Linear Blend Skinning(LBS)
  - Others: Advanced techniques
- Challenges
  - [] 2.1: Load/Export Mesh(.obj)
  - [] 2.2: Blendshape animation
  - [] 2.3: (Advanced) LBS animation

- 参考資料
  - バーテックスブレンディング [ [床井研究室](https://marina.sys.wakayama-u.ac.jp/~tokoi/?date=20091231) ]

## Lecture 3: Motion Interpolation / Motion Blending

- Date: 2024.06.13
- 概要: モーションの補間やブレンド手法を知ろう。
  - SLERP
- Challenges
  - [] Motion segmentation based on fixed length (ex. 2 sec.)
  - [] Angle
  - [] Quaternion
  - [] SLERP
  - [] QLERP

## Lecture 4: Motion Search / Motion Matching

- Date: 2024.06.20
- 概要: 動作の検索手法について知ろう。
  - Motion Graph
  - Motion Matching
- Challenges:
  - [] Motion Graph
- Refereces:
  - Motion Graph, SIGGRAPH 2002 [ [paper](https://dl.acm.org/doi/10.1145/566654.566605) ]

## Lecture 5: Motion Clustering

- Date: 2024.06.27
- 概要: モーションの分類
  - Principal Component Analysis(PCA)
  - Varietional Auto Encoder(VAE)
- Challenges
  - [] PCA
  - [] VAE

## 中間課題: これからの検索について考えよう

- Date: 2024.07.04
- Theme: 「これからの検索」
  - 生成AIにより従来型の検索と生成、合成といった分類が曖昧になりつつある今、</br>
    これからの検索はどうなっていくか、考えてみよう。
- Challenges
  - 「これからの検索」について考え、そのアイデアをpptを用いて5分間プレゼンせよ。
  - 上記のアイデアをモーション検索に応用し、プロトタイプを実装せよ。</br>
    加えて、上記結果と課題をpptを用いて5分間プレゼンせよ。
- Deadline: 2024.07.25
- Keywords
  - Generative AI
  - Retrieval Augmented Generation(RAG)

## Reference

- キャラクタアニメーションの数理とシステム [ [書籍](https://www.coronasha.co.jp/np/isbn/9784339029093/) ]
