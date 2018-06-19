# Summary of Real Property Tax Exemptions by Municipality: Beginning Roll Year 1999

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/summary-of-real-property-tax-exemptions-by-municipality-beginning-roll-year-1999) |
| Metadata | [Link](https://data.ny.gov/api/views/ffnx-ezem) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ffnx-ezem/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ffnx-ezem/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ffnx-ezem |
| Name | Summary of Real Property Tax Exemptions by Municipality: Beginning Roll Year 1999 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | property, exempt, exemption, tax |
| Created | 2013-02-26T20:57:15Z |
| Publication Date | 2016-04-22T18:44:53Z |

## Description

The Department of Taxation and Finance annually produces a report pertaining to the exemptions from real property taxation in New York State.  The data analysis includes an examination and summary of exemptions by type or purpose for each municipality in the State.  The summary data include the number of exemptions in each type or purpose, as well as the full value of the exemption amounts.  The types are first broken down into categories of properties that are wholly exempt (and subsequently, not taxable for real property purposes) and those which are partially exempt.  Within those categories, further analysis of the type of ownership of these exempt properties is examined.   Specifically, these types of ownership are public and private.  Additionally, some properties may have exemption codes that are not contained in an agency maintained list of valid codes.  The data file contains a summary by count and full value of these invalidly coded properties, as well.  Finally, properties may have exemptions for various taxation purposes, also stated as taxing jurisdictions.  Those purposes are County, City/Town, and School taxation.  This dataset contains columns with the count and full value for exemptions in each of these taxing jurisdictions.

## Columns

```ls
| Included | Schema Type    | Field Name                                            | Name                                                  | Data Type | Render Type |
| ======== | ============== | ===================================================== | ===================================================== | ========= | =========== |
| Yes      | time           | roll_year                                             | Roll Year                                             | number    | number      |
| Yes      | series tag     | swis_code                                             | SWIS Code                                             | text      | text        |
| Yes      | series tag     | municipality_name                                     | Municipality Name                                     | text      | text        |
| Yes      | series tag     | county_name                                           | County Name                                           | text      | text        |
| Yes      | numeric metric | wholly_exempt_publicly_owned_exemption_count          | Wholly Exempt Publicly Owned Exemption Count          | number    | number      |
| Yes      | numeric metric | wholly_exempt_publicly_owned_exemption_full_value     | Wholly Exempt Publicly Owned Exemption Full Value     | number    | number      |
| Yes      | numeric metric | wholly_exempt_privately_owned_exemption_count         | Wholly Exempt Privately Owned Exemption Count         | number    | number      |
| Yes      | numeric metric | wholly_exempt_privately_owned_exemption_full_value    | Wholly Exempt Privately Owned Exemption Full Value    | number    | number      |
| Yes      | numeric metric | partially_exempt_publicly_owned_exemption_count       | Partially Exempt Publicly Owned Exemption Count       | number    | number      |
| Yes      | numeric metric | partially_exempt_publicly_owned_exemption_full_value  | Partially Exempt Publicly Owned Exemption Full Value  | number    | number      |
| Yes      | numeric metric | partially_exempt_privately_owned_exemption_count      | Partially Exempt Privately Owned Exemption Count      | number    | number      |
| Yes      | numeric metric | partially_exempt_privately_owned_exemption_full_value | Partially Exempt Privately Owned Exemption Full Value | number    | number      |
| Yes      | numeric metric | invalidly_coded_exemption_count                       | Invalidly Coded Exemption Count                       | number    | number      |
| Yes      | numeric metric | invalidly_coded_exemption_full_value                  | Invalidly Coded Exemption Full Value                  | number    | number      |
| Yes      | numeric metric | exempt_for_county_purposes_exemption_count            | Exempt for County Purposes Exemption Count            | number    | number      |
| Yes      | numeric metric | exempt_for_county_purposes_exemption_full_value       | Exempt for County Purposes Exemption Full Value       | number    | number      |
| Yes      | numeric metric | exempt_for_city_town_purposes_exemption_count         | Exempt for City/Town Purposes Exemption Count         | number    | number      |
| Yes      | numeric metric | exempt_for_city_town_purposes_exemption_full_value    | Exempt for City/Town Purposes Exemption Full Value    | number    | number      |
| Yes      | numeric metric | exempt_for_school_purposes_exemption_count            | Exempt for School Purposes Exemption Count            | number    | number      |
| Yes      | numeric metric | exempt_for_school_purposes_exemption_value            | Exempt for School Purposes Exemption Value            | number    | number      |
```

## Time Field

```ls
Value = roll_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ffnx-ezem d:2014-01-01T00:00:00.000Z t:municipality_name=Albany t:swis_code=010100 t:county_name=Albany m:exempt_for_county_purposes_exemption_count=7069 m:invalidly_coded_exemption_full_value=0 m:exempt_for_city_town_purposes_exemption_count=7084 m:wholly_exempt_privately_owned_exemption_full_value=1455531262 m:wholly_exempt_publicly_owned_exemption_count=1765 m:partially_exempt_publicly_owned_exemption_count=3 m:partially_exempt_privately_owned_exemption_full_value=696308594 m:exempt_for_city_town_purposes_exemption_full_value=6964803858 m:invalidly_coded_exemption_count=0 m:exempt_for_school_purposes_exemption_value=7376688724 m:exempt_for_school_purposes_exemption_count=17299 m:partially_exempt_publicly_owned_exemption_full_value=619713 m:wholly_exempt_publicly_owned_exemption_full_value=5298304887 m:wholly_exempt_privately_owned_exemption_count=1365 m:partially_exempt_privately_owned_exemption_count=16406 m:exempt_for_county_purposes_exemption_full_value=6961391352

series e:ffnx-ezem d:2014-01-01T00:00:00.000Z t:municipality_name=Cohoes t:swis_code=010300 t:county_name=Albany m:exempt_for_county_purposes_exemption_count=1129 m:invalidly_coded_exemption_full_value=757485 m:exempt_for_city_town_purposes_exemption_count=1137 m:wholly_exempt_privately_owned_exemption_full_value=36070670 m:wholly_exempt_publicly_owned_exemption_count=200 m:partially_exempt_publicly_owned_exemption_count=1 m:partially_exempt_privately_owned_exemption_full_value=214082971 m:exempt_for_city_town_purposes_exemption_full_value=313531320 m:invalidly_coded_exemption_count=2 m:exempt_for_school_purposes_exemption_value=407270303 m:exempt_for_school_purposes_exemption_count=3425 m:partially_exempt_publicly_owned_exemption_full_value=555556 m:wholly_exempt_publicly_owned_exemption_full_value=175241019 m:wholly_exempt_privately_owned_exemption_count=50 m:partially_exempt_privately_owned_exemption_count=3694 m:exempt_for_county_purposes_exemption_full_value=310767491

series e:ffnx-ezem d:2014-01-01T00:00:00.000Z t:municipality_name=Watervliet t:swis_code=011800 t:county_name=Albany m:exempt_for_county_purposes_exemption_count=577 m:invalidly_coded_exemption_full_value=5890000 m:exempt_for_city_town_purposes_exemption_count=577 m:wholly_exempt_privately_owned_exemption_full_value=15169500 m:wholly_exempt_publicly_owned_exemption_count=40 m:partially_exempt_publicly_owned_exemption_count=0 m:partially_exempt_privately_owned_exemption_full_value=77014499 m:exempt_for_city_town_purposes_exemption_full_value=304931179 m:invalidly_coded_exemption_count=1 m:exempt_for_school_purposes_exemption_value=352641083 m:exempt_for_school_purposes_exemption_count=1720 m:partially_exempt_publicly_owned_exemption_full_value=0 m:wholly_exempt_publicly_owned_exemption_full_value=264424300 m:wholly_exempt_privately_owned_exemption_count=37 m:partially_exempt_privately_owned_exemption_count=1947 m:exempt_for_county_purposes_exemption_full_value=304931179
```

## Meta Commands

```ls
metric m:wholly_exempt_publicly_owned_exemption_count p:integer l:"Wholly Exempt Publicly Owned Exemption Count" d:"Number of exemptions where the property is wholly exempt and publicly owned" t:dataTypeName=number

metric m:wholly_exempt_publicly_owned_exemption_full_value p:long l:"Wholly Exempt Publicly Owned Exemption Full Value" d:"The full value of the exemptions where the property is wholly exempt and publicly owned" t:dataTypeName=number

metric m:wholly_exempt_privately_owned_exemption_count p:integer l:"Wholly Exempt Privately Owned Exemption Count" d:"Number of exemptions where the property is wholly exempt and privately owned" t:dataTypeName=number

metric m:wholly_exempt_privately_owned_exemption_full_value p:long l:"Wholly Exempt Privately Owned Exemption Full Value" d:"The full value of the exemptions where the property is wholly exempt and privately owned" t:dataTypeName=number

metric m:partially_exempt_publicly_owned_exemption_count p:integer l:"Partially Exempt Publicly Owned Exemption Count" d:"The number of exemptions where the property is partially exempt and publicly owned" t:dataTypeName=number

metric m:partially_exempt_publicly_owned_exemption_full_value p:long l:"Partially Exempt Publicly Owned Exemption Full Value" d:"The full value of the exemptions where the property is partially exempt and publicly owned" t:dataTypeName=number

metric m:partially_exempt_privately_owned_exemption_count p:integer l:"Partially Exempt Privately Owned Exemption Count" d:"The number of exemptions where the property is partially exempt and privately owned" t:dataTypeName=number

metric m:partially_exempt_privately_owned_exemption_full_value p:long l:"Partially Exempt Privately Owned Exemption Full Value" d:"The full value of the exemptions where the property is partially exempt and privately owned" t:dataTypeName=number

metric m:invalidly_coded_exemption_count p:integer l:"Invalidly Coded Exemption Count" d:"The number of exemptions where an invalid code has been used" t:dataTypeName=number

metric m:invalidly_coded_exemption_full_value p:integer l:"Invalidly Coded Exemption Full Value" d:"The full value of exemptions where an invalid code has been used" t:dataTypeName=number

metric m:exempt_for_county_purposes_exemption_count p:integer l:"Exempt for County Purposes Exemption Count" d:"The number of exemptions where the property is exempt for county taxation purposes" t:dataTypeName=number

metric m:exempt_for_county_purposes_exemption_full_value p:long l:"Exempt for County Purposes Exemption Full Value" d:"The full value of the exemptions where the property is exempt for county taxation purposes" t:dataTypeName=number

metric m:exempt_for_city_town_purposes_exemption_count p:integer l:"Exempt for City/Town Purposes Exemption Count" d:"The number of exemption where the property is exempt for city or town taxation purposes" t:dataTypeName=number

metric m:exempt_for_city_town_purposes_exemption_full_value p:long l:"Exempt for City/Town Purposes Exemption Full Value" d:"The full value of the exemptions where the property is exempt for city or town taxation purposes" t:dataTypeName=number

metric m:exempt_for_school_purposes_exemption_count p:integer l:"Exempt for School Purposes Exemption Count" d:"The number of exemption where the property is exempt for school taxation purposes" t:dataTypeName=number

metric m:exempt_for_school_purposes_exemption_value p:long l:"Exempt for School Purposes Exemption Value" d:"The full value of the exemptions where the property is exempt for school taxation purposes" t:dataTypeName=number

entity e:ffnx-ezem l:"Summary of Real Property Tax Exemptions by Municipality: Beginning Roll Year 1999" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/ffnx-ezem

property e:ffnx-ezem t:meta.view v:id=ffnx-ezem v:category="Government & Finance" v:attributionLink=http://www.tax.ny.gov/pubs_and_bulls/orpts/publications/reports_annual.htm v:averageRating=0 v:name="Summary of Real Property Tax Exemptions by Municipality: Beginning Roll Year 1999" v:attribution="New York State Department of Taxation and Finance"

property e:ffnx-ezem t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ffnx-ezem t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ffnx-ezem t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| roll_year | swis_code | municipality_name | county_name | wholly_exempt_publicly_owned_exemption_count | wholly_exempt_publicly_owned_exemption_full_value | wholly_exempt_privately_owned_exemption_count | wholly_exempt_privately_owned_exemption_full_value | partially_exempt_publicly_owned_exemption_count | partially_exempt_publicly_owned_exemption_full_value | partially_exempt_privately_owned_exemption_count | partially_exempt_privately_owned_exemption_full_value | invalidly_coded_exemption_count | invalidly_coded_exemption_full_value | exempt_for_county_purposes_exemption_count | exempt_for_county_purposes_exemption_full_value | exempt_for_city_town_purposes_exemption_count | exempt_for_city_town_purposes_exemption_full_value | exempt_for_school_purposes_exemption_count | exempt_for_school_purposes_exemption_value | 
| ========= | ========= | ================= | =========== | ============================================ | ================================================= | ============================================= | ================================================== | =============================================== | ==================================================== | ================================================ | ===================================================== | =============================== | ==================================== | ========================================== | =============================================== | ============================================= | ================================================== | ========================================== | ========================================== | 
| 2014      | 010100    | Albany            | Albany      | 1765                                         | 5298304887                                        | 1365                                          | 1455531262                                         | 3                                               | 619713                                               | 16406                                            | 696308594                                             | 0                               | 0                                    | 7069                                       | 6961391352                                      | 7084                                          | 6964803858                                         | 17299                                      | 7376688724                                 | 
| 2014      | 010300    | Cohoes            | Albany      | 200                                          | 175241019                                         | 50                                            | 36070670                                           | 1                                               | 555556                                               | 3694                                             | 214082971                                             | 2                               | 757485                               | 1129                                       | 310767491                                       | 1137                                          | 313531320                                          | 3425                                       | 407270303                                  | 
| 2014      | 011800    | Watervliet        | Albany      | 40                                           | 264424300                                         | 37                                            | 15169500                                           | 0                                               | 0                                                    | 1947                                             | 77014499                                              | 1                               | 5890000                              | 577                                        | 304931179                                       | 577                                           | 304931179                                          | 1720                                       | 352641083                                  | 
| 2014      | 012000    | Berne             | Albany      | 37                                           | 25152266                                          | 35                                            | 7133752                                            | 12                                              | 2629137                                              | 1250                                             | 52683689                                              | 0                               | 0                                    | 451                                        | 51831552                                        | 435                                           | 49213930                                           | 1280                                       | 81762960                                   | 
| 2014      | 012200    | Bethlehem         | Albany      | 131                                          | 262494616                                         | 125                                           | 110339200                                          | 0                                               | 0                                                    | 11377                                            | 463318205                                             | 4                               | 2000                                 | 2381                                       | 500273298                                       | 2381                                          | 500273298                                          | 10179                                      | 755236913                                  | 
| 2014      | 012400    | Coeymans          | Albany      | 54                                           | 125539200                                         | 36                                            | 7562600                                            | 1                                               | 600                                                  | 2283                                             | 94485631                                              | 1                               | 275000                               | 664                                        | 159782717                                       | 666                                           | 159813395                                          | 2031                                       | 215730034                                  | 
| 2014      | 012600    | Colonie           | Albany      | 561                                          | 1179763441                                        | 231                                           | 608883232                                          | 7                                               | 19854                                                | 27329                                            | 1160897496                                            | 1                               | 5839416                              | 6806                                       | 2120914770                                      | 6763                                          | 2092220710                                         | 23832                                      | 2746616396                                 | 
| 2014      | 012800    | Green Island      | Albany      | 41                                           | 36741800                                          | 9                                             | 2008600                                            | 0                                               | 0                                                    | 493                                              | 23257640                                              | 0                               | 0                                    | 172                                        | 46334640                                        | 139                                           | 44482654                                           | 426                                        | 58580092                                   | 
| 2014      | 013000    | Guilderland       | Albany      | 212                                          | 170775897                                         | 130                                           | 90091556                                           | 0                                               | 0                                                    | 10965                                            | 439485714                                             | 0                               | 0                                    | 2221                                       | 361958775                                       | 2215                                          | 359056249                                          | 10969                                      | 679297465                                  | 
| 2014      | 013200    | Knox              | Albany      | 25                                           | 2530169                                           | 33                                            | 5641657                                            | 0                                               | 0                                                    | 1170                                             | 44914097                                              | 0                               | 0                                    | 406                                        | 21570629                                        | 383                                           | 19932611                                           | 1204                                       | 51312988                                   | 
```