# 鳥の悪魔討伐戦

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
東方ライクのシューティングゲーム

## ゲームの遊び方
* 矢印キーでUFOを操作し，スペースキー押下による球で敵を倒していく
* 敵、敵の球に当たると残機が減り、残機が0となるとゲームオーバーとなる

## ゲームの実装
### 共通基本機能
* スコア等の表示、自分のシューティング機能、もとは無双こうかとん

### 担当追加機能
* 味方残機、UI作成（担当：李）：自分の残機を管理するクラス、ゲームオーバー条件も設定
* 武器強化（担当：竹田）：敵を倒していくごとにレベルアップで武器を強くしていく機能
* 雑魚敵の作成、配置など（担当：楠）：雑魚敵の作成を行い、配置を行う
* ボスに作成（担当：森）：ボスを作り、ボスのHPなど諸々の判定などを決める
* ステージ背景、縦スク処理など（担当：沢田）：ステージ背景の作成、縦スクゲームみたいにする

### ToDo
- [ ] 味方残機
- [ ] 武器強化
- [ ] 敵の作成、配置管理
- [ ] ボス
- [ ] ステージ背景、縦スク処理など

### メモ
* クラス内の変数は，すべて，「get_変数名」という名前のメソッドを介してアクセスするように設計してある
* すべてのクラスに関係する関数は，クラスの外で定義してある
