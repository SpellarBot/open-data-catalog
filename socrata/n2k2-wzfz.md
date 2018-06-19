# OpenNY Press Releases

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/openny-press-releases) |
| Metadata | [Link](https://data.ny.gov/api/views/n2k2-wzfz) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/n2k2-wzfz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/n2k2-wzfz/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | n2k2-wzfz |
| Name | OpenNY Press Releases |
| Created | 2014-03-11T18:18:12Z |
| Publication Date | 2017-02-09T15:30:50Z |

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | =========== | ========================= | ========================= | ============= | ============= |
| Yes      | time        | date                      | Date                      | calendar_date | calendar_date |
| Yes      | series tag  | press_release_title       | Press Release Title       | text          | text          |
| Yes      | series tag  | press_release_website_url | Press Release Website URL | url           | url           |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:n2k2-wzfz d:2013-03-11T00:00:00.000Z t:press_release_title="Governor Cuomo Launches Open.NY.Gov Providing Public Unprecedented User-Friendly Access to Federal, State and Local Data" t:press_release_website_url=http://www.governor.ny.gov/press/03112013open-data m:row_number.n2k2-wzfz=1

series e:n2k2-wzfz d:2013-03-14T00:00:00.000Z t:press_release_title="Governor Cuomo Announces 64 Local Governments Have Signed up to Share Data on OPEN.NY.GOV Days After Website Launch" t:press_release_website_url=http://www.governor.ny.gov/press/03142013-64-local-governments-signed-up-for-opennygov-since-launch m:row_number.n2k2-wzfz=2

series e:n2k2-wzfz d:2013-05-01T00:00:00.000Z t:press_release_title="Governor Cuomo Makes Millions of Additional Records Available on Open.Ny.Gov" t:press_release_website_url=http://www.governor.ny.gov/press/05012013millions-of-records-opennygov m:row_number.n2k2-wzfz=3
```

## Meta Commands

```ls
metric m:row_number.n2k2-wzfz p:long l:"Row Number"

entity e:n2k2-wzfz l:"OpenNY Press Releases" t:url=https://data.ny.gov/api/views/n2k2-wzfz

property e:n2k2-wzfz t:meta.view v:id=n2k2-wzfz v:averageRating=0 v:name="OpenNY Press Releases"

property e:n2k2-wzfz t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:n2k2-wzfz t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:n2k2-wzfz t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| date                | press_release_title                                                                                                                             | press_release_website_url                                                                                                               | 
| =================== | =============================================================================================================================================== | ======================================================================================================================================= | 
| 2013-03-11T00:00:00 | Governor Cuomo Launches Open.NY.Gov Providing Public Unprecedented User-Friendly Access to Federal, State and Local Data                        | [http://www.governor.ny.gov/press/03112013open-data, null]                                                                              | 
| 2013-03-14T00:00:00 | Governor Cuomo Announces 64 Local Governments Have Signed up to Share Data on OPEN.NY.GOV Days After Website Launch                             | [http://www.governor.ny.gov/press/03142013-64-local-governments-signed-up-for-opennygov-since-launch, null]                             | 
| 2013-05-01T00:00:00 | Governor Cuomo Makes Millions of Additional Records Available on Open.Ny.Gov                                                                    | [http://www.governor.ny.gov/press/05012013millions-of-records-opennygov, null]                                                          | 
| 2013-05-21T00:00:00 | Governor Cuomo Encourages New Yorkers to Use Open.Ny.Gov to Support Local Farmers' Markets and Beverage Businesses                              | [http://www.governor.ny.gov/press/05212013-governor-encourages-use-of-website-to-support-farmers-markets-and-beverage-businesses, null] | 
| 2013-05-22T00:00:00 | Governor Cuomo Unveils Major Economic Development Initiative to Transform University Communities into Magnets for New Businesses and Investment | [http://www.governor.ny.gov/press/05222013-tax-free-ny-initiative, null]                                                                | 
| 2013-06-13T00:00:00 | Governor Cuomo Releases Provisional Open Data Guidelines to Increase Transparency Among State Agencies                                          | [http://www.governor.ny.gov/press/06132013-open-data-guidelines, null]                                                                  | 
| 2013-07-24T00:00:00 | Governor Cuomo Expands Open.Ny.Gov by Adding More Than 100 Transportation Datasets Now Available to The Public                                  | [http://www.governor.ny.gov/press/07102413-opennygov-expands, null]                                                                     | 
| 2013-07-26T00:00:00 | Governor Cuomo Launches Project Sunlight to Give Public Access to Database of Who Appears Before State Government                               | [http://www.governor.ny.gov/press/07262013-project-sunlight-public-access, null]                                                        | 
| 2013-01-22T00:00:00 | Governor Cuomo Announces Launch of 'Open Budget' Transparency Portal                                                                            | [http://www.governor.ny.gov/press/01222013-cuomo-annc-launch-openbudget-portal, null]                                                   | 
| 2013-12-23T00:00:00 | Governor Cuomo Announces Winter Farmers' Markets Now Available on Open.NY.Gov                                                                   | [http://www.governor.ny.gov/press/12232013-2014-winter-farmers-market, null]                                                            | 
```