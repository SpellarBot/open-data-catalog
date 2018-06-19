# Population Change For 20 Largest Cities In the United States

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/population-change-for-20-largest-cities-in-the-united-states-81f57) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6u6h-px7z) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6u6h-px7z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6u6h-px7z/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6u6h-px7z |
| Name | Population Change For 20 Largest Cities In the United States |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | dcp, city, planning, population, growth, us |
| Created | 2013-02-20T18:13:00Z |
| Publication Date | 2013-06-26T17:16:13Z |

## Description

Population Change For 20 Largest Cities In the United States

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | numeric metric | rank            | Rank            | number    | number      |
| Yes      | series tag     | city            | City            | text      | text        |
| Yes      | numeric metric | 2000_population | 2000 Population | number    | text        |
| Yes      | numeric metric | 2010_population | 2010 Population | number    | text        |
| Yes      | series tag     | comments        | Comments        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6u6h-px7z d:2013-02-20T10:13:01.000Z t:comments="Achieved population peak in 2010" t:city="New York, NY" m:2000_population=8008278 m:rank=1 m:2010_population=8175133

series e:6u6h-px7z d:2013-02-20T10:13:01.000Z t:comments="Achieved population peak in 2010" t:city="Los Angeles, CA" m:2000_population=3694820 m:rank=2 m:2010_population=3792621

series e:6u6h-px7z d:2013-02-20T10:13:01.000Z t:city="Chicago, IL" m:2000_population=2896016 m:rank=3 m:2010_population=2695598
```

## Meta Commands

```ls
metric m:rank p:integer l:Rank t:dataTypeName=number

metric m:2010_population p:long l:"2010 Population" t:dataTypeName=number

entity e:6u6h-px7z l:"Population Change For 20 Largest Cities In the United States" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/6u6h-px7z

property e:6u6h-px7z t:meta.view v:id=6u6h-px7z v:category="City Government" v:attributionLink=http://www.nyc.gov/html/dcp/pdf/census/census2010/pgrhc.pdf v:averageRating=0 v:name="Population Change For 20 Largest Cities In the United States" v:attribution="Department of City Planning (DCP)"

property e:6u6h-px7z t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6u6h-px7z t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | rank | city             | 2000_population | 2010_population | comments                         | 
| =========== | ==== | ================ | =============== | =============== | ================================ | 
| 1361355181  | 1    | New York, NY     | 8,008,278       | 8,175,133       | Achieved population peak in 2010 | 
| 1361355181  | 2    | Los Angeles, CA  | 3,694,820       | 3,792,621       | Achieved population peak in 2010 | 
| 1361355181  | 3    | Chicago, IL      | 2,896,016       | 2,695,598       |                                  | 
| 1361355181  | 4    | Houston, TX      | 1,953,631       | 2,099,451       | Achieved population peak in 2010 | 
| 1361355181  | 5    | Philadelphia, PA | 1,517,550       | 1,526,006       |                                  | 
| 1361355181  | 6    | Phoenix, AZ      | 1,321,045       | 1,445,632       | Achieved population peak in 2010 | 
| 1361355181  | 7    | San Antonio, TX  | 1,144,646       | 1,327,407       | Achieved population peak in 2010 | 
| 1361355181  | 8    | San Diego, CA    | 1,223,400       | 1,307,402       | Achieved population peak in 2010 | 
| 1361355181  | 9    | Dallas, TX       | 1,188,580       | 1,197,816       | Achieved population peak in 2010 | 
| 1361355181  | 10   | San Jose, CA     | 894,943         | 945,942         | Achieved population peak in 2010 | 
```