# Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 3 - Philadelphia

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/impaired-driving-death-rate-by-age-and-gender-2012-region-3-philadelphia-42bcb) |
| Metadata | [Link](https://data.cdc.gov/api/views/pvxp-wfpg) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/pvxp-wfpg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/pvxp-wfpg/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | pvxp-wfpg |
| Name | Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 3 - Philadelphia |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-17T15:44:24Z |
| Publication Date | 2016-09-14T15:28:51Z |

## Description

Rate of deaths by age/gender (per 100,000 population) for people killed in crashes involving a driver with BAC =>0.08%, 2012, 2014. 2012 Source: Fatality Analysis Reporting System (FARS). 2014 Source: National Highway Traffic Administration's (NHTSA) Fatality Analysis Reporting System (FARS), 2014 Annual Report File. Note: Blank cells indicate data are suppressed. Fatality rates based on fewer than 20 deaths are suppressed.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type | Render Type |
| ======== | ============== | =============== | ================ | ========= | =========== |
| Yes      | series tag     | state           | State            | text      | text        |
| Yes      | numeric metric | all_ages        | All Ages, 2012   | number    | number      |
| Yes      | numeric metric | all_ages_2014   | All Ages, 2014   | number    | number      |
| Yes      | numeric metric | ages_0_20       | Ages 0-20, 2012  | number    | number      |
| Yes      | numeric metric | ages_0_20_2014  | Ages 0-20, 2014  | number    | number      |
| Yes      | numeric metric | ages_21_34      | Ages 21-34, 2012 | number    | number      |
| Yes      | numeric metric | ages_21_34_2014 | Ages 21-34, 2014 | number    | number      |
| Yes      | numeric metric | ages_35         | Ages 35+, 2012   | number    | number      |
| Yes      | numeric metric | ages_35_2014    | Ages 35+, 2014   | number    | number      |
| Yes      | numeric metric | male            | Male, 2012       | number    | number      |
| Yes      | numeric metric | male_2014       | Male, 2014       | number    | number      |
| Yes      | numeric metric | female          | Female, 2012     | number    | number      |
| Yes      | numeric metric | female_2014     | Female, 2014     | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pvxp-wfpg d:2012-01-01T00:00:00.000Z t:state=Delaware m:ages_21_34_2014=11.7 m:male_2014=7.4 m:male=6.6 m:ages_35=4 m:all_ages_2014=5.2 m:all_ages=3.8 m:ages_35_2014=4.6

series e:pvxp-wfpg d:2012-01-01T00:00:00.000Z t:state="West Virginia" m:ages_21_34_2014=10 m:male_2014=7.1 m:ages_21_34=12.9 m:male=9.3 m:ages_35=4.4 m:all_ages_2014=4.7 m:all_ages=5.6 m:ages_35_2014=4

series e:pvxp-wfpg d:2012-01-01T00:00:00.000Z t:state="United States" m:ages_21_34_2014=6.2 m:ages_0_20_2014=1.2 m:male_2014=4.9 m:female_2014=1.4 m:female=1.5 m:ages_21_34=6.7 m:male=5.2 m:ages_0_20=1.3 m:ages_35=3.1 m:all_ages_2014=3.1 m:all_ages=3.3 m:ages_35_2014=3
```

## Meta Commands

```ls
metric m:all_ages p:float l:"All Ages, 2012" t:dataTypeName=number

metric m:all_ages_2014 p:float l:"All Ages, 2014" t:dataTypeName=number

metric m:ages_0_20 p:float l:"Ages 0-20, 2012" t:dataTypeName=number

metric m:ages_0_20_2014 p:float l:"Ages 0-20, 2014" t:dataTypeName=number

metric m:ages_21_34 p:float l:"Ages 21-34, 2012" t:dataTypeName=number

metric m:ages_21_34_2014 p:float l:"Ages 21-34, 2014" t:dataTypeName=number

metric m:ages_35 p:float l:"Ages 35+, 2012" t:dataTypeName=number

metric m:ages_35_2014 p:float l:"Ages 35+, 2014" t:dataTypeName=number

metric m:male p:float l:"Male, 2012" t:dataTypeName=number

metric m:male_2014 p:float l:"Male, 2014" t:dataTypeName=number

metric m:female p:float l:"Female, 2012" t:dataTypeName=number

metric m:female_2014 p:float l:"Female, 2014" t:dataTypeName=number

entity e:pvxp-wfpg l:"Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 3 - Philadelphia" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/pvxp-wfpg

property e:pvxp-wfpg t:meta.view v:id=pvxp-wfpg v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 3 - Philadelphia" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:pvxp-wfpg t:meta.view.license v:name="Public Domain"

property e:pvxp-wfpg t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:pvxp-wfpg t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:pvxp-wfpg t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state                | all_ages | all_ages_2014 | ages_0_20 | ages_0_20_2014 | ages_21_34 | ages_21_34_2014 | ages_35 | ages_35_2014 | male | male_2014 | female | female_2014 | 
| ==================== | ======== | ============= | ========= | ============== | ========== | =============== | ======= | ============ | ==== | ========= | ====== | =========== | 
| Delaware             | 3.8      | 5.2           |           |                |            | 11.7            | 4.0     | 4.6          | 6.6  | 7.4       |        |             | 
| District of Columbia |          |               |           |                |            |                 |         |              |      |           |        |             | 
| West Virginia        | 5.6      | 4.7           |           |                | 12.9       | 10              | 4.4     | 4            | 9.3  | 7.1       |        |             | 
| United States        | 3.3      | 3.1           | 1.3       | 1.2            | 6.7        | 6.2             | 3.1     | 3            | 5.2  | 4.9       | 1.5    | 1.4         | 
| Maryland             | 2.7      | 2.2           | 1.6       |                | 5.8        | 5.4             | 2.2     | 1.8          | 4.1  | 3.5       | 1.4    | 0.9         | 
| Pennsylvania         | 3.3      | 2.7           | 1.4       | 0.7            | 7.2        | 5.5             | 2.8     | 2.7          | 5.4  | 4.4       | 1.3    | 1.1         | 
| Virginia             | 2.5      | 2.5           | 1.2       | 1.2            | 4.5        | 5.1             | 2.6     | 2.3          | 4.1  | 3.9       | 0.9    | 1.2         | 
```