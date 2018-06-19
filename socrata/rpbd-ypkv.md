# Hawaii Renewable Energy Generation by Utility/County (Source: Hawaii Public Utilities Commission)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-renewable-energy-generation-by-utility-county-source-hawaii-public-utilities-commis) |
| Metadata | [Link](https://data.hawaii.gov/api/views/rpbd-ypkv) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/rpbd-ypkv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/rpbd-ypkv/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | rpbd-ypkv |
| Name | Hawaii Renewable Energy Generation by Utility/County (Source: Hawaii Public Utilities Commission) |
| Created | 2014-01-16T00:42:45Z |
| Publication Date | 2017-05-31T22:04:35Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name                | Data Type | Render Type |
| ======== | ============== | ========== | =================== | ========= | =========== |
| Yes      | time           | year       | Year                | number    | number      |
| Yes      | numeric metric | heco       | HECO/Oahu           | number    | number      |
| Yes      | numeric metric | helco      | HELCO/Hawaii Island | number    | number      |
| Yes      | numeric metric | meco       | MECO/Maui County    | number    | number      |
| Yes      | numeric metric | kiuc       | KIUC/Kauai          | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rpbd-ypkv d:2010-01-01T00:00:00.000Z m:helco=383622 m:meco=182560 m:heco=344809 m:kiuc=39750

series e:rpbd-ypkv d:2011-01-01T00:00:00.000Z m:helco=453349 m:meco=202270 m:heco=484826 m:kiuc=45562

series e:rpbd-ypkv d:2012-01-01T00:00:00.000Z m:helco=507062 m:meco=238319 m:heco=530853 m:kiuc=47719
```

## Meta Commands

```ls
metric m:heco p:integer l:HECO/Oahu t:dataTypeName=number

metric m:helco p:integer l:"HELCO/Hawaii Island" t:dataTypeName=number

metric m:meco p:integer l:"MECO/Maui County" t:dataTypeName=number

metric m:kiuc p:integer l:KIUC/Kauai t:dataTypeName=number

entity e:rpbd-ypkv l:"Hawaii Renewable Energy Generation by Utility/County (Source: Hawaii Public Utilities Commission)" t:url=https://data.hawaii.gov/api/views/rpbd-ypkv

property e:rpbd-ypkv t:meta.view d:2017-09-25T07:22:46.443Z v:averageRating=0 v:name="Hawaii Renewable Energy Generation by Utility/County (Source: Hawaii Public Utilities Commission)" v:id=rpbd-ypkv

property e:rpbd-ypkv t:meta.view.owner d:2017-09-25T07:22:46.443Z v:displayName=Kathy v:id=vf6n-ptiq v:screenName=Kathy

property e:rpbd-ypkv t:meta.view.tableauthor d:2017-09-25T07:22:46.443Z v:displayName=Kathy v:roleName=publisher v:id=vf6n-ptiq v:screenName=Kathy
```

## Top Records

```ls
| year | heco    | helco  | meco   | kiuc   | 
| ==== | ======= | ====== | ====== | ====== | 
| 2010 | 344809  | 383622 | 182560 | 39750  | 
| 2011 | 484826  | 453349 | 202270 | 45562  | 
| 2012 | 530853  | 507062 | 238319 | 47719  | 
| 2013 | 801009  | 517375 | 330067 | 59385  | 
| 2014 | 1029070 | 503140 | 381351 | 75203  | 
| 2016 | 1292042 | 578770 | 412308 | 182904 | 
| 2015 | 1159629 | 518311 | 402832 | 118027 | 
```