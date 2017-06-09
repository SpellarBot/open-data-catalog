# Statewide -- Hatchery Standards 2016 SOS 10172016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statewide-hatchery-standards-2014-sos-1132015) |
| Metadata | [Link](https://data.wa.gov/api/views/spnc-z2pw) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/spnc-z2pw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/spnc-z2pw/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | spnc-z2pw |
| Name | Statewide -- Hatchery Standards 2016 SOS 10172016 |
| Created | 2014-12-15T13:30:50Z |
| Publication Date | 2016-10-17T14:29:09Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | number      |
| Yes      | numeric metric | meeting     | Meeting     | number    | number      |
| Yes      | numeric metric | not_meeting | Not Meeting | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:spnc-z2pw d:1998-01-01T00:00:00.000Z m:not_meeting=82 m:meeting=18

series e:spnc-z2pw d:2008-01-01T00:00:00.000Z m:not_meeting=75 m:meeting=25

series e:spnc-z2pw d:2010-01-01T00:00:00.000Z m:not_meeting=55 m:meeting=45
```

## Meta Commands

```ls
metric m:meeting p:integer l:Meeting t:dataTypeName=number

metric m:not_meeting p:integer l:"Not Meeting" t:dataTypeName=number

entity e:spnc-z2pw l:"Statewide -- Hatchery Standards 2016 SOS 10172016" t:url=https://data.wa.gov/api/views/spnc-z2pw

property e:spnc-z2pw t:meta.view d:2017-06-09T13:58:40.532Z v:id=spnc-z2pw v:averageRating=0 v:name="Statewide -- Hatchery Standards 2016 SOS 10172016"

property e:spnc-z2pw t:meta.view.owner d:2017-06-09T13:58:40.532Z v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:spnc-z2pw t:meta.view.tableauthor d:2017-06-09T13:58:40.532Z v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| year | meeting | not_meeting | 
| ==== | ======= | =========== | 
| 1998 | 18      | 82          | 
| 2008 | 25      | 75          | 
| 2010 | 45      | 55          | 
| 2011 | 61      | 39          | 
| 2012 | 61      | 39          | 
| 2013 | 69      | 31          | 
| 2014 | 83      | 17          | 
| 2015 | 88      | 12          | 
| 2016 | 88      | 12          | 
```