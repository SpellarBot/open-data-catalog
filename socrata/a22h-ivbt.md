# Belleville Businesses by Sector

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/belleville-businesses-by-sector-612bc) |
| Metadata | [Link](https://data.illinois.gov/api/views/a22h-ivbt) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/a22h-ivbt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/a22h-ivbt/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | a22h-ivbt |
| Name | Belleville Businesses by Sector |
| Attribution | 2007 Economic Census |
| Category | Economics |
| Created | 2013-02-04T20:33:09Z |
| Publication Date | 2013-02-04T20:39:35Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | business_sector          | Business Sector          | text      | text        |
| Yes      | time           | year                     | Year                     | number    | number      |
| Yes      | numeric metric | number_of_estabilshments | Number of Estabilshments | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:a22h-ivbt d:2007-01-01T00:00:00.000Z t:business_sector=Manufacturing m:number_of_estabilshments=49

series e:a22h-ivbt d:2007-01-01T00:00:00.000Z t:business_sector="Wholesale trade" m:number_of_estabilshments=38

series e:a22h-ivbt d:2007-01-01T00:00:00.000Z t:business_sector="Retail trade" m:number_of_estabilshments=203
```

## Meta Commands

```ls
metric m:number_of_estabilshments p:integer l:"Number of Estabilshments" t:dataTypeName=number

entity e:a22h-ivbt l:"Belleville Businesses by Sector" t:attribution="2007 Economic Census" t:url=https://data.illinois.gov/api/views/a22h-ivbt

property e:a22h-ivbt t:meta.view v:id=a22h-ivbt v:category=Economics v:averageRating=0 v:name="Belleville Businesses by Sector" v:attribution="2007 Economic Census"

property e:a22h-ivbt t:meta.view.owner v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"

property e:a22h-ivbt t:meta.view.tableauthor v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"
```

## Top Records

```ls
| business_sector                     | year | number_of_estabilshments | 
| =================================== | ==== | ======================== | 
| Manufacturing                       | 2007 | 49                       | 
| Wholesale trade                     | 2007 | 38                       | 
| Retail trade                        | 2007 | 203                      | 
| Information                         | 2007 | 14                       | 
| Real estate and rental and leasing  | 2007 | 64                       | 
| Educational services                | 2007 | 17                       | 
| Health care and social assistance   | 2007 | 237                      | 
| Arts, entertainment, and recreation | 2007 | 24                       | 
| Accommodation and food services     | 2007 | 145                      | 
| Other services                      | 2007 | 135                      | 
```