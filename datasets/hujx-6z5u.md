# HPD Other City Financial Assistance Element

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hpd-other-city-financial-assistance-element-b1b05) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hujx-6z5u) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hujx-6z5u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hujx-6z5u/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hujx-6z5u |
| Name | HPD Other City Financial Assistance Element |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | department of housing preservation and development, hpd, city financial assistance |
| Created | 2014-02-26T21:35:12Z |
| Publication Date | 2014-08-21T14:12:01Z |

## Description

Information on the amounts, names and types of other City Financial Assistance such as credit facility, HPD Section 8 Project Based Voucher (PBV) Housing Assistance Payment (HAP), Inclusionary affordable floor area, and discounted land value for each project.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| No       | time           | :updated_at                        | updated_at                         | meta_data | meta_data   |
| Yes      | series tag     | projectdwid                        | ProjectDWID                        | text      | number      |
| Yes      | series tag     | project_id                         | Project ID                         | text      | number      |
| Yes      | numeric metric | hpd_pbvhap_year1_amount            | HPD PBVHAP Year1 Amount            | number    | number      |
| Yes      | series tag     | is_credit_facility                 | Is Credit Facility?                | text      | text        |
| Yes      | numeric metric | inclusionary_low_income_floor_area | Inclusionary Low Income Floor Area | number    | number      |
| Yes      | numeric metric | acquisition_price                  | Acquisition Price                  | number    | number      |
| Yes      | numeric metric | as_is_appraisal_amount             | As Is Appraisal Amount             | number    | number      |
| Yes      | numeric metric | highest_best_appraisal_amount      | Highest Best Appraisal Amount      | number    | number      |
| Yes      | numeric metric | intended_use_appraisal_amount      | Intended Use Appraisal Amount      | number    | number      |
| Yes      | series tag     | is_nominal                         | Is Nominal?                        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hujx-6z5u d:2014-07-25T07:30:55.000Z t:projectdwid=16829 t:project_id=39405 m:hpd_pbvhap_year1_amount=451009

series e:hujx-6z5u d:2014-07-25T07:30:55.000Z t:projectdwid=16835 t:project_id=39433 m:highest_best_appraisal_amount=1020000 m:acquisition_price=3 m:hpd_pbvhap_year1_amount=477539

series e:hujx-6z5u d:2014-07-25T07:30:55.000Z t:projectdwid=16857 t:project_id=39479 m:as_is_appraisal_amount=196650
```

## Meta Commands

```ls
metric m:hpd_pbvhap_year1_amount p:double l:"HPD PBVHAP Year1 Amount" d:"Estimated dollar amount of HPD Section 8 Project Based Voucher (PBV) annual Housing Assistance Payments (HAP) contract for Year 1" t:dataTypeName=number

metric m:inclusionary_low_income_floor_area p:float l:"Inclusionary Low Income Floor Area" d:"The Inclusionary Low Income Floor Area is the affordable floor area that is provided for low-income households or, upon resale as defined in Section 23-913, eligible buyers" t:dataTypeName=number

metric m:acquisition_price p:float l:"Acquisition Price" d:"Purchase price identified in the City deed" t:dataTypeName=number

metric m:as_is_appraisal_amount p:float l:"As Is Appraisal Amount" d:"Value of the property based on the ""As Is"" appraisal. This is the market pre-rehab value of the property. It is situational and may be based on a variety of things including market rate housing, vacant land or existing affordable housing with restricted rents" t:dataTypeName=number

metric m:highest_best_appraisal_amount p:float l:"Highest Best Appraisal Amount" d:"Value of the property based on the ""Highest and Best"" appraisal. This is the market post-rehab value of the property" t:dataTypeName=number

metric m:intended_use_appraisal_amount p:float l:"Intended Use Appraisal Amount" d:"Value of the property based on the ""Intended Use"" appraisal. This is the post-rehab value of the property based on the planned affordable housing project and is often ""Nominal.""" t:dataTypeName=number

entity e:hujx-6z5u l:"HPD Other City Financial Assistance Element" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/hujx-6z5u

property e:hujx-6z5u t:meta.view v:id=hujx-6z5u v:category="Housing & Development" v:averageRating=0 v:name="HPD Other City Financial Assistance Element" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:hujx-6z5u t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hujx-6z5u t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | projectdwid | project_id | hpd_pbvhap_year1_amount | is_credit_facility | inclusionary_low_income_floor_area | acquisition_price | as_is_appraisal_amount | highest_best_appraisal_amount | intended_use_appraisal_amount | is_nominal | 
| =========== | =========== | ========== | ======================= | ================== | ================================== | ================= | ====================== | ============================= | ============================= | ========== | 
| 1406273455  | 16762       | 38989      |                         | Yes                |                                    |                   |                        |                               |                               |            | 
| 1406273455  | 16763       | 38990      |                         | Yes                |                                    |                   |                        |                               |                               |            | 
| 1406273455  | 16764       | 38991      |                         | Yes                |                                    |                   |                        |                               |                               |            | 
| 1406273455  | 16829       | 39405      | 451009                  |                    |                                    |                   |                        |                               |                               |            | 
| 1406273455  | 16835       | 39433      | 477539                  |                    |                                    | 3                 |                        | 1020000                       |                               |            | 
| 1406273455  | 16857       | 39479      |                         |                    |                                    |                   | 196650                 |                               |                               |            | 
| 1406273455  | 16880       | 40072      |                         | Yes                |                                    |                   |                        |                               |                               |            | 
| 1406273455  | 16896       | 40548      |                         |                    |                                    | 3                 |                        | 2200000                       |                               |            | 
| 1406273455  | 16932       | 41249      |                         | Yes                |                                    |                   |                        |                               |                               |            | 
| 1406273455  | 16960       | 41814      |                         | Yes                |                                    |                   |                        |                               |                               |            | 
```