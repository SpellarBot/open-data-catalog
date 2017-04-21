# Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 9 - San Francisco

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/impaired-driving-death-rate-by-age-and-gender-2012-region-9-san-francisco-10199) |
| Metadata | [Link](https://data.cdc.gov/api/views/3se3-rwj2) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/3se3-rwj2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/3se3-rwj2/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 3se3-rwj2 |
| Name | Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 9 - San Francisco |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-17T15:55:17Z |
| Publication Date | 2016-09-14T13:55:53Z |

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
series e:3se3-rwj2 d:2012-01-01T00:00:00.000Z t:state=Hawaii m:male_2014=3.6 m:male=5.7 m:ages_35=3.2 m:all_ages_2014=2.2 m:all_ages=3.8

series e:3se3-rwj2 d:2012-01-01T00:00:00.000Z t:state="United States" m:ages_21_34_2014=6.2 m:ages_0_20_2014=1.2 m:male_2014=4.9 m:female_2014=1.4 m:female=1.5 m:ages_21_34=6.7 m:male=5.2 m:ages_0_20=1.3 m:ages_35=3.1 m:all_ages_2014=3.1 m:all_ages=3.3 m:ages_35_2014=3

series e:3se3-rwj2 d:2012-01-01T00:00:00.000Z t:state=Arizona m:ages_21_34_2014=5.5 m:male_2014=4.5 m:female_2014=1.5 m:female=1.7 m:ages_21_34=6.9 m:male=5.4 m:ages_0_20=1.6 m:ages_35=3.3 m:all_ages_2014=3 m:all_ages=3.6 m:ages_35_2014=3.1
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

entity e:3se3-rwj2 l:"Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 9 - San Francisco" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/3se3-rwj2

property e:3se3-rwj2 t:meta.view v:id=3se3-rwj2 v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 9 - San Francisco" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:3se3-rwj2 t:meta.view.license v:name="Public Domain"

property e:3se3-rwj2 t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:3se3-rwj2 t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:3se3-rwj2 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state         | all_ages | all_ages_2014 | ages_0_20 | ages_0_20_2014 | ages_21_34 | ages_21_34_2014 | ages_35 | ages_35_2014 | male | male_2014 | female | female_2014 | 
| ============= | ======== | ============= | ========= | ============== | ========== | =============== | ======= | ============ | ==== | ========= | ====== | =========== | 
| Hawaii        | 3.8      | 2.2           |           |                |            |                 | 3.2     |              | 5.7  | 3.6       |        |             | 
| United States | 3.3      | 3.1           | 1.3       | 1.2            | 6.7        | 6.2             | 3.1     | 3            | 5.2  | 4.9       | 1.5    | 1.4         | 
| Arizona       | 3.6      | 3             | 1.6       |                | 6.9        | 5.5             | 3.3     | 3.1          | 5.4  | 4.5       | 1.7    | 1.5         | 
| California    | 2.0      | 2.2           | 0.9       | 1              | 4.5        | 4.6             | 1.8     | 2            | 3.2  | 3.4       | 1.0    | 1.1         | 
| Nevada        | 2.8      | 3.3           |           |                | 4.6        | 6.4             | 3.2     | 2.7          | 4.2  | 4.9       | 1.4    | 1.7         | 
```