---
tags: [csv, sqlite3]
title: sqlite3 import csv
created: '2020-11-17T16:25:04.405Z'
modified: '2020-11-17T16:25:51.593Z'
---

# sqlite3 import csv

sqlite> create table foo(a, b);
sqlite> .separator ,
sqlite> .import test.csv foo

[link](https://stackoverflow.com/questions/14947916/import-csv-to-sqlite)
