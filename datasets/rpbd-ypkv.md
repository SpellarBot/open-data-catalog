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
| Publication Date | 2016-04-11T21:13:10Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name                | Data Type | Render Type |
| ======== | ============== | =========== | =================== | ========= | =========== |
| Yes      | time           | year        | Year                | number    | number      |
| Yes      | numeric metric | heco        | HECO/Oahu           | number    | number      |
| Yes      | numeric metric | helco       | HELCO/Hawaii Island | number    | number      |
| Yes      | numeric metric | meco        | MECO/Maui County    | number    | number      |
| Yes      | numeric metric | kiuc        | KIUC/Kauai          | number    | number      |
| Yes      | numeric metric | state_total | State Total         | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rpbd-ypkv d:2009-01-01T00:00:00.000Z m:state_total=964600 m:helco=377730 m:kiuc=41737 m:meco=165835 m:heco=379298

series e:rpbd-ypkv d:2010-01-01T00:00:00.000Z m:state_total=950741 m:helco=383622 m:kiuc=39750 m:meco=182560 m:heco=344809

series e:rpbd-ypkv d:2011-01-01T00:00:00.000Z m:state_total=1186007 m:helco=453349 m:kiuc=45562 m:meco=202270 m:heco=484826
```

## Meta Commands

```ls
metric m:heco p:integer l:HECO/Oahu t:dataTypeName=number

metric m:helco p:integer l:"HELCO/Hawaii Island" t:dataTypeName=number

metric m:meco p:integer l:"MECO/Maui County" t:dataTypeName=number

metric m:kiuc p:integer l:KIUC/Kauai t:dataTypeName=number

metric m:state_total p:integer l:"State Total" t:dataTypeName=number

entity e:rpbd-ypkv l:"Hawaii Renewable Energy Generation by Utility/County (Source: Hawaii Public Utilities Commission)" t:url=https://data.hawaii.gov/api/views/rpbd-ypkv

property e:rpbd-ypkv t:meta.view v:id=rpbd-ypkv v:averageRating=0 v:name="Hawaii Renewable Energy Generation by Utility/County (Source: Hawaii Public Utilities Commission)"

property e:rpbd-ypkv t:meta.view.owner v:id=vf6n-ptiq v:screenName=Kathy v:displayName=Kathy

property e:rpbd-ypkv t:meta.view.tableauthor v:id=vf6n-ptiq v:screenName=Kathy v:roleName=publisher v:displayName=Kathy
```

## Top Records

```ls
| year | heco    | helco  | meco   | kiuc   | state_total | 
| ==== | ======= | ====== | ====== | ====== | =========== | 
| 2009 | 379298  | 377730 | 165835 | 41737  | 964600      | 
| 2010 | 344809  | 383622 | 182560 | 39750  | 950741      | 
| 2011 | 484826  | 453349 | 202270 | 45562  | 1186007     | 
| 2012 | 530853  | 507062 | 238319 | 47719  | 1323953     | 
| 2013 | 801009  | 517375 | 330067 | 59385  | 1707836     | 
| 2014 | 1029070 | 503140 | 381351 | 75203  | 1988764     | 
| 2015 | 1159630 | 518311 | 402832 | 118026 | 2198801     | 
```