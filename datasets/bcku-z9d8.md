# Austin Police Forensics Quality Records

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-police-forensics-quality-records) |
| Metadata | [Link](https://data.austintexas.gov/api/views/bcku-z9d8) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/bcku-z9d8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/bcku-z9d8/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | bcku-z9d8 |
| Name | Austin Police Forensics Quality Records |
| Attribution | Austin Police Department |
| Category | Public Safety |
| Tags | blood-alcohol, forensics, apd, austin police |
| Created | 2014-12-19T15:43:30Z |
| Publication Date | 2015-01-20T21:31:05Z |

## Description

These records are archives of forensics lab records, including blood alcohol tests, for use in civil or criminal court.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | folder        | Folder        | text      | text        |
| Yes      | series tag  | document_name | Document Name | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bcku-z9d8 d:2014-12-19T11:36:44.000Z t:folder="All Chromatograms" m:row_number.bcku-z9d8=1

series e:bcku-z9d8 d:2014-12-19T12:11:20.000Z t:folder="All Chromatograms" m:row_number.bcku-z9d8=2

series e:bcku-z9d8 d:2014-12-19T12:12:30.000Z t:folder="All Chromatograms" m:row_number.bcku-z9d8=3
```

## Meta Commands

```ls
metric m:row_number.bcku-z9d8 p:long l:"Row Number"

entity e:bcku-z9d8 l:"Austin Police Forensics Quality Records" t:attribution="Austin Police Department" t:url=https://data.austintexas.gov/api/views/bcku-z9d8

property e:bcku-z9d8 t:meta.view v:id=bcku-z9d8 v:category="Public Safety" v:attributionLink=http://www.austintexas.gov/police v:averageRating=0 v:name="Austin Police Forensics Quality Records" v:attribution="Austin Police Department"

property e:bcku-z9d8 t:meta.view.license v:name="Public Domain"

property e:bcku-z9d8 t:meta.view.owner v:id=sht8-rzx9 v:screenName="Colleen Waters" v:displayName="Colleen Waters"

property e:bcku-z9d8 t:meta.view.tableauthor v:id=sht8-rzx9 v:screenName="Colleen Waters" v:roleName=editor v:displayName="Colleen Waters"
```

## Top Records

```ls
| :updated_at | folder                   | document_name                                                          | 
| =========== | ======================== | ====================================================================== | 
| 1418989004  | All Chromatograms        | [null, Chromatograms Agilent 2013-12-13]                               | 
| 1418991080  | All Chromatograms        | [null, Chromatograms Agilent 2012-10-18]                               | 
| 1418991150  | All Chromatograms        | [null, Chromatograms Agilent 2013-07-23]                               | 
| 1418991810  | All Chromatograms        | [null, Chromatograms Agilent 2014-03-17]                               | 
| 1418992445  | Certificates of Analysis | [null, BAC Resolution Control Standard - Restek - A088401 exp 2015-06] | 
| 1418992511  | Certificates of Analysis | [null, Isopropanol - Macron Lot 0000025726]                            | 
| 1418993294  | Ethanol 150              | [null, Ethanol 150 11012012-C-2017 rec 2014-07-21]                     | 
| 1418993474  | Ethanol 300              | [null, Ethanol 300 FN072310-02 exp 2015-07]                            | 
| 1418993482  | Ethanol 300              | [null, Ethanol 300 FN121510-01 exp 2015-12]                            | 
| 1418993561  | Ethanol 400              | [null, Ethanol 400 FN012712-01 exp 2017-01]                            | 
```