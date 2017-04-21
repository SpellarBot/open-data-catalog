# Hospital Inpatient Discharges by DRG, U.S., FY2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hospital-inpatient-discharges-by-drg-u-s-fy2011-a04a0) |
| Metadata | [Link](https://data.wa.gov/api/views/swuj-ccgu) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/swuj-ccgu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/swuj-ccgu/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | swuj-ccgu |
| Name | Hospital Inpatient Discharges by DRG, U.S., FY2011 |
| Category | Health |
| Tags | hospital inpatient discharges drg |
| Created | 2013-06-20T15:48:02Z |
| Publication Date | 2013-06-20T20:21:36Z |

## Description

This table shows the low, high, and average percents of discharges related to a referenced DRG (diagnosis-related group) as a share of the total discharges from the top 100 common DRGs for hospitals in the United States. The source of data for this table is FY2011 hospital charges file provided by the Centers for Medicare and Medicaid Services (CMS).

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                    | Data Type | Render Type |
| ======== | ============== | ==================================== | ======================================= | ========= | =========== |
| Yes      | series tag     | referenced_drg                       | Referenced DRG                          | html      | html        |
| Yes      | series tag     | drg_definition                       | DRG Definition                          | text      | text        |
| Yes      | series tag     | region                               | Region                                  | text      | text        |
| Yes      | numeric metric | number_of_hospitals                  | Number of Hospitals*                    | number    | number      |
| Yes      | numeric metric | total_discharges                     | Total Discharges*                       | number    | number      |
| Yes      | numeric metric | referenced_drg_discharges            | Referenced DRG Discharges*              | number    | number      |
| Yes      | numeric metric | lowest_of_referenced_drg_discharges  | Lowest % of Referenced DRG Discharges*  | percent   | percent     |
| Yes      | numeric metric | highest_of_referenced_drg_discharges | Highest % of Referenced DRG Discharges* | percent   | percent     |
| Yes      | numeric metric | average_of_referenced_drg_discharges | Average % of Referenced DRG Discharges* | percent   | percent     |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:swuj-ccgu d:2011-01-01T00:00:00.000Z t:region=US t:drg_definition="SEIZURES W/O MCC" t:referenced_drg=101 m:highest_of_referenced_drg_discharges=7.6 m:total_discharges=5702677 m:average_of_referenced_drg_discharges=0.9 m:number_of_hospitals=1580 m:referenced_drg_discharges=48854 m:lowest_of_referenced_drg_discharges=0.2

series e:swuj-ccgu d:2011-01-01T00:00:00.000Z t:region=US t:drg_definition=DYSEQUILIBRIUM t:referenced_drg=149 m:highest_of_referenced_drg_discharges=7.4 m:total_discharges=4246449 m:average_of_referenced_drg_discharges=0.6 m:number_of_hospitals=982 m:referenced_drg_discharges=23427 m:lowest_of_referenced_drg_discharges=0.1

series e:swuj-ccgu d:2011-01-01T00:00:00.000Z t:region=US t:drg_definition="PULMONARY EMBOLISM W/O MCC" t:referenced_drg=176 m:highest_of_referenced_drg_discharges=5.5 m:total_discharges=5219223 m:average_of_referenced_drg_discharges=0.6 m:number_of_hospitals=1387 m:referenced_drg_discharges=32042 m:lowest_of_referenced_drg_discharges=0.2
```

## Meta Commands

```ls
metric m:number_of_hospitals p:integer l:"Number of Hospitals*" d:"Number of hospitals with the referenced DRG" t:dataTypeName=number

metric m:total_discharges p:integer l:"Total Discharges*" d:"Total discharges for the most common 100 DRGs for hospitals with the referenced DRG" t:dataTypeName=number

metric m:referenced_drg_discharges p:integer l:"Referenced DRG Discharges*" d:"Discharges related to the referenced DRG among hospitals with this DRG" t:dataTypeName=number

metric m:lowest_of_referenced_drg_discharges p:float l:"Lowest % of Referenced DRG Discharges*" d:"Lowest percent found for discharges related to the referenced DRG of the total discharges for the 100 most common DRGs among hospitals with the referenced DRG" t:dataTypeName=percent

metric m:highest_of_referenced_drg_discharges p:float l:"Highest % of Referenced DRG Discharges*" d:"Highest percent found for discharges related to the referenced DRG of the total discharges for the 100 most common DRGs among hospitals with the referenced DRG" t:dataTypeName=percent

metric m:average_of_referenced_drg_discharges p:float l:"Average % of Referenced DRG Discharges*" d:"Average percent found for discharges related to the referenced DRG of the total discharges for the 100 most common DRGs among hospitals with the referenced DRG" t:dataTypeName=percent

entity e:swuj-ccgu l:"Hospital Inpatient Discharges by DRG, U.S., FY2011" t:url=https://data.wa.gov/api/views/swuj-ccgu

property e:swuj-ccgu t:meta.view v:id=swuj-ccgu v:category=Health v:averageRating=0 v:name="Hospital Inpatient Discharges by DRG, U.S., FY2011"

property e:swuj-ccgu t:meta.view.owner v:id=8ghr-nmpd v:screenName="Wei Yen" v:displayName="Wei Yen"

property e:swuj-ccgu t:meta.view.tableauthor v:id=8ghr-nmpd v:screenName="Wei Yen" v:roleName=publisher v:displayName="Wei Yen"
```

## Top Records

```ls
| referenced_drg | drg_definition                                   | region | number_of_hospitals | total_discharges | referenced_drg_discharges | lowest_of_referenced_drg_discharges | highest_of_referenced_drg_discharges | average_of_referenced_drg_discharges | 
| ============== | ================================================ | ====== | =================== | ================ | ========================= | =================================== | ==================================== | ==================================== | 
| 101            | SEIZURES W/O MCC                                 | US     | 1580                | 5702677          | 48854                     | 0.2                                 | 7.6                                  | 0.9                                  | 
| 149            | DYSEQUILIBRIUM                                   | US     | 982                 | 4246449          | 23427                     | 0.1                                 | 7.4                                  | 0.6                                  | 
| 176            | PULMONARY EMBOLISM W/O MCC                       | US     | 1387                | 5219223          | 32042                     | 0.2                                 | 5.5                                  | 0.6                                  | 
| 177            | RESPIRATORY INFECTIONS & INFLAMMATIONS W MCC     | US     | 1879                | 6062272          | 66660                     | 0.2                                 | 22.0                                 | 1.1                                  | 
| 178            | RESPIRATORY INFECTIONS & INFLAMMATIONS W CC      | US     | 1938                | 6018343          | 56100                     | 0.2                                 | 50.0                                 | 0.9                                  | 
| 189            | PULMONARY EDEMA & RESPIRATORY FAILURE            | US     | 2078                | 6234455          | 95099                     | 0.2                                 | 23.0                                 | 1.5                                  | 
| 190            | CHRONIC OBSTRUCTIVE PULMONARY DISEASE W MCC      | US     | 2685                | 6791761          | 149677                    | 0.3                                 | 54.0                                 | 2.2                                  | 
| 191            | CHRONIC OBSTRUCTIVE PULMONARY DISEASE W CC       | US     | 2692                | 6794007          | 148491                    | 0.4                                 | 52.0                                 | 2.2                                  | 
| 192            | CHRONIC OBSTRUCTIVE PULMONARY DISEASE W/O CC/MCC | US     | 2640                | 6630433          | 114790                    | 0.2                                 | 100.0                                | 1.7                                  | 
| 193            | SIMPLE PNEUMONIA & PLEURISY W MCC                | US     | 2550                | 6734330          | 127989                    | 0.5                                 | 37.0                                 | 1.9                                  | 
```