# Concentrations of Protected Classes from Analysis of Impediments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/concentrations-of-protected-classes-from-analysis-of-impediments) |
| Metadata | [Link](https://data.austintexas.gov/api/views/692b-xsit) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/692b-xsit/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/692b-xsit/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 692b-xsit |
| Name | Concentrations of Protected Classes from Analysis of Impediments |
| Attribution | NHCD |
| Category | Neighborhood |
| Tags | housing, poverty, minority, rcap, ecap, analysis of impediments, fair housing |
| Created | 2015-09-04T17:32:44Z |
| Publication Date | 2015-09-04T17:57:37Z |

## Description

A new component of fair housing studies is an analysis of the opportunities residents are afforded in ?racially or ethnically concentrated areas of poverty,? also called RCAPs or ECAPs. An RCAP or ECAP is a neighborhood with significant concentrations of extreme poverty and minority populations.
HUD?s definition of an RCAP/ECAP is:
?	A Census tract that has a non?white population of 50 percent or more AND a poverty rate of 40 percent or more; OR
?	A Census tract that has a non?white population of 50 percent or more AND the poverty rate is three times the average tract poverty rate for the metro/micro area, whichever is lower.

Why the 40 percent threshold? The RCAP/ECAP definition is not meant to suggest that a slightly?lower?than?40 percent poverty rate is ideal or acceptable. The threshold was borne out of research that concluded a 40 percent poverty rate was the point at which a neighborhood became significantly socially and economically challenged. Conversely, research has shown that areas with up to 14 percent of poverty have no noticeable effect on community opportunity. (See Section II in City of Austin?s 2015 Analysis of Impediments to Fair Housing Choice: http://www.austintexas.gov/sites/default/files/files/NHCD/Reports_Publications/1Analysis_Impediments_for_web.pdf)

This dataset provides socioeconomic data on protected classes from the 2008-2012 American Community Survey on census tracts in Austin?s city limits and designates which of those tracts are considered RCAPs or ECAPs based on these socioeconomic characteristics. A map of the census tracts designated as RCAPs or ECAPs is attached to this dataset and downloadable as a pdf (see below).

## Columns

```ls
| Included | Schema Type | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | =========== | ===================================== | ===================================== | ========= | =========== |
| No       | time        | :updated_at                           | updated_at                            | meta_data | meta_data   |
| Yes      | series tag  | geoid                                 | GEOID                                 | text      | number      |
| Yes      | series tag  | census_tract                          | Census Tract                          | text      | text        |
| Yes      | series tag  | county                                | County                                | text      | text        |
| Yes      | series tag  | rcap_or_ecap                          | RCAP or ECAP                          | text      | text        |
| Yes      | series tag  | majority_minority                     | Majority-Minority                     | text      | text        |
| Yes      | series tag  | hispanic_concentration                | Hispanic Concentration                | text      | text        |
| Yes      | series tag  | black_african_american_concentration  | Black/African American Concentration  | text      | text        |
| Yes      | series tag  | asian_concentration                   | Asian Concentration                   | text      | text        |
| Yes      | series tag  | poverty_concentration                 | Poverty Concentration                 | text      | text        |
| Yes      | series tag  | disabled_concentration                | Disabled Concentration                | text      | text        |
| Yes      | series tag  | linguistically_isolated_concentration | Linguistically Isolated Concentration | text      | text        |
| Yes      | series tag  | foreign_born_concentration            | Foreign-Born Concentration            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:692b-xsit d:2015-09-04T10:32:52.000Z t:foreign_born_concentration=NO t:rcap_or_ecap=NO t:black_african_american_concentration=NO t:linguistically_isolated_concentration=NO t:hispanic_concentration=NO t:county="Hays County" t:asian_concentration=NO t:majority_minority=NO t:disabled_concentration=NO t:census_tract="Census Tract 101" t:geoid=48209010100 t:poverty_concentration=NO m:row_number.692b-xsit=1

series e:692b-xsit d:2015-09-04T10:32:52.000Z t:foreign_born_concentration=NO t:rcap_or_ecap=NO t:black_african_american_concentration=NO t:linguistically_isolated_concentration=NO t:hispanic_concentration=NO t:county="Hays County" t:asian_concentration=NO t:majority_minority=NO t:disabled_concentration=NO t:census_tract="Census Tract 102" t:geoid=48209010200 t:poverty_concentration=NO m:row_number.692b-xsit=2

series e:692b-xsit d:2015-09-04T10:32:52.000Z t:foreign_born_concentration=NO t:rcap_or_ecap=NO t:black_african_american_concentration=NO t:linguistically_isolated_concentration=NO t:hispanic_concentration=YES t:county="Hays County" t:asian_concentration=NO t:majority_minority=YES t:disabled_concentration=NO t:census_tract="Census Tract 103.02" t:geoid=48209010302 t:poverty_concentration=NO m:row_number.692b-xsit=3
```

## Meta Commands

```ls
metric m:row_number.692b-xsit p:long l:"Row Number"

entity e:692b-xsit l:"Concentrations of Protected Classes from Analysis of Impediments" t:attribution=NHCD t:url=https://data.austintexas.gov/api/views/692b-xsit

property e:692b-xsit t:meta.view v:id=692b-xsit v:category=Neighborhood v:averageRating=0 v:name="Concentrations of Protected Classes from Analysis of Impediments" v:attribution=NHCD

property e:692b-xsit t:meta.view.license v:name="Public Domain"

property e:692b-xsit t:meta.view.owner v:id=8uru-zr6m v:screenName=Lauren v:displayName=Lauren

property e:692b-xsit t:meta.view.tableauthor v:id=8uru-zr6m v:screenName=Lauren v:roleName=editor v:displayName=Lauren
```

## Top Records

```ls
| :updated_at | geoid       | census_tract        | county      | rcap_or_ecap | majority_minority | hispanic_concentration | black_african_american_concentration | asian_concentration | poverty_concentration | disabled_concentration | linguistically_isolated_concentration | foreign_born_concentration | 
| =========== | =========== | =================== | =========== | ============ | ================= | ====================== | ==================================== | =================== | ===================== | ====================== | ===================================== | ========================== | 
| 1441362772  | 48209010100 | Census Tract 101    | Hays County | NO           | NO                | NO                     | NO                                   | NO                  | NO                    | NO                     | NO                                    | NO                         | 
| 1441362772  | 48209010200 | Census Tract 102    | Hays County | NO           | NO                | NO                     | NO                                   | NO                  | NO                    | NO                     | NO                                    | NO                         | 
| 1441362772  | 48209010302 | Census Tract 103.02 | Hays County | NO           | YES               | YES                    | NO                                   | NO                  | NO                    | NO                     | NO                                    | NO                         | 
| 1441362772  | 48209010303 | Census Tract 103.03 | Hays County | YES          | YES               | NO                     | NO                                   | NO                  | YES                   | NO                     | NO                                    | NO                         | 
| 1441362772  | 48209010304 | Census Tract 103.04 | Hays County | YES          | YES               | NO                     | NO                                   | NO                  | YES                   | NO                     | NO                                    | NO                         | 
| 1441362772  | 48209010400 | Census Tract 104    | Hays County | NO           | YES               | NO                     | NO                                   | NO                  | NO                    | NO                     | NO                                    | NO                         | 
| 1441362772  | 48209010500 | Census Tract 105    | Hays County | NO           | YES               | YES                    | NO                                   | NO                  | NO                    | NO                     | NO                                    | NO                         | 
| 1441362772  | 48209010600 | Census Tract 106    | Hays County | NO           | NO                | NO                     | NO                                   | NO                  | NO                    | NO                     | NO                                    | NO                         | 
| 1441362772  | 48209010701 | Census Tract 107.01 | Hays County | NO           | NO                | NO                     | NO                                   | NO                  | YES                   | NO                     | NO                                    | NO                         | 
| 1441362772  | 48209010702 | Census Tract 107.02 | Hays County | NO           | NO                | NO                     | NO                                   | NO                  | NO                    | NO                     | NO                                    | NO                         | 
```