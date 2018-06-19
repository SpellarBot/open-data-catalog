# RPS copy on data.hawaii.gov

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rps-copy-on-data-hawaii-gov-47222) |
| Metadata | [Link](https://data.hawaii.gov/api/views/u7nx-vred) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/u7nx-vred/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/u7nx-vred/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | u7nx-vred |
| Name | RPS copy on data.hawaii.gov |
| Created | 2014-04-28T22:57:57Z |
| Publication Date | 2014-04-28T23:00:56Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type     | Render Type   |
| ======== | ============== | =========== | =========== | ============= | ============= |
| No       |                | year        | Year        | number        | text          |
| Yes      | numeric metric | heco        | HECO        | percent       | percent       |
| Yes      | numeric metric | helco       | HELCO       | percent       | percent       |
| Yes      | numeric metric | meco        | MECO        | percent       | percent       |
| Yes      | numeric metric | kiuc        | KIUC        | percent       | percent       |
| Yes      | numeric metric | state_total | State Total | percent       | percent       |
| Yes      | time           | date_time   | Date Time   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:u7nx-vred d:2006-12-31T00:00:00.000Z m:state_total=8.2 m:helco=25.7 m:kiuc=7.9 m:meco=10.8 m:heco=5.1

series e:u7nx-vred d:2007-12-31T00:00:00.000Z m:state_total=8.9 m:helco=33.8 m:kiuc=5.8 m:meco=15.4 m:heco=4.3

series e:u7nx-vred d:2008-12-31T00:00:00.000Z m:state_total=9.4 m:helco=35.4 m:kiuc=8.7 m:meco=13.9 m:heco=4.8
```

## Meta Commands

```ls
metric m:heco p:float l:HECO t:dataTypeName=percent

metric m:helco p:float l:HELCO t:dataTypeName=percent

metric m:meco p:float l:MECO t:dataTypeName=percent

metric m:kiuc p:double l:KIUC t:dataTypeName=percent

metric m:state_total p:float l:"State Total" t:dataTypeName=percent

entity e:u7nx-vred l:"RPS copy on data.hawaii.gov" t:url=https://data.hawaii.gov/api/views/u7nx-vred

property e:u7nx-vred t:meta.view v:id=u7nx-vred v:averageRating=0 v:name="RPS copy on data.hawaii.gov"

property e:u7nx-vred t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:u7nx-vred t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| year | heco | helco | meco | kiuc | state_total | date_time           | 
| ==== | ==== | ===== | ==== | ==== | =========== | =================== | 
| 2006 | 5.1  | 25.7  | 10.8 | 7.9  | 8.2         | 2006-12-31T00:00:00 | 
| 2007 | 4.3  | 33.8  | 15.4 | 5.8  | 8.9         | 2007-12-31T00:00:00 | 
| 2008 | 4.8  | 35.4  | 13.9 | 8.7  | 9.4         | 2008-12-31T00:00:00 | 
| 2009 | 5.1  | 33.7  | 13.9 | 9.6  | 9.5         | 2009-12-31T00:00:00 | 
| 2010 | 4.7  | 34.6  | 15.3 | 9.1  | 9.5         | 2010-12-31T00:00:00 | 
| 2011 | 6.7  | 41.1  | 17.1 | 10.5 | 11.9        | 2011-12-31T00:00:00 | 
| 2012 | 7.6  | 46.7  | 20.8 | 11   | 13.7        | 2012-12-31T00:00:00 | 
```