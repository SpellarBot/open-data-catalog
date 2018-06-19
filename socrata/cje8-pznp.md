# ARR Household Hazardous Waste Totals Comparison of Fiscal Years 2010-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arr-household-hazardous-waste-totals-comparison-of-fiscal-years-2010-2015) |
| Metadata | [Link](https://data.austintexas.gov/api/views/cje8-pznp) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/cje8-pznp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/cje8-pznp/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | cje8-pznp |
| Name | ARR Household Hazardous Waste Totals Comparison of Fiscal Years 2010-2015 |
| Tags | household, hazardous, waste, participation, resource, recovery, arr |
| Created | 2015-09-14T18:35:38Z |
| Publication Date | 2015-09-15T18:25:14Z |

## Description

Comparison of Disposal/ Recycling Costs, Weight Collected and Participation in the Household Hazardous Waste program for Fiscal Years 2010-2015.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                     | Data Type | Render Type |
| ======== | ============== | ======================= | ======================== | ========= | =========== |
| Yes      | series tag     | description_fiscal_year | Description/ Fiscal Year | text      | text        |
| Yes      | numeric metric | oct_14                  | Oct-14                   | number    | number      |
| Yes      | numeric metric | nov_14                  | Nov-14                   | number    | number      |
| Yes      | numeric metric | dec_14                  | Dec-14                   | number    | number      |
| Yes      | numeric metric | jan_15                  | Jan-15                   | number    | number      |
| Yes      | numeric metric | feb_15                  | Feb-15                   | number    | number      |
| Yes      | numeric metric | mar_15                  | Mar-15                   | number    | number      |
| Yes      | numeric metric | apr_15                  | Apr-15                   | number    | number      |
| Yes      | numeric metric | may_15                  | May-15                   | number    | number      |
| Yes      | numeric metric | jun_15                  | Jun-15                   | number    | number      |
| Yes      | numeric metric | jul_15                  | Jul-15                   | number    | number      |
| Yes      | numeric metric | aug_15                  | Aug-15                   | number    | number      |
| Yes      | numeric metric | sep_15                  | Sep-15                   | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cje8-pznp d:2010-01-01T00:00:00.000Z t:description_fiscal_year="FY 14-15" m:nov_14=13197 m:sep_15=0 m:oct_14=32577.5 m:jul_15=41907.75 m:mar_15=29141.5 m:may_15=27680.25 m:aug_15=0 m:jan_15=32131.6 m:jun_15=30816.25 m:dec_14=21551.25 m:feb_15=29199.25 m:apr_15=34421.25

series e:cje8-pznp d:2010-01-01T00:00:00.000Z t:description_fiscal_year="FY 13-14" m:nov_14=29212.75 m:sep_15=19683.75 m:oct_14=32034 m:jul_15=31763.1 m:mar_15=19732 m:may_15=35203.57 m:aug_15=31967.63 m:jan_15=24299.75 m:jun_15=27363.6 m:dec_14=17736.54 m:feb_15=19586.11 m:apr_15=30487.95

series e:cje8-pznp d:2010-01-01T00:00:00.000Z t:description_fiscal_year="FY 12-13" m:nov_14=28506.44 m:sep_15=9988 m:oct_14=22533.25 m:jul_15=27203.49 m:mar_15=32633.75 m:may_15=39624.82 m:aug_15=29730.02 m:jan_15=41334 m:jun_15=23723.5 m:dec_14=19490 m:feb_15=24691.74 m:apr_15=30568
```

## Meta Commands

```ls
metric m:oct_14 p:float l:Oct-14 t:dataTypeName=number

metric m:nov_14 p:float l:Nov-14 t:dataTypeName=number

metric m:dec_14 p:float l:Dec-14 t:dataTypeName=number

metric m:jan_15 p:float l:Jan-15 t:dataTypeName=number

metric m:feb_15 p:double l:Feb-15 t:dataTypeName=number

metric m:mar_15 p:float l:Mar-15 t:dataTypeName=number

metric m:apr_15 p:double l:Apr-15 t:dataTypeName=number

metric m:may_15 p:float l:May-15 t:dataTypeName=number

metric m:jun_15 p:double l:Jun-15 t:dataTypeName=number

metric m:jul_15 p:double l:Jul-15 t:dataTypeName=number

metric m:aug_15 p:double l:Aug-15 t:dataTypeName=number

metric m:sep_15 p:double l:Sep-15 t:dataTypeName=number

entity e:cje8-pznp l:"ARR Household Hazardous Waste Totals Comparison of Fiscal Years 2010-2015" t:url=https://data.austintexas.gov/api/views/cje8-pznp

property e:cje8-pznp t:meta.view v:id=cje8-pznp v:averageRating=0 v:name="ARR Household Hazardous Waste Totals Comparison of Fiscal Years 2010-2015"

property e:cje8-pznp t:meta.view.owner v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:displayName=erin.benoit@austintexas.gov

property e:cje8-pznp t:meta.view.tableauthor v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:roleName=editor v:displayName=erin.benoit@austintexas.gov
```

## Top Records

```ls
| description_fiscal_year | oct_14       | nov_14      | dec_14      | jan_15     | feb_15      | mar_15       | apr_15        | may_15      | jun_15      | jul_15      | aug_15      | sep_15        | 
| ======================= | ============ | =========== | =========== | ========== | =========== | ============ | ============= | =========== | =========== | =========== | =========== | ============= | 
| FY 14-15                | 32577.5      | 13197       | 21551.25    | 32131.6    | 29199.25    | 29141.5      | 34421.25      | 27680.25    | 30816.25    | 41907.75    | 0           | 0             | 
| FY 13-14                | 32034        | 29212.75    | 17736.54    | 24299.75   | 19586.11    | 19732        | 30487.95      | 35203.57    | 27363.6     | 31763.1     | 31967.63    | 19683.75      | 
| FY 12-13                | 22533.25     | 28506.44    | 19490       | 41334      | 24691.74    | 32633.75     | 30568         | 39624.82    | 23723.5     | 27203.49    | 29730.02    | 9988          | 
| FY 11-12                | 28843.94     | 18548.24    | 27335       | 29922      | 28822       | 34145        | 25638.32      | 29625.94    | 40017.24    | 26629.1     | 19150.3     | 41334.22      | 
| FY 10-11                | 27674        | 30840.5     | 18079.05    | 25091.5    | 19309       | 31867        | 29805         | 27960       | 37068.1     | 27671.12    | 35387.06    | 23442         | 
| FY 12-13                | 96192.625    | 95838.49375 | 66805.34375 | 77288.3625 | 94969.40625 | 129500.60625 | 132876.5      | 124864.3375 | 119949.125  | 126640.7875 | 112197.25   | 54349         | 
| FY 11-12                | 108249.34375 | 80456.9375  | 90680.40625 | 103450     | 98333.46875 | 111650.31    | 105230.453125 | 120157.125  | 161936.13   | 88858.03125 | 92898.28125 | 122113.234375 | 
| FY 10-11                | 85386.5625   | 92385.125   | 71141       | 77956.94   | 63419.06    | 101544.93    | 124772.5      | 96052.5     | 144239.2625 | 85702.6275  | 99643.13    | 75158.44      | 
| FY 14-15                | 1260         | 1000        | 1232        | 1379       | 1287        | 1575         | 1984          | 1638        | 1964        | 2334        | 0           | 0             | 
| FY 13-14                | 1482         | 2045        | 813         | 1284       | 888         | 1368         | 2052          | 1587        | 1400        | 2041        | 1513        | 1452          | 
```