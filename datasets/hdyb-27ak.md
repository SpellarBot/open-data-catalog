# CCTV Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cctv-locations-f4af6) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/hdyb-27ak) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/hdyb-27ak/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/hdyb-27ak/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | hdyb-27ak |
| Name | CCTV Locations |
| Attribution | Baltimore Police Department |
| Category | Public Safety |
| Tags | police, camera, cctv |
| Created | 2011-07-18T12:43:10Z |
| Publication Date | 2014-03-27T23:52:41Z |

## Description

Closed circuit camera locations capturing activity within 256ft (~2 blocks).

## Columns

```ls
| Included | Schema Type | Field Name  | Name           | Data Type | Render Type |
| ======== | =========== | =========== | ============== | ========= | =========== |
| No       | time        | :updated_at | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | name        | cameraLocation | text      | text        |
| Yes      | series tag  | description | cameraNumber   | text      | text        |
| Yes      | series tag  | project     | cameraProject  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hdyb-27ak d:2013-01-16T06:41:51.000Z t:project=Downtown t:description=1 t:name="Eutaw and Lexington Market" m:row_number.hdyb-27ak=1

series e:hdyb-27ak d:2013-01-16T06:41:51.000Z t:project=Downtown t:description=2 t:name="Eutaw and Fayette" m:row_number.hdyb-27ak=2

series e:hdyb-27ak d:2013-01-16T06:41:51.000Z t:project=Downtown t:description=3 t:name="Eutaw and Baltimore" m:row_number.hdyb-27ak=3
```

## Meta Commands

```ls
metric m:row_number.hdyb-27ak p:long l:"Row Number"

entity e:hdyb-27ak l:"CCTV Locations" t:attribution="Baltimore Police Department" t:url=https://data.baltimorecity.gov/api/views/hdyb-27ak

property e:hdyb-27ak t:meta.view v:id=hdyb-27ak v:category="Public Safety" v:attributionLink=http://www.baltimorepolice.org/ v:averageRating=0 v:name="CCTV Locations" v:attribution="Baltimore Police Department"

property e:hdyb-27ak t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:hdyb-27ak t:meta.view.owner v:id=ye7n-cr57 v:screenName="Jeffrey Cooper" v:displayName="Jeffrey Cooper"

property e:hdyb-27ak t:meta.view.tableauthor v:id=ye7n-cr57 v:screenName="Jeffrey Cooper" v:roleName=publisher v:displayName="Jeffrey Cooper"
```

## Top Records

```ls
| :updated_at | name                       | description | project  | 
| =========== | ========================== | =========== | ======== | 
| 1358318511  | Eutaw and Lexington Market | 1           | Downtown | 
| 1358318511  | Eutaw and Fayette          | 2           | Downtown | 
| 1358318511  | Eutaw and Baltimore        | 3           | Downtown | 
| 1358318511  | Eutaw and Redwood          | 4           | Downtown | 
| 1358318511  | Eutaw and Lombard          | 5           | Downtown | 
| 1358318511  | Eutaw and Camden           | 6           | Downtown | 
| 1358318511  | Paca and Pratt             | 7           | Downtown | 
| 1358318511  | Greene and Lombard         | 8           | Downtown | 
| 1358318511  | Greene and Baltimore       | 9           | Downtown | 
| 1358318511  | Greene and Fayette         | 10          | Downtown | 
```