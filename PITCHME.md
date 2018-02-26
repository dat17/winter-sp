# 特別講義
## テーマ：就職に向けて
（就活が終わった人も、モノ作りに役立つと思います）

---

# 就職活動のためにやっておきたいこと
- 個人作品を作ってどんどん発表（これを今日やります）
- チームで作業したエピソード作り(これもちょっと関連)
- 興味がある分野について、雑学を仕入れておこう

---

# 個人作品を作る
## お手本を探そう
- Asset Store
- Sketchfab
- pixiv
- Poly

---

## Asset Store
- Unityライセンスを作成(以前、作成したような...)
- 作品を探してみる
- Unityに読み込む

---

### 仕組みを確認しよう
- ポリゴンや頂点数
- 構造(どこを一体化しているか)
- テクスチャーの使い方
- マテリアルの使い方

## Sketchfab
- 作品を探す
- 構造を確かめよう
- ポストエフェクトの効果を確認する
- Unityに読み込んでみよう

## その他も確認
- pixiv
- poly

# 発表する
- 会社に見せる前に、色々な人に見せよう
- 「勉強を始めました」とか「作ってみました」の時点で発表した方がハードルが下がる
- SNS、pixivなどからはじめて、Asset StoreやSketchfabなどで販売することを目指そう
- スクリーンショットなども気軽でおススメ
  -  Unity Asset Portal スクショコンテスト http://assetstore.info/eventandcontest/screenshotposting/

誰にも見せたことがない状態でいきなり会社に持ち込むのは、一度も練習試合をせずに甲子園の予選に出るようなもの。


# ゲームに使うデータの作成
ここからは、チーム活動について。

## UnityとMAYAの連携
- UnityのモデルをMAYAに持っていく
- MAYAから持ってくる

## キャラクターのアニメーション
- Pivotをそろえよう

## TileMapを触ってみよう
- 2D Game Kitの読み込み
- レベルデザインをしてみよう

## その他、注意事項
- 日本語や全角文字は使わないように！

# ポートフォリオに向けた作品作り
- 使い方を限定したものを作ってみよう
  - 何にでも使えるものは、何にも使えない


# まとめ
- 個人作品を作ってどんどん発表（これを今日やります）
- チームで作業したエピソード作り(これもちょっと関連)
- 興味がある分野について、雑学を仕入れておこう

# 宣伝
- 来学期（おそらく水曜日）は16時半以降、A601教室にてもくもく会を行います。質問や共同作業をしたい場合はお気軽に来てください



------ 


- 発表をしよう / できれば販売も
  - pixiv(ただちょっと色々炎上している)
    - https://factory.pixiv.net/
  - Sketchfab
  - Unity Asset Store
    - https://docs.unity3d.com/jp/530/Manual/AssetStoreMassLabeler.html
    - https://qiita.com/tempura/items/d8048ef72c94b59778f9
  - Unity Asset Portal スクショコンテスト http://assetstore.info/eventandcontest/screenshotposting/
  - https://poly.google.com/
  - https://vr.google.com/blocks/


# 手順
## アセットストアの紹介
- アセットストアの紹介
  - Unityアカウントを作成
  - 右上の言語を日本語に
  - 部屋 3D Modles -> 小道具 -> 家具 / Pack Gesta Furniture #1
    - Clear Baked Dataをやって、違いを確認。また、Boxをおいてみる
    - Bakeしなおす(Bouncesの2が重要。これで光が2回跳ね返るので明るくなる)
    - 家具を動かすと、影が焼きついているのが分かる
    - Auto Generateをつけると、家具を動かしたら自動的にリビルド開始(時間がかかる)
  - マップ 3D Models -> Environments / Urban Town Pack / NYC Block #6 を読み込んで、構造を観察する。FPS Controllerがない

## キャラクターをいじる
- キャラ 3D Models -> Characters / Animation
- Animation / RPG Character Mecanim Animation Pack
  - 
- パーティクル Unity Standard Particle
- 人モデルへのアニメ適用 Unity Chan
  - https://sketchfab.com/ も使える
  - モデルを用意
  - アニメーションを用意
- mayaからunityへ
  - 上記のアニメを持っていく
  - FBX Exporter を検索して、ダウンロード -> インポート
  - 

## 仕上げる
- 部屋へのGI設定 テラシュール
  - 部屋モデル
- クロスシミュレーション
- unityに持っていくときの注意点
  - 日本語や全角はやめて
  - 規則性のある命名を
  - ポリゴン数に気をつける
  - マップは3つから4つ
  - マテリアルごとにモデルを分ける
  - 透明を使う場合は分ける
- 公開先の紹介
  - アセットストア
  - poly




