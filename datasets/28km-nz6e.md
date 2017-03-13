# Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 4 - Atlanta

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/impaired-driving-death-rate-by-age-and-gender-2012-region-4-atlanta) |
| Metadata | [Link](https://data.cdc.gov/api/views/28km-nz6e) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/28km-nz6e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/28km-nz6e/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 28km-nz6e |
| Name | Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 4 - Atlanta |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-17T15:46:24Z |
| Publication Date | 2016-09-14T15:18:14Z |
| Rows Updated | 2016-09-14T15:16:48Z |

## Description

Rate of deaths by age/gender (per 100,000 population) for people killed in crashes involving a driver with BAC =>0.08%, 2012, 2014. 2012 Source: Fatality Analysis Reporting System (FARS). 2014 Source: National Highway Traffic Administration's (NHTSA) Fatality Analysis Reporting System (FARS), 2014 Annual Report File. Note: Blank cells indicate data are suppressed. Fatality rates based on fewer than 20 deaths are suppressed.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type | Render Type |
| ======== | ============== | =============== | ================ | ========= | =========== |
| No       | time           | :updated_at     | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | state           | State            | text      | text        |
| Yes      | numeric metric | all_ages        | All Ages, 2012   | number    | number      |
| Yes      | numeric metric | ages_0_20       | Ages 0-20, 2012  | number    | number      |
| Yes      | numeric metric | ages_21_34      | Ages 21-34, 2012 | number    | number      |
| Yes      | numeric metric | ages_35         | Ages 35+, 2012   | number    | number      |
| Yes      | numeric metric | male            | Male, 2012       | number    | number      |
| Yes      | numeric metric | female          | Female, 2012     | number    | number      |
| Yes      | numeric metric | all_ages_2014   | All Ages, 2014   | number    | number      |
| Yes      | numeric metric | ages_0_20_2014  | Ages 0-20, 2014  | number    | number      |
| Yes      | numeric metric | ages_21_34_2014 | Ages 21-34, 2014 | number    | number      |
| Yes      | numeric metric | ages_35_2014    | Ages 35+, 2014   | number    | number      |
| Yes      | numeric metric | male_2014       | Male, 2014       | number    | number      |
| Yes      | numeric metric | female_2014     | Female, 2014     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:28km-nz6e d:2016-09-14T15:16:34.000Z t:state="United States" m:ages_21_34_2014=6.2 m:ages_0_20_2014=1.2 m:male_2014=4.9 m:female_2014=1.4 m:female=1.5 m:ages_21_34=6.7 m:male=5.2 m:ages_0_20=1.3 m:ages_35=3.1 m:all_ages_2014=3.1 m:all_ages=3.3 m:ages_35_2014=3

series e:28km-nz6e d:2016-09-14T15:16:37.000Z t:state=Alabama m:ages_21_34_2014=10 m:ages_0_20_2014=2.1 m:male_2014=8.6 m:female_2014=2.6 m:female=2.9 m:ages_21_34=10.3 m:male=8.4 m:ages_0_20=2.7 m:ages_35=5 m:all_ages_2014=5.5 m:all_ages=5.5 m:ages_35_2014=5.5

series e:28km-nz6e d:2016-09-14T15:16:38.000Z t:state=Florida m:ages_21_34_2014=7.4 m:ages_0_20_2014=1.2 m:male_2014=5.4 m:female_2014=1.7 m:female=1.7 m:ages_21_34=8 m:male=5.7 m:ages_0_20=1.2 m:ages_35=3.3 m:all_ages_2014=3.5 m:all_ages=3.7 m:ages_35_2014=3.1
```

## Meta Commands

```ls
metric m:all_ages p:float l:"All Ages, 2012" t:dataTypeName=number

metric m:ages_0_20 p:float l:"Ages 0-20, 2012" t:dataTypeName=number

metric m:ages_21_34 p:float l:"Ages 21-34, 2012" t:dataTypeName=number

metric m:ages_35 p:float l:"Ages 35+, 2012" t:dataTypeName=number

metric m:male p:float l:"Male, 2012" t:dataTypeName=number

metric m:female p:float l:"Female, 2012" t:dataTypeName=number

metric m:all_ages_2014 p:double l:"All Ages, 2014" t:dataTypeName=number

metric m:ages_0_20_2014 p:float l:"Ages 0-20, 2014" t:dataTypeName=number

metric m:ages_21_34_2014 p:float l:"Ages 21-34, 2014" t:dataTypeName=number

metric m:ages_35_2014 p:float l:"Ages 35+, 2014" t:dataTypeName=number

metric m:male_2014 p:float l:"Male, 2014" t:dataTypeName=number

metric m:female_2014 p:float l:"Female, 2014" t:dataTypeName=number

entity e:28km-nz6e l:"Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 4 - Atlanta" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/28km-nz6e

property e:28km-nz6e t:meta.view v:id=28km-nz6e v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 4 - Atlanta" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:28km-nz6e t:meta.view.license v:name="Public Domain"

property e:28km-nz6e t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:28km-nz6e t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:28km-nz6e t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```