# Selected Trend Table from Health, United States, 2011. Health conditions among children under 18 years of age, by selected characteristics: United States, average annual, selected years 1997 - 1999...

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/selected-trend-table-from-health-united-states-2011-health-conditions-among-children-under-89503) |
| Metadata | [Link](https://data.cdc.gov/api/views/bbhn-4mdn) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/bbhn-4mdn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/bbhn-4mdn/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | bbhn-4mdn |
| Name | Selected Trend Table from Health, United States, 2011. Health conditions among children under 18 years of age, by selected characteristics: United States, average annual, selected years 1997 - 1999... |
| Attribution | Health, United States |
| Category | Health Statistics |
| Tags | hus, health conditions, children |
| Created | 2013-07-29T15:45:06Z |
| Publication Date | 2013-08-05T14:26:00Z |

## Description

Health, United States is an annual report on trends in health statistics, find more information at http://www.cdc.gov/nchs/hus.htm.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | question            | Question            | text      | text        |
| Yes      | numeric metric | question_sort       | Question Sort       | number    | number      |
| Yes      | series tag     | characteristic      | Characteristic      | text      | text        |
| Yes      | numeric metric | characteristic_sort | Characteristic Sort | number    | number      |
| No       |                | characteristic_flag | Characteristic Flag | text      | text        |
| Yes      | series tag     | group               | Group               | text      | text        |
| Yes      | numeric metric | group_flag          | Group flag          | number    | number      |
| Yes      | numeric metric | 1997_1999           | 1997-1999           | number    | number      |
| No       |                | 1997_1999_flag      | 1997-1999 flag      | text      | text        |
| Yes      | numeric metric | 1997_1999_se        | 1997-1999 SE        | number    | number      |
| No       |                | 1997_1999_se_flag   | 1997-1999 SE flag   | text      | text        |
| Yes      | numeric metric | 2000_2002           | 2000-2002           | number    | number      |
| No       |                | 2000_2002_flag      | 2000-2002 flag      | text      | text        |
| Yes      | numeric metric | 2000_2002_se        | 2000-2002 SE        | number    | number      |
| No       |                | 2000_2002_se_flag   | 2000-2002 SE flag   | text      | text        |
| Yes      | numeric metric | 2003_2005           | 2003-2005           | number    | number      |
| No       |                | 2003_2005_flag      | 2003-2005 flag      | text      | text        |
| Yes      | numeric metric | 2003_2005_se        | 2003-2005 SE        | number    | number      |
| No       |                | 2003_2005_se_flag   | 2003-2005 SE flag   | text      | text        |
| Yes      | numeric metric | 2006_2008           | 2006-2008           | number    | number      |
| No       |                | 2006_2008_flag      | 2006-2008 flag      | text      | text        |
| Yes      | numeric metric | 2006_2008_se        | 2006-2008 SE        | number    | number      |
| No       |                | 2006_2008_se_flag   | 2006-2008 SE flag   | text      | text        |
| Yes      | numeric metric | 2007_2009           | 2007-2009           | number    | number      |
| No       |                | 2007_2009_flag      | 2007-2009 flag      | text      | text        |
| Yes      | numeric metric | 2007_2009_se        | 2007-2009 SE        | number    | number      |
| No       |                | 2007_2009_se_flag   | 2007-2009 SE flag   | text      | text        |
| Yes      | numeric metric | 2008_2010           | 2008-2010           | number    | number      |
| No       |                | 2008_2010_flag      | 2008-2010 flag      | text      | text        |
| Yes      | numeric metric | 2008_2010_se        | 2008-2010 SE        | number    | number      |
| No       |                | 2008_2010_se_flag   | 2008-2010 SE flag   | text      | text        |
| Yes      | numeric metric | 2009_2011           | 2009-2011           | number    | number      |
| No       |                | 2009_2011_flag      | 2009-2011 flag      | text      | text        |
| Yes      | numeric metric | 2009_2011_se        | 2009-2011 SE        | number    | number      |
| No       |                | 2009_2011_se_flag   | 2009-2011 SE flag   | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = characteristic_flag,1997_1999_flag,1997_1999_se_flag,2000_2002_flag,2000_2002_se_flag,2003_2005_flag,2003_2005_se_flag,2006_2008_flag,2006_2008_se_flag,2007_2009_flag,2007_2009_se_flag,2008_2010_flag,2008_2010_se_flag,2009_2011_flag,2009_2011_se_flag
```

## Data Commands

```ls
series e:bbhn-4mdn d:2011-01-01T00:00:00.000Z t:question=Age t:group="Current asthma" t:characteristic="Under 18 years" m:2008_2010_se=0.2 m:2003_2005_se=0.2 m:2009_2011=9.5 m:2007_2009=9.4 m:2006_2008=9.3 m:group_flag=1 m:2009_2011_se=0.2 m:characteristic_sort=5 m:2003_2005=8.7 m:2008_2010=9.5 m:2006_2008_se=0.2 m:question_sort=1 m:2007_2009_se=0.2

series e:bbhn-4mdn d:2011-01-01T00:00:00.000Z t:question=Age t:group="Current asthma" t:characteristic="0-4 years" m:2008_2010_se=0.3 m:2003_2005_se=0.3 m:2009_2011=6.4 m:2007_2009=6.4 m:2006_2008=6.2 m:group_flag=1 m:2009_2011_se=0.3 m:characteristic_sort=1 m:2003_2005=6.1 m:2008_2010=6.2 m:2006_2008_se=0.3 m:question_sort=1 m:2007_2009_se=0.4

series e:bbhn-4mdn d:2011-01-01T00:00:00.000Z t:question=Age t:group="Current asthma" t:characteristic="5-17 years" m:2008_2010_se=0.3 m:2003_2005_se=0.2 m:2009_2011=10.7 m:2007_2009=10.6 m:2006_2008=10.5 m:group_flag=1 m:2009_2011_se=0.2 m:characteristic_sort=2 m:2003_2005=9.6 m:2008_2010=10.8 m:2006_2008_se=0.3 m:question_sort=1 m:2007_2009_se=0.3
```

## Meta Commands

```ls
metric m:question_sort p:integer l:"Question Sort" t:dataTypeName=number

metric m:characteristic_sort p:integer l:"Characteristic Sort" t:dataTypeName=number

metric m:group_flag p:integer l:"Group flag" t:dataTypeName=number

metric m:1997_1999 p:float l:1997-1999 t:dataTypeName=number

metric m:1997_1999_se p:float l:"1997-1999 SE" t:dataTypeName=number

metric m:2000_2002 p:float l:2000-2002 t:dataTypeName=number

metric m:2000_2002_se p:float l:"2000-2002 SE" t:dataTypeName=number

metric m:2003_2005 p:float l:2003-2005 t:dataTypeName=number

metric m:2003_2005_se p:float l:"2003-2005 SE" t:dataTypeName=number

metric m:2006_2008 p:float l:2006-2008 t:dataTypeName=number

metric m:2006_2008_se p:float l:"2006-2008 SE" t:dataTypeName=number

metric m:2007_2009 p:float l:2007-2009 t:dataTypeName=number

metric m:2007_2009_se p:float l:"2007-2009 SE" t:dataTypeName=number

metric m:2008_2010 p:float l:2008-2010 t:dataTypeName=number

metric m:2008_2010_se p:float l:"2008-2010 SE" t:dataTypeName=number

metric m:2009_2011 p:float l:2009-2011 t:dataTypeName=number

metric m:2009_2011_se p:float l:"2009-2011 SE" t:dataTypeName=number

entity e:bbhn-4mdn l:"Selected Trend Table from Health, United States, 2011. Health conditions among children under 18 years of age, by selected characteristics: United States, average annual, selected years 1997 - 1999 through 2008 - 2010" t:attribution="Health, United States" t:url=https://data.cdc.gov/api/views/bbhn-4mdn

property e:bbhn-4mdn t:meta.view v:id=bbhn-4mdn v:category="Health Statistics" v:attributionLink=http://www.cdc.gov/nchs/hus.htm v:averageRating=0 v:name="Selected Trend Table from Health, United States, 2011. Health conditions among children under 18 years of age, by selected characteristics: United States, average annual, selected years 1997 - 1999 through 2008 - 2010" v:attribution="Health, United States"

property e:bbhn-4mdn t:meta.view.owner v:id=vr5q-rutf v:screenName=SFranco v:displayName=SFranco

property e:bbhn-4mdn t:meta.view.tableauthor v:id=g3fc-zmqn v:profileImageUrlMedium=/api/users/g3fc-zmqn/profile_images/THUMB v:profileImageUrlLarge=/api/users/g3fc-zmqn/profile_images/LARGE v:screenName=CDC v:profileImageUrlSmall=/api/users/g3fc-zmqn/profile_images/TINY v:roleName=publisher v:displayName=CDC

property e:bbhn-4mdn t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| question | question_sort | characteristic                        | characteristic_sort | characteristic_flag | group          | group_flag | 1997_1999 | 1997_1999_flag | 1997_1999_se | 1997_1999_se_flag | 2000_2002 | 2000_2002_flag | 2000_2002_se | 2000_2002_se_flag | 2003_2005 | 2003_2005_flag | 2003_2005_se | 2003_2005_se_flag | 2006_2008 | 2006_2008_flag | 2006_2008_se | 2006_2008_se_flag | 2007_2009 | 2007_2009_flag | 2007_2009_se | 2007_2009_se_flag | 2008_2010 | 2008_2010_flag | 2008_2010_se | 2008_2010_se_flag | 2009_2011 | 2009_2011_flag | 2009_2011_se | 2009_2011_se_flag | 
| ======== | ============= | ===================================== | =================== | =================== | ============== | ========== | ========= | ============== | ============ | ================= | ========= | ============== | ============ | ================= | ========= | ============== | ============ | ================= | ========= | ============== | ============ | ================= | ========= | ============== | ============ | ================= | ========= | ============== | ============ | ================= | ========= | ============== | ============ | ================= | 
| Age      | 1             | Under 18 years                        | 5                   | 3                   | Current asthma | 1          |           |                |              |                   |           |                |              |                   | 8.7       |                | 0.2          |                   | 9.3       |                | 0.2          |                   | 9.4       |                | 0.2          |                   | 9.5       |                | 0.2          |                   | 9.5       |                | 0.2          |                   | 
| Age      | 1             | 0-4 years                             | 1                   |                     | Current asthma | 1          |           |                |              |                   |           |                |              |                   | 6.1       |                | 0.3          |                   | 6.2       |                | 0.3          |                   | 6.4       |                | 0.4          |                   | 6.2       |                | 0.3          |                   | 6.4       |                | 0.3          |                   | 
| Age      | 1             | 5-17 years                            | 2                   |                     | Current asthma | 1          |           |                |              |                   |           |                |              |                   | 9.6       |                | 0.2          |                   | 10.5      |                | 0.3          |                   | 10.6      |                | 0.3          |                   | 10.8      |                | 0.3          |                   | 10.7      |                | 0.2          |                   | 
| Age      | 1             | 5-9 years                             | 3                   |                     | Current asthma | 1          |           |                |              |                   |           |                |              |                   | 9.1       |                | 0.4          |                   | 10.6      |                | 0.5          |                   | 10.2      |                | 0.4          |                   | 10.7      |                | 0.4          |                   | 10.2      |                | 0.4          |                   | 
| Age      | 1             | 10-17 years                           | 4                   |                     | Current asthma | 1          |           |                |              |                   |           |                |              |                   | 9.9       |                | 0.3          |                   | 10.4      |                | 0.4          |                   | 10.8      |                | 0.4          |                   | 10.9      |                | 0.3          |                   | 11.1      |                | 0.3          |                   | 
| Sex      | 2             | Male                                  | 1                   |                     | Current asthma | 1          |           |                |              |                   |           |                |              |                   | 9.9       |                | 0.3          |                   | 10.7      |                | 0.3          |                   | 10.8      |                | 0.3          |                   | 11.1      |                | 0.3          |                   | 10.7      |                | 0.3          |                   | 
| Sex      | 2             | Female                                | 2                   |                     | Current asthma | 1          |           |                |              |                   |           |                |              |                   | 7.3       |                | 0.2          |                   | 7.8       |                | 0.3          |                   | 7.9       |                | 0.3          |                   | 7.8       |                | 0.3          |                   | 8.3       |                | 0.3          |                   | 
| Race     | 3             | White only                            | 1                   | 4                   | Current asthma | 1          |           |                |              |                   |           |                |              |                   | 7.7       |                | 0.2          |                   | 8.2       |                | 0.3          |                   | 8.0       |                | 0.2          |                   | 8.2       |                | 0.2          |                   | 8.1       |                | 0.2          |                   | 
| Race     | 3             | Black or African American only        | 2                   | 4                   | Current asthma | 1          |           |                |              |                   |           |                |              |                   | 13.0      |                | 0.6          |                   | 14.6      |                | 0.6          |                   | 16.0      |                | 0.7          |                   | 16.0      |                | 0.7          |                   | 16.4      |                | 0.7          |                   | 
| Race     | 3             | American Indian or Alaska Native only | 3                   | 4                   | Current asthma | 1          |           |                |              |                   |           |                |              |                   | 12.2      |                | 2.1          |                   | 10.4      | *              | 2.5          | *                 | 10.8      | *              | 2.4          | *                 | 10.3      | *              | 2.4          | *                 | 6.6       | *              | 1.4          | *                 | 
```