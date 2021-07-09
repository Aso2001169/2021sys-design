### データベース詳細

 d_syouhin
|属性名|型|PK|NN|FK|
|--|--|--|--|--|
|syouhin_id|int(4)|○|○||
|syouhin_code|varchar(4)||○||
|syouhin_date|int(11)||○||
---
 d_order
|属性名|型|PK|NN|FK|
|--|--|--|--|--|
|orderc_id|int(4)|○|○|○|
|order_id|varchar(4)||○||
|syouhin_code|int(11)||○||
|order_date|date||○||
---
 d_customer
|属性名|型|PK|NN|FK|
|--|--|--|--|--|
|customer_id|int(4)|○|○||
|pass|varchar(20)||○||
|customer_name|text||○||
|customer_address|text||○||
|customer_tel|int(11)||○||
|customer_mail|text||○||
