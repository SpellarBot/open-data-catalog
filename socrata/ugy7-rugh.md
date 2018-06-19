# PARC meeting minute archive

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parc-meeting-minute-archive-688a1) |
| Metadata | [Link](https://data.oregon.gov/api/views/ugy7-rugh) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ugy7-rugh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ugy7-rugh/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ugy7-rugh |
| Name | PARC meeting minute archive |
| Category | Natural Resources |
| Tags | parc |
| Created | 2014-05-05T17:43:58Z |
| Publication Date | 2014-05-05T19:40:44Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | time        | date        | Date        | calendar_date | calendar_date |
| Yes      | series tag  | information | Information | document      | document      |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ugy7-rugh d:2012-11-21T00:00:00.000Z t:information.filename=parcminutes112112.pdf t:information.size=236696 t:information.file_id=bOJ97pOW9DmmNAhh-ZvMKOnl2z9YLi222C9GJjoT6CA t:information.content_type="application/pdf; charset=binary" m:row_number.ugy7-rugh=1

series e:ugy7-rugh d:2012-05-09T00:00:00.000Z t:information.filename=parcminutes050912.pdf t:information.size=237554 t:information.file_id=gGcv1bZEHat7Uf8_kzt1XsbwV4tn7j_KaWT5FCnzTOs t:information.content_type="application/pdf; charset=binary" m:row_number.ugy7-rugh=2

series e:ugy7-rugh d:2012-03-21T00:00:00.000Z t:information.filename=parcminutes032112.pdf t:information.size=305862 t:information.file_id=cMkIu6iCeXKLw-nPlnIdO6nZe4tUsBoBE9c9noqzak0 t:information.content_type="application/pdf; charset=binary" m:row_number.ugy7-rugh=3
```

## Meta Commands

```ls
metric m:row_number.ugy7-rugh p:long l:"Row Number"

entity e:ugy7-rugh l:"PARC meeting minute archive" t:url=https://data.oregon.gov/api/views/ugy7-rugh

property e:ugy7-rugh t:meta.view v:id=ugy7-rugh v:category="Natural Resources" v:averageRating=0 v:name="PARC meeting minute archive"

property e:ugy7-rugh t:meta.view.owner v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:displayName="Andy Zimmerman"

property e:ugy7-rugh t:meta.view.tableauthor v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:roleName=editor v:displayName="Andy Zimmerman"
```

## Top Records

```ls
| date                | information                                                                                                     | 
| =================== | =============================================================================================================== | 
| 2012-11-21T00:00:00 | [application/pdf; charset=binary, bOJ97pOW9DmmNAhh-ZvMKOnl2z9YLi222C9GJjoT6CA, parcminutes112112.pdf, 236696]   | 
| 2012-05-09T00:00:00 | [application/pdf; charset=binary, gGcv1bZEHat7Uf8_kzt1XsbwV4tn7j_KaWT5FCnzTOs, parcminutes050912.pdf, 237554]   | 
| 2012-03-21T00:00:00 | [application/pdf; charset=binary, cMkIu6iCeXKLw-nPlnIdO6nZe4tUsBoBE9c9noqzak0, parcminutes032112.pdf, 305862]   | 
| 2012-01-18T00:00:00 | [application/pdf; charset=binary, PWi5VDt5MXslI0HG58TcDErh0eTjpPdyPyBk-8mq8i4, parcminutes011812.pdf, 296108]   | 
| 2011-09-21T00:00:00 | [application/pdf; charset=binary, xovkpbWqvKy6l0QfcPFtlAMl2ux2Tg6Ap2FZz5UsXVQ, parcminutes092111.pdf, 254321]   | 
| 2011-07-20T00:00:00 | [application/pdf; charset=binary, 5XnEqu2NyA7rKjqOpvOuacvdZ2XQmnQ8v_igDxSRWYk, parcminutes07202011.pdf, 231068] | 
| 2011-05-18T00:00:00 | [application/pdf; charset=binary, SDCaXqzsWWcf0Ld5HP2DuQQ45tpuCdkvdABpvY3QG0c, parcminutes05182011.pdf, 232025] | 
| 2011-03-16T00:00:00 | [application/pdf; charset=binary, TPCG5AGssC9KqmVbcdteN-PqVjQxv-Ei_4Bx3PRcfEM, parcminutes031611.pdf, 221006]   | 
| 2011-01-19T00:00:00 | [application/pdf; charset=binary, B9v_1prmailnxXCon0CIrpaLbK9IZj6_PdnzuLyGbYY, parcminutes011911.pdf, 205142]   | 
| 2011-01-19T00:00:00 | [application/pdf; charset=binary, BM_HFrthod_AhC_7FaK_3M0GVa9ihL7CGty_PjU96Xk, zp_geese_outreach.pdf, 636905]   | 
```