# Most Popular Baby Names by Sex and Mother's Ethnic Group, New York City

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/most-popular-baby-names-by-sex-and-mothers-ethnic-group-new-york-city-8c742) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/25th-nujf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/25th-nujf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/25th-nujf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 25th-nujf |
| Name | Most Popular Baby Names by Sex and Mother's Ethnic Group, New York City |
| Attribution | Department of Health and Mental Hygiene (DOHMH) |
| Category | Health |
| Tags | popular name, birth name, name, health, male, female, boy, girl, vital statistic, race, ethnicity |
| Created | 2013-10-25T18:14:54Z |
| Publication Date | 2013-12-12T21:00:43Z |

## Description

The most popular baby names by sex and mother's ethnicity in New York City.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | numeric metric | brth_yr     | BRTH_YR    | number    | number      |
| Yes      | series tag     | gndr        | GNDR       | text      | text        |
| Yes      | series tag     | ethcty      | ETHCTY     | text      | text        |
| No       |                | nm          | NM         | text      | text        |
| Yes      | numeric metric | cnt         | CNT        | number    | number      |
| Yes      | numeric metric | rnk         | RNK        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = nm
```

## Data Commands

```ls
series e:25th-nujf d:2013-12-12T12:58:45.000Z t:gndr=FEMALE t:ethcty=HISPANIC m:cnt=13 m:brth_yr=2011 m:rnk=75

series e:25th-nujf d:2013-12-12T12:58:45.000Z t:gndr=FEMALE t:ethcty=HISPANIC m:cnt=21 m:brth_yr=2011 m:rnk=67

series e:25th-nujf d:2013-12-12T12:58:45.000Z t:gndr=FEMALE t:ethcty=HISPANIC m:cnt=49 m:brth_yr=2011 m:rnk=42
```

## Meta Commands

```ls
metric m:brth_yr p:integer l:BRTH_YR t:dataTypeName=number

metric m:cnt p:integer l:CNT t:dataTypeName=number

metric m:rnk p:integer l:RNK t:dataTypeName=number

entity e:25th-nujf l:"Most Popular Baby Names by Sex and Mother's Ethnic Group, New York City" t:attribution="Department of Health and Mental Hygiene (DOHMH)" t:url=https://data.cityofnewyork.us/api/views/25th-nujf

property e:25th-nujf t:meta.view v:id=25th-nujf v:category=Health v:averageRating=0 v:name="Most Popular Baby Names by Sex and Mother's Ethnic Group, New York City" v:attribution="Department of Health and Mental Hygiene (DOHMH)"

property e:25th-nujf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:25th-nujf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | brth_yr | gndr   | ethcty   | nm        | cnt | rnk | 
| =========== | ======= | ====== | ======== | ========= | === | === | 
| 1386853125  | 2011    | FEMALE | HISPANIC | GERALDINE | 13  | 75  | 
| 1386853125  | 2011    | FEMALE | HISPANIC | GIA       | 21  | 67  | 
| 1386853125  | 2011    | FEMALE | HISPANIC | GIANNA    | 49  | 42  | 
| 1386853125  | 2011    | FEMALE | HISPANIC | GISELLE   | 38  | 51  | 
| 1386853125  | 2011    | FEMALE | HISPANIC | GRACE     | 36  | 53  | 
| 1386853125  | 2011    | FEMALE | HISPANIC | GUADALUPE | 26  | 62  | 
| 1386853125  | 2011    | FEMALE | HISPANIC | HAILEY    | 126 | 8   | 
| 1386853125  | 2011    | FEMALE | HISPANIC | HALEY     | 14  | 74  | 
| 1386853125  | 2011    | FEMALE | HISPANIC | HANNAH    | 17  | 71  | 
| 1386853125  | 2011    | FEMALE | HISPANIC | HAYLEE    | 17  | 71  | 
```