# Graph-Neural-Networks_PyG

グラフニューラルネットワーク（GNNs）のリポジトリです。

## リポジトリ構成

```
.
├── Dockerfile
├── README.md
├── data
├── docker-compose.yml
├── docs
├── models
├── notebooks
│   ├── 1_Introduction.ipynb
│   ├── 2_Node_Classification.ipynb
│   ├── 3_Graph_Classification.ipynb
│   ├── 4_Scaling_GNNs.ipynb
│   ├── 5_Point_Cloud_Classification.ipynb
│   ├── 6_GNN_Explanation.ipynb
│   ├── Mutagenicity
│   │   ├── processed
│   │   └── raw
│   └── data
│       ├── GeometricShapes
│       ├── Planetoid
│       └── TUDataset
├── pyproject.toml
├── requirements.txt
├── setup.cfg
├── src
│   └── __init__.py
├── tests
│   └── __init__.py
└── work
```

## 環境詳細

- Python : 3.9.6

## 事前準備

- Docker インストール

## 環境構築

- Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/Graph-Neural-Networks_PyG）

```
cd Desktop/Graph-Neural-Networks_PyG
```

- Dockerによる環境構築（フォルダをマウント：Desktop/Graph-Neural-Networks_PyG）

```
docker-compose up --build
```

- ブラウザーを立ち上げてlocalhost:8888へアクセス
- ローカルフォルダがマウントされている

## 動作環境

マシンスペック（Mac)

- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
