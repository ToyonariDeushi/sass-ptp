用途
=================================================
パーセンテージをピクセル表記で記述するための変数集。  
__ベースサイズ__は以下の4つを用意しました。
* 13 px
* 14 px
* 15 px
* 16 px

使い方
=================================================
```scss
@import "ptp-12";

#main {
  font-size: $px50;
}
```

出力：
```css
#main {
  font-size: 417%;
}
```

> [CSSの常識が変わる！「Compass」、基礎から応用まで！](http://liginc.co.jp/designer/archives/11623)
