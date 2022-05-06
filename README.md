# subject-220506

### デベロッパーツールのコンソール( 楽天トップ )
```js
jQuery("#common-header-search-input").val("母の日")
```
- 検索後のページで
```js
jQuery("#ri-cmn-hdr-sitem").val()
jQuery("#ri-cmn-hdr-sitem").css("background-color","aqua")
jQuery("#ri-cmn-hdr-sitem").css({ "background-color":"gray", "text-align":"right" })

```
- DOM で値セット
```js
document.getElementById("ri-cmn-hdr-sitem").value = "母の日 プレゼント 洋菓子"
document.getElementById("ri-cmn-hdr-sitem").style.backgroundColor = "gray"
document.getElementById("ri-cmn-hdr-sitem").style.textAlign = "right"
```

- ブックマークレットで入力を省く
```js
javascript:jQuery("#ri-cmn-hdr-sitem").val("母の日");void(0);
```
