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
javascript:document.getElementById("ri-cmn-hdr-sitem").value="父の日";void(0);
```

### 掲示板初期画面
![image](https://user-images.githubusercontent.com/1501327/167070439-dceaf5ce-8ca4-40cc-9aea-a5a19b7904dd.png)

### VSCode : MySQL 接続作成
![image](https://user-images.githubusercontent.com/1501327/167071194-70bf142c-0585-4095-83c3-8b58a2d9480b.png)

### Sqlite3
![image](https://user-images.githubusercontent.com/1501327/167071542-63832115-6506-41fb-9f60-4ac6f5dee6da.png)

## MySQL ODBC32 構成
![image](https://user-images.githubusercontent.com/1501327/167072410-6023949c-f2e3-4d56-b37e-d2f285f25bec.png)

## Sqlite3 ODBC32 構成( このままでは化けるので使用できない )
![image](https://user-images.githubusercontent.com/1501327/167073252-e7a21d26-5f98-472b-9880-793483b1e35e.png)

## CSV ODBC32 構成
![image](https://user-images.githubusercontent.com/1501327/167074500-eb77211d-32a0-43b8-b2c6-a165d2816e4b.png)


## 手作業の C#プロジェクト の作成
```
dotnet new console -f net5.0 
dotnet add package System.Data.Odbc
```
