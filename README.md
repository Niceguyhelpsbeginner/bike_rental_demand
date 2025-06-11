# 🚲 自転車レンタル需要予測プロジェクト

このリポジトリは、Kaggleコンペティション「[Bike Sharing Demand](https://www.kaggle.com/competitions/bike-sharing-demand)」に参加するために作成されたプロジェクトです。

## 📌 概要

ワシントンD.C.のレンタルサイクルの利用履歴データを使用して、特定の日時におけるレンタル数（`count`）を予測することを目的としています。

提供されるデータには、気象情報や休日情報、曜日などの特徴が含まれています。

## 📁 ファイル構成

- `bike_rental.ipynb`：データの前処理、特徴量エンジニアリング、モデリング（XGBoostなど）を行うJupyter Notebook。
- `train.csv`, `test.csv`：Kaggleより提供されたトレーニング・テストデータ（GitHubには含めていません）。

## 🔧 使用技術

- Python
- Pandas / NumPy
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn

## 🧠 モデルと評価

主に以下の手法を使用しました：

- 特徴量のエンジニアリング（時間帯、曜日、祝日など）
- ログ変換によるスケール調整
- XGBoostによる回帰モデルの構築
- RMSLE（対数平均二乗誤差）を評価指標として使用

## 🏆 結果

- Kaggle スコア：*例: 0.41 (Private Leaderboard)*  
（※実際のスコアに応じて編集してください）

## 📈 今後の課題

- 深層学習モデル（例: LSTM, TabNet）の導入
- 外部気象データの活用
- モデルアンサンブルによる精度向上

## ✍️ 作者

- 김성진（Sungjin Kim）  
- Kaggle: [あなたのKaggleプロフィールへのリンク]  
- GitHub: [あなたのGitHubプロフィールへのリンク]

## 📄 ライセンス

このプロジェクトはMITライセンスのもとで公開されています。
