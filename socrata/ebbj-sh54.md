# Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, All States

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/impaired-driving-death-rate-by-age-and-gender-2012-all-states-587fd) |
| Metadata | [Link](https://data.cdc.gov/api/views/ebbj-sh54) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/ebbj-sh54/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/ebbj-sh54/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | ebbj-sh54 |
| Name | Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, All States |
| Attribution | National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-15T15:25:53Z |
| Publication Date | 2016-09-26T19:17:17Z |

## Description

Rate of deaths by age/gender (per 100,000 population) for people killed in crashes involving a driver with BAC =>0.08%, 2012. 2012 Source: Fatality Analysis Reporting System (FARS)Note: Blank cells indicate data are suppressed. 2014 Source: Source: National Highway Traffic Administration's (NHTSA) Fatality Analysis Reporting System (FARS), 2014 Annual Report File. Fatality rates based on fewer than 20 deaths are suppressed.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name             | Data Type | Render Type |
| ======== | ============== | ================== | ================ | ========= | =========== |
| Yes      | series tag     | state_not_geocoded | State            | text      | text        |
| Yes      | numeric metric | all_ages           | All Ages, 2012   | number    | number      |
| Yes      | numeric metric | all_ages_2014      | All Ages, 2014   | number    | number      |
| Yes      | numeric metric | ages_0_20          | Ages 0-20, 2012  | number    | number      |
| Yes      | numeric metric | ages_0_20_2014     | Ages 0-20, 2014  | number    | number      |
| Yes      | numeric metric | ages_21_34         | Ages 21-34, 2012 | number    | number      |
| Yes      | numeric metric | ages_21_34_2014    | Ages 21-34, 2014 | number    | number      |
| Yes      | numeric metric | ages_35            | Ages 35+, 2012   | number    | number      |
| Yes      | numeric metric | ages_35_2014       | Ages 35+, 2014   | number    | number      |
| Yes      | numeric metric | male               | Male, 2012       | number    | number      |
| Yes      | numeric metric | male_2014          | Male, 2014       | number    | number      |
| Yes      | numeric metric | female             | Female, 2012     | number    | number      |
| Yes      | numeric metric | female_2014        | Female, 2014     | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ebbj-sh54 d:2012-01-01T00:00:00.000Z t:state_not_geocoded="United States" m:ages_21_34_2014=6.2 m:ages_0_20_2014=1.2 m:male_2014=4.9 m:female_2014=1.4 m:female=1.5 m:ages_21_34=6.7 m:male=5.2 m:ages_0_20=1.3 m:ages_35=3.1 m:all_ages_2014=3.1 m:all_ages=3.3 m:ages_35_2014=3

series e:ebbj-sh54 d:2012-01-01T00:00:00.000Z t:state_not_geocoded=Alabama m:ages_21_34_2014=10 m:ages_0_20_2014=2.1 m:male_2014=8.6 m:female_2014=2.6 m:female=2.9 m:ages_21_34=10.3 m:male=8.4 m:ages_0_20=2.7 m:ages_35=5 m:all_ages_2014=5.5 m:all_ages=5.5 m:ages_35_2014=5.5

series e:ebbj-sh54 d:2012-01-01T00:00:00.000Z t:state_not_geocoded=Alaska m:all_ages_2014=2.8
```

## Meta Commands

```ls
metric m:all_ages p:float l:"All Ages, 2012" t:dataTypeName=number

metric m:all_ages_2014 p:float l:"All Ages, 2014" t:dataTypeName=number

metric m:ages_0_20 p:float l:"Ages 0-20, 2012" t:dataTypeName=number

metric m:ages_0_20_2014 p:float l:"Ages 0-20, 2014" t:dataTypeName=number

metric m:ages_21_34 p:float l:"Ages 21-34, 2012" t:dataTypeName=number

metric m:ages_21_34_2014 p:float l:"Ages 21-34, 2014" t:dataTypeName=number

metric m:ages_35 p:double l:"Ages 35+, 2012" t:dataTypeName=number

metric m:ages_35_2014 p:float l:"Ages 35+, 2014" t:dataTypeName=number

metric m:male p:float l:"Male, 2012" t:dataTypeName=number

metric m:male_2014 p:float l:"Male, 2014" t:dataTypeName=number

metric m:female p:double l:"Female, 2012" t:dataTypeName=number

metric m:female_2014 p:float l:"Female, 2014" t:dataTypeName=number

entity e:ebbj-sh54 l:"Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, All States" t:attribution="National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/ebbj-sh54

property e:ebbj-sh54 t:meta.view v:id=ebbj-sh54 v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety v:averageRating=0 v:name="Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, All States" v:attribution="National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:ebbj-sh54 t:meta.view.license v:name="Public Domain"

property e:ebbj-sh54 t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:ebbj-sh54 t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:ebbj-sh54 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state_not_geocoded   | all_ages           | all_ages_2014 | ages_0_20 | ages_0_20_2014 | ages_21_34 | ages_21_34_2014 | ages_35 | ages_35_2014 | male | male_2014 | female             | female_2014 | 
| ==================== | ================== | ============= | ========= | ============== | ========== | =============== | ======= | ============ | ==== | ========= | ================== | =========== | 
| United States        | 3.3                | 3.1           | 1.3       | 1.2            | 6.7        | 6.2             | 3.1     | 3.0          | 5.2  | 4.9       | 1.5                | 1.4         | 
| Alabama              | 5.5                | 5.5           | 2.7       | 2.1            | 10.3       | 10.0            | 5       | 5.5          | 8.4  | 8.6       | 2.9                | 2.6         | 
| Alaska               |                    | 2.8           |           |                |            |                 |         |              |      |           |                    |             | 
| Arizona              | 3.6                | 3.0           | 1.6       |                | 6.9        | 5.5             | 3.3     | 3.1          | 5.4  | 4.5       | 1.7                | 1.5         | 
| Arkansas             | 5.0999999999999996 | 4.6           |           |                | 10.5       | 6.3             | 4.3     | 5.4          | 8.1  | 7.2       | 2.2000000000000002 | 2.2         | 
| California           | 2                  | 2.2           | 0.9       | 1.0            | 4.5        | 4.6             | 1.8     | 2.0          | 3.2  | 3.4       | 1                  | 1.1         | 
| Colorado             | 2.5                | 3.0           |           | 1.7            | 5.6        | 5.6             | 2       | 2.6          | 3.9  | 4.6       | 1.1000000000000001 | 1.3         | 
| Connecticut          | 2.4                | 2.7           |           |                | 5.9        | 6.1             | 2.1     | 2.5          | 3.7  | 4.6       | 1.1000000000000001 |             | 
| Delaware             | 3.8                | 5.2           |           |                |            | 11.7            | 4       | 4.6          | 6.6  | 7.4       |                    |             | 
| District of Columbia |                    |               |           |                |            |                 |         |              |      |           |                    |             | 
```