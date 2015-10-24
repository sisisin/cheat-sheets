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

data_type
## 数値
* TINYINT -128から127 (符号無しの場合0から255)
* SMALLINT -32768から32767 (符号無しの場合0から65535)
* MEDIUMINT -8388608から8388607 (符号無しの場合0から16777215)
* INT -2147483648から2147483647 (符号無しの場合0から4294967295)  
  別名：INTEGER
* BIGINT -9223372036854775808から9223372036854775807
  (符号無しの場合0から18446744073709551615)
  
## 日付
* DATE  
  フォーマット : 'YYYY-MM-DD'  
  範囲 : '1000-01-01' から '9999-12-31'  

* DATETIME  
  フォーマット : 'YYYY-MM-DD HH:MM:SS'  
  範囲 : '1000-01-01 00:00:00' から '9999-12-31 23:59:59'  
  
* TIMESTAMP  
  フォーマット : 'YYYY-MM-DD HH:MM:SS'  
  範囲 : '1970-01-01 00:00:01' から '2037-12-31 23:59:59'  
  
* TIME  
  フォーマット : 'HH:MM:SS'  
  範囲 : '-838:59:59' から '838:59:59'  
  
* YEAR[(2|4)]  
  フォーマット : YYYY  
  範囲 : 1901 から 2155、そして 0000 (4桁の場合)  
  範囲 : 70  から 69 (2桁の場合、70は1970を表し69は2069を表す)  
  デフォルトは4桁  
  
## 文字列
* CHAR(M)  
  固定長文字列  
  Mは文字数を指定。0から255文字  
  別名：CHAR(M)はCHARACTER(M)の別名  
  
* VARCHAR(M)  
  可変長文字列  
  Mはバイト数を指定。0から65535バイト  
  別名：VARCHAR(M)はCHARACTER VARYING(M)の別名  
	
opt(オプション)
* NOT NULL
* AUTO_INCREMENT
* UNSIGNED 数値型を作成するときに符号なしとするオプション

SHOW CREATE文
table_nameのテーブルを作成するCREATE文を出力
```
SHOW CREATE TABLE table_name
```
