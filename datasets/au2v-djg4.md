# WTC Disorders

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wtc-disorders-f594c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/au2v-djg4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/au2v-djg4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/au2v-djg4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | au2v-djg4 |
| Name | WTC Disorders |
| Attribution | Health and Hospitals Corporation (HHC) |
| Category | Health |
| Tags | health, patient, world trade center, wtc, disorder, environmental health center, healthy living |
| Created | 2011-09-30T18:45:42Z |
| Publication Date | 2011-10-11T19:24:06Z |

## Description

The New York City Health and Hospitals Corporation (HHC) World Trade Center (WTC) Environmental Health Center program, one of three Centers of Excellence in New York City, provides medical and mental healthcare to residents, students, workers, and passersby who may still be sick from 9/11.  This data shows the major disorders suffered by patients who were enrolled between 4/1/2010 and 3/31/2011..
Update Frequency: As needed

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | disorder    | DISORDER   | text      | text        |
| Yes      | series tag  | percentage  | PERCENTAGE | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:au2v-djg4 d:2011-09-30T11:45:51.000Z t:disorder=PTSD/Anxiety/depression t:percentage=51% m:row_number.au2v-djg4=1

series e:au2v-djg4 d:2011-09-30T11:45:51.000Z t:disorder="Digestive Disorders" t:percentage=40% m:row_number.au2v-djg4=2

series e:au2v-djg4 d:2011-09-30T11:45:51.000Z t:disorder="Lower Respiratory Symptoms" t:percentage=76% m:row_number.au2v-djg4=3
```

## Meta Commands

```ls
metric m:row_number.au2v-djg4 p:long l:"Row Number"

entity e:au2v-djg4 l:"WTC Disorders" t:attribution="Health and Hospitals Corporation (HHC)" t:url=https://data.cityofnewyork.us/api/views/au2v-djg4

property e:au2v-djg4 t:meta.view v:id=au2v-djg4 v:category=Health v:averageRating=0 v:name="WTC Disorders" v:attribution="Health and Hospitals Corporation (HHC)"

property e:au2v-djg4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:au2v-djg4 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | disorder                   | percentage | 
| =========== | ========================== | ========== | 
| 1317383151  | PTSD/Anxiety/depression    | 51%        | 
| 1317383151  | Digestive Disorders        | 40%        | 
| 1317383151  | Lower Respiratory Symptoms | 76%        | 
| 1317383151  | Upper Respiratory Symtomps | 40%        | 
```