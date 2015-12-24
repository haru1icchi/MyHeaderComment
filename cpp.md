以下のサイトを参照  
<http://futurismo.biz/archives/655>
Doxygenを利用したコメント記述

### ヘッダコメント
```cpp
/*!
* @file fname.c
*
* @date Created on: 2015/12/24
* @author Author: Haruyuki Ichino
* @version 1.0
* @brief 説明文
* @par 追加見出し項目
*/
```

### 関数ヘッダ関係
```cpp
/*!
* @fn function_name
* @brief 概要
* @param (引数名) 引数の説明
* @param (引数名) 引数の説明
* @return 戻り値の説明
* @sa 参照すべき関数を書けばリンクが貼れる
* @detail 関数の詳細
*/
```

### クラスコメント
```cpp
/**
* @class class_name
* @brief abstruct
* @n <改行タグです。いろいろなところで使えます>
* @author Haruyuki Ichino
* @version 1.0
* @date 2015/12/24
* <pre>
* HTMLのタグを使って、説明を書けば、それも出力されます。ちなみにpreは、内容をそのまま出力するHTMLのタグです。
* </pre>
*/
```

### 変数コメント
```cpp
/// 変数へのコメント
int HenSu = 0;
```

### 構造体コメント
```cpp
/*! @struct Struct_name
* @brief 説明
*/
typedef struct NUM
{
/// 説明
int num;

/// 説明
int count;
}struct_val;
```

### 列挙型コメント
```cpp
/* @enum
* 説明
*/
typedef enum{
/// 説明
item1,

/// 説明
item2,

/// 説明
item3
}enum_val;
```

### 一般的なコメント
```cpp
/**
 * ここにテキストを書く
 */
```
