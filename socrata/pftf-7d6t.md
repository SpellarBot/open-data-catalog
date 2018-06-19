# Building and Zoning - Certificate Of Compliance Issued

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-and-zoning-certificate-of-compliance-issued-c424b) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/pftf-7d6t) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/pftf-7d6t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/pftf-7d6t/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | pftf-7d6t |
| Name | Building and Zoning - Certificate Of Compliance Issued |
| Attribution | Cook County Department of Building and Zoning |
| Category | Economic Development |
| Created | 2011-09-27T17:20:43Z |
| Publication Date | 2014-10-09T22:59:02Z |

## Description

Number of Certificate of Compliance issued by year for 1993 through part of 2011. Data is incomplete for 2011.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| Yes      | time           | fiscal_year                      | Fiscal Year                      | text      | text        |
| Yes      | numeric metric | certificate_of_compliance_issued | Certificate of Compliance Issued | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pftf-7d6t d:1993-01-01T00:00:00.000Z m:certificate_of_compliance_issued=102

series e:pftf-7d6t d:1994-01-01T00:00:00.000Z m:certificate_of_compliance_issued=453

series e:pftf-7d6t d:1995-01-01T00:00:00.000Z m:certificate_of_compliance_issued=555
```

## Meta Commands

```ls
metric m:certificate_of_compliance_issued p:integer l:"Certificate of Compliance Issued" t:dataTypeName=number

entity e:pftf-7d6t l:"Building and Zoning - Certificate Of Compliance Issued" t:attribution="Cook County Department of Building and Zoning" t:url=https://datacatalog.cookcountyil.gov/api/views/pftf-7d6t

property e:pftf-7d6t t:meta.view v:id=pftf-7d6t v:category="Economic Development" v:attributionLink=http://www.cookcountyil.gov/BuildingZoning v:averageRating=0 v:name="Building and Zoning - Certificate Of Compliance Issued" v:attribution="Cook County Department of Building and Zoning"

property e:pftf-7d6t t:meta.view.license v:name="Public Domain"

property e:pftf-7d6t t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:pftf-7d6t t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| fiscal_year | certificate_of_compliance_issued | 
| =========== | ================================ | 
| 1993        | 102                              | 
| 1994        | 453                              | 
| 1995        | 555                              | 
| 1996        | 544                              | 
| 1997        | 645                              | 
| 1998        | 887                              | 
| 1999        | 1047                             | 
| 2000        | 872                              | 
| 2001        | 638                              | 
| 2002        | 633                              | 
```