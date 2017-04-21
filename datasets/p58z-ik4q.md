# County Level Attainment Status of National Ambient Air Quality Standards (NAAQS)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/county-level-attainment-status-of-national-ambient-air-quality-standards-naaqs) |
| Metadata | [Link](https://data.ny.gov/api/views/p58z-ik4q) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/p58z-ik4q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/p58z-ik4q/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | p58z-ik4q |
| Name | County Level Attainment Status of National Ambient Air Quality Standards (NAAQS) |
| Attribution | Environmental Conservation, Department of |
| Category | Energy & Environment |
| Tags | naaqs, attainment, carbon, nitrogen, ozone, criteria |
| Created | 2016-09-01T19:58:27Z |
| Publication Date | 2016-09-01T20:36:42Z |

## Description

A list by county of the current attainment status of the National Ambient Air Quality Standards (NAAQS).

## Columns

```ls
| Included | Schema Type | Field Name                     | Name                           | Data Type | Render Type |
| ======== | =========== | ============================== | ============================== | ========= | =========== |
| Yes      | time        | year                           | YEAR                           | number    | number      |
| Yes      | series tag  | state                          | STATE                          | text      | text        |
| Yes      | series tag  | county                         | COUNTY                         | text      | text        |
| Yes      | series tag  | naaqs_pollutant                | NAAQS POLLUTANT                | text      | text        |
| No       |             | naaqs_level_and_averaging_time | NAAQS LEVEL AND AVERAGING TIME | text      | text        |
| Yes      | series tag  | naaqs_standard                 | NAAQS STANDARD                 | text      | text        |
| Yes      | series tag  | attainment_status              | ATTAINMENT STATUS              | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = naaqs_level_and_averaging_time
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:p58z-ik4q l:"County Level Attainment Status of National Ambient Air Quality Standards (NAAQS)" t:attribution="Environmental Conservation, Department of" t:url=https://data.ny.gov/api/views/p58z-ik4q

property e:p58z-ik4q t:meta.view v:id=p58z-ik4q v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/chemical/8406.html v:averageRating=0 v:name="County Level Attainment Status of National Ambient Air Quality Standards (NAAQS)" v:attribution="Environmental Conservation, Department of"

property e:p58z-ik4q t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:p58z-ik4q t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| year | state    | county      | naaqs_pollutant      | naaqs_level_and_averaging_time  | naaqs_standard                             | attainment_status | 
| ==== | ======== | =========== | ==================== | =============================== | ========================================== | ================= | 
| 2016 | New York | Albany      | Carbon Monoxide (CO) | 8-hour (9 ppm), 1-hour (35 ppm) | Not to be exceeded more than once per year | Attainment        | 
| 2016 | New York | Allegany    | Carbon Monoxide (CO) | 8-hour (9 ppm), 1-hour (35 ppm) | Not to be exceeded more than once per year | Attainment        | 
| 2016 | New York | Bronx       | Carbon Monoxide (CO) | 8-hour (9 ppm), 1-hour (35 ppm) | Not to be exceeded more than once per year | Maintenance       | 
| 2016 | New York | Broome      | Carbon Monoxide (CO) | 8-hour (9 ppm), 1-hour (35 ppm) | Not to be exceeded more than once per year | Attainment        | 
| 2016 | New York | Cattaraugus | Carbon Monoxide (CO) | 8-hour (9 ppm), 1-hour (35 ppm) | Not to be exceeded more than once per year | Attainment        | 
| 2016 | New York | Cayuga      | Carbon Monoxide (CO) | 8-hour (9 ppm), 1-hour (35 ppm) | Not to be exceeded more than once per year | Attainment        | 
| 2016 | New York | Chautauqua  | Carbon Monoxide (CO) | 8-hour (9 ppm), 1-hour (35 ppm) | Not to be exceeded more than once per year | Attainment        | 
| 2016 | New York | Chemung     | Carbon Monoxide (CO) | 8-hour (9 ppm), 1-hour (35 ppm) | Not to be exceeded more than once per year | Attainment        | 
| 2016 | New York | Chenango    | Carbon Monoxide (CO) | 8-hour (9 ppm), 1-hour (35 ppm) | Not to be exceeded more than once per year | Attainment        | 
| 2016 | New York | Clinton     | Carbon Monoxide (CO) | 8-hour (9 ppm), 1-hour (35 ppm) | Not to be exceeded more than once per year | Attainment        | 
```