# 2015 Dialysis AR BSI TABLE

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-dialysis-ar-bsi-table) |
| Metadata | [Link](https://data.oregon.gov/api/views/4wzc-acdn) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/4wzc-acdn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/4wzc-acdn/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 4wzc-acdn |
| Name | 2015 Dialysis AR BSI TABLE |
| Attribution | Oregon HAI Program |
| Category | Health & Human Services |
| Tags | 2015 hai report |
| Created | 2016-07-05T15:42:08Z |
| Publication Date | 2016-07-25T17:52:59Z |

## Description

Access-related bloodstream infections at dialysis centers

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| Yes      | series tag     | facility_name                       | Facility Name                       | text      | text        |
| Yes      | series tag     | access_type                         | Access Type                         | text      | text        |
| Yes      | numeric metric | ar_bsi_count                        | AR-BSI Count                        | number    | number      |
| Yes      | numeric metric | patient_months                      | Patient Months                      | number    | number      |
| Yes      | numeric metric | ar_bsi_100_pt_months                | AR-BSI/100 Pt. Months               | number    | number      |
| Yes      | numeric metric | national_ar_bsi_mean                | National AR-BSI Mean                | number    | number      |
| Yes      | series tag     | comparison_interpretation           | Comparison Interpretation           | text      | text        |
| Yes      | series tag     | sir_icon                            | SIR Icon                            | photo     | photo       |
| Yes      | numeric metric | percentile_on_national_distribution | Percentile on National Distribution | number    | number      |
| Yes      | series tag     | county                              | County                              | text      | text        |
| Yes      | series tag     | hppregion                           | HPPRegion                           | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4wzc-acdn d:2015-01-01T00:00:00.000Z t:comparison_interpretation=n/a t:facility_name="NOBLE WOODS DIALYSIS CLINIC" t:county=WASHINGTON t:access_type="Nontunneled Central Line" t:hppregion=Region1 m:patient_months=0 m:ar_bsi_count=0 m:national_ar_bsi_mean=2.18

series e:4wzc-acdn d:2015-01-01T00:00:00.000Z t:comparison_interpretation=n/a t:facility_name="FMC LEBANON" t:county=LINN t:access_type="Nontunneled Central Line" t:hppregion=Region2 m:patient_months=0 m:ar_bsi_count=0 m:national_ar_bsi_mean=2.18

series e:4wzc-acdn d:2015-01-01T00:00:00.000Z t:comparison_interpretation=n/a t:facility_name="FMC NEWPORT" t:county=LINCOLN t:access_type="Other Access" t:hppregion=Region2 m:patient_months=0 m:ar_bsi_count=0
```

## Meta Commands

```ls
metric m:ar_bsi_count p:integer l:"AR-BSI Count" t:dataTypeName=number

metric m:patient_months p:integer l:"Patient Months" t:dataTypeName=number

metric m:ar_bsi_100_pt_months p:float l:"AR-BSI/100 Pt. Months" t:dataTypeName=number

metric m:national_ar_bsi_mean p:float l:"National AR-BSI Mean" t:dataTypeName=number

metric m:percentile_on_national_distribution p:integer l:"Percentile on National Distribution" t:dataTypeName=number

entity e:4wzc-acdn l:"2015 Dialysis AR BSI TABLE" t:attribution="Oregon HAI Program" t:url=https://data.oregon.gov/api/views/4wzc-acdn

property e:4wzc-acdn t:meta.view v:id=4wzc-acdn v:category="Health & Human Services" v:averageRating=0 v:name="2015 Dialysis AR BSI TABLE" v:attribution="Oregon HAI Program"

property e:4wzc-acdn t:meta.view.owner v:id=jsgg-5kv8 v:screenName="Lisa Takeuchi" v:displayName="Lisa Takeuchi"

property e:4wzc-acdn t:meta.view.tableauthor v:id=jsgg-5kv8 v:screenName="Lisa Takeuchi" v:roleName=editor v:displayName="Lisa Takeuchi"
```

## Top Records

```ls
| facility_name                    | access_type              | ar_bsi_count | patient_months | ar_bsi_100_pt_months | national_ar_bsi_mean | comparison_interpretation | sir_icon | percentile_on_national_distribution | county     | hppregion | 
| ================================ | ======================== | ============ | ============== | ==================== | ==================== | ========================= | ======== | =================================== | ========== | ========= | 
| NOBLE WOODS DIALYSIS CLINIC      | Nontunneled Central Line | 0            | 0              |                      | 2.18                 | n/a                       |          |                                     | WASHINGTON | Region1   | 
| FMC LEBANON                      | Nontunneled Central Line | 0            | 0              |                      | 2.18                 | n/a                       |          |                                     | LINN       | Region2   | 
| FMC NEWPORT                      | Other Access             | 0            | 0              |                      |                      | n/a                       |          |                                     | LINCOLN    | Region2   | 
| HILLTOP DIALYSIS                 | Other Access             | 0            | 0              |                      |                      | n/a                       |          |                                     | CLACKAMAS  | Region1   | 
| PNRS/THC RAINES DIALYSIS CENTER  | Other Access             | 0            | 0              |                      |                      | n/a                       |          |                                     | WASHINGTON | Region1   | 
| FMC SPRINGFIELD                  | Nontunneled Central Line | 0            | 0              |                      | 2.18                 | n/a                       |          |                                     | LANE       | Region3   | 
| PNRS NEWBERG DIALYSIS CENTER     | Nontunneled Central Line | 0            | 0              |                      | 2.18                 | n/a                       |          |                                     | YAMHILL    | Region2   | 
| MCMINNVILLE DIALYSIS             | Nontunneled Central Line | 0            | 0              |                      | 2.18                 | n/a                       |          |                                     | YAMHILL    | Region2   | 
| PNRS NORTH COAST DIALYSIS CLINIC | Nontunneled Central Line | 0            | 0              |                      | 2.18                 | n/a                       |          |                                     | YAMHILL    | Region2   | 
| FMC WEST SALEM                   | Nontunneled Central Line | 0            | 0              |                      | 2.18                 | n/a                       |          |                                     | POLK       | Region1   | 
```