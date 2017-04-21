# Important dates - Vietnamese

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/important-dates-vietnamese-1c218) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/kkvw-hirn) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/kkvw-hirn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/kkvw-hirn/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | kkvw-hirn |
| Name | Important dates - Vietnamese |
| Category | Election operations |
| Tags | calendar, elections, vietnamese |
| Created | 2012-01-13T20:47:45Z |
| Publication Date | 2013-01-03T18:30:00Z |

## Description

Important dates for the election calendar posted to the King County Elections website

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| No       |             | date        | Date       | text      | text        |
| Yes      | series tag  | event       | Event      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:kkvw-hirn d:2013-01-03T10:29:43.000Z t:event="L? phi?u d?nh cho c? tri ? n??c ngo?i v? trong qu?n ??i ?? ???c g?i ?i cho Cu?c B?u C? ??c Bi?t ng?y 12 th?ng 2" m:row_number.kkvw-hirn=1

series e:kkvw-hirn d:2013-01-03T10:29:43.000Z t:event="H?n ch?t g?i ??n ??ng k? v? chuy?n h? s? c? tri qua ???ng b?u ?i?n v? tr?c tuy?n cho Cu?c B?u C? ??c Bi?t" m:row_number.kkvw-hirn=2

series e:kkvw-hirn d:2013-01-03T10:29:43.000Z t:event="M?y Ti?p C?n B? Phi?u v? l? phi?u c? s?n cho ??n Ng?y B?u C?" m:row_number.kkvw-hirn=3
```

## Meta Commands

```ls
metric m:row_number.kkvw-hirn p:long l:"Row Number"

entity e:kkvw-hirn l:"Important dates - Vietnamese" t:url=https://data.kingcounty.gov/api/views/kkvw-hirn

property e:kkvw-hirn t:meta.view v:id=kkvw-hirn v:category="Election operations" v:averageRating=0 v:name="Important dates - Vietnamese"

property e:kkvw-hirn t:meta.view.license v:name="Public Domain"

property e:kkvw-hirn t:meta.view.owner v:id=jqm9-tbbq v:screenName="Dave Pohl" v:displayName="Dave Pohl"

property e:kkvw-hirn t:meta.view.tableauthor v:id=jqm9-tbbq v:screenName="Dave Pohl" v:displayName="Dave Pohl"
```

## Top Records

```ls
| :updated_at | date                     | event                                                                                                           | 
| =========== | ======================== | =============================================================================================================== | 
| 1357208983  | Ng?y 12 th?ng 1 n?m 2013 | L? phi?u d?nh cho c? tri ? n??c ngo?i v? trong qu?n ??i ?? ???c g?i ?i cho Cu?c B?u C? ??c Bi?t ng?y 12 th?ng 2 | 
| 1357208983  | Ng?y 14 th?ng 1 n?m 2013 | H?n ch?t g?i ??n ??ng k? v? chuy?n h? s? c? tri qua ???ng b?u ?i?n v? tr?c tuy?n cho Cu?c B?u C? ??c Bi?t       | 
| 1357208983  | Ng?y 18 th?ng 1 n?m 2013 | M?y Ti?p C?n B? Phi?u v? l? phi?u c? s?n cho ??n Ng?y B?u C?                                                    | 
| 1357208983  | Ng?y 4 th?ng 2 n?m 2013  | H?n ch?t ??ng k? tr?c ti?p cho Cu?c B?u C? ??c Bi?t                                                             | 
| 1357208983  | Ng?y 11 th?ng 2 n?m 2013 | C?c ??a ?i?m Trung T?m Ti?p C?n B? Phi?u b? sung ???c m? c?a                                                    | 
| 1357208983  | Ng?y 12 th?ng 2 n?m 2013 | Cu?c B?u C? ??c Bi?t                                                                                            | 
| 1357208983  | Ng?y 26 th?ng 2 n?m 2013 | Ch?ng nh?n Cu?c B?u C? ??c Bi?t ng?y 12 th?ng 2                                                                 | 
| 1357208983  | Ng?y 28 th?ng 2 n?m 2013 | H?n ch?t n?p ??n y?u c?u ??m l?i phi?u v?i qu?n                                                                 | 
```