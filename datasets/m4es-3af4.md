# Selected Trend Table from Health, United States, 2011. Low birthweight live births, by race and Hispanic origin of mother, and state: United States, 2000 - 2002, 2003 - 2005, and 2006 - 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/selected-trend-table-from-health-united-states-2011-low-birthweight-live-births-by-race-an) |
| Metadata | [Link](https://data.cdc.gov/api/views/m4es-3af4) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/m4es-3af4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/m4es-3af4/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | m4es-3af4 |
| Name | Selected Trend Table from Health, United States, 2011. Low birthweight live births, by race and Hispanic origin of mother, and state: United States, 2000 - 2002, 2003 - 2005, and 2006 - 2008 |
| Attribution | Health, United States |
| Category | Health Statistics |
| Tags | hus, low birthweight |
| Created | 2013-07-29T19:44:00Z |
| Publication Date | 2013-07-29T19:47:59Z |

## Description

Health, United States is an annual report on trends in health statistics, find more information at http://www.cdc.gov/nchs/hus.htm.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | state          | State          | text      | text        |
| Yes      | series tag     | race_ethnicity | Race Ethnicity | text      | text        |
| Yes      | numeric metric | re_sort        | RE Sort        | number    | number      |
| Yes      | numeric metric | re_flag        | RE Flag        | number    | number      |
| Yes      | numeric metric | 2000_2002      | 2000-2002      | number    | number      |
| No       |                | 2000_2002_flag | 2000-2002 Flag | text      | text        |
| Yes      | numeric metric | 2003_2005      | 2003-2005      | number    | number      |
| No       |                | 2003_2005_flag | 2003-2005 Flag | text      | text        |
| Yes      | numeric metric | 2007_2009      | 2007-2009      | number    | number      |
| No       |                | 2007_2009_flag | 2007-2009 Flag | text      | text        |
| Yes      | numeric metric | 2008_2010      | 2008-2010      | number    | number      |
| No       |                | 2008_2010_flag | 2008-2010 Flag | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = 2000_2002_flag,2003_2005_flag,2007_2009_flag,2008_2010_flag
```

## Data Commands

```ls
series e:m4es-3af4 d:2011-01-01T00:00:00.000Z t:state=Missouri t:race_ethnicity="All races" m:2007_2009=8.03 m:re_sort=1 m:2000_2002=7.74 m:2003_2005=8.12 m:2008_2010=8.15

series e:m4es-3af4 d:2011-01-01T00:00:00.000Z t:state="United States" t:race_ethnicity="All races" m:2007_2009=8.19 m:re_sort=1 m:2000_2002=7.69 m:2003_2005=8.07 m:2008_2010=8.16

series e:m4es-3af4 d:2011-01-01T00:00:00.000Z t:state="United States" t:race_ethnicity="American Indian or Alaska Native" m:re_flag=3 m:2007_2009=7.38 m:re_sort=6 m:2000_2002=7.11 m:2003_2005=7.39 m:2008_2010=7.43
```

## Meta Commands

```ls
metric m:re_sort p:integer l:"RE Sort" t:dataTypeName=number

metric m:re_flag p:integer l:"RE Flag" t:dataTypeName=number

metric m:2000_2002 p:float l:2000-2002 t:dataTypeName=number

metric m:2003_2005 p:float l:2003-2005 t:dataTypeName=number

metric m:2007_2009 p:float l:2007-2009 t:dataTypeName=number

metric m:2008_2010 p:float l:2008-2010 t:dataTypeName=number

entity e:m4es-3af4 l:"Selected Trend Table from Health, United States, 2011. Low birthweight live births, by race and Hispanic origin of mother, and state: United States, 2000 - 2002, 2003 - 2005, and 2006 - 2008" t:attribution="Health, United States" t:url=https://data.cdc.gov/api/views/m4es-3af4

property e:m4es-3af4 t:meta.view v:id=m4es-3af4 v:category="Health Statistics" v:attributionLink=http://www.cdc.gov/nchs/hus.htm v:averageRating=0 v:name="Selected Trend Table from Health, United States, 2011. Low birthweight live births, by race and Hispanic origin of mother, and state: United States, 2000 - 2002, 2003 - 2005, and 2006 - 2008" v:attribution="Health, United States"

property e:m4es-3af4 t:meta.view.owner v:id=vr5q-rutf v:screenName=SFranco v:displayName=SFranco

property e:m4es-3af4 t:meta.view.tableauthor v:id=g3fc-zmqn v:profileImageUrlMedium=/api/users/g3fc-zmqn/profile_images/THUMB v:profileImageUrlLarge=/api/users/g3fc-zmqn/profile_images/LARGE v:screenName=CDC v:profileImageUrlSmall=/api/users/g3fc-zmqn/profile_images/TINY v:roleName=publisher v:displayName=CDC

property e:m4es-3af4 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state         | race_ethnicity                   | re_sort | re_flag | 2000_2002 | 2000_2002_flag | 2003_2005 | 2003_2005_flag | 2007_2009 | 2007_2009_flag | 2008_2010 | 2008_2010_flag | 
| ============= | ================================ | ======= | ======= | ========= | ============== | ========= | ============== | ========= | ============== | ========= | ============== | 
| Missouri      | All races                        | 1       |         | 7.74      |                | 8.12      |                | 8.03      |                | 8.15      |                | 
| United States | All races                        | 1       |         | 7.69      |                | 8.07      |                | 8.19      |                | 8.16      |                | 
| United States | American Indian or Alaska Native | 6       | 3       | 7.11      |                | 7.39      |                | 7.38      |                | 7.43      |                | 
| United States | Asian or Pacific Islander        | 5       | 3       | 7.54      |                | 7.89      |                | 8.18      |                | 8.31      |                | 
| United States | Black or African American        | 3       |         | 13.19     |                | 13.77     |                | 13.74     |                | 13.62     |                | 
| United States | Hispanic or Latina               | 4       | 2       | 6.48      |                | 6.79      |                | 6.94      |                | 6.96      |                | 
| United States | White                            | 2       |         | 6.75      |                | 7.18      |                | 7.23      |                | 7.18      |                | 
| Kentucky      | Black or African American        | 3       |         | 13.84     |                | 13.52     |                | 14.77     |                | 14.04     |                | 
| Illinois      | All races                        | 1       |         | 8.04      |                | 8.40      |                | 8.41      |                | 8.34      |                | 
| Minnesota     | Black or African American        | 3       |         | 10.54     |                | 10.71     |                | 10.56     |                | 10.38     |                | 
```