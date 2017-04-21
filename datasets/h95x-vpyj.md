# L&I Intent Details - Journey Level Trades And Wages

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/li-intent-details-journey-level-trades-and-wages) |
| Metadata | [Link](https://data.wa.gov/api/views/h95x-vpyj) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/h95x-vpyj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/h95x-vpyj/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | h95x-vpyj |
| Name | L&I Intent Details - Journey Level Trades And Wages |
| Attribution | L&I |
| Category | Labor |
| Tags | contractor, wages, trades |
| Created | 2015-11-13T18:52:03Z |
| Publication Date | 2015-12-04T22:37:05Z |

## Description

Contractor filing intent details about their wages and trades

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                        | Data Type | Render Type |
| ======== | ============== | ======================= | =========================== | ========= | =========== |
| No       | time           | :updated_at             | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | intent_id               | Intent ID Number            | text      | number      |
| Yes      | series tag     | job_classification_desc | Job Classification          | text      | text        |
| Yes      | series tag     | county_name             | County Name                 | text      | text        |
| Yes      | numeric metric | hrly_rate_amt           | Hourly Wage Rate            | number    | number      |
| Yes      | numeric metric | hrly_fringe_rate_amt    | Hourly Fringe Benefits Rate | number    | number      |
| Yes      | series tag     | work_qty_num            | Number Of Hour Worked       | text      | number      |
| Yes      | series tag     | trade_name              | Prevailing Wage Trade       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:h95x-vpyj d:2015-11-13T10:52:19.000Z t:job_classification_desc="Drywall Applicator" t:intent_id=12924 t:trade_name=CARPENTERS t:work_qty_num=6 t:county_name=King m:hrly_rate_amt=28.74 m:hrly_fringe_rate_amt=8.25

series e:h95x-vpyj d:2015-11-13T10:52:19.000Z t:job_classification_desc="Journey Level" t:intent_id=88070 t:trade_name="CEMENT MASONS" t:work_qty_num=4 t:county_name=King m:hrly_rate_amt=23.8 m:hrly_fringe_rate_amt=7.89

series e:h95x-vpyj d:2015-11-13T10:52:19.000Z t:job_classification_desc="Journey Level" t:intent_id=12924 t:trade_name="DRYWALL TAPERS" t:work_qty_num=4 t:county_name=King m:hrly_rate_amt=26.18 m:hrly_fringe_rate_amt=10.71
```

## Meta Commands

```ls
metric m:hrly_rate_amt p:double l:"Hourly Wage Rate" d:"Hourly Wage Rate" t:dataTypeName=number

metric m:hrly_fringe_rate_amt p:double l:"Hourly Fringe Benefits Rate" d:"Hourly Fringe Benefits Rate" t:dataTypeName=number

entity e:h95x-vpyj l:"L&I Intent Details - Journey Level Trades And Wages" t:attribution=L&I t:url=https://data.wa.gov/api/views/h95x-vpyj

property e:h95x-vpyj t:meta.view v:id=h95x-vpyj v:category=Labor v:averageRating=0 v:name="L&I Intent Details - Journey Level Trades And Wages" v:attribution=L&I

property e:h95x-vpyj t:meta.view.owner v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:displayName=Nithya

property e:h95x-vpyj t:meta.view.tableauthor v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:roleName=publisher v:displayName=Nithya
```

## Top Records

```ls
| :updated_at | intent_id | job_classification_desc | county_name | hrly_rate_amt | hrly_fringe_rate_amt | work_qty_num | trade_name            | 
| =========== | ========= | ======================= | =========== | ============= | ==================== | ============ | ===================== | 
| 1447411939  | 12924     | Drywall Applicator      | King        | 28.74         | 8.25                 | 6            | CARPENTERS            | 
| 1447411939  | 88070     | Journey Level           | King        | 23.8          | 7.89                 | 4            | CEMENT MASONS         | 
| 1447411939  | 12924     | Journey Level           | King        | 26.18         | 10.71                | 4            | DRYWALL TAPERS        | 
| 1447411939  | 268324    | Journey Level           | King        | 35.83         | 0                    | 4            | ELECTRICIANS - INSIDE | 
| 1447411939  | 3433      | Constructor             | King        | 50            | 0                    | 2            | ELEVATOR CONSTRUCTORS | 
| 1447411939  | 3433      | Mechanic                | King        | 50            | 0                    | 2            | ELEVATOR CONSTRUCTORS | 
| 1447411939  | 3433      | Mechanic In Charge      | King        | 50            | 0                    | 2            | ELEVATOR CONSTRUCTORS | 
| 1447411939  | 5254      | Journey Level           | King        | 16.68         | 5.19                 | 3            | FLAGGERS              | 
| 1447411939  | 88070     | Cement Finisher Tender  | King        | 21.36         | 5.19                 | 4            | LABORERS              | 
| 1447411939  | 5254      | General Laborer         | King        | 21.36         | 5.19                 | 1            | LABORERS              | 
```