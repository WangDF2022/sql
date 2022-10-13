## 练习题-第二部分（请给出代码、包含代码及代码执行结果的截图）

### 2.5

请指出下述SELECT语句中所有的语法错误。

```sql
SELECT product_id, SUM（product_name）
--本SELECT语句中存在错误。
  FROM product 
 GROUP BY product_type 
 WHERE regist_date > '2009-09-01';
```

### 2.6

请编写一条SELECT语句，求出销售单价（ `sale_price` 列）合计值大于进货单价（ `purchase_price` 列）合计值1.5倍的商品种类。执行结果如下所示。

```sql
product_type | sum  | sum 
-------------+------+------
衣服         | 5000 | 3300
办公用品      |  600 | 320
```

![图片](D:\wonderful-sql-main\img\ch02\ch02.08test26.png)

### 2.7

此前我们曾经使用SELECT语句选取出了product（商品）表中的全部记录。当时我们使用了 `ORDER BY` 子句来指定排列顺序，但现在已经无法记起当时如何指定的了。请根据下列执行结果，思考 `ORDER BY` 子句的内容。

![图片](D:\wonderful-sql-main\img\ch02\ch02.09test27.png)