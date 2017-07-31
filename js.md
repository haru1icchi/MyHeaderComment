# JavaScript
JavaScriptのDocプラグイン有名どころ
* [ESDOC](https://github.com/esdoc/esdoc)
* [YUIDoc](http://yui.github.io/yuidoc/)
* [JSDOC3](http://usejsdoc.org/)

ESDOCの使い方やDOC後のUIが好みだったのでこれを採用  
* [ESDOCを開発した経緯](http://blog.h13i32maru.jp/entry/2015/05/06/221041)  
* [比較記事](http://chikathreesix.com/?p=98)




## ヘッダ
```js
/**
 * @author Haruyuki Ichino <mail address>
 * @version 0.0.1
 * @date 2017/07/31
 */
```

## クラス
定義の上に説明文を記述
```js
/**
 * this is BaseClass.
 */
export class BaseClass {
}
```

## 関数
関数定義の上に説明文を記述
```js
/**
 * this is method of MyClass.
 * @param {number} a - this is a 1st number value.
 * @param {number} b - this is a 2nd number value.
 * @returns {string} repeated Hello
 */
 method(a, b){
     return 'Hello'.repeat((a + b) * this._property);
 }
```

## docの生成
> * [Official](https://esdoc.org/manual/usage.html)  
> * [使ってみたサイト](http://akabeko.me/blog/2015/07/esdoc/)
