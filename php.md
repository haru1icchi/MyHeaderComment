# PHPコメント
> official
> <https://www.phpdoc.org/docs/latest/index.html>

> <https://simple-it-life.com/2017/01/16/php-documentor/>
> <http://qiita.com/itosho/items/0f809e067a9e4a41515e>

## ヘッダコメント
```php
<?php
/**
 * ファイルの説明
 *
 * @copyright hoge Inc.
 * @license https://opensource.org/licenses/mit-license.html MIT License
 * @author Haruyuki Ichino <mail address>
 * @link 資料
 */

```

## クラス
```php
/**
 * このクラスではXXXを行います
 *
 * 1行空けてもう少し詳しく記述することができる
 * 複数行記述ができて、不要なら省略もできる
 *
 * @access アクセスレベル
 * @author 名前 <メールアドレス>
 * @copyright 会社名 All Rights Reserved
 * @category カテゴリー（処理系）
 * @package パッケージ（MVC）
 */
```

## 関数
```php
/**
 * このメソッドはXXを行います
 *
 * 詳細(略)
 *
 * @access アクセスレベル
 * @param int    $id
 * @param string $name
 * @return boolean ユーザが存在するかどうか
 * @link 参考資料のURL
 * @see 関連(呼び出したり)する関数
 * @throws 可能性のある例外を記述する
 * @todo TODO事項
 */
 function hoge($id, $name)
 { 関数の中身は省略 }

```

## phpdocの生成
```bash
// composerで導入するのでcomposerを準備
$ sudo bash -c "curl -sS https://getcomposer.org/installer | php"
$ sudo mv composer.phar /usr/local/bin/composer
// phpdocumentor導入
$ composer require "phpdocumentor/phpdocumentor:2.*"
既にPHPDoc形式でコメントを記述したPHPファイルがあるとしてphpdocコマンドでHTMLを作成する
```

```bash
$ ./vendor/bin/phpdoc -t output/ -d src/
 -t: DOCの出力先
 -d:DOCにする対象フォルダ
 -o:出力形式の指定
```
