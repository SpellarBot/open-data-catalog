# DBEDT Clean Economy Job Growth 2003-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-clean-economy-job-growth-2003-2010-4bed7) |
| Metadata | [Link](https://data.hawaii.gov/api/views/5fix-ixwc) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/5fix-ixwc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/5fix-ixwc/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 5fix-ixwc |
| Name | DBEDT Clean Economy Job Growth 2003-2010 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | clean, economy |
| Created | 2012-08-28T19:26:11Z |
| Publication Date | 2012-08-29T01:23:44Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                     | Data Type | Render Type |
| ======== | ============== | ==================== | ======================== | ========= | =========== |
| Yes      | numeric metric | job_growth_2003_2010 | Job Growth 2003-2010 (%) | percent   | percent     |
```

## Time Field

```ls
Value = 2003
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5fix-ixwc d:2003-01-01T00:00:00.000Z m:job_growth_2003_2010=10.23

series e:5fix-ixwc d:2003-01-01T00:00:00.000Z m:job_growth_2003_2010=6.71

series e:5fix-ixwc d:2003-01-01T00:00:00.000Z m:job_growth_2003_2010=6.52
```

## Meta Commands

```ls
metric m:job_growth_2003_2010 p:float l:"Job Growth 2003-2010 (%)" t:dataTypeName=percent

entity e:5fix-ixwc l:"DBEDT Clean Economy Job Growth 2003-2010" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/5fix-ixwc

property e:5fix-ixwc t:meta.view v:id=5fix-ixwc v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Clean Economy Job Growth 2003-2010" v:attribution="Department of Economic Development and Tourism"

property e:5fix-ixwc t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:5fix-ixwc t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:5fix-ixwc t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| job_growth_2003_2010 | 
| ==================== | 
| 10.23                | 
| 6.71                 | 
| 6.52                 | 
| 6.31                 | 
| 5.96                 | 
| 3.45                 | 
```