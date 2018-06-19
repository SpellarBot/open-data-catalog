# Total Crime Index For The Nation?s Largest Cities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-crime-index-for-the-nations-largest-cities-3a1aa) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3h6b-pt5u) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3h6b-pt5u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3h6b-pt5u/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3h6b-pt5u |
| Name | Total Crime Index For The Nation?s Largest Cities |
| Attribution | Office of the Mayor (OTM) |
| Category | City Government |
| Tags | crime, index, nationwide, fbi data, new york city, safest |
| Created | 2013-02-13T21:56:56Z |
| Publication Date | 2013-06-21T20:03:50Z |

## Description

Total Crime Index for the Nation?s Largest Cities

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | time           | year                | Year                | number    | number      |
| Yes      | numeric metric | crime_index_ranking | Crime Index Ranking | number    | number      |
| Yes      | series tag     | city                | City                | text      | text        |
| Yes      | numeric metric | rate                | Rate                | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3h6b-pt5u d:2009-01-01T00:00:00.000Z t:city="New York" m:crime_index_ranking=1 m:rate=2242.1

series e:3h6b-pt5u d:2009-01-01T00:00:00.000Z t:city="San Jose" m:crime_index_ranking=2 m:rate=2745.7

series e:3h6b-pt5u d:2009-01-01T00:00:00.000Z t:city="San Diego" m:crime_index_ranking=3 m:rate=2903.7
```

## Meta Commands

```ls
metric m:crime_index_ranking p:integer l:"Crime Index Ranking" t:dataTypeName=number

metric m:rate p:float l:Rate t:dataTypeName=number

entity e:3h6b-pt5u l:"Total Crime Index For The Nation?s Largest Cities" t:attribution="Office of the Mayor (OTM)" t:url=https://data.cityofnewyork.us/api/views/3h6b-pt5u

property e:3h6b-pt5u t:meta.view v:id=3h6b-pt5u v:category="City Government" v:attributionLink=http://www.nyc.gov/html/omb/downloads/pdf/sum1_13.pdf v:averageRating=0 v:name="Total Crime Index For The Nation?s Largest Cities" v:attribution="Office of the Mayor (OTM)"

property e:3h6b-pt5u t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:3h6b-pt5u t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| year | crime_index_ranking | city         | rate    | 
| ==== | =================== | ============ | ======= | 
| 2009 | 1                   | New York     | 2242.10 | 
| 2009 | 2                   | San Jose     | 2745.70 | 
| 2009 | 3                   | San Diego    | 2903.70 | 
| 2009 | 4                   | Los Angeles  | 3074.00 | 
| 2009 | 5                   | Las Vegas    | 4407.70 | 
| 2009 | 6                   | Phoenix      | 4654.30 | 
| 2009 | 7                   | Philadelphia | 4849.50 | 
| 2009 | 8                   | Dallas       | 4407.70 | 
| 2009 | 9                   | Houston      | 6444.20 | 
| 2009 | 10                  | San Antonio  | 7241.60 | 
```