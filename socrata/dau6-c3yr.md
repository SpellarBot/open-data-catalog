# Median Household Income, Cook County Municipalities, 2000 Census and ACS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/median-household-income-cook-county-municipalities-2000-census-and-acs-9f644) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/dau6-c3yr) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/dau6-c3yr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/dau6-c3yr/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | dau6-c3yr |
| Name | Median Household Income, Cook County Municipalities, 2000 Census and ACS |
| Attribution | Chicago Metropolitan Agency for Planning MetroPulse |
| Category | Economic Development |
| Created | 2012-08-30T19:55:18Z |
| Publication Date | 2014-10-09T21:43:42Z |

## Description

Courtesy of MetroPulse

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                     | Data Type | Render Type |
| ======== | ============== | ===================================== | ======================================== | ========= | =========== |
| Yes      | series tag     | municipality                          | Municipality                             | text      | text        |
| Yes      | numeric metric | income_median_household_2000_census   | Income: Median Household (2000 Census)   | number    | number      |
| Yes      | numeric metric | income_median_household_2005_2009_acs | Income: Median Household (2005-2009 ACS) | number    | number      |
| Yes      | numeric metric | income_median_household_2006_acs      | Income: Median Household (2006 ACS)      | number    | number      |
| Yes      | numeric metric | income_median_household_2007_acs      | Income: Median Household (2007 ACS)      | number    | number      |
| Yes      | series tag     | location_1                            | Location 1                               | text      | text        |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dau6-c3yr d:2000-01-01T00:00:00.000Z t:municipality="Mount Prospect" m:income_median_household_2005_2009_acs=66645 m:income_median_household_2000_census=57165

series e:dau6-c3yr d:2000-01-01T00:00:00.000Z t:municipality=Hillside m:income_median_household_2005_2009_acs=49909 m:income_median_household_2000_census=50776

series e:dau6-c3yr d:2000-01-01T00:00:00.000Z t:municipality=Wilmette m:income_median_household_2005_2009_acs=127319 m:income_median_household_2000_census=106773
```

## Meta Commands

```ls
metric m:income_median_household_2000_census p:integer l:"Income: Median Household (2000 Census)" t:dataTypeName=number

metric m:income_median_household_2005_2009_acs p:integer l:"Income: Median Household (2005-2009 ACS)" t:dataTypeName=number

metric m:income_median_household_2006_acs p:integer l:"Income: Median Household (2006 ACS)" t:dataTypeName=number

metric m:income_median_household_2007_acs p:integer l:"Income: Median Household (2007 ACS)" t:dataTypeName=number

entity e:dau6-c3yr l:"Median Household Income, Cook County Municipalities, 2000 Census and ACS" t:attribution="Chicago Metropolitan Agency for Planning MetroPulse" t:url=https://datacatalog.cookcountyil.gov/api/views/dau6-c3yr

property e:dau6-c3yr t:meta.view v:id=dau6-c3yr v:category="Economic Development" v:averageRating=0 v:name="Median Household Income, Cook County Municipalities, 2000 Census and ACS" v:attribution="Chicago Metropolitan Agency for Planning MetroPulse"

property e:dau6-c3yr t:meta.view.license v:name="Public Domain"

property e:dau6-c3yr t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:dau6-c3yr t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| municipality   | income_median_household_2000_census | income_median_household_2005_2009_acs | income_median_household_2006_acs | income_median_household_2007_acs | location_1 | 
| ============== | =================================== | ===================================== | ================================ | ================================ | ========== | 
| Mount Prospect | 57165                               | 66645                                 |                                  |                                  |            | 
| Hillside       | 50776                               | 49909                                 |                                  |                                  |            | 
| Wilmette       | 106773                              | 127319                                |                                  |                                  |            | 
| Schiller Park  | 41583                               | 48904                                 |                                  |                                  |            | 
| Chicago Ridge  | 44101                               | 46426                                 |                                  |                                  |            | 
| Palatine       | 63321                               | 73049                                 | 75967                            | 66689                            |            | 
| Sauk Village   | 46718                               | 49060                                 |                                  |                                  |            | 
| Morton Grove   | 63511                               | 70504                                 |                                  |                                  |            | 
| Richton Park   | 48299                               | 61217                                 |                                  |                                  |            | 
| Melrose Park   | 40689                               | 41256                                 |                                  |                                  |            | 
```