# dups

dups.jsが常駐している場合、url?edit=1000でEDITが現れる。
EDIT中はCTRL+Sで自分を更新可能

また、リンクが存在しない、内部リンクに対しては、複製できる。

## インターフェイス
```
<script src="dups.js" onload="

const rewriteQuery = 'main'
dups(rewriteQuery)

// |EDIT|

" />
```
