# Juvenile Rehabilitation Parole Average Daily Population (2004-2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/juvenile-rehabilitation-parole-average-daily-population-2004-2013) |
| Metadata | [Link](https://data.wa.gov/api/views/7vbx-4zb3) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/7vbx-4zb3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/7vbx-4zb3/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 7vbx-4zb3 |
| Name | Juvenile Rehabilitation Parole Average Daily Population (2004-2013) |
| Attribution | Office of Juvenile Justice |
| Category | Public Safety |
| Tags | juvenile justice, annual report, wa-pcjj report, office of juvenile justice, dshs, rehabilitation, youth, parole |
| Created | 2015-12-29T07:46:12Z |
| Publication Date | 2016-01-12T18:31:22Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name  | Data Type | Render Type |
| ======== | ============== | ========== | ===== | ========= | =========== |
| Yes      | series tag     | month      | Month | text      | text        |
| Yes      | numeric metric | 2013       | 2013  | number    | number      |
| Yes      | numeric metric | 2012       | 2012  | number    | number      |
| Yes      | numeric metric | 2011       | 2011  | number    | number      |
| Yes      | numeric metric | 2010       | 2010  | number    | number      |
| Yes      | numeric metric | 2009       | 2009  | number    | number      |
| Yes      | numeric metric | 2008       | 2008  | number    | number      |
| Yes      | numeric metric | 2007       | 2007* | number    | number      |
| Yes      | numeric metric | 2006       | 2006* | number    | number      |
| Yes      | numeric metric | 2005       | 2005  | number    | number      |
| Yes      | numeric metric | 2004       | 2004  | number    | number      |
```

## Time Field

```ls
Value = 2004
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7vbx-4zb3 d:2004-01-01T00:00:00.000Z t:month=January m:2008=720 m:2009=654 m:2006=750 m:2007=660 m:2013=372 m:2004=825 m:2005=721 m:2012=367 m:2011=432 m:2010=442

series e:7vbx-4zb3 d:2004-01-01T00:00:00.000Z t:month=February m:2008=709 m:2009=647 m:2006=733 m:2007=662 m:2013=369 m:2004=806 m:2005=726 m:2012=366 m:2011=428 m:2010=442

series e:7vbx-4zb3 d:2004-01-01T00:00:00.000Z t:month=March m:2008=699 m:2009=640 m:2006=735 m:2007=676 m:2013=362 m:2004=792 m:2005=722 m:2012=375 m:2011=431 m:2010=438
```

## Meta Commands

```ls
metric m:2013 p:integer l:2013 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

metric m:2011 p:integer l:2011 t:dataTypeName=number

metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2007 p:integer l:2007* t:dataTypeName=number

metric m:2006 p:integer l:2006* t:dataTypeName=number

metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2004 p:integer l:2004 t:dataTypeName=number

entity e:7vbx-4zb3 l:"Juvenile Rehabilitation Parole Average Daily Population (2004-2013)" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/7vbx-4zb3

property e:7vbx-4zb3 t:meta.view v:id=7vbx-4zb3 v:category="Public Safety" v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=0 v:name="Juvenile Rehabilitation Parole Average Daily Population (2004-2013)" v:attribution="Office of Juvenile Justice"

property e:7vbx-4zb3 t:meta.view.license v:name="Public Domain"

property e:7vbx-4zb3 t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:7vbx-4zb3 t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```

## Top Records

```ls
| month     | 2013 | 2012 | 2011 | 2010 | 2009 | 2008 | 2007 | 2006 | 2005 | 2004 | 
| ========= | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | 
| January   | 372  | 367  | 432  | 442  | 654  | 720  | 660  | 750  | 721  | 825  | 
| February  | 369  | 366  | 428  | 442  | 647  | 709  | 662  | 733  | 726  | 806  | 
| March     | 362  | 375  | 431  | 438  | 640  | 699  | 676  | 735  | 722  | 792  | 
| April     | 365  | 373  | 417  | 437  | 630  | 691  | 682  | 732  | 732  | 775  | 
| May       | 355  | 370  | 407  | 439  | 619  | 688  | 686  | 737  | 740  | 758  | 
| June      | 388  | 372  | 402  | 431  | 606  | 680  | 691  | 738  | 756  | 733  | 
| July      | 328  | 373  | 403  | 426  | 451  | 674  | 718  | 723  | 755  | 732  | 
| August    | 325  | 367  | 391  | 423  | 448  | 676  | 720  | 719  | 766  | 721  | 
| September | 323  | 364  | 375  | 420  | 435  | 662  | 726  | 726  | 776  | 723  | 
| October   | 330  | 367  | 362  | 412  | 431  | 665  | 720  | 708  | 775  | 733  | 
```