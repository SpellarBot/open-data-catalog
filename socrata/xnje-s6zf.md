# Significant Noncompliance List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/significant-noncompliance-list-c6f5f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xnje-s6zf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xnje-s6zf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xnje-s6zf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xnje-s6zf |
| Name | Significant Noncompliance List |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | dep, department of environmental protection, environment, noncompliance, compliance, significant noncompliance list, healthy living |
| Created | 2013-01-31T15:05:02Z |
| Publication Date | 2013-06-21T19:45:11Z |

## Description

List of establishments in New York City that were in significant noncompliance with applicable pretreatment standards and other requirements. Significant noncompliance is defined in 40 CFR 403.8(f) (2) (viii)

(* Indicates that these establishments are on the list for late reporting only)

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | period             | Period             | text      | text        |
| Yes      | series tag  | establishment_name | Establishment Name | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xnje-s6zf d:2013-01-31T07:05:03.000Z t:period="July 1, 2011 - June 30, 2012" t:establishment_name="*A1 RADIATOR EXPRESS & AUTO REPAIR, INC." m:row_number.xnje-s6zf=1

series e:xnje-s6zf d:2013-01-31T07:05:03.000Z t:period="July 1, 2011 - June 30, 2012" t:establishment_name="*ADELPHIA CONTAINER CORP." m:row_number.xnje-s6zf=2

series e:xnje-s6zf d:2013-01-31T07:05:03.000Z t:period="July 1, 2011 - June 30, 2012" t:establishment_name="ALSCO JEWELRY OF NEW YORK, INC." m:row_number.xnje-s6zf=3
```

## Meta Commands

```ls
metric m:row_number.xnje-s6zf p:long l:"Row Number"

entity e:xnje-s6zf l:"Significant Noncompliance List" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/xnje-s6zf

property e:xnje-s6zf t:meta.view v:id=xnje-s6zf v:category=Environment v:attributionLink=http://www.nyc.gov/html/dep/html/wastewater/snclist.shtml v:averageRating=0 v:name="Significant Noncompliance List" v:attribution="Department of Environmental Protection (DEP)"

property e:xnje-s6zf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xnje-s6zf t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| :updated_at | period                       | establishment_name                       | 
| =========== | ============================ | ======================================== | 
| 1359615903  | July 1, 2011 - June 30, 2012 | *A1 RADIATOR EXPRESS & AUTO REPAIR, INC. | 
| 1359615903  | July 1, 2011 - June 30, 2012 | *ADELPHIA CONTAINER CORP.                | 
| 1359615903  | July 1, 2011 - June 30, 2012 | ALSCO JEWELRY OF NEW YORK, INC.          | 
| 1359615903  | July 1, 2011 - June 30, 2012 | *AMERICO IZZO                            | 
| 1359615903  | July 1, 2011 - June 30, 2012 | APEXX OMNI-GRAPHICS, INC.                | 
| 1359615903  | July 1, 2011 - June 30, 2012 | *ARCHITECTURAL COATINGS, INC.            | 
| 1359615903  | July 1, 2011 - June 30, 2012 | ATLANTIS JEWELRY CONTRACTORS, INC.       | 
| 1359615903  | July 1, 2011 - June 30, 2012 | *B & M LINEN CORP.                       | 
| 1359615903  | July 1, 2011 - June 30, 2012 | BNNS CO., INC.                           | 
| 1359615903  | July 1, 2011 - June 30, 2012 | BRILLIANT JEWELERS/MJJ INC.              | 
```