# Summary of Real Property Tax Exemptions by Code by Municipality: Beginning Roll Year 1999

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/summary-of-real-property-tax-exemptions-by-code-by-municipality-beginning-roll-year-1999) |
| Metadata | [Link](https://data.ny.gov/api/views/ykg4-r7ad) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ykg4-r7ad/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ykg4-r7ad/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ykg4-r7ad |
| Name | Summary of Real Property Tax Exemptions by Code by Municipality: Beginning Roll Year 1999 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | property, exempt, exemption, tax |
| Created | 2015-04-27T20:07:10Z |
| Publication Date | 2016-04-21T22:19:34Z |

## Description

The Department of Taxation and Finance annually produces a report pertaining to the exemptions from real property taxation in New York State.  The data analysis includes an examination and summary of exemptions by exemption code for each municipality in the State.  The summary data include the number of exemptions in each code, the assessed value of the parcels containing the exemption code and the exemption amount itself, as well as the estimated full value of both the parcels containing the exemption code and the exemption amount.

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                         | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================ | ========= | =========== |
| Yes      | time           | roll_year                                    | Roll Year                                    | number    | number      |
| Yes      | series tag     | swis_code                                    | SWIS Code                                    | text      | text        |
| Yes      | series tag     | municipality_name                            | Municipality Name                            | text      | text        |
| Yes      | series tag     | county_name                                  | County Name                                  | text      | text        |
| Yes      | series tag     | exemption_code_number                        | Exemption Code Number                        | text      | number      |
| Yes      | series tag     | law_type_section                             | Law Type/Section                             | text      | text        |
| Yes      | series tag     | exemption_description                        | Exemption Description                        | text      | text        |
| Yes      | series tag     | exemption_group_type                         | Exemption Group/Type                         | text      | text        |
| Yes      | numeric metric | exempt_parcels                               | Exempt Parcels Count                         | number    | number      |
| Yes      | numeric metric | total_assessed_value_of_exempt_parcels       | Total Assessed Value of Exempt Parcels       | number    | number      |
| Yes      | numeric metric | estimated_total_full_value_of_exempt_parcels | Estimated Total Full Value of Exempt Parcels | number    | number      |
| Yes      | numeric metric | total_exempt_amount                          | Total Exempt Amount                          | number    | number      |
| Yes      | numeric metric | estimated_total_full_value_of_exempt_amount  | Estimated Total Full Value of Exempt Amount  | number    | number      |
```

## Time Field

```ls
Value = roll_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ykg4-r7ad d:2014-01-01T00:00:00.000Z t:municipality_name=Albany t:exemption_group_type=B t:law_type_section="RPTL 404(1)" t:swis_code=010100 t:exemption_code_number=1210 t:exemption_description="NYS - GENERALLY" t:county_name=Albany m:estimated_total_full_value_of_exempt_amount=3806705810 m:exempt_parcels=176 m:estimated_total_full_value_of_exempt_parcels=3806705810 m:total_assessed_value_of_exempt_parcels=4167200850 m:total_exempt_amount=4167200850

series e:ykg4-r7ad d:2014-01-01T00:00:00.000Z t:municipality_name=Albany t:exemption_group_type=B t:law_type_section="RPTL 404(3)" t:swis_code=010100 t:exemption_code_number=1220 t:exemption_description="NYS TEACHERS RETIREMENT SYSTEM" t:county_name=Albany m:estimated_total_full_value_of_exempt_amount=29633964 m:exempt_parcels=5 m:estimated_total_full_value_of_exempt_parcels=29633964 m:total_assessed_value_of_exempt_parcels=32440300 m:total_exempt_amount=32440300

series e:ykg4-r7ad d:2014-01-01T00:00:00.000Z t:municipality_name=Albany t:exemption_group_type=B t:law_type_section="RPTL 412" t:swis_code=010100 t:exemption_code_number=1235 t:exemption_description="PUBLIC AUTHORITY - STATE" t:county_name=Albany m:estimated_total_full_value_of_exempt_amount=55590755 m:exempt_parcels=3 m:estimated_total_full_value_of_exempt_parcels=55590755 m:total_assessed_value_of_exempt_parcels=60855200 m:total_exempt_amount=60855200
```

## Meta Commands

```ls
metric m:exempt_parcels p:integer l:"Exempt Parcels Count" d:"The number of parcels containing the exemption" t:dataTypeName=number

metric m:total_assessed_value_of_exempt_parcels p:long l:"Total Assessed Value of Exempt Parcels" d:"The assessed value of the parcels containing the exemption" t:dataTypeName=number

metric m:estimated_total_full_value_of_exempt_parcels p:long l:"Estimated Total Full Value of Exempt Parcels" d:"The estimated full value of the parcels containing the exemption" t:dataTypeName=number

metric m:total_exempt_amount p:long l:"Total Exempt Amount" d:"The assessed value of the exemption amounts for parcels containing the exemption" t:dataTypeName=number

metric m:estimated_total_full_value_of_exempt_amount p:long l:"Estimated Total Full Value of Exempt Amount" d:"The estimated full value of the exemption amounts for parcels containing the exemption" t:dataTypeName=number

entity e:ykg4-r7ad l:"Summary of Real Property Tax Exemptions by Code by Municipality: Beginning Roll Year 1999" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/ykg4-r7ad

property e:ykg4-r7ad t:meta.view v:id=ykg4-r7ad v:category="Government & Finance" v:attributionLink=http://www.tax.ny.gov/pubs_and_bulls/orpts/publications/reports_annual.htm v:averageRating=0 v:name="Summary of Real Property Tax Exemptions by Code by Municipality: Beginning Roll Year 1999" v:attribution="New York State Department of Taxation and Finance"

property e:ykg4-r7ad t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ykg4-r7ad t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ykg4-r7ad t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| roll_year | swis_code | municipality_name | county_name | exemption_code_number | law_type_section | exemption_description            | exemption_group_type | exempt_parcels | total_assessed_value_of_exempt_parcels | estimated_total_full_value_of_exempt_parcels | total_exempt_amount | estimated_total_full_value_of_exempt_amount | 
| ========= | ========= | ================= | =========== | ===================== | ================ | ================================ | ==================== | ============== | ====================================== | ============================================ | =================== | =========================================== | 
| 2014      | 010100    | Albany            | Albany      | 1210                  | RPTL 404(1)      | NYS - GENERALLY                  | B                    | 176            | 4167200850                             | 3806705810                                   | 4167200850          | 3806705810                                  | 
| 2014      | 010100    | Albany            | Albany      | 1220                  | RPTL 404(3)      | NYS TEACHERS RETIREMENT SYSTEM   | B                    | 5              | 32440300                               | 29633964                                     | 32440300            | 29633964                                    | 
| 2014      | 010100    | Albany            | Albany      | 1235                  | RPTL 412         | PUBLIC AUTHORITY - STATE         | B                    | 3              | 60855200                               | 55590755                                     | 60855200            | 55590755                                    | 
| 2014      | 010100    | Albany            | Albany      | 1236                  | RPTL 412         | NYS ENVIRON'L FACILITIES CORP    | B                    | 26             | 34660187                               | 31661813                                     | 34660187            | 31661813                                    | 
| 2014      | 010100    | Albany            | Albany      | 1237                  | RPTL 412         | STATE AUTHORITIES SPECIFIED      | B                    | 3              | 9522700                                | 8698913                                      | 9522700             | 8698913                                     | 
| 2014      | 010100    | Albany            | Albany      | 1238                  | RPTL 412         | CENTRAL N Y REGIONAL TRANSP AUTH | B                    | 51             | 11508000                               | 10512469                                     | 11508000            | 10512469                                    | 
| 2014      | 010100    | Albany            | Albany      | 1310                  | RPTL 406(1)      | COUNTY - GENERALLY               | C                    | 455            | 135845650                              | 124093953                                    | 134125204           | 122522339                                   | 
| 2014      | 010100    | Albany            | Albany      | 1311                  | RPTL 446         | COUNTY - CEMETERY LAND           | C                    | 8              | 49941200                               | 45620901                                     | 49941200            | 45620901                                    | 
| 2014      | 010100    | Albany            | Albany      | 1335                  | RPTL 406(1)      | CITY - GENERALLY                 | C                    | 558            | 354759800                              | 324070339                                    | 354759800           | 324070339                                   | 
| 2014      | 010100    | Albany            | Albany      | 1350                  | RPTL 406(1)      | TOWN - GENERALLY                 | C                    | 3              | 37900                                  | 34621                                        | 37900               | 34621                                       | 
```