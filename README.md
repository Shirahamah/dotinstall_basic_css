# dotinstall_basic_css

詳解CSS 基礎文法編
ウェブページの見た目を整えるための言語である、CSSの基礎的な文法について学んでいきます。
https://dotinstall.com/lessons/basic_css_styles_v2

成果物を置くリポジトリです

## 01 CSSを学んでいこう
https://dotinstall.com/lessons/basic_css_styles_v2/51201

### 講座内容
- CSSの概要
- 学習の流れ
- 使用ブラウザ、エディタの確認

### 成果物
- なし  
基礎文法編での学習内容の確認、学習の流れの確認  

### コメント  
この講座で学ぶ内容の概要がわかった。

## 02 学習の準備を整えよう
https://dotinstall.com/lessons/basic_css_styles_v2/51202

### 講座内容
- 画像素材の確認
- プロジェクトフォルダの設定
- index.htmlの作成

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/02/

### コメント  
CSSを記述するためのindex.htmlを作成した。内容自体はHTML講座の復習のような感じなので新しく学んだことは特になかったです。

## 03 はじめてのCSS
https://dotinstall.com/lessons/basic_css_styles_v2/51203

### 講座内容
- styleタグ
- linkタグ
- cssファイルの作成
- style属性

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/03/

### コメント  
CSSの書き方については知っていたので、特に新しく学んだことはなかったです。

## 04 CSSの文法に慣れよう
https://dotinstall.com/lessons/basic_css_styles_v2/51204

### 講座内容
- CSSの書き方
- 用語の確認
- コメント

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/04/

### コメント
書き方については知っていましたが、スタイルを指定する用語が「セレクター」、指定するスタイルを「宣言」、宣言の左側を「プロパティ」、右側を「値」という用語までは把握していなかった。

## 05 スタイルの継承を理解しよう
https://dotinstall.com/lessons/basic_css_styles_v2/51205

### 講座内容
- スタイルの継承
- Cascading Style Sheets

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/05/

### コメント
CSSの継承については何が継承させて何が継承されないのか分かっていないのでしっかり把握する。継承は次回以降の講座で詳しく見ていく予定。

## 06 CSSの仕様を調べてみよう
https://dotinstall.com/lessons/basic_css_styles_v2/51206

### 講座内容
- MDN
- 継承の有無
- inherit

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/06/

### コメント
MDNサイトを使ってh1、borderの仕様、継承の有無を確認。継承がない場合でもinheritを使うことで適用させることができることがわかった。

## 07 デベロッパーツールを使ってみよう
https://dotinstall.com/lessons/basic_css_styles_v2/51207

### 講座内容
- デベロッパーツールの操作方法
- パネルの見方

### 成果物
- なし  
第6回のソースをデベロッパーツールで確認。

### コメント
デベロッパーツールは普段から見ることもあったため、ある程度の見方はわかっていました。

## 08 テキストにスタイルを設定しよう
https://dotinstall.com/lessons/basic_css_styles_v2/51208

### 講座内容
- color
- font-size
- font-weight
- text-align
- text-decoration

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/08/

### コメント
text-decorationでテキストの打消し線、下線を設定できることがわかった。

## 09 font-familyでフォントを指定しよう
https://dotinstall.com/lessons/basic_css_styles_v2/51209

### 講座内容
- フォント決定の仕組み
- font-family
- 総称フォントファミリー

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/09/

### コメント
font-familyの仕組み、フォント名に空白がある場合は「'」か「"」で囲む必要があること、cssに日本語が含まれる場合は、文字化けの可能性があるためcssファイルの先頭に@charset "utf-8";を書く必要があることがわかった。

## 10 line-heightで行の高さを調整しよう
https://dotinstall.com/lessons/basic_css_styles_v2/51210

### 講座内容
- line-height
- em
- 単位なしの指定

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/10/

### コメント
line-heightを指定することで、行間の制御もできることがわかった。また高さに、1文字分を表す「em」が使えることがわかった。単位なしでの違いについては次回の講座で見る予定。

## 11 単位なしでline-heightを指定しよう
https://dotinstall.com/lessons/basic_css_styles_v2/51211

### 講座内容
- 単位ありの指定
- 単位なしの指定

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/11/

### コメント
単位ありで書いた場合は親要素で計算された値がそのまま子要素に継承、単位なしで書いた場合は親要素の値を継承せず、子要素のほうで再計算されることがわかった。

## 12 vertical-alignで位置を調整しよう
https://dotinstall.com/lessons/basic_css_styles_v2/51212

### 講座内容
- vertical-align
- baselineの位置について

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/12/

### コメント
文中に画像を配置する際の位置と指定の仕方、vertival-alignはpタグには適応できないことがわかった。

## 13 RGBAを使った色の表現方法を覚えよう
https://dotinstall.com/lessons/basic_css_styles_v2/51213

### 講座内容
- キーワードによる色の指定
- rgba()
- rgb()
- 16進数による指定

### 成果物
- なし  
rgbaについてスライドを使った説明。

### コメント
rgbaでの色指定については知っていたため特に問題ありませんでした。

## 14 HSLAを使った色の表現方法を覚えよう
https://dotinstall.com/lessons/basic_css_styles_v2/51214

### 講座内容
- hsla()
- hsl()
- opacity

### 成果物
- なし  
hslaについてスライドを使った説明。

### コメント
hslaでの色の表現方法は知らなかったので覚える。

## 15 リストをスタイリングしてみよう
https://dotinstall.com/lessons/basic_css_styles_v2/51215

### 講座内容
- list-style-type
- list-style-position
- list-style-image
- 画像ファイルの指定

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/15/

### コメント
listの先頭の記号の変え方、消し方がわかった。

## 16 一括指定プロパティを使ってみよう (02:47)
https://dotinstall.com/lessons/basic_css_styles_v2/51216

### 講座内容
- 一括指定プロパティ
- MDNによる仕様確認
- 初期値について

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/16/

### コメント
一括指定プロパティで値を省略した場合は初期値が入るため、その前に書いた個別の設定が上書きされてしまう動きになることがわかった。

## 17 クラスセレクターの基本をおさえよう
https://dotinstall.com/lessons/basic_css_styles_v2/51217

### 講座内容
- クラスセレクター

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/17/

### コメント
class属性のスタイリングについて、概要がわかりました。セレクターについての詳細は別レッスンで行う予定です。

## 18 ボックスモデルを理解しよう
https://dotinstall.com/lessons/basic_css_styles_v2/51218

### 講座内容
- ボックスモデル
- width
- height
- border
- padding
- margin
- デベロッパーツールでの確認

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/18/

### コメント
ボックスモデルの領域の関係性がわかりました。ボックスモデルの操作は次回以降の講座で行います。

## 19 width､heightを設定してみよう
https://dotinstall.com/lessons/basic_css_styles_v2/51219

### 講座内容
- width
- px, %による指定
- height
- overflow

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/19/

### コメント
コンテンツが領域からはみ出た場合、overflow: hidden;であふれた部分を隠せる、overflow: scroll;で領域内でスクロールできるようになることがわかった。

## 20 borderで境界線をつけてみよう
https://dotinstall.com/lessons/basic_css_styles_v2/51220

### 講座内容
- border-width、border-style、border-color
- border
- border-top、border-bottom
- border-radius

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/20/

### コメント
ボーダーの書き方、角の丸め方がわかりました。ボーダーの種類は必要に応じてMDNサイトで調べます。

## 21 paddingで内側の余白を付けよう
https://dotinstall.com/lessons/basic_css_styles_v2/51221

### 講座内容
- padding-top
- padding-left
- padding

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/21/

### コメント
paddingの一括指定の値の数とルールがわかった。

## 22 marginで外側の余白を付けよう
https://dotinstall.com/lessons/basic_css_styles_v2/51222

### 講座内容
- margin-bottom
- margin
- margin-left
- margin-right
- auto

### 成果物
- https://shirahamah.github.io/dotinstall_basic_css/22/

### コメント
左右のmarginをautoにすることでボックスモデルを中央揃えにすることができる。

## 23 marginの相殺を理解しよう
https://dotinstall.com/lessons/basic_css_styles_v2/51223

### 講座内容
- marginの相殺

### 成果物
- なし  
marginの相殺についてスライドで説明

### コメント
垂直方向のmarginが重なったときは値が小さいほうのmarginが相殺されることがわかった。垂直のmarginでおかしな挙動が起きたらmarginの相殺を疑うようにする。

## 24 displayプロパティについて理解しよう
https://dotinstall.com/lessons/basic_css_styles_v2/51224

### 講座内容
- block
- inline
- inline-block
- 挙動の違い

### 成果物
- なし  
displayプロパティについてスライドで説明

### コメント
blockとinline、inline-blockでは、配置方法とwidth、heightの操作に違いがあることがわかった。