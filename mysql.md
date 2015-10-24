# サービス回り

開始
```
mysql.server start
```

# クエリ
## CREATE

CREATE文
```
CREATE TABLE db_name.tbl_name
  (
		col_name1 data_type1 opt
		, col_name2 data_type2 opt
		, ...
		,PRIMARY KEY ([col_name])
	);
```

opt(オプション)
* NOT NULL
* AUTO_INCREMENT


SHOW CREATE文
table_nameのテーブルを作成するCREATE文を出力
```
SHOW CREATE TABLE table_name
```
