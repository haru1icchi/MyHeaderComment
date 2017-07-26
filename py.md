# Pythonのコメント
> <https://hondou.homedns.org/pukiwiki/pukiwiki.php?Python%20%A5%B3%A5%E1%A5%F3%A5%C8%A1%A2Pydoc#mb247c42>
> <http://symfoware.blog68.fc2.com/blog-entry-884.html>

## ヘッダコメント
```python
#!/usr/bin/env python
# coding: utf-8

"""
説明文
"""

__author__ = "Haruyuki Ichino <Mail Address>"
__version__ = "0.0.1"
__date__    = "2015/12/24"

```

## クラス
定義の下に説明文を記述
```python
class hoge(object):
    """
    クラスの先頭に書いたコメント
    """
```

## 関数
関数定義の下に説明文を記述
```python
def test(self):
    """
    メソッドの先頭に書いたコメント

    @param  list  引数1
    @return list の各要素に 1 を加えたリスト
    """
    pass
```

## pydocの生成
```bash
# pydocを標準出力
$ pydoc [filename] # 拡張子なし

# pydocをhtmlで出力
$ pydoc -w [filename]
```
