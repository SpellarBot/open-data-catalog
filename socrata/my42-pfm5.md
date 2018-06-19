# First In Nation "Race to the Top" (Source: Energy Services Coalition)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/first-in-nation-2013-energy-services-coalition-race-to-the-top-source-energy-services-coal-5bf1c) |
| Metadata | [Link](https://data.hawaii.gov/api/views/my42-pfm5) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/my42-pfm5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/my42-pfm5/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | my42-pfm5 |
| Name | First In Nation "Race to the Top" (Source: Energy Services Coalition) |
| Created | 2012-11-19T20:06:29Z |
| Publication Date | 2016-11-28T23:04:46Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | state                   | State                   | text      | text        |
| Yes      | numeric metric | population              | Population              | number    | number      |
| Yes      | numeric metric | performance_contracting | Performance Contracting | money     | money       |
| Yes      | numeric metric | dollars_per_capita      | Dollars per Capita      | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:my42-pfm5 d:2016-11-28T22:58:07.000Z t:state=Hawaii m:performance_contracting=442432189 m:dollars_per_capita=325.25 m:population=1360301

series e:my42-pfm5 d:2016-11-28T22:58:42.000Z t:state=Kentucky m:performance_contracting=750000000 m:dollars_per_capita=172.84 m:population=4339367

series e:my42-pfm5 d:2016-11-28T22:59:10.000Z t:state=Delaware m:performance_contracting=138707463 m:dollars_per_capita=154.47 m:population=897934
```

## Meta Commands

```ls
metric m:population p:integer l:Population t:dataTypeName=number

metric m:performance_contracting p:integer l:"Performance Contracting" t:dataTypeName=money

metric m:dollars_per_capita p:double l:"Dollars per Capita" t:dataTypeName=money

entity e:my42-pfm5 l:"First In Nation ""Race to the Top""  (Source: Energy Services Coalition)" t:url=https://data.hawaii.gov/api/views/my42-pfm5

property e:my42-pfm5 t:meta.view v:id=my42-pfm5 v:averageRating=0 v:name="First In Nation ""Race to the Top""  (Source: Energy Services Coalition)"

property e:my42-pfm5 t:meta.view.owner v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:displayName="Jerome Koehler"

property e:my42-pfm5 t:meta.view.tableauthor v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:roleName=publisher v:displayName="Jerome Koehler"
```

## Top Records

```ls
| :updated_at | state         | population | performance_contracting | dollars_per_capita | 
| =========== | ============= | ========== | ======================= | ================== | 
| 1480373887  | Hawaii        | 1360301    | 442432189               | 325.25             | 
| 1480373922  | Kentucky      | 4339367    | 750000000               | 172.84             | 
| 1480373950  | Delaware      | 897934     | 138707463               | 154.47             | 
| 1480373980  | Massachusetts | 6547629    | 865349091               | 132.16             | 
| 1480374123  | Ohio          | 11536504   | 1252683627              | 108.58             | 
```