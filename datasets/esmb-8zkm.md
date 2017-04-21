# School Based Programs by Borough

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-based-programs-by-borough) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/esmb-8zkm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/esmb-8zkm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/esmb-8zkm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | esmb-8zkm |
| Name | School Based Programs by Borough |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | sca, programs, schools |
| Created | 2016-06-02T14:47:12Z |
| Publication Date | 2016-06-02T15:01:29Z |

## Description

School based programs by borough with cost.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag     | district    | District    | text      | text        |
| Yes      | series tag     | school      | School      | text      | text        |
| Yes      | series tag     | project     | Project #   | text      | text        |
| Yes      | series tag     | description | Description | text      | text        |
| No       |                | fy          | FY          | number    | number      |
| Yes      | numeric metric | total       | Total       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = fy
```

## Data Commands

```ls
series e:esmb-8zkm d:2016-06-02T07:47:21.000Z t:project=DSF0000755393 t:school="P.S. 3 - Brooklyn" t:description="State of Good Repair - Building Upgrade - Low-Voltage Electrical Systems" t:district=13 m:total=2040836

series e:esmb-8zkm d:2016-06-02T07:47:21.000Z t:project=DSF0000798244 t:school="P.S. 3 - Brooklyn" t:description="State of Good Repair - Building Upgrade - Boiler Conversion" t:district=13 m:total=5445738

series e:esmb-8zkm d:2016-06-02T07:47:21.000Z t:project=DSF0000798245 t:school="P.S. 3 - Brooklyn" t:description="State of Good Repair - Building Upgrade - Climate Control" t:district=13 m:total=1618281
```

## Meta Commands

```ls
metric m:total p:integer l:Total t:dataTypeName=number

entity e:esmb-8zkm l:"School Based Programs by Borough" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/esmb-8zkm

property e:esmb-8zkm t:meta.view v:id=esmb-8zkm v:category=Education v:averageRating=0 v:name="School Based Programs by Borough" v:attribution="School Construction Authority (SCA)"

property e:esmb-8zkm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:esmb-8zkm t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | district | school             | project       | description                                                                              | fy   | total   | 
| =========== | ======== | ================== | ============= | ======================================================================================== | ==== | ======= | 
| 1464853641  | 13       | P.S. 3 - Brooklyn  | DSF0000755393 | State of Good Repair - Building Upgrade - Low-Voltage Electrical Systems                 | 2015 | 2040836 | 
| 1464853641  | 13       | P.S. 3 - Brooklyn  | DSF0000798244 | State of Good Repair - Building Upgrade - Boiler Conversion                              | 2016 | 5445738 | 
| 1464853641  | 13       | P.S. 3 - Brooklyn  | DSF0000798245 | State of Good Repair - Building Upgrade - Climate Control                                | 2016 | 1618281 | 
| 1464853641  | 13       | P.S. 3 - Brooklyn  | DSF0000801203 | State of Good Repair - System Replacements - Toilets-Students                            | 2015 | 188697  | 
| 1464853641  | 13       | P.S. 8 - Brooklyn  | DSF0000777455 | Safety and Security - Safety and Security - Emergency Lighting and Fire Safety Retrofits | 2015 | 64445   | 
| 1464853641  | 13       | P.S. 9 - Brooklyn  | DSF0000777935 | State of Good Repair - System Replacements - Heating Plant Upgrade                       | 2015 | 35263   | 
| 1464853641  | 13       | P.S. 20 - Brooklyn | DSF0000822131 | State of Good Repair - System Replacements - Toilets-Students                            | 2016 | 189391  | 
| 1464853641  | 13       | P.S. 20 - Brooklyn | DSF0000824038 | State of Good Repair - System Replacements - Heating Plant Upgrade                       | 2017 | 78110   | 
| 1464853641  | 13       | P.S. 44 - Brooklyn | DSF0000710245 | State of Good Repair - Building Upgrade - Boiler Conversion                              | 2017 | 5116242 | 
| 1464853641  | 13       | P.S. 44 - Brooklyn | DSF0000710254 | State of Good Repair - Building Upgrade - Climate Control                                | 2017 | 2209470 | 
```