# Referrals to Child Protective Services (2004-2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/referrals-to-child-protective-services-2004-2013) |
| Metadata | [Link](https://data.wa.gov/api/views/snj2-p7np) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/snj2-p7np/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/snj2-p7np/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | snj2-p7np |
| Name | Referrals to Child Protective Services (2004-2013) |
| Attribution | Office of Juvenile Justice |
| Category | Public Safety |
| Tags | juvenile justice, annual report, wa-pcjj report, office of juvenile justice, dshs, child protective services, youth |
| Created | 2015-12-14T14:55:08Z |
| Publication Date | 2016-01-20T03:13:49Z |

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
| Yes      | numeric metric | 2007       | 2007  | number    | number      |
| Yes      | numeric metric | 2006       | 2006  | number    | number      |
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
series e:snj2-p7np d:2004-01-01T00:00:00.000Z t:month=January m:2008=6335 m:2009=6088 m:2006=6933 m:2007=6446 m:2013=7534 m:2004=6296 m:2005=6645 m:2012=6340 m:2011=6593 m:2010=6613

series e:snj2-p7np d:2004-01-01T00:00:00.000Z t:month=February m:2008=6143 m:2009=6032 m:2006=6245 m:2007=6177 m:2013=6939 m:2004=6666 m:2005=6104 m:2012=7051 m:2011=6127 m:2010=6426

series e:snj2-p7np d:2004-01-01T00:00:00.000Z t:month=March m:2008=6701 m:2009=6677 m:2006=7358 m:2007=7280 m:2013=7918 m:2004=7832 m:2005=7320 m:2012=7806 m:2011=7479 m:2010=7498
```

## Meta Commands

```ls
metric m:2013 p:integer l:2013 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

metric m:2011 p:integer l:2011 t:dataTypeName=number

metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2004 p:integer l:2004 t:dataTypeName=number

entity e:snj2-p7np l:"Referrals to Child Protective Services (2004-2013)" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/snj2-p7np

property e:snj2-p7np t:meta.view v:id=snj2-p7np v:category="Public Safety" v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=0 v:name="Referrals to Child Protective Services (2004-2013)" v:attribution="Office of Juvenile Justice"

property e:snj2-p7np t:meta.view.license v:name="Public Domain"

property e:snj2-p7np t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:snj2-p7np t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```

## Top Records

```ls
| month     | 2013 | 2012 | 2011 | 2010 | 2009 | 2008 | 2007 | 2006 | 2005 | 2004 | 
| ========= | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | 
| January   | 7534 | 6340 | 6593 | 6613 | 6088 | 6335 | 6446 | 6933 | 6645 | 6296 | 
| February  | 6939 | 7051 | 6127 | 6426 | 6032 | 6143 | 6177 | 6245 | 6104 | 6666 | 
| March     | 7918 | 7806 | 7479 | 7498 | 6677 | 6701 | 7280 | 7358 | 7320 | 7832 | 
| April     | 7738 | 6936 | 6597 | 7421 | 6595 | 6622 | 6317 | 6134 | 6559 | 7136 | 
| May       | 8571 | 7876 | 7148 | 7192 | 6529 | 6792 | 7292 | 7414 | 7717 | 7075 | 
| June      | 6725 | 6629 | 6467 | 6076 | 6225 | 5870 | 5999 | 6364 | 6757 | 6662 | 
| July      | 6358 | 5769 | 4454 | 5411 | 5253 | 5306 | 5291 | 5237 | 5427 | 5517 | 
| August    | 6452 | 6019 | 5673 | 5809 | 5098 | 5170 | 5666 | 5794 | 5990 | 5852 | 
| September | 7065 | 6163 | 6477 | 6508 | 5934 | 6147 | 5905 | 6138 | 6760 | 6245 | 
| October   | 7950 | 7726 | 6560 | 6961 | 6076 | 6680 | 6846 | 6815 | 6831 | 6763 | 
```