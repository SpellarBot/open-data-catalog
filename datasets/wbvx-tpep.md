# Ethnic Distribution of Detention Population 2004-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ethnic-distribution-of-detention-population-2004-2013) |
| Metadata | [Link](https://data.wa.gov/api/views/wbvx-tpep) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/wbvx-tpep/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/wbvx-tpep/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | wbvx-tpep |
| Name | Ethnic Distribution of Detention Population 2004-2013 |
| Attribution | Office of Juvenile Justice |
| Category | Public Safety |
| Tags | juvenile justice, annual report, wa-pcjj report, office of juvenile justice, dshs, ethnic, detention, youth |
| Created | 2015-12-27T05:45:45Z |
| Publication Date | 2016-01-12T20:06:06Z |

## Columns

```ls
| Included | Schema Type | Field Name       | Name                | Data Type | Render Type |
| ======== | =========== | ================ | =================== | ========= | =========== |
| Yes      | series tag  | year             | Year                | text      | text        |
| Yes      | series tag  | white            | White               | text      | text        |
| Yes      | series tag  | black            | Black               | text      | text        |
| Yes      | series tag  | native_american  | Native American     | text      | text        |
| Yes      | series tag  | asian_pacific_is | Asian & Pacific Is. | text      | text        |
| Yes      | series tag  | hispanic         | Hispanic            | text      | text        |
| Yes      | series tag  | other_unknown    | Other/Unknown       | text      | text        |
| Yes      | series tag  | total            | Total               | text      | text        |
```

## Time Field

```ls
Value = 2004
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wbvx-tpep d:2004-01-01T00:00:00.000Z t:total=18,393 t:asian_pacific_is=444 t:native_american=1,255 t:other_unknown=329 t:white=9,922 t:year="# 2013" t:hispanic=3,855 t:black=2,588 m:row_number.wbvx-tpep=1

series e:wbvx-tpep d:2004-01-01T00:00:00.000Z t:total=100% t:asian_pacific_is=2% t:native_american=7% t:other_unknown=2% t:white=54% t:year="% 2013" t:hispanic=21% t:black=14% m:row_number.wbvx-tpep=2

series e:wbvx-tpep d:2004-01-01T00:00:00.000Z t:total=19,760 t:asian_pacific_is=467 t:native_american=1,332 t:other_unknown=385 t:white=10,983 t:year="# 2012" t:hispanic=3,942 t:black=2,651 m:row_number.wbvx-tpep=3
```

## Meta Commands

```ls
metric m:row_number.wbvx-tpep p:long l:"Row Number"

entity e:wbvx-tpep l:"Ethnic Distribution of Detention Population 2004-2013" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/wbvx-tpep

property e:wbvx-tpep t:meta.view v:id=wbvx-tpep v:category="Public Safety" v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=0 v:name="Ethnic Distribution of Detention Population 2004-2013" v:attribution="Office of Juvenile Justice"

property e:wbvx-tpep t:meta.view.license v:name="Public Domain"

property e:wbvx-tpep t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:wbvx-tpep t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```

## Top Records

```ls
| year   | white  | black | native_american | asian_pacific_is | hispanic | other_unknown | total  | 
| ====== | ====== | ===== | =============== | ================ | ======== | ============= | ====== | 
| # 2013 | 9,922  | 2,588 | 1,255           | 444              | 3,855    | 329           | 18,393 | 
| % 2013 | 54%    | 14%   | 7%              | 2%               | 21%      | 2%            | 100%   | 
| # 2012 | 10,983 | 2,651 | 1,332           | 467              | 3,942    | 385           | 19,760 | 
| % 2012 | 56%    | 13%   | 7%              | 2%               | 20%      | 2%            | 100%   | 
| # 2011 | 12,080 | 2,675 | 1,248           | 469              | 4,260    | 484           | 21,216 | 
| % 2011 | 57%    | 13%   | 6%              | 2%               | 20%      | 2%            | 100%   | 
| # 2010 | 13,013 | 3,187 | 1,279           | 525              | 4,276    | 487           | 22,767 | 
| % 2010 | 57%    | 14%   | 6%              | 2%               | 19%      | 2%            | 100%   | 
| # 2009 | 13,873 | 3,289 | 1,311           | 671              | 4,331    | 522           | 23,997 | 
| % 2009 | 58%    | 14%   | 5%              | 3%               | 18%      | 2%            | 100%   | 
```