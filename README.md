# subject-1001-mysql

![image](https://user-images.githubusercontent.com/1501327/135567023-9395f481-9892-4b7b-a57b-26c804d1da76.png)

```sql
LOAD DATA [LOCAL] INFILE
    'C:/app/workspace/subject-1001/sql/data01.csv'
 INTO TABLE table01
    FIELDS TERMINATED BY ','
    OPTIONALLY ENCLOSED BY '"'
    LINES TERMINATED BY '\r\n';
```

**ファイルのパスは、Windows のフルパスですが、MySQL に渡す時は、\ を / に変えてください**

※ 先頭の \ を 選択して CTRL + B で必要な場所まで選択として、/ キーを押して一括選択しましょう\
※ LOCAL は省略した場合ファイルはサーバーホスト上にある必要があります
