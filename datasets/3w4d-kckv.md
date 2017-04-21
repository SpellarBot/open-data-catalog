# BPD Officer Involved Use Of Force

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-2014-bpd-officer-involved-shootings-bcf3c) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/3w4d-kckv) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/3w4d-kckv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/3w4d-kckv/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 3w4d-kckv |
| Name | BPD Officer Involved Use Of Force |
| Attribution | BPD |
| Category | Public Safety |
| Tags | bpd, officer involved shootings, fit |
| Created | 2014-05-22T12:26:21Z |
| Publication Date | 2015-12-04T16:29:15Z |

## Description

This data set contains the date, incident #, and location of officer involved use of force incidents that are investigated by the BPD Force Investigation Team (FIT).  The data, ranging from 2013 through 2015, is used to keep up to date a map displayed on the department's website.

## Columns

```ls
| Included | Schema Type | Field Name | Name     | Data Type     | Render Type   |
| ======== | =========== | ========== | ======== | ============= | ============= |
| Yes      | time        | date       | DATE     | calendar_date | calendar_date |
| No       |             | cc         | CC#      | text          | text          |
| Yes      | series tag  | district   | DISTRICT | text          | text          |
| Yes      | series tag  | location   | LOCATION | text          | text          |
| Yes      | series tag  | type       | TYPE     | text          | text          |
| No       |             | x_long     | X (LONG) | number        | number        |
| No       |             | y_lat      | Y (LAT)  | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = cc,x_long,y_lat
```

## Data Commands

```ls
series e:3w4d-kckv d:2013-01-02T00:00:00.000Z t:location="3200 Cliftmont Rd" t:type=Shooting t:district=NED m:row_number.3w4d-kckv=1

series e:3w4d-kckv d:2013-01-13T00:00:00.000Z t:location="5415 York Rd" t:type=Shooting t:district=ND m:row_number.3w4d-kckv=2

series e:3w4d-kckv d:2013-01-25T00:00:00.000Z t:location="500 N Madeira St" t:type=Shooting t:district=ED m:row_number.3w4d-kckv=3
```

## Meta Commands

```ls
metric m:row_number.3w4d-kckv p:long l:"Row Number"

entity e:3w4d-kckv l:"BPD Officer Involved Use Of Force" t:attribution=BPD t:url=https://data.baltimorecity.gov/api/views/3w4d-kckv

property e:3w4d-kckv t:meta.view v:id=3w4d-kckv v:category="Public Safety" v:averageRating=0 v:name="BPD Officer Involved Use Of Force" v:attribution=BPD

property e:3w4d-kckv t:meta.view.owner v:id=ye7n-cr57 v:screenName="Jeffrey Cooper" v:displayName="Jeffrey Cooper"

property e:3w4d-kckv t:meta.view.tableauthor v:id=ye7n-cr57 v:screenName="Jeffrey Cooper" v:roleName=publisher v:displayName="Jeffrey Cooper"
```

## Top Records

```ls
| date                | cc        | district | location              | type     | x_long         | y_lat         | 
| =================== | ========= | ======== | ===================== | ======== | ============== | ============= | 
| 2013-01-02T00:00:00 | 134A00685 | NED      | 3200 Cliftmont Rd     | Shooting | -76.5737176216 | 39.3189978152 | 
| 2013-01-13T00:00:00 | 135A05457 | ND       | 5415 York Rd          | Shooting | -76.6098638869 | 39.3561475240 | 
| 2013-01-25T00:00:00 | 133A11199 | ED       | 500 N Madeira St      | Shooting | -76.5858118569 | 39.2970004089 | 
| 2013-01-28T00:00:00 | 138A12326 | SWD      | 3300 Edmondson Ave    | Shooting | -76.6728214620 | 39.2941972073 | 
| 2013-01-29T00:00:00 | 136A12790 | NWD      | 5002 Pimlico Rd       | Shooting | -76.6693065652 | 39.3501473134 | 
| 2013-03-28T00:00:00 | 132C12587 | SED      | 6706 Danville Ave     | Shooting | -76.5295020443 | 39.2769560811 | 
| 2013-04-18T00:00:00 | 132D08633 | SED      | 3400 Foster Ave       | Shooting | -76.5687489914 | 39.2845448684 | 
| 2013-04-22T00:00:00 | 137D10409 | WD       | 2700 Edmondson Ave    | Shooting | -76.6615113213 | 39.2945651064 | 
| 2013-05-25T00:00:00 | 139E12127 | SD       | 400 S Poppleton St    | Shooting | -76.6318639809 | 39.2835928182 | 
| 2013-08-13T00:00:00 | 138H08647 | SWD      | 3400 Old Frederick Rd | Shooting | -76.6919883658 | 39.2901480834 | 
```