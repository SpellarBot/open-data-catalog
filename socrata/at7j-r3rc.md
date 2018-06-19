# Total Number of Drug- and Alcohol-Related Intoxication Deaths Occurring in Maryland, 2007-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/overdose-deaths-by-year-2007-to-present-6842a) |
| Metadata | [Link](https://data.maryland.gov/api/views/at7j-r3rc) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/at7j-r3rc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/at7j-r3rc/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | at7j-r3rc |
| Name | Total Number of Drug- and Alcohol-Related Intoxication Deaths Occurring in Maryland, 2007-2015 |
| Attribution | Department of Health and Mental Hygiene (DHMH) |
| Category | Health and Human Services |
| Tags | substance abuse, health, dhmh, overdose |
| Created | 2013-03-18T17:58:58Z |
| Publication Date | 2016-10-25T17:04:52Z |

## Description

Total Number of Drug- and Alcohol-Related Intoxication Deaths Occurring in Maryland, 2007-2015.

## Columns

```ls
| Included | Schema Type    | Field Name                                     | Name                                           | Data Type | Render Type |
| ======== | ============== | ============================================== | ============================================== | ========= | =========== |
| Yes      | series tag     | calendar_year                                  | Calendar Year                                  | text      | text        |
| Yes      | numeric metric | accidental_or_undetermined_intoxication_deaths | Accidental or Undetermined Intoxication Deaths | number    | number      |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:at7j-r3rc d:2007-01-01T00:00:00.000Z t:calendar_year=CY2007 m:accidental_or_undetermined_intoxication_deaths=815

series e:at7j-r3rc d:2007-01-01T00:00:00.000Z t:calendar_year=CY2008 m:accidental_or_undetermined_intoxication_deaths=694

series e:at7j-r3rc d:2007-01-01T00:00:00.000Z t:calendar_year=CY2009 m:accidental_or_undetermined_intoxication_deaths=731
```

## Meta Commands

```ls
metric m:accidental_or_undetermined_intoxication_deaths p:integer l:"Accidental or Undetermined Intoxication Deaths" t:dataTypeName=number

entity e:at7j-r3rc l:"Total Number of Drug- and Alcohol-Related Intoxication Deaths Occurring in Maryland, 2007-2015" t:attribution="Department of Health and Mental Hygiene (DHMH)" t:url=https://data.maryland.gov/api/views/at7j-r3rc

property e:at7j-r3rc t:meta.view v:id=at7j-r3rc v:category="Health and Human Services" v:attributionLink=http://bha.dhmh.maryland.gov/OVERDOSE_PREVENTION/Pages/Data-and-Reports.aspx v:averageRating=0 v:name="Total Number of Drug- and Alcohol-Related Intoxication Deaths Occurring in Maryland, 2007-2015" v:attribution="Department of Health and Mental Hygiene (DHMH)"

property e:at7j-r3rc t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:at7j-r3rc t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| calendar_year | accidental_or_undetermined_intoxication_deaths | 
| ============= | ============================================== | 
| CY2007        | 815                                            | 
| CY2008        | 694                                            | 
| CY2009        | 731                                            | 
| CY2010        | 649                                            | 
| CY2011        | 671                                            | 
| CY2012        | 799                                            | 
| CY2013        | 858                                            | 
| CY2014        | 1041                                           | 
| CY2015        | 1259                                           | 
```