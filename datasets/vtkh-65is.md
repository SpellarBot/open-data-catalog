# Cleanup Sites in Washington State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cleanup-sites-in-washington-state-f0851) |
| Metadata | [Link](https://data.wa.gov/api/views/vtkh-65is) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/vtkh-65is/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/vtkh-65is/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | vtkh-65is |
| Name | Cleanup Sites in Washington State |
| Attribution | Toxics Cleanup Program : Washington Department of Ecology |
| Category | Natural Resources & Environment |
| Tags | cleanup sites, mtca, warm ranking, toxics cleanup, cleanup, cleanup status, ecology, nfa date, nfa reason |
| Created | 2013-08-26T22:57:30Z |
| Publication Date | 2014-05-28T20:02:53Z |

## Description

This is a list of cleanup sites in Washington State. It includes sites and associated websites.  It includes location data, Cleanup Status, Site Rank ? if the site is ranked, and if the site has an Environmental Covenant.  

Over half the cleanup sites have a status of ?No Further Action Required/Decision? or NFA.  If a site has a NFA it includes the latest NFA date and NFA reason.  

The Washington Department of Ecology (Toxics Cleanup Program) works to clean up contaminated sites/properties throughout the state of Washington. This data was downloaded from the Integrated Site Information System (ISIS) database and is monthly.

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | =========== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag  | cleanup_site_id            | Cleanup Site ID            | text          | number        |
| Yes      | series tag  | cleanup_site_name          | Cleanup Site Name          | text          | text          |
| Yes      | series tag  | cleanup_status             | Cleanup Status             | text          | text          |
| Yes      | series tag  | statute                    | Statute                    | text          | text          |
| Yes      | series tag  | rank                       | Rank                       | text          | text          |
| Yes      | series tag  | responsible_section        | Responsible Section        | text          | text          |
| Yes      | series tag  | has_environmental_covenant | Has Environmental Covenant | text          | text          |
| Yes      | series tag  | county_name                | County Name                | text          | text          |
| Yes      | series tag  | region                     | Region                     | text          | text          |
| No       |             | address                    | Address                    | text          | text          |
| Yes      | series tag  | city                       | City                       | text          | text          |
| Yes      | series tag  | zipcode                    | ZipCode                    | text          | text          |
| Yes      | series tag  | facility_site_id           | Facility Site ID           | text          | number        |
| Yes      | series tag  | legislative_district       | Legislative District       | text          | number        |
| Yes      | series tag  | congressional_district     | Congressional District     | text          | number        |
| Yes      | series tag  | website                    | Website                    | url           | url           |
| No       |             | latitude                   | Latitude                   | number        | number        |
| No       |             | longitude                  | Longitude                  | number        | number        |
| Yes      | time        | no_further_action_date     | No Further Action Date     | calendar_date | calendar_date |
| Yes      | series tag  | no_further_action_reason   | No Further Action Reason   | text          | text          |
```

## Time Field

```ls
Value = no_further_action_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,latitude,longitude
```

## Data Commands

```ls
series e:vtkh-65is d:2011-05-24T00:00:00.000Z t:cleanup_status="No Further Action" t:statute=MTCA t:region=Eastern t:responsible_section=Eastern t:facility_site_id=31288157 t:website="https://fortress.wa.gov/ecy/gsp/Sitepage.aspx?csid=8661" t:legislative_district=9 t:cleanup_site_name="ADAMS COUNTY MAINTENANCE SHOP" t:zipcode=99169 t:cleanup_site_id=8661 t:no_further_action_reason="NFA-Initial Investigation" t:congressional_district=4 t:county_name=Adams t:city=RITZVILLE m:row_number.vtkh-65is=1

series e:vtkh-65is d:2002-08-27T00:00:00.000Z t:cleanup_status="No Further Action" t:statute=MTCA t:region=Eastern t:rank="3 - Moderate Risk" t:responsible_section=Eastern t:facility_site_id=562 t:website="https://fortress.wa.gov/ecy/gsp/Sitepage.aspx?csid=4947" t:legislative_district=9 t:cleanup_site_name="ADAMS COUNTY MAINTENANCE SHOP OTHELLO" t:zipcode=99344 t:cleanup_site_id=4947 t:no_further_action_reason="NFA-Ecology Supervised/Conducted Cleanup" t:congressional_district=4 t:county_name=Adams t:city=OTHELLO m:row_number.vtkh-65is=2

series e:vtkh-65is d:2017-04-20T20:35:21.000Z t:cleanup_status="Cleanup Complete-Active O&M/Monitoring" t:statute=MTCA t:region=Eastern t:responsible_section=Eastern t:facility_site_id=53522166 t:website="https://fortress.wa.gov/ecy/gsp/Sitepage.aspx?csid=9596" t:legislative_district=9 t:cleanup_site_name="ASTRO 106" t:zipcode=99169 t:cleanup_site_id=9596 t:congressional_district=4 t:county_name=Adams t:city=RITZVILLE m:row_number.vtkh-65is=3
```

## Meta Commands

```ls
metric m:row_number.vtkh-65is p:long l:"Row Number"

entity e:vtkh-65is l:"Cleanup Sites in Washington State" t:attribution="Toxics Cleanup Program : Washington Department of Ecology" t:url=https://data.wa.gov/api/views/vtkh-65is

property e:vtkh-65is t:meta.view v:id=vtkh-65is v:category="Natural Resources & Environment" v:averageRating=20 v:name="Cleanup Sites in Washington State" v:attribution="Toxics Cleanup Program : Washington Department of Ecology"

property e:vtkh-65is t:meta.view.owner v:id=dkdf-7x68 v:profileImageUrlMedium=/api/users/dkdf-7x68/profile_images/THUMB v:profileImageUrlLarge=/api/users/dkdf-7x68/profile_images/LARGE v:screenName="Toxics Cleanup Program" v:profileImageUrlSmall=/api/users/dkdf-7x68/profile_images/TINY v:displayName="Toxics Cleanup Program"

property e:vtkh-65is t:meta.view.tableauthor v:id=dkdf-7x68 v:profileImageUrlMedium=/api/users/dkdf-7x68/profile_images/THUMB v:profileImageUrlLarge=/api/users/dkdf-7x68/profile_images/LARGE v:screenName="Toxics Cleanup Program" v:profileImageUrlSmall=/api/users/dkdf-7x68/profile_images/TINY v:roleName=publisher v:displayName="Toxics Cleanup Program"
```

## Top Records

```ls
| cleanup_site_id | cleanup_site_name                     | cleanup_status                         | statute              | rank                      | responsible_section | has_environmental_covenant | county_name | region  | address                      | city      | zipcode    | facility_site_id | legislative_district | congressional_district | website                                                          | latitude  | longitude   | no_further_action_date | no_further_action_reason                 | 
| =============== | ===================================== | ====================================== | ==================== | ========================= | =================== | ========================== | =========== | ======= | ============================ | ========= | ========== | ================ | ==================== | ====================== | ================================================================ | ========= | =========== | ====================== | ======================================== | 
| 8661            | ADAMS COUNTY MAINTENANCE SHOP         | No Further Action                      | MTCA                 |                           | Eastern             |                            | Adams       | Eastern | 109 W ALDER                  | RITZVILLE | 99169      | 31288157         | 9                    | 4                      | [https://fortress.wa.gov/ecy/gsp/Sitepage.aspx?csid=8661, null]  | 47.128335 | -118.382183 | 2011-05-24T00:00:00    | NFA-Initial Investigation                | 
| 4947            | ADAMS COUNTY MAINTENANCE SHOP OTHELLO | No Further Action                      | MTCA                 | 3 - Moderate Risk         | Eastern             |                            | Adams       | Eastern | STATE RD 26                  | OTHELLO   | 99344      | 562              | 9                    | 4                      | [https://fortress.wa.gov/ecy/gsp/Sitepage.aspx?csid=4947, null]  | 46.811406 | -119.167789 | 2002-08-27T00:00:00    | NFA-Ecology Supervised/Conducted Cleanup | 
| 9596            | ASTRO 106                             | Cleanup Complete-Active O&M/Monitoring | MTCA                 |                           | Eastern             |                            | Adams       | Eastern | 1401 W 1ST                   | RITZVILLE | 99169      | 53522166         | 9                    | 4                      | [https://fortress.wa.gov/ecy/gsp/Sitepage.aspx?csid=9596, null]  | 47.119922 | -118.386326 |                        |                                          | 
| 1909            | BURLINGTON NORTHERN OTHELLO           | No Further Action                      | WPCA - Ch. 90.48 RCW | 1 - Highest Assessed Risk | Eastern             | Yes                        | Adams       | Eastern | BROADWAY & MAIN              | OTHELLO   | 99344      | 558              | 9                    | 4                      | [https://fortress.wa.gov/ecy/gsp/Sitepage.aspx?csid=1909, null]  | 46.826171 | -119.177931 | 2003-08-26T00:00:00    | NFA-Ecology Supervised/Conducted Cleanup | 
| 1868            | CHS Inc Bruce                         | Awaiting Cleanup                       | MTCA                 |                           | Eastern             |                            | Adams       | Eastern | 528 S BOOKER RD              | OTHELLO   | 99344      | 566              | 9                    | 4                      | [https://fortress.wa.gov/ecy/gsp/Sitepage.aspx?csid=1868, null]  | 46.835153 | -119.047932 |                        |                                          | 
| 1688            | CMC REAL ESTATE OTHELLO               | Cleanup Started                        | WPCA - Ch. 90.48 RCW | 5 - Lowest Assessed Risk  | Eastern             |                            | Adams       | Eastern | CUNNINGHAM ST                | OTHELLO   | 99344      | 559              | 9                    | 4                      | [https://fortress.wa.gov/ecy/gsp/Sitepage.aspx?csid=1688, null]  | 46.816530 | -119.184460 |                        |                                          | 
| 1731            | Crop Production Services Inc Othello  | Awaiting Cleanup                       | MTCA                 | 5 - Lowest Assessed Risk  | Eastern             |                            | Adams       | Eastern | 511 S BRUCE RD               | OTHELLO   | 99344      | 564              | 9                    | 4                      | [https://fortress.wa.gov/ecy/gsp/Sitepage.aspx?csid=1731, null]  | 46.837758 | -119.054163 |                        |                                          | 
| 9296            | DOT - WASHTUCNA MAINTENANCE SITE      | Cleanup Started                        | MTCA                 |                           | Eastern             |                            | Adams       | Eastern | SR 26 JCT & SR 261 NORTHSIDE | WASHTUCNA | 99371      | 45682921         | 9                    | 4                      | [https://fortress.wa.gov/ecy/gsp/Sitepage.aspx?csid=9296, null]  | 46.758824 | -118.308877 |                        |                                          | 
| 10092           | EMPIRE SEED FACILITY                  | No Further Action                      | MTCA                 |                           | Eastern             |                            | Adams       | Eastern | 690 S BROADWAY               | OTHELLO   | 99344-1759 | 66481327         | 9                    | 4                      | [https://fortress.wa.gov/ecy/gsp/Sitepage.aspx?csid=10092, null] | 46.818568 | -119.176327 | 2011-05-25T00:00:00    | NFA-Initial Investigation                | 
| 9720            | ERNIE'S CONOCO                        | Cleanup Started                        | MTCA                 |                           | Eastern             |                            | Adams       | Eastern | 565 E MAIN                   | OTHELLO   | 99344-1148 | 55815371         | 9                    | 4                      | [https://fortress.wa.gov/ecy/gsp/Sitepage.aspx?csid=9720, null]  | 46.826366 | -119.166767 |                        |                                          | 
```