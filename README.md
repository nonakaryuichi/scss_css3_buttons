SCSS CSS3 Buttons
==================================================
SCSS用に作られた質感の良いボタンを簡単に指定できるMixinです。  
このMixinを利用するにはSassとcompassが必要です。

バージョン
--------------------------------------------------
ver 0.1 (Beta)

読み込み方法
--------------------------------------------------
出力用のscssファイルにインポートします。

```css
@import "compass";
@import "css3_buttons";
```

説明
--------------------------------------------------
### 基本的な利用方法
** css3_button ( $type: [buttonType], $color: [buttonBgColor], $font_color: [white|black] ) **  
@param $type: [normal] button type. 
@param $color: [color code] button bg color. 
@param $font_color: [white|black] button font color. 

### 記述サンプル
```css
.button
{
        @include css3_buttons( normal, #ccc );
}
```

ライセンス
----------------------------------------------------
SCSS CSS3 Buttons
 
Aauthor   : Ryuichi Nonaka  
Version   : 0.1 Beta
Copyright : 2012 Ryuichi Nonaka  
Date      : 2012/10/28  

Released under the MIT license

