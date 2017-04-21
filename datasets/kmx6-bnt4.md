# Electric Vehicles, Registered 2015 (Source: 2016 US Clean Tech Leadership Index)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/second-in-nation-2013-united-states-renewable-energy-attractiveness-indices-source-ernst-y-f10cb) |
| Metadata | [Link](https://data.hawaii.gov/api/views/kmx6-bnt4) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/kmx6-bnt4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/kmx6-bnt4/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | kmx6-bnt4 |
| Name | Electric Vehicles, Registered 2015 (Source: 2016 US Clean Tech Leadership Index) |
| Created | 2013-08-31T00:48:56Z |
| Publication Date | 2016-11-28T23:47:38Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | state             | State             | text      | text        |
| Yes      | numeric metric | rank              | Rank              | number    | number      |
| Yes      | numeric metric | evs_per_1m_people | EVs Per 1M People | number    | number      |
| Yes      | numeric metric | total_evs         | Total EVs         | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kmx6-bnt4 d:2015-01-01T00:00:00.000Z t:state=California m:total_evs=102527 m:rank=1 m:evs_per_1m_people=2619

series e:kmx6-bnt4 d:2015-01-01T00:00:00.000Z t:state=Hawaii m:total_evs=3252 m:rank=2 m:evs_per_1m_people=2272

series e:kmx6-bnt4 d:2015-01-01T00:00:00.000Z t:state=Georgia m:total_evs=19792 m:rank=3 m:evs_per_1m_people=1938
```

## Meta Commands

```ls
metric m:rank p:integer l:Rank t:dataTypeName=number

metric m:evs_per_1m_people p:integer l:"EVs Per 1M People" t:dataTypeName=number

metric m:total_evs p:integer l:"Total EVs" t:dataTypeName=number

entity e:kmx6-bnt4 l:"Electric Vehicles, Registered 2015 (Source: 2016 US Clean Tech Leadership Index)" t:url=https://data.hawaii.gov/api/views/kmx6-bnt4

property e:kmx6-bnt4 t:meta.view v:id=kmx6-bnt4 v:averageRating=0 v:name="Electric Vehicles, Registered 2015 (Source: 2016 US Clean Tech Leadership Index)"

property e:kmx6-bnt4 t:meta.view.owner v:id=vf6n-ptiq v:screenName=Kathy v:displayName=Kathy

property e:kmx6-bnt4 t:meta.view.tableauthor v:id=vf6n-ptiq v:screenName=Kathy v:roleName=publisher v:displayName=Kathy
```

## Top Records

```ls
| state      | rank | evs_per_1m_people | total_evs | 
| ========== | ==== | ================= | ========= | 
| California | 1    | 2619              | 102527    | 
| Hawaii     | 2    | 2272              | 3252      | 
| Georgia    | 3    | 1938              | 19792     | 
| Washington | 4    | 1689              | 12113     | 
| Oregon     | 5    | 1293              | 5208      | 
```