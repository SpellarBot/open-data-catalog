# Real Property Tax Rates Levy Data By Municipality: Beginning 2004

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/real-property-tax-rates-levy-data-by-municipality-beginning-2004) |
| Metadata | [Link](https://data.ny.gov/api/views/iq85-sdzs) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/iq85-sdzs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/iq85-sdzs/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | iq85-sdzs |
| Name | Real Property Tax Rates Levy Data By Municipality: Beginning 2004 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | tax, property tax, tax rates, levies |
| Created | 2013-02-27T15:21:11Z |
| Publication Date | 2016-08-03T22:02:59Z |

## Description

The Department of Taxation and Finance annually produces a data file providing property tax rates and levies for the taxing jurisdictions in New York State.  The data are culled from files on the State Comptroller?s website.  The dataset takes each school district segment and provides the levy for county, municipal and school tax purposes, as well as the tax rates that apply in those taxing jurisdictions.

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                 | Data Type | Render Type |
| ======== | ============== | ========================================================== | ==================================================== | ========= | =========== |
| Yes      | time           | fiscal_year_ending                                         | Fiscal Year Ending                                   | number    | number      |
| No       |                | roll_year                                                  | Roll Year                                            | number    | number      |
| Yes      | series tag     | swis_code                                                  | Swis Code                                            | text      | text        |
| Yes      | series tag     | municipality                                               | Municipality                                         | text      | text        |
| Yes      | series tag     | county                                                     | County                                               | text      | text        |
| Yes      | series tag     | school_code                                                | School Code                                          | text      | text        |
| Yes      | series tag     | school_name                                                | School Name                                          | text      | text        |
| Yes      | series tag     | type_of_value_on_whichtax_rates_are_applied                | Type of Value on which Tax Rates are applied         | text      | text        |
| Yes      | numeric metric | county_tax_levy                                            | County Tax Levy                                      | money     | money       |
| Yes      | numeric metric | county_tax_rate_outside_village_per_1000_assessed_value    | County Tax Rate Outside Village (per $1000 value)    | money     | money       |
| Yes      | numeric metric | county_tax_rate_inside_village_per_1000_assessed_value     | County Tax Rate Inside Village (per $1000 value)     | money     | money       |
| Yes      | numeric metric | municipality_tax_levy                                      | Municipality Tax Levy                                | money     | money       |
| Yes      | numeric metric | municipal_tax_rate_outside_village_per_1000_assessed_value | Municipal Tax Rate Outside Village (per $1000 value) | money     | money       |
| Yes      | numeric metric | municipal_tax_rate_inside_village_per_1000_assessed_value  | Municipal Tax Rate Inside Village (per $1000 value)  | money     | money       |
| Yes      | series tag     | school_district_tax_levy                                   | School District Tax Levy                             | text      | money       |
| Yes      | series tag     | school_district_tax_rate_per_1000_assessed_value           | School District Tax Rate (per $1000 value)           | text      | money       |
```

## Time Field

```ls
Value = fiscal_year_ending
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = roll_year
```

## Data Commands

```ls
series e:iq85-sdzs d:2013-01-01T00:00:00.000Z t:type_of_value_on_whichtax_rates_are_applied="Full Value" t:school_name=Albany t:county=Albany t:school_district_tax_levy=117009648 t:municipality=Albany t:swis_code=010100 t:school_code=010100 t:school_district_tax_rate_per_1000_assessed_value=25.55 m:municipality_tax_levy=55148000 m:county_tax_rate_inside_village_per_1000_assessed_value=0 m:county_tax_levy=17618600 m:municipal_tax_rate_outside_village_per_1000_assessed_value=12.27 m:municipal_tax_rate_inside_village_per_1000_assessed_value=0 m:county_tax_rate_outside_village_per_1000_assessed_value=3.84

series e:iq85-sdzs d:2013-01-01T00:00:00.000Z t:type_of_value_on_whichtax_rates_are_applied="Full Value" t:school_name=Cohoes t:county=Albany t:school_district_tax_levy=13731979 t:municipality=Cohoes t:swis_code=010300 t:school_code=010300 t:school_district_tax_rate_per_1000_assessed_value=19.06 m:municipality_tax_levy=6800559 m:county_tax_rate_inside_village_per_1000_assessed_value=0 m:county_tax_levy=2744044 m:municipal_tax_rate_outside_village_per_1000_assessed_value=9.65 m:municipal_tax_rate_inside_village_per_1000_assessed_value=0 m:county_tax_rate_outside_village_per_1000_assessed_value=3.84

series e:iq85-sdzs d:2013-01-01T00:00:00.000Z t:type_of_value_on_whichtax_rates_are_applied="Full Value" t:school_name=Watervliet t:county=Albany t:school_district_tax_levy=5352233 t:municipality=Watervliet t:swis_code=011800 t:school_code=011800 t:school_district_tax_rate_per_1000_assessed_value=13.04 m:municipality_tax_levy=3975421 m:county_tax_rate_inside_village_per_1000_assessed_value=0 m:county_tax_levy=1566598 m:municipal_tax_rate_outside_village_per_1000_assessed_value=9.92 m:municipal_tax_rate_inside_village_per_1000_assessed_value=0 m:county_tax_rate_outside_village_per_1000_assessed_value=3.84
```

## Meta Commands

```ls
metric m:county_tax_levy p:integer l:"County Tax Levy" d:"Levy for county purposes" t:dataTypeName=money

metric m:county_tax_rate_outside_village_per_1000_assessed_value p:double l:"County Tax Rate Outside Village (per $1000 value)" d:"County tax rate on municipality not located inside a village" t:dataTypeName=money

metric m:county_tax_rate_inside_village_per_1000_assessed_value p:double l:"County Tax Rate Inside Village (per $1000 value)" d:"County tax rate on municipality located inside a village" t:dataTypeName=money

metric m:municipality_tax_levy p:long l:"Municipality Tax Levy" d:"Levy for municipal purposes" t:dataTypeName=money

metric m:municipal_tax_rate_outside_village_per_1000_assessed_value p:double l:"Municipal Tax Rate Outside Village (per $1000 value)" d:"Municipal tax rate on municipality not located inside a village" t:dataTypeName=money

metric m:municipal_tax_rate_inside_village_per_1000_assessed_value p:double l:"Municipal Tax Rate Inside Village (per $1000 value)" d:"Municipal tax rate on municipality located inside a village" t:dataTypeName=money

entity e:iq85-sdzs l:"Real Property Tax Rates Levy Data By Municipality: Beginning 2004" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/iq85-sdzs

property e:iq85-sdzs t:meta.view v:id=iq85-sdzs v:category="Government & Finance" v:attributionLink=http://www.tax.ny.gov/pubs_and_bulls/orpts/publications/reports_annual.htm v:averageRating=0 v:name="Real Property Tax Rates Levy Data By Municipality: Beginning 2004" v:attribution="New York State Department of Taxation and Finance"

property e:iq85-sdzs t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:iq85-sdzs t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:iq85-sdzs t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| fiscal_year_ending | roll_year | swis_code | municipality | county | school_code | school_name             | type_of_value_on_whichtax_rates_are_applied | county_tax_levy | county_tax_rate_outside_village_per_1000_assessed_value | county_tax_rate_inside_village_per_1000_assessed_value | municipality_tax_levy | municipal_tax_rate_outside_village_per_1000_assessed_value | municipal_tax_rate_inside_village_per_1000_assessed_value | school_district_tax_levy | school_district_tax_rate_per_1000_assessed_value | 
| ================== | ========= | ========= | ============ | ====== | =========== | ======================= | =========================================== | =============== | ======================================================= | ====================================================== | ===================== | ========================================================== | ========================================================= | ======================== | ================================================ | 
| 2013               | 2012      | 010100    | Albany       | Albany | 010100      | Albany                  | Full Value                                  | 17618600        | 3.84                                                    | 0                                                      | 55148000              | 12.27                                                      | 0                                                         | 117009648                | 25.55                                            | 
| 2013               | 2012      | 010300    | Cohoes       | Albany | 010300      | Cohoes                  | Full Value                                  | 2744044         | 3.84                                                    | 0                                                      | 6800559               | 9.65                                                       | 0                                                         | 13731979                 | 19.06                                            | 
| 2013               | 2012      | 011800    | Watervliet   | Albany | 011800      | Watervliet              | Full Value                                  | 1566598         | 3.84                                                    | 0                                                      | 3975421               | 9.92                                                       | 0                                                         | 5352233                  | 13.04                                            | 
| 2013               | 2012      | 012000    | Berne        | Albany | 012001      | Berne-Knox-Westerlo     | Full Value                                  | 933887          | 3.84                                                    | 0                                                      | 875295                | 3.58                                                       | 0                                                         | 4450872                  | 19.73                                            | 
| 2013               | 2012      | 012000    | Berne        | Albany | 013403      | Voorheesville           | Full Value                                  | 933887          | 3.84                                                    | 0                                                      | 875295                | 3.58                                                       | 0                                                         | 218370                   | 19.46                                            | 
| 2013               | 2012      | 012000    | Berne        | Albany | 193201      | Greenville              | Full Value                                  | 933887          | 3.84                                                    | 0                                                      | 875295                | 3.58                                                       | 0                                                         | 7480                     | 19.98                                            | 
| 2013               | 2012      | 012000    | Berne        | Albany | 433801      | Middleburgh             | Full Value                                  | 933887          | 3.84                                                    | 0                                                      | 875295                | 3.58                                                       | 0                                                         | 271841                   | 19.6                                             | 
| 2013               | 2012      | 012200    | Bethlehem    | Albany | 012206      | Bethlehem               | Full Value                                  | 13050068        | 3.84                                                    | 0                                                      | 12491392              | 3.66                                                       | 0                                                         | 58022909                 | 21.73                                            | 
| 2013               | 2012      | 012200    | Bethlehem    | Albany | 012402      | Ravena-Coeymans-Selkirk | Full Value                                  | 13050068        | 3.84                                                    | 0                                                      | 12491392              | 3.66                                                       | 0                                                         | 9899780                  | 21.08                                            | 
| 2013               | 2012      | 012200    | Bethlehem    | Albany | 013002      | Guilderland             | Full Value                                  | 13050068        | 3.84                                                    | 0                                                      | 12491392              | 3.66                                                       | 0                                                         | 4065311                  | 19.54                                            | 
```