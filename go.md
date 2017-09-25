# Golangのコメント
> http://golang.jp/effective_go#commentary
> https://qiita.com/macococo/items/fb6da04d3909edc90e37

## ヘッダコメント
```Golang
/**
 * Author: Haruyuki Ichino <mail@icchi.me>
 * Version: 0.0.1
 * Date: 2015/12/24
 */
```

## Package
定義の上に説明文を記述
```Golang
// クラスの先頭に書いたコメント
// about package
package main
```

## 関数
関数定義の上に説明文を記述
```Golang
// メソッドの先頭に書いたコメント
func test(hoge string) {
    ...
}
```

## pydocの生成
```bash
# $GOPATH配下のソースドキュメントを見る
godoc -http=:6060
```
