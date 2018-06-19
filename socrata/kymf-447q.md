# 2015 Dialysis BSI TABLE

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-dialysis-bsi-table) |
| Metadata | [Link](https://data.oregon.gov/api/views/kymf-447q) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/kymf-447q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/kymf-447q/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | kymf-447q |
| Name | 2015 Dialysis BSI TABLE |
| Attribution | Oregon HAI Program |
| Category | Health & Human Services |
| Tags | 2015 hai report |
| Created | 2016-07-05T15:54:26Z |
| Publication Date | 2016-07-25T17:53:14Z |

## Description

Bloodstream infections at dialysis centers

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| Yes      | series tag     | facility_name                       | Facility Name                       | text      | text        |
| Yes      | series tag     | access_type                         | Access Type                         | text      | text        |
| Yes      | numeric metric | bsi_count                           | BSI Count                           | number    | number      |
| Yes      | numeric metric | patient_months                      | Patient Months                      | number    | number      |
| Yes      | numeric metric | bsi_100_pt_months                   | BSI/100 Pt. Months                  | number    | number      |
| Yes      | numeric metric | national_bsi_mean                   | National BSI Mean                   | number    | number      |
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
series e:kymf-447q d:2015-01-01T00:00:00.000Z t:comparison_interpretation=n/a t:facility_name="FMC EUGENE" t:county=LANE t:access_type="Nontunneled Central Line" t:hppregion=Region3 m:patient_months=0 m:national_bsi_mean=2.78 m:bsi_count=0

series e:kymf-447q d:2015-01-01T00:00:00.000Z t:comparison_interpretation=n/a t:facility_name="FOUR RIVERS DIALYSIS CENTER" t:county=MALHEUR t:access_type="Other Access" t:hppregion=Region9 m:patient_months=0 m:bsi_count=0

series e:kymf-447q d:2015-01-01T00:00:00.000Z t:comparison_interpretation=n/a t:facility_name="NOBLE WOODS DIALYSIS CLINIC" t:county=WASHINGTON t:access_type="Nontunneled Central Line" t:hppregion=Region1 m:patient_months=0 m:national_bsi_mean=2.78 m:bsi_count=0
```

## Meta Commands

```ls
metric m:bsi_count p:integer l:"BSI Count" t:dataTypeName=number

metric m:patient_months p:integer l:"Patient Months" t:dataTypeName=number

metric m:bsi_100_pt_months p:float l:"BSI/100 Pt. Months" t:dataTypeName=number

metric m:national_bsi_mean p:float l:"National BSI Mean" t:dataTypeName=number

metric m:percentile_on_national_distribution p:integer l:"Percentile on National Distribution" t:dataTypeName=number

entity e:kymf-447q l:"2015 Dialysis BSI TABLE" t:attribution="Oregon HAI Program" t:url=https://data.oregon.gov/api/views/kymf-447q

property e:kymf-447q t:meta.view v:id=kymf-447q v:category="Health & Human Services" v:averageRating=0 v:name="2015 Dialysis BSI TABLE" v:attribution="Oregon HAI Program"

property e:kymf-447q t:meta.view.owner v:id=jsgg-5kv8 v:screenName="Lisa Takeuchi" v:displayName="Lisa Takeuchi"

property e:kymf-447q t:meta.view.tableauthor v:id=jsgg-5kv8 v:screenName="Lisa Takeuchi" v:roleName=editor v:displayName="Lisa Takeuchi"
```

## Top Records

```ls
| facility_name                  | access_type              | bsi_count | patient_months | bsi_100_pt_months | national_bsi_mean | comparison_interpretation | sir_icon | percentile_on_national_distribution | county     | hppregion | 
| ============================== | ======================== | ========= | ============== | ================= | ================= | ========================= | ======== | =================================== | ========== | ========= | 
| FMC EUGENE                     | Nontunneled Central Line | 0         | 0              |                   | 2.78              | n/a                       |          |                                     | LANE       | Region3   | 
| FOUR RIVERS DIALYSIS CENTER    | Other Access             | 0         | 0              |                   |                   | n/a                       |          |                                     | MALHEUR    | Region9   | 
| NOBLE WOODS DIALYSIS CLINIC    | Nontunneled Central Line | 0         | 0              |                   | 2.78              | n/a                       |          |                                     | WASHINGTON | Region1   | 
| PNRS MCMINNVILLE KIDNEY CENTER | Other Access             | 0         | 0              |                   |                   | n/a                       |          |                                     | MULTNOMAH  | Region1   | 
| SALEM NORTH DIALYSIS           | Nontunneled Central Line | 0         | 0              |                   | 2.78              | n/a                       |          |                                     | MARION     | Region2   | 
| LAKE ROAD DIALYSIS CENTER      | Other Access             | 0         | 0              |                   |                   | n/a                       |          |                                     | CLACKAMAS  | Region1   | 
| FMC MAYWOOD PARK               | Other Access             | 0         | 0              |                   |                   | n/a                       |          |                                     | MULTNOMAH  | Region1   | 
| REDWOOD DIALYSIS               | Nontunneled Central Line | 0         | 0              |                   | 2.78              | n/a                       |          |                                     | HOOD RIVER | Region6   | 
| MADRAS DIALYSIS                | Nontunneled Central Line | 0         | 0              |                   | 2.78              | n/a                       |          |                                     | JEFFERSON  | Region7   | 
| NE SALEM DIALYSIS              | Other Access             | 0         | 0              |                   |                   | n/a                       |          |                                     | MARION     | Region2   | 
```