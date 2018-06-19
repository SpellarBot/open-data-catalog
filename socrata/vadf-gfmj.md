# 2015 Dialysis AR BSI TABLE for MAP

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-dialysis-ar-bsi-table-for-map) |
| Metadata | [Link](https://data.oregon.gov/api/views/vadf-gfmj) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/vadf-gfmj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/vadf-gfmj/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | vadf-gfmj |
| Name | 2015 Dialysis AR BSI TABLE for MAP |
| Attribution | Oregon HAI Program |
| Category | Health & Human Services |
| Created | 2016-07-05T15:45:46Z |
| Publication Date | 2016-07-05T17:20:11Z |

## Description

Combined access-related bloodstream infections at dialysis centers

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | facility_name             | Facility Name             | text      | text        |
| Yes      | numeric metric | ar_bsi_count              | AR-BSI Count              | number    | number      |
| Yes      | numeric metric | patient_months            | Patient Months            | number    | number      |
| Yes      | numeric metric | ar_bsi_100_pt_months      | AR-BSI/100 Pt. Months     | number    | number      |
| Yes      | numeric metric | national_ar_bsi_mean      | National AR-BSI Mean      | number    | number      |
| Yes      | series tag     | comparison_interpretation | Comparison Interpretation | text      | text        |
| Yes      | series tag     | sir_icon                  | SIR Icon                  | photo     | photo       |
| Yes      | series tag     | county                    | County                    | text      | text        |
| Yes      | series tag     | hppregion                 | HPPRegion                 | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vadf-gfmj d:2015-01-01T00:00:00.000Z t:comparison_interpretation="Better: fewer infections" t:facility_name="BLUE MOUNTAIN KIDNEY CENTER" t:county=UMATILLA t:hppregion=Region9 t:sir_icon=825f4470-2366-4aa6-9f71-a0b466bae579 m:patient_months=276 m:ar_bsi_count=0 m:national_ar_bsi_mean=0.88 m:ar_bsi_100_pt_months=0

series e:vadf-gfmj d:2015-01-01T00:00:00.000Z t:comparison_interpretation="Better: statistically fewer infections" t:facility_name="FMC ALBANY" t:county=LINN t:hppregion=Region2 t:sir_icon=35b330c9-d73c-4192-b207-b3ef193fcbba m:patient_months=631 m:ar_bsi_count=1 m:national_ar_bsi_mean=0.88 m:ar_bsi_100_pt_months=0.16

series e:vadf-gfmj d:2015-01-01T00:00:00.000Z t:comparison_interpretation="Better: statistically fewer infections" t:facility_name="FMC BEND" t:county=DESCHUTES t:hppregion=Region7 t:sir_icon=4afabc81-3c40-46f8-9a5f-28e6c349e51f m:patient_months=771 m:ar_bsi_count=1 m:national_ar_bsi_mean=0.88 m:ar_bsi_100_pt_months=0.13
```

## Meta Commands

```ls
metric m:ar_bsi_count p:integer l:"AR-BSI Count" t:dataTypeName=number

metric m:patient_months p:integer l:"Patient Months" t:dataTypeName=number

metric m:ar_bsi_100_pt_months p:float l:"AR-BSI/100 Pt. Months" t:dataTypeName=number

metric m:national_ar_bsi_mean p:float l:"National AR-BSI Mean" t:dataTypeName=number

entity e:vadf-gfmj l:"2015 Dialysis AR BSI TABLE for MAP" t:attribution="Oregon HAI Program" t:url=https://data.oregon.gov/api/views/vadf-gfmj

property e:vadf-gfmj t:meta.view v:id=vadf-gfmj v:category="Health & Human Services" v:averageRating=0 v:name="2015 Dialysis AR BSI TABLE for MAP" v:attribution="Oregon HAI Program"

property e:vadf-gfmj t:meta.view.owner v:id=jsgg-5kv8 v:screenName="Lisa Takeuchi" v:displayName="Lisa Takeuchi"

property e:vadf-gfmj t:meta.view.tableauthor v:id=jsgg-5kv8 v:screenName="Lisa Takeuchi" v:roleName=editor v:displayName="Lisa Takeuchi"
```

## Top Records

```ls
| facility_name                    | ar_bsi_count | patient_months | ar_bsi_100_pt_months | national_ar_bsi_mean | comparison_interpretation              | sir_icon                             | county    | hppregion | 
| ================================ | ============ | ============== | ==================== | ==================== | ====================================== | ==================================== | ========= | ========= | 
| BLUE MOUNTAIN KIDNEY CENTER      | 0            | 276            | 0.00                 | 0.88                 | Better: fewer infections               | 825f4470-2366-4aa6-9f71-a0b466bae579 | UMATILLA  | Region9   | 
| FMC ALBANY                       | 1            | 631            | 0.16                 | 0.88                 | Better: statistically fewer infections | 35b330c9-d73c-4192-b207-b3ef193fcbba | LINN      | Region2   | 
| FMC BEND                         | 1            | 771            | 0.13                 | 0.88                 | Better: statistically fewer infections | 4afabc81-3c40-46f8-9a5f-28e6c349e51f | DESCHUTES | Region7   | 
| FMC CLACKAMAS                    | 5            | 1004           | 0.50                 | 0.88                 | Better: fewer infections               | 1d22e5b2-62b0-45e5-a615-41d0f15d8363 | CLACKAMAS | Region1   | 
| FMC COOS BAY                     | 4            | 1038           | 0.39                 | 0.88                 | Better: fewer infections               | 435faf35-44f7-4323-a9c7-3886ddb36d11 | COOS      | Region3   | 
| FMC CORVALLIS OREGON             | 0            | 441            | 0.00                 | 0.88                 | Better: statistically fewer infections | 41170347-afff-49f3-8cba-3f9fcb04f510 | BENTON    | Region2   | 
| FMC DIALYSIS SERVICES OF MT HOOD | 3            | 970            | 0.31                 | 0.88                 | Better: statistically fewer infections | 9ef4f749-50e7-47e7-b9e8-9f89f271ee40 | MULTNOMAH | Region1   | 
| FMC EUGENE                       | 5            | 1479           | 0.34                 | 0.88                 | Better: statistically fewer infections | 95215dda-b9cf-4217-9e01-b72920c71ce7 | LANE      | Region3   | 
| FMC LEBANON                      | 2            | 651            | 0.31                 | 0.88                 | Better: fewer infections               | 9acad8f2-80f3-4771-a214-42b8e821b393 | LINN      | Region2   | 
| FMC MAYWOOD PARK                 | 2            | 619            | 0.32                 | 0.88                 | Better: fewer infections               | 56400b4f-d5a0-4bb3-9a1e-5043093487ae | MULTNOMAH | Region1   | 
```