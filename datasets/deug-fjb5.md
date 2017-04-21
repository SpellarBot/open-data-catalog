# IDPH Births, by County, by Characteristics, 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-births-by-county-by-characteristics-2009-d21ea) |
| Metadata | [Link](https://data.illinois.gov/api/views/deug-fjb5) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/deug-fjb5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/deug-fjb5/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | deug-fjb5 |
| Name | IDPH Births, by County, by Characteristics, 2009 |
| Attribution | Illinois Center for Health Statistics |
| Tags | birth characteristics |
| Created | 2012-01-17T21:25:42Z |
| Publication Date | 2012-01-23T21:48:04Z |

## Description

Note:  The sum of certain variables may not equal the total due to unknown geography and/or demographics.

 *   Rate or percentage does not meet standards of reliability (numerator <10 or denominator <100)
-0-  Percentage zero corresponding to '0' in frequency column
**   Uknowns excluded from denominator when calculating percentage

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                     | Data Type | Render Type |
| ======== | ============== | ====================================== | ======================================== | ========= | =========== |
| Yes      | series tag     | county                                 | County                                   | text      | text        |
| Yes      | numeric metric | total_births                           | Total Births                             | number    | number      |
| Yes      | numeric metric | low_birth_weight                       | Low Birth Weight                         | number    | number      |
| Yes      | numeric metric | low_birth_weight_rate                  | Low Birth Weight Rate                    | percent   | percent     |
| Yes      | numeric metric | very_low_birth_weight                  | Very Low Birth Weight                    | number    | number      |
| Yes      | numeric metric | very_low_birth_weight_rate             | Very Low Birth Weight Rate               | percent   | percent     |
| Yes      | numeric metric | preterm                                | Preterm                                  | number    | number      |
| Yes      | numeric metric | preterm_rate                           | Preterm Rate                             | percent   | percent     |
| Yes      | numeric metric | adequate_prenatal_care_kotelchuck_     | Adequate Prenatal Care (Kotelchuck)      | number    | number      |
| Yes      | numeric metric | adequate_prenatal_care_kotelchuck_rate | Adequate Prenatal Care (Kotelchuck) Rate | percent   | percent     |
| Yes      | numeric metric | cesarean_section                       | Cesarean Section                         | number    | number      |
| Yes      | numeric metric | cesarean_section_rate                  | Cesarean Section Rate                    | percent   | percent     |
| Yes      | numeric metric | unmarried_mother                       | Unmarried Mother                         | number    | number      |
| Yes      | numeric metric | unmarried_mother_rate                  | Unmarried Mother Rate                    | percent   | percent     |
| Yes      | numeric metric | not_h_s_graduateage_20_                | Not H.S. GraduateAge 20+                 | number    | number      |
| Yes      | numeric metric | not_h_s_graduateage_20_rate            | Not H.S.GraduateAge 20+ Rate             | percent   | percent     |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:deug-fjb5 d:2009-01-01T00:00:00.000Z t:county=Adams m:low_birth_weight=64 m:cesarean_section=199 m:adequate_prenatal_care_kotelchuck_=730 m:not_h_s_graduateage_20_rate=8.8 m:very_low_birth_weight_rate=1.2 m:unmarried_mother=372 m:preterm=79 m:adequate_prenatal_care_kotelchuck_rate=92.1 m:preterm_rate=9.8 m:total_births=804 m:not_h_s_graduateage_20_=63 m:cesarean_section_rate=24.8 m:very_low_birth_weight=10 m:unmarried_mother_rate=46.3 m:low_birth_weight_rate=8

series e:deug-fjb5 d:2009-01-01T00:00:00.000Z t:county=Alexander m:unmarried_mother=81 m:low_birth_weight=15 m:preterm=15 m:cesarean_section=43 m:adequate_prenatal_care_kotelchuck_=52 m:preterm_rate=13.2 m:total_births=114 m:not_h_s_graduateage_20_=11 m:cesarean_section_rate=37.7 m:very_low_birth_weight=3 m:unmarried_mother_rate=71.1 m:low_birth_weight_rate=13.2

series e:deug-fjb5 d:2009-01-01T00:00:00.000Z t:county=Bond m:low_birth_weight=19 m:cesarean_section=68 m:adequate_prenatal_care_kotelchuck_=176 m:not_h_s_graduateage_20_rate=8.5 m:unmarried_mother=83 m:preterm=25 m:adequate_prenatal_care_kotelchuck_rate=88.9 m:preterm_rate=12.6 m:total_births=198 m:not_h_s_graduateage_20_=15 m:very_low_birth_weight=2 m:unmarried_mother_rate=41.9 m:cesarean_section_rate=34.3 m:low_birth_weight_rate=9.6
```

## Meta Commands

```ls
metric m:total_births p:integer l:"Total Births" t:dataTypeName=number

metric m:low_birth_weight p:integer l:"Low Birth Weight" t:dataTypeName=number

metric m:low_birth_weight_rate p:float l:"Low Birth Weight Rate" t:dataTypeName=percent

metric m:very_low_birth_weight p:integer l:"Very Low Birth Weight" t:dataTypeName=number

metric m:very_low_birth_weight_rate p:float l:"Very Low Birth Weight Rate" t:dataTypeName=percent

metric m:preterm p:integer l:Preterm t:dataTypeName=number

metric m:preterm_rate p:float l:"Preterm Rate" t:dataTypeName=percent

metric m:adequate_prenatal_care_kotelchuck_ p:integer l:"Adequate Prenatal Care (Kotelchuck)" t:dataTypeName=number

metric m:adequate_prenatal_care_kotelchuck_rate p:float l:"Adequate Prenatal Care (Kotelchuck) Rate" t:dataTypeName=percent

metric m:cesarean_section p:integer l:"Cesarean Section" t:dataTypeName=number

metric m:cesarean_section_rate p:float l:"Cesarean Section Rate" t:dataTypeName=percent

metric m:unmarried_mother p:integer l:"Unmarried Mother" t:dataTypeName=number

metric m:unmarried_mother_rate p:float l:"Unmarried Mother Rate" t:dataTypeName=percent

metric m:not_h_s_graduateage_20_ p:integer l:"Not H.S. GraduateAge 20+" t:dataTypeName=number

metric m:not_h_s_graduateage_20_rate p:float l:"Not H.S.GraduateAge 20+ Rate" t:dataTypeName=percent

entity e:deug-fjb5 l:"IDPH Births, by County, by Characteristics,  2009" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/deug-fjb5

property e:deug-fjb5 t:meta.view v:id=deug-fjb5 v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Births, by County, by Characteristics,  2009" v:attribution="Illinois Center for Health Statistics"

property e:deug-fjb5 t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:deug-fjb5 t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| county    | total_births | low_birth_weight | low_birth_weight_rate | very_low_birth_weight | very_low_birth_weight_rate | preterm | preterm_rate | adequate_prenatal_care_kotelchuck_ | adequate_prenatal_care_kotelchuck_rate | cesarean_section | cesarean_section_rate | unmarried_mother | unmarried_mother_rate | not_h_s_graduateage_20_ | not_h_s_graduateage_20_rate | 
| ========= | ============ | ================ | ===================== | ===================== | ========================== | ======= | ============ | ================================== | ====================================== | ================ | ===================== | ================ | ===================== | ======================= | =========================== | 
| Adams     | 804          | 64               | 8.0                   | 10                    | 1.2                        | 79      | 9.8          | 730                                | 92.1                                   | 199              | 24.8                  | 372              | 46.3                  | 63                      | 8.8                         | 
| Alexander | 114          | 15               | 13.2                  | 3                     |                            | 15      | 13.2         | 52                                 |                                        | 43               | 37.7                  | 81               | 71.1                  | 11                      |                             | 
| Bond      | 198          | 19               | 9.6                   | 2                     |                            | 25      | 12.6         | 176                                | 88.9                                   | 68               | 34.3                  | 83               | 41.9                  | 15                      | 8.5                         | 
| Boone     | 622          | 39               | 6.3                   | 5                     |                            | 59      | 9.5          | 442                                | 75.8                                   | 202              | 33.5                  | 223              | 35.9                  | 110                     | 19.6                        | 
| Brown     | 65           | 6                |                       | 0                     |                            | 7       |              | 58                                 |                                        | 14               |                       | 18               |                       | 8                       |                             | 
| Bureau    | 381          | 15               | 3.9                   | 2                     |                            | 19      | 5.0          | 328                                | 86.3                                   | 106              | 28.2                  | 157              | 41.2                  | 49                      | 14.4                        | 
| Calhoun   | 53           | 5                |                       | 0                     |                            | 4       |              | 46                                 |                                        | 11               |                       | 14               |                       | 5                       |                             | 
| Carroll   | 123          | 6                |                       | 0                     |                            | 13      | 10.6         | 76                                 |                                        | 34               | 28.3                  | 57               | 46.3                  | 6                       |                             | 
| Cass      | 164          | 12               | 7.3                   | 1                     |                            | 12      | 7.3          | 136                                | 82.9                                   | 50               | 31.3                  | 77               | 47.0                  | 35                      | 24.6                        | 
| Champaign | 2407         | 175              | 7.3                   | 30                    | 1.2                        | 202     | 8.4          | 1699                               | 83.9                                   | 750              | 31.5                  | 914              | 38.0                  | 147                     | 6.8                         | 
```