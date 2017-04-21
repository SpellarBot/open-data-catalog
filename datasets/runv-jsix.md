# Offenders Released from Prison

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/prison-closures) |
| Metadata | [Link](https://data.iowa.gov/api/views/runv-jsix) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/runv-jsix/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/runv-jsix/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | runv-jsix |
| Name | Offenders Released from Prison |
| Attribution | Iowa Department of Corrections |
| Category | Public Safety |
| Tags | months served, time served |
| Created | 2016-10-05T14:34:09Z |
| Publication Date | 2016-10-12T13:16:28Z |

## Description

This dataset includes the Fiscal Year of when an Offender is released from prison, their Age Groups, Sex, Race - Ethnicity's, Closure Type, Convicting Offense with description and the number of Months Served.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                              | Data Type     | Render Type   |
| ======== | ============== | ========================== | ================================= | ============= | ============= |
| No       |                | fiscal_year_closed         | Fiscal Year Closed                | number        | number        |
| Yes      | time           | release_month_year         | Release Month & Year              | calendar_date | calendar_date |
| Yes      | series tag     | closure_type               | Closure Type                      | text          | text          |
| Yes      | series tag     | race_ethnicity             | Race - Ethnicity                  | text          | text          |
| Yes      | series tag     | sex                        | Sex                               | text          | text          |
| Yes      | numeric metric | age_at_closure             | Age at Closure                    | number        | number        |
| Yes      | series tag     | institution_name           | Institution Name                  | text          | text          |
| Yes      | series tag     | convicting_offense         | Convicting Offense                | text          | text          |
| Yes      | series tag     | convicting_offense_class   | Convicting Offense Classification | text          | text          |
| Yes      | series tag     | convicting_offense_desc    | Convicting Offense Description    | text          | text          |
| Yes      | series tag     | convicting_offense_type    | Convicting Offense Type           | text          | text          |
| Yes      | series tag     | convicting_offense_subtype | Convicting Offense Subtype        | text          | text          |
| Yes      | numeric metric | months_served              | Months Served                     | number        | number        |
```

## Time Field

```ls
Value = release_month_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year_closed
```

## Data Commands

```ls
series e:runv-jsix d:2015-06-01T00:00:00.000Z t:convicting_offense_desc="BURGLARY 3RD DEGREE" t:convicting_offense_class="D Felony" t:sex=Male t:convicting_offense_type=Property t:race_ethnicity="White - Non-Hispanic" t:convicting_offense_subtype=Burglary t:closure_type="Parole Granted" t:convicting_offense=713.6A t:institution_name="Iowa State Penitentiary" m:months_served=10.33 m:age_at_closure=37

series e:runv-jsix d:2015-07-01T00:00:00.000Z t:convicting_offense_desc="BURGLARY 2ND DEGREE" t:convicting_offense_class="C Felony" t:sex=Male t:convicting_offense_type=Property t:race_ethnicity="White - Hispanic" t:convicting_offense_subtype=Burglary t:closure_type="Parole Granted" t:convicting_offense=713.5 t:institution_name="Mount Pleasant Correctional Facility" m:months_served=23.72 m:age_at_closure=21

series e:runv-jsix d:2014-08-01T00:00:00.000Z t:convicting_offense_desc="THEFT 2ND DEGREE" t:convicting_offense_class="D Felony" t:sex=Male t:convicting_offense_type=Property t:race_ethnicity="White - Non-Hispanic" t:convicting_offense_subtype=Theft t:closure_type="Parole Granted" t:convicting_offense=714.2(2) t:institution_name="Newton Correctional Facility" m:months_served=4.57 m:age_at_closure=36
```

## Meta Commands

```ls
metric m:age_at_closure p:integer l:"Age at Closure" d:"Age of the offender when released from prison." t:dataTypeName=number

metric m:months_served p:float l:"Months Served" d:"The number of months the offender spent in prison." t:dataTypeName=number

entity e:runv-jsix l:"Offenders Released from Prison" t:attribution="Iowa Department of Corrections" t:url=https://data.iowa.gov/api/views/runv-jsix

property e:runv-jsix t:meta.view v:id=runv-jsix v:category="Public Safety" v:averageRating=0 v:name="Offenders Released from Prison" v:attribution="Iowa Department of Corrections"

property e:runv-jsix t:meta.view.license v:name="Public Domain"

property e:runv-jsix t:meta.view.owner v:id=jikf-f8f6 v:profileImageUrlMedium=/api/users/jikf-f8f6/profile_images/THUMB v:profileImageUrlLarge=/api/users/jikf-f8f6/profile_images/LARGE v:screenName="Iowa Department of Corrections" v:profileImageUrlSmall=/api/users/jikf-f8f6/profile_images/TINY v:displayName="Iowa Department of Corrections"

property e:runv-jsix t:meta.view.tableauthor v:id=jikf-f8f6 v:profileImageUrlMedium=/api/users/jikf-f8f6/profile_images/THUMB v:profileImageUrlLarge=/api/users/jikf-f8f6/profile_images/LARGE v:screenName="Iowa Department of Corrections" v:profileImageUrlSmall=/api/users/jikf-f8f6/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Corrections"
```

## Top Records

```ls
| fiscal_year_closed | release_month_year  | closure_type                  | race_ethnicity       | sex  | age_at_closure | institution_name                     | convicting_offense  | convicting_offense_class | convicting_offense_desc                                | convicting_offense_type | convicting_offense_subtype | months_served | 
| ================== | =================== | ============================= | ==================== | ==== | ============== | ==================================== | =================== | ======================== | ====================================================== | ======================= | ========================== | ============= | 
| 2015               | 2015-06-01T00:00:00 | Parole Granted                | White - Non-Hispanic | Male | 37             | Iowa State Penitentiary              | 713.6A              | D Felony                 | BURGLARY 3RD DEGREE                                    | Property                | Burglary                   | 10.33         | 
| 2016               | 2015-07-01T00:00:00 | Parole Granted                | White - Hispanic     | Male | 21             | Mount Pleasant Correctional Facility | 713.5               | C Felony                 | BURGLARY 2ND DEGREE                                    | Property                | Burglary                   | 23.72         | 
| 2015               | 2014-08-01T00:00:00 | Parole Granted                | White - Non-Hispanic | Male | 36             | Newton Correctional Facility         | 714.2(2)            | D Felony                 | THEFT 2ND DEGREE                                       | Property                | Theft                      | 4.57          | 
| 2016               | 2015-09-01T00:00:00 | Work Release Granted          | White - Non-Hispanic | Male | 35             | Newton Correctional Facility         | 715A.2(2)a          | D Felony                 | FORGERY                                                | Property                | Forgery/Fraud              | 20.20         | 
| 2014               | 2013-10-01T00:00:00 | Parole Granted                | White - Hispanic     | Male | 21             | Iowa State Penitentiary              | 713.6A              | D Felony                 | BURGLARY 3RD DEGREE                                    | Property                | Burglary                   | 6.02          | 
| 2015               | 2014-11-01T00:00:00 | Work Release Granted          | White - Non-Hispanic | Male | 33             | Newton Correctional Facility         | 714.2(2)            | D Felony                 | THEFT 2ND DEGREE                                       | Property                | Theft                      | 19.47         | 
| 2016               | 2015-11-01T00:00:00 | Parole Granted                | Black - Non-Hispanic | Male | 43             | Newton Correctional Facility         | 713.5               | C Felony                 | BURGLARY 2ND DEGREE                                    | Property                | Burglary                   | 34.05         | 
| 2015               | 2015-06-01T00:00:00 | Paroled to Detainer - INS     | White - Hispanic     | Male | 42             | Anamosa State Penitentiary           | 124.401(1)(a)(2)(b) | B Felony                 | Proh Acts-Mfg, Del, Consp or Poss w/Int-Cocaine GT 5kg | Drug                    | Trafficking                | 96.58         | 
| 2014               | 2014-01-01T00:00:00 | Paroled w/Immediate Discharge | White - Non-Hispanic | Male | 24             | Newton Correctional Facility         | 713.5               | C Felony                 | BURGLARY 2ND DEGREE                                    | Property                | Burglary                   | 23.13         | 
| 2015               | 2015-01-01T00:00:00 | Parole Granted                | White - Non-Hispanic | Male | 26             | Clarinda Correctional Facility       | 714.2(1)            | C Felony                 | THEFT 1ST DEGREE                                       | Property                | Theft                      | 17.93         | 
```