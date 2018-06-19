# Reentry Housing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/reentry-housing) |
| Metadata | [Link](https://data.mo.gov/api/views/ybbi-ajb9) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/ybbi-ajb9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/ybbi-ajb9/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | ybbi-ajb9 |
| Name | Reentry Housing |
| Created | 2016-02-23T14:43:30Z |
| Publication Date | 2017-04-20T23:00:33Z |

## Columns

```ls
| Included | Schema Type | Field Name                          | Name                                             | Data Type | Render Type |
| ======== | =========== | =================================== | ================================================ | ========= | =========== |
| No       | time        | :updated_at                         | updated_at                                       | meta_data | meta_data   |
| Yes      | series tag  | business_name                       | Business Name                                    | text      | text        |
| No       |             | business_address                    | Business Address                                 | text      | text        |
| Yes      | series tag  | city                                | City                                             | text      | text        |
| Yes      | series tag  | county                              | County                                           | text      | text        |
| Yes      | series tag  | state                               | State                                            | text      | text        |
| Yes      | series tag  | zipcode                             | Zip Code                                         | text      | text        |
| Yes      | series tag  | primary_phone_number                | Primary Phone Number                             | text      | text        |
| Yes      | series tag  | additional_phone_numbers            | Additional Phone Numbers                         | text      | text        |
| Yes      | series tag  | website                             | Website                                          | text      | text        |
| Yes      | series tag  | permanent_housing                   | Permanent housing                                | text      | text        |
| Yes      | series tag  | transitional_housing                | Transitional housing                             | text      | text        |
| Yes      | series tag  | emergency_shelter                   | Emergency Shelter                                | text      | text        |
| Yes      | series tag  | persons_with_hiv_aids               | Persons with HIV/AIDS                            | text      | text        |
| Yes      | series tag  | serious_mental_illness              | Serious Mental Illness                           | text      | text        |
| Yes      | series tag  | substance_use_disorder              | Substance Use disorder                           | text      | text        |
| Yes      | series tag  | developmental_disabilities          | Developmental Disabilities                       | text      | text        |
| Yes      | series tag  | veterans_oth_discharge_or_higher    | Veterans OTH discharge or higher                 | text      | text        |
| Yes      | series tag  | veteran_general_discharge_or_higher | Veteran General discharge or higher              | text      | text        |
| Yes      | series tag  | gender_specific_program             | Gender specific program                          | text      | text        |
| Yes      | series tag  | family_unit                         | Family unit                                      | text      | text        |
| Yes      | series tag  | rental_assistance_subsidy           | Rental Assistance/Subsidy                        | text      | text        |
| Yes      | series tag  | meets_hud_s_definition_of_homeless  | Meets HUD?s definition of Homeless               | text      | text        |
| Yes      | series tag  | sex_offender                        | Disqualifies Sex offenders                       | text      | text        |
| Yes      | series tag  | prior_meth_sales_at_housing_program | Disqualifies Prior Meth sales at housing program | text      | text        |
| Yes      | series tag  | felony_conviction                   | Disqualifies Felony conviction                   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = business_address
```

## Data Commands

```ls
series e:ybbi-ajb9 d:2017-04-20T23:00:12.000Z t:rental_assistance_subsidy=No t:family_unit=No t:felony_conviction=No t:website=http://freedomchristianministries.org/ t:sex_offender=No t:persons_with_hiv_aids=No t:prior_meth_sales_at_housing_program=No t:zipcode=65605 t:permanent_housing=No t:state=MO t:gender_specific_program="not gender specific" t:veteran_general_discharge_or_higher=No t:city=Aurora t:business_name="Freedom Dream Center" t:substance_use_disorder=Yes t:serious_mental_illness=No t:veterans_oth_discharge_or_higher=No t:transitional_housing=Yes t:county=Lawrence t:primary_phone_number=417-678-6909 t:emergency_shelter=No t:meets_hud_s_definition_of_homeless=No t:developmental_disabilities=No m:row_number.ybbi-ajb9=1

series e:ybbi-ajb9 d:2017-04-20T23:00:12.000Z t:rental_assistance_subsidy=No t:family_unit=No t:felony_conviction=No t:sex_offender=Yes t:persons_with_hiv_aids=No t:prior_meth_sales_at_housing_program=No t:zipcode=63829 t:permanent_housing=No t:state=MO t:gender_specific_program="Male only" t:veteran_general_discharge_or_higher=No t:city=Cardwell t:business_name="Shepherd&#039;s Fold Ministry" t:substance_use_disorder=Yes t:serious_mental_illness=No t:veterans_oth_discharge_or_higher=No t:transitional_housing=Yes t:county=Dunklin t:primary_phone_number=573-654-2280 t:emergency_shelter=No t:meets_hud_s_definition_of_homeless=No t:developmental_disabilities=No m:row_number.ybbi-ajb9=2

series e:ybbi-ajb9 d:2017-04-20T23:00:12.000Z t:rental_assistance_subsidy=No t:family_unit=No t:felony_conviction=No t:website=https://www.harrishousestl.org/ t:sex_offender=Yes t:persons_with_hiv_aids=No t:prior_meth_sales_at_housing_program=No t:zipcode=63111 t:permanent_housing=No t:state=MO t:gender_specific_program="not gender specific" t:veteran_general_discharge_or_higher=No t:city="St. Louis" t:business_name="Harris House Foundation" t:substance_use_disorder=Yes t:serious_mental_illness=No t:veterans_oth_discharge_or_higher=No t:transitional_housing=Yes t:county="St. Louis (county),St. Louis City (county)" t:primary_phone_number=314-631-4299 t:emergency_shelter=No t:meets_hud_s_definition_of_homeless=No t:developmental_disabilities=No m:row_number.ybbi-ajb9=3
```

## Meta Commands

```ls
metric m:row_number.ybbi-ajb9 p:long l:"Row Number"

entity e:ybbi-ajb9 l:"Reentry Housing" t:url=https://data.mo.gov/api/views/ybbi-ajb9

property e:ybbi-ajb9 t:meta.view v:id=ybbi-ajb9 v:averageRating=0 v:name="Reentry Housing"

property e:ybbi-ajb9 t:meta.view.owner v:id=jzbz-iqr6 v:screenName=Breanna v:lastNotificationSeenAt=1492723347 v:displayName=Breanna

property e:ybbi-ajb9 t:meta.view.tableauthor v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:lastNotificationSeenAt=1492723347 v:displayName=Breanna
```

## Top Records

```ls
| :updated_at | business_name                | business_address            | city      | county                                     | state | zipcode | primary_phone_number | additional_phone_numbers | website                                | permanent_housing | transitional_housing | emergency_shelter | persons_with_hiv_aids | serious_mental_illness | substance_use_disorder | developmental_disabilities | veterans_oth_discharge_or_higher | veteran_general_discharge_or_higher | gender_specific_program | family_unit | rental_assistance_subsidy | meets_hud_s_definition_of_homeless | sex_offender | prior_meth_sales_at_housing_program | felony_conviction | 
| =========== | ============================ | =========================== | ========= | ========================================== | ===== | ======= | ==================== | ======================== | ====================================== | ================= | ==================== | ================= | ===================== | ====================== | ====================== | ========================== | ================================ | =================================== | ======================= | =========== | ========================= | ================================== | ============ | =================================== | ================= | 
| 1492729212  | Freedom Dream Center         | 17044 Hwy 39                | Aurora    | Lawrence                                   | MO    | 65605   | 417-678-6909         |                          | http://freedomchristianministries.org/ | No                | Yes                  | No                | No                    | No                     | Yes                    | No                         | No                               | No                                  | not gender specific     | No          | No                        | No                                 | No           | No                                  | No                | 
| 1492729212  | Shepherd's Fold Ministry     | 201 E Loeb St               | Cardwell  | Dunklin                                    | MO    | 63829   | 573-654-2280         |                          |                                        | No                | Yes                  | No                | No                    | No                     | Yes                    | No                         | No                               | No                                  | Male only               | No          | No                        | No                                 | Yes          | No                                  | No                | 
| 1492729212  | Harris House Foundation      | 8315 South Broadway         | St. Louis | St. Louis (county),St. Louis City (county) | MO    | 63111   | 314-631-4299         |                          | https://www.harrishousestl.org/        | No                | Yes                  | No                | No                    | No                     | Yes                    | No                         | No                               | No                                  | not gender specific     | No          | No                        | No                                 | Yes          | No                                  | No                | 
| 1492729212  | Oxford House Winfield        | 60 Franke Drive             | Winfield  | Lincoln                                    | MO    | 63389   | 636-566-6258         |                          | http://oxfordhouse.org/userfiles/file/ | No                | Yes                  | No                | No                    | No                     | Yes                    | No                         | No                               | No                                  | Male only               | No          | No                        | No                                 | Yes          | No                                  | No                | 
| 1492729212  | Oxford House Shenandoah      | 720 Shenandoah              | St. Louis | St. Louis (county),St. Louis City (county) | MO    | 63104   | 314-776-4883         |                          | http://oxfordhouse.org/userfiles/file/ | No                | Yes                  | No                | No                    | No                     | Yes                    | No                         | No                               | No                                  | Male only               | No          | No                        | No                                 | Yes          | No                                  | No                | 
| 1492729212  | Oxford House Monitor         | 3633 Meramec                | St. Louis | St. Louis (county),St. Louis City (county) | MO    | 63116   | 314-752-1213         |                          | http://oxfordhouse.org/userfiles/file/ | No                | Yes                  | No                | No                    | No                     | Yes                    | No                         | No                               | No                                  | Female only             | Yes         | No                        | No                                 | Yes          | No                                  | No                | 
| 1492729212  | oxford House Cote Brilliante | 5049 Cote Brillianta Avenue | St. Louis | St. Louis (county),St. Louis City (county) | MO    | 63113   | 314-367-3407         |                          | http://oxfordhouse.org/userfiles/file/ | No                | Yes                  | No                | No                    | No                     | Yes                    | No                         | No                               | No                                  | Male only               | No          | No                        | No                                 | Yes          | No                                  | No                | 
| 1492729212  | Oxford House Osage           | 2715 Osage Street           | St. Louis | St. Louis (county),St. Louis City (county) | MO    | 63118   | 314-932-5871         |                          | http://oxfordhouse.org/userfiles/file/ | No                | Yes                  | No                | No                    | No                     | Yes                    | No                         | No                               | No                                  | Female only             | Yes         | No                        | No                                 | Yes          | No                                  | No                | 
| 1492729212  | Oxford House Michigan        | 7127 Michigan Avenue        | St. Louis | St. Louis (county),St. Louis City (county) | MO    | 63111   | 314-351-2712         |                          | http://oxfordhouse.org/userfiles/file/ | No                | Yes                  | No                | No                    | No                     | Yes                    | No                         | No                               | No                                  | Male only               | No          | No                        | No                                 | Yes          | No                                  | No                | 
| 1492729212  | Owford House Lusher          | 11876 Lusher Road           | St. Louis | St. Louis (county),St. Louis City (county) | MO    | 63138   | 314-741-7536         |                          | http://oxfordhouse.org/userfiles/file/ | No                | Yes                  | No                | No                    | No                     | Yes                    | No                         | No                               | No                                  | Male only               | No          | No                        | No                                 | Yes          | No                                  | No                | 
```