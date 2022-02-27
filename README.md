![main-image](https://user-images.githubusercontent.com/98724087/153336746-0210b0f9-34be-4532-9290-bcd9f80675c5.png)<br><br>

## 🔧 ツールと言語
<a href="https://developer.apple.com/swift/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/swift/swift-original.svg" alt="swift" width="40" height="40"/> </a>
<a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a>
<br><br>

## 💬 概要
### 好きな映画で英語を学ぶアプリ<br>
※ 映画の他、TED / 洋楽 / Youtube等でも<br><br>

## 📃 使い方
### 1. テスト情報を登録する<br>
- 英語字幕を撮影すると日本語訳の自動生成&単語の抽出が自動的に行われます。
- カードをスワイプすると英語/日本語訳/単語の3つの情報が保存されます。<br><br>
![add-card](https://user-images.githubusercontent.com/98724087/151968422-d7b3778c-928d-40d3-a4f5-3f7c2af37759.gif)<br><br><br>
※ 自動翻訳が期待通りでない場合は、日本語字幕を参考に手動入力します。<br>
( 英語と日本語の字幕が同時に表示されるように設定をしておくと修正が楽です )<br><br>
![modified](https://user-images.githubusercontent.com/98724087/151967194-e1d46c65-a71a-4fe1-a128-91e5414b5d41.gif)<br><br><br>
※ 長文の場合は、ピンチアウトで撮影領域を広げます。<br><br>
![capture-long](https://user-images.githubusercontent.com/98724087/151967102-fce026f4-9caf-498f-9389-2dfad93093e9.gif)<br><br><br>
※ 単語を登録する場合<br>
任意の単語をタップすると辞書が表示されます。<br>
辞書で単語の意味を確認の上、登録します。<br><br>
![add-word](https://user-images.githubusercontent.com/98724087/151966906-729ab7d3-a92a-434d-8aec-b627c52220aa.gif)<br><br><br>

### 2. テストする<br>
1で登録した情報を用いて各種テストが生成されます。<br>
テストする映画、テストの種類を選択します。<br>
※ テストの種類については、「テストの種類」をご覧ください。<br><br>
![test-new](https://user-images.githubusercontent.com/98724087/155653627-44badfdb-67ca-4028-a321-fb887524317b.gif)<br><br>

### 3. ダウンロードする
自分の勉強のために作ったテストが他の誰かの勉強にも役だったらおもしろいと思い、ダウンロードできるようにしました。<br><br>
![download](https://user-images.githubusercontent.com/98724087/151967953-2473b579-820c-4f00-91b7-21bddd923261.gif)<br><br>

## 🔤 テストの種類
※ DEMO動画に表示される黄色いテキストは音声です
| 種類 | DEMO | テスト方法 |
| :-: | :-: | :-|
|リスニング| ![listening-new](https://user-images.githubusercontent.com/98724087/155654082-024aa972-488f-4908-95c7-29b812d8e42d.gif) | ・ 音声を聞いて回答します。 <br> ・ 正解したら左に、不正解なら右にスワイプします。(全テスト共通)<br> ・ 答えがわからない時は、答えボタンを押して答えを確認します。(全テスト共通) |
|スピーキング| ![speaking](https://user-images.githubusercontent.com/98724087/151964064-60e85451-9f57-4594-8b08-b19f4395a4f6.gif) | ・ 発話した英語が認識されれば、穴埋め部分に表示されます。|
|単語| ![vocabrary](https://user-images.githubusercontent.com/98724087/151964133-2e16b37e-6b64-4101-8daf-9d3e9b1e4fa6.gif) |・音声を聞いて回答します。<br>・正解するとテキストが緑色になります。|
|ディクテーション| ![dictaion](https://user-images.githubusercontent.com/98724087/151964223-c2cc7f9f-a38c-4a10-a01e-66c585ce7155.gif) |・音声を聞いて回答します。<br>・正解するとテキストが緑色になります。|
|シャドーイング| ![shadowing](https://user-images.githubusercontent.com/98724087/151964718-cde442d9-a32d-4b98-b03f-a6b7b4eff1e5.gif) |・ 繰り返し回数を設定します。<br>・ 音声が設定した回数の数だけ繰り返されるので、音声の後に続けて発音します。|

<br><br>
## 📝 ライブラリ
以下のMLKitを使用しています。<br>
- Text recognition ... 画像内のテキストを認識するために使用<br>
- Translation ... 日本語翻訳のために使用<br><br>

## 🗺 全体の構成
![kousei](https://user-images.githubusercontent.com/98724087/152219955-f9a4ca2d-5866-4acd-ac2d-a272a7eee350.png)
<br><br>

## 🔍 リサーチ
英語が流暢なyoutuberの方々の勉強方法紹介動画を見てリサーチを行なったところ、<br>
映画、ドラマ、洋楽、TED、youtubeなどを通した勉強方法を紹介されている方が多くいらっしゃいました。<br>
その理由として、<br><br>

```
・ 楽しく続けられる
・ 実践的な英語が学べる
・ ネイティブの発音に慣れることができ、リスニング力&スピーキング力が向上する
```

<br>
等があげられていました。<br>
そして、<br><br>

```
・ スキマ時間の活用
・ 反復
```

<br>
の大切さも言及されていました。<br><br>
以上を踏まえて、<br>
映画を見ているときに覚えたいフレーズや知らない単語が出てきたらメモ代わりに字幕を撮影し、<br>
スキマ時間で復習テストが行えるアプリをつくってみたいと思いました。

<br><br>

## ⭐️  特徴
- no story board
- MVVM
