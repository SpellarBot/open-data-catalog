# 2015 Dialysis BSI TABLE MAP

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-dialysis-bsi-table-map) |
| Metadata | [Link](https://data.oregon.gov/api/views/3bu4-7bnc) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/3bu4-7bnc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/3bu4-7bnc/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 3bu4-7bnc |
| Name | 2015 Dialysis BSI TABLE MAP |
| Attribution | Oregon HAI Program |
| Category | Health & Human Services |
| Created | 2016-07-05T15:56:48Z |
| Publication Date | 2016-07-05T18:49:55Z |

## Description

Combined bloodstream infections at dialysis centers

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | facility_name             | Facility Name             | text      | text        |
| Yes      | numeric metric | bsi_count                 | BSI Count                 | number    | number      |
| Yes      | numeric metric | patient_months            | Patient Months            | number    | number      |
| Yes      | numeric metric | bsi_100_pt_months         | BSI/100 Pt. Months        | number    | number      |
| Yes      | numeric metric | national_bsi_mean         | National BSI Mean         | number    | number      |
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
series e:3bu4-7bnc d:2015-01-01T00:00:00.000Z t:comparison_interpretation="Better: fewer infections" t:facility_name="BLUE MOUNTAIN KIDNEY CENTER" t:county=UMATILLA t:hppregion=Region9 t:sir_icon=7cbe7acb-8e1b-449e-b3ef-8698a259df71 m:patient_months=276 m:national_bsi_mean=1.27 m:bsi_count=1 m:bsi_100_pt_months=0.36

series e:3bu4-7bnc d:2015-01-01T00:00:00.000Z t:comparison_interpretation="Better: statistically fewer infections" t:facility_name="FMC ALBANY" t:county=LINN t:hppregion=Region2 t:sir_icon=1b5f14c3-9567-4f19-a4af-43e3fc595292 m:patient_months=631 m:national_bsi_mean=1.27 m:bsi_count=1 m:bsi_100_pt_months=0.16

series e:3bu4-7bnc d:2015-01-01T00:00:00.000Z t:comparison_interpretation="Better: statistically fewer infections" t:facility_name="FMC BEND" t:county=DESCHUTES t:hppregion=Region7 t:sir_icon=a4138715-3510-4ed0-9dad-4b3492d623ac m:patient_months=771 m:national_bsi_mean=1.27 m:bsi_count=1 m:bsi_100_pt_months=0.13
```

## Meta Commands

```ls
metric m:bsi_count p:integer l:"BSI Count" t:dataTypeName=number

metric m:patient_months p:integer l:"Patient Months" t:dataTypeName=number

metric m:bsi_100_pt_months p:float l:"BSI/100 Pt. Months" t:dataTypeName=number

metric m:national_bsi_mean p:float l:"National BSI Mean" t:dataTypeName=number

entity e:3bu4-7bnc l:"2015 Dialysis BSI TABLE MAP" t:attribution="Oregon HAI Program" t:url=https://data.oregon.gov/api/views/3bu4-7bnc

property e:3bu4-7bnc t:meta.view v:id=3bu4-7bnc v:category="Health & Human Services" v:averageRating=0 v:name="2015 Dialysis BSI TABLE MAP" v:attribution="Oregon HAI Program"

property e:3bu4-7bnc t:meta.view.owner v:id=jsgg-5kv8 v:screenName="Lisa Takeuchi" v:displayName="Lisa Takeuchi"

property e:3bu4-7bnc t:meta.view.tableauthor v:id=jsgg-5kv8 v:screenName="Lisa Takeuchi" v:roleName=editor v:displayName="Lisa Takeuchi"
```

## Top Records

```ls
| facility_name                    | bsi_count | patient_months | bsi_100_pt_months | national_bsi_mean | comparison_interpretation              | sir_icon                             | county    | hppregion | 
| ================================ | ========= | ============== | ================= | ================= | ====================================== | ==================================== | ========= | ========= | 
| BLUE MOUNTAIN KIDNEY CENTER      | 1         | 276            | 0.36              | 1.27              | Better: fewer infections               | 7cbe7acb-8e1b-449e-b3ef-8698a259df71 | UMATILLA  | Region9   | 
| FMC ALBANY                       | 1         | 631            | 0.16              | 1.27              | Better: statistically fewer infections | 1b5f14c3-9567-4f19-a4af-43e3fc595292 | LINN      | Region2   | 
| FMC BEND                         | 1         | 771            | 0.13              | 1.27              | Better: statistically fewer infections | a4138715-3510-4ed0-9dad-4b3492d623ac | DESCHUTES | Region7   | 
| FMC CLACKAMAS                    | 5         | 1004           | 0.50              | 1.27              | Better: statistically fewer infections | 3d468625-616c-47e6-b525-867fc4398a7f | CLACKAMAS | Region1   | 
| FMC COOS BAY                     | 7         | 1038           | 0.67              | 1.27              | Better: fewer infections               | 61d44432-509e-4f41-8635-b68659b34640 | COOS      | Region3   | 
| FMC CORVALLIS OREGON             | 0         | 441            | 0.00              | 1.27              | Better: statistically fewer infections | c6092abd-1593-41b4-8b30-986d4f81ce77 | BENTON    | Region2   | 
| FMC DIALYSIS SERVICES OF MT HOOD | 4         | 970            | 0.41              | 1.27              | Better: statistically fewer infections | 29e562d8-963e-4f0c-ae75-6287b798cd88 | MULTNOMAH | Region1   | 
| FMC EUGENE                       | 10        | 1479           | 0.68              | 1.27              | Better: statistically fewer infections | 62459700-5ef9-4e5d-bf50-70e015ae5be3 | LANE      | Region3   | 
| FMC LEBANON                      | 2         | 651            | 0.31              | 1.27              | Better: statistically fewer infections | 44b30f63-41da-47c2-8230-db75f076483d | LINN      | Region2   | 
| FMC MAYWOOD PARK                 | 3         | 619            | 0.48              | 1.27              | Better: fewer infections               | f81d47a1-a316-49ee-bd09-36880e668ec0 | MULTNOMAH | Region1   | 
```