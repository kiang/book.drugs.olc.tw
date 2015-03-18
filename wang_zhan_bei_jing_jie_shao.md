# 網站背景介紹

在一位醫師朋友轉貼的資訊中，注意到 [食品藥物開放資料平臺](http://data.fda.gov.tw/) 開始著手將一些資訊開放給民眾取用，接著看了一下官方推出的 [藥物許可證查詢作業](http://www.fda.gov.tw/MLMS/%28S%28mya1xwyafu34m1y41pmblgr4%29%29/HList.aspx) 網站，覺得有可以發揮的地方，所以開始著手進行一些網站雛型的開發。

藥要看截至目前為止使用了下面來自[食品藥物開放資料平臺](http://data.fda.gov.tw/)開放的資料集：
* [PIC/S GMP藥廠名單資料集](http://data.fda.gov.tw/frontsite/data/DataAction.do?method=doDetail&infoId=31)
* [回收藥品資料集](http://data.fda.gov.tw/frontsite/data/DataAction.do?method=doDetail&infoId=34)
* [全部藥品許可證資料集](http://data.fda.gov.tw/frontsite/data/DataAction.do?method=doDetail&infoId=36)
* [藥品仿單或外盒資料集](http://data.fda.gov.tw/frontsite/data/DataAction.do?method=doDetail&infoId=39)
* [藥品藥理治療分類ATC碼資料集](http://data.fda.gov.tw/frontsite/data/DataAction.do?method=doDetail&infoId=41)
* [藥品外觀資料集](http://data.fda.gov.tw/frontsite/data/DataAction.do?method=doDetail&infoId=42)
* [藥品詳細處方成分資料集](http://data.fda.gov.tw/frontsite/data/DataAction.do?method=doDetail&infoId=43)
* [嚴重違反GMP藥廠](http://data.fda.gov.tw/frontsite/data/DataAction.do?method=doDetail&infoId=45)
* [消費紅綠燈-國際藥品](http://data.fda.gov.tw/frontsite/data/DataAction.do?method=doDetail&infoId=65)
* [藥品健保藥價資料集](http://data.fda.gov.tw/frontsite/data/DataAction.do?method=doDetail&infoId=74)

同時整併來自下面網站的資料：
* [健保局特約藥局](http://www.nhi.gov.tw/Query/query3_list.aspx)
* [中醫藥司中藥許可證資料](http://www.mohw.gov.tw/CHT/DOCMAP/query_liense.aspx?mode=1)

以及透過美國 [openFDA](https://open.fda.gov/) 網站的 API ，在檢視西藥成份時嘗試取得該網站所蒐集的藥物不良反應通報統計。

[藥要看](http://drugs.olc.tw/) 網站期望透過開放、友善的方式降低藥物資訊檢索的難度，未來除了既有資料的交叉應用外，也希望發展出符合使用者期待的加值應用。