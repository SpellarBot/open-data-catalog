# Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 8 - Denver

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/impaired-driving-death-rate-by-age-and-gender-2012-region-8-denver-0d868) |
| Metadata | [Link](https://data.cdc.gov/api/views/3bjr-fr6m) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/3bjr-fr6m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/3bjr-fr6m/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 3bjr-fr6m |
| Name | Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 8 - Denver |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-17T15:53:50Z |
| Publication Date | 2016-09-14T14:40:58Z |

## Description

Rate of deaths by age/gender (per 100,000 population) for people killed in crashes involving a driver with BAC =>0.08%, 2012, 2014. 2012 Source: Fatality Analysis Reporting System (FARS). 2014 Source: National Highway Traffic Administration's (NHTSA) Fatality Analysis Reporting System (FARS), 2014 Annual Report File. Note: Blank cells indicate data are suppressed. Fatality rates based on fewer than 20 deaths are suppressed.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type | Render Type |
| ======== | ============== | =============== | ================ | ========= | =========== |
| Yes      | series tag     | state           | State            | text      | text        |
| Yes      | numeric metric | all_ages        | All Ages, 2012   | number    | number      |
| Yes      | numeric metric | all_ages_2014   | All Ages, 2014   | number    | number      |
| Yes      | numeric metric | ages_0_20       | Ages 0-20, 2012  | number    | text        |
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
series e:3bjr-fr6m d:2012-01-01T00:00:00.000Z t:state="North Dakota" m:ages_21_34_2014=15.2 m:male_2014=10.7 m:ages_21_34=15.3 m:male=17.4 m:ages_35=12 m:all_ages_2014=7.2 m:all_ages=11.3 m:ages_35_2014=6.1

series e:3bjr-fr6m d:2012-01-01T00:00:00.000Z t:state="South Dakota" m:male_2014=8.7 m:male=7.4 m:all_ages_2014=5.6 m:all_ages=5.7 m:ages_35_2014=6.2

series e:3bjr-fr6m d:2012-01-01T00:00:00.000Z t:state=Utah m:male_2014=3 m:male=1.7 m:ages_35=1.9 m:all_ages_2014=2 m:all_ages=1.2 m:ages_35_2014=2.3
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

entity e:3bjr-fr6m l:"Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 8 - Denver" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/3bjr-fr6m

property e:3bjr-fr6m t:meta.view v:id=3bjr-fr6m v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 8 - Denver" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:3bjr-fr6m t:meta.view.license v:name="Public Domain"

property e:3bjr-fr6m t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:3bjr-fr6m t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:3bjr-fr6m t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state         | all_ages | all_ages_2014 | ages_0_20 | ages_0_20_2014 | ages_21_34 | ages_21_34_2014 | ages_35 | ages_35_2014 | male | male_2014 | female | female_2014 | 
| ============= | ======== | ============= | ========= | ============== | ========== | =============== | ======= | ============ | ==== | ========= | ====== | =========== | 
| North Dakota  | 11.3     | 7.2           |           |                | 15.3       | 15.2            | 12.0    | 6.1          | 17.4 | 10.7      |        |             | 
| South Dakota  | 5.7      | 5.6           |           |                |            |                 |         | 6.2          | 7.4  | 8.7       |        |             | 
| Utah          | 1.2      | 2             |           |                |            |                 | 1.9     | 2.3          | 1.7  | 3         |        |             | 
| Wyoming       | 7.1      | 8.2           |           |                | 17.3       |                 |         | 8.1          | 11.3 | 13.1      |        |             | 
| United States | 3.3      | 3.1           | 1.3       | 1.2            | 6.7        | 6.2             | 3.1     | 3            | 5.2  | 4.9       | 1.5    | 1.4         | 
| Colorado      | 2.5      | 3             |           | 1.7            | 5.6        | 5.6             | 2.0     | 2.6          | 3.9  | 4.6       | 1.1    | 1.3         | 
| Montana       | 9.4      | 7.3           |           |                | 21.4       | 15.4            | 7.2     | 6.9          | 14.9 | 10.2      | 4.0    | 4.3         | 
```