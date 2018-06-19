# Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, All States

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/motor-vehicle-occupant-death-rate-by-age-and-gender-2012-all-states-2997e) |
| Metadata | [Link](https://data.cdc.gov/api/views/rqg5-mkef) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/rqg5-mkef/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/rqg5-mkef/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | rqg5-mkef |
| Name | Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, All States |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | death rate, motor vehicle |
| Created | 2014-12-12T17:06:57Z |
| Publication Date | 2016-10-17T11:30:02Z |

## Description

Rate of deaths by age/gender (per 100,000 population) for motor vehicle occupants killed in crashes, 2012 & 2014. 2012 Source: Fatality Analysis Reporting System (FARS). 2014 Source: National Highway Traffic Safety Administration's (NHTSA) Fatality Analysis Reporting System (FARS), 2014 Annual Report File Note: Blank cells indicate data are suppressed. Fatality rates based on fewer than 20 deaths are suppressed.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name            | Data Type | Render Type |
| ======== | ============== | ================== | =============== | ========= | =========== |
| Yes      | series tag     | state_not_geocoded | State           | text      | text        |
| Yes      | numeric metric | all_ages           | All Ages, 2012  | number    | number      |
| Yes      | numeric metric | all_ages_2014      | All Ages, 2014  | number    | number      |
| Yes      | numeric metric | age_0_20           | Age 0-20, 2012  | number    | number      |
| Yes      | numeric metric | age_0_20_2014      | Age 0-20, 2014  | number    | number      |
| Yes      | numeric metric | age_21_34          | Age 21-34, 2012 | number    | number      |
| Yes      | numeric metric | age_21_34_2014     | Age 21-34, 2014 | number    | number      |
| Yes      | numeric metric | age_35_54          | Age 35-54, 2012 | number    | number      |
| Yes      | numeric metric | age_35_54_2014     | Age 35-54, 2014 | number    | number      |
| Yes      | numeric metric | age_55             | Age 55+, 2012   | number    | number      |
| Yes      | numeric metric | age_55_2014        | Age 55+, 2014   | number    | number      |
| Yes      | numeric metric | male               | Male, 2012      | number    | number      |
| Yes      | numeric metric | male_2014          | Male, 2014      | number    | number      |
| Yes      | numeric metric | female             | Female, 2012    | number    | number      |
| Yes      | numeric metric | female_2014        | Female, 2014    | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rqg5-mkef d:2012-01-01T00:00:00.000Z m:age_0_20_2014=4.3

series e:rqg5-mkef d:2012-01-01T00:00:00.000Z t:state_not_geocoded=California m:male_2014=5.7 m:female_2014=2.8 m:age_35_54=4 m:age_21_34_2014=6.9 m:male=5.6 m:age_0_20_2014=2.7 m:age_55=4.5 m:all_ages_2014=4.3 m:age_35_54_2014=3.5 m:age_21_34=6.9 m:age_55_2014=4.7 m:female=2.7 m:age_0_20=2.4 m:all_ages=4.2

series e:rqg5-mkef d:2012-01-01T00:00:00.000Z t:state_not_geocoded=Massachusetts m:male_2014=4.6 m:female_2014=1.5 m:age_35_54=2.2 m:age_21_34_2014=4.4 m:male=4.1 m:age_0_20_2014=1.2 m:age_55=3.9 m:all_ages_2014=3 m:age_35_54_2014=3.1 m:age_21_34=4.7 m:age_55_2014=3.7 m:female=1.7 m:age_0_20=1.8 m:all_ages=2.9
```

## Meta Commands

```ls
metric m:all_ages p:float l:"All Ages, 2012" t:dataTypeName=number

metric m:all_ages_2014 p:float l:"All Ages, 2014" t:dataTypeName=number

metric m:age_0_20 p:float l:"Age 0-20, 2012" t:dataTypeName=number

metric m:age_0_20_2014 p:float l:"Age 0-20, 2014" t:dataTypeName=number

metric m:age_21_34 p:float l:"Age 21-34, 2012" t:dataTypeName=number

metric m:age_21_34_2014 p:float l:"Age 21-34, 2014" t:dataTypeName=number

metric m:age_35_54 p:float l:"Age 35-54, 2012" t:dataTypeName=number

metric m:age_35_54_2014 p:float l:"Age 35-54, 2014" t:dataTypeName=number

metric m:age_55 p:float l:"Age 55+, 2012" t:dataTypeName=number

metric m:age_55_2014 p:float l:"Age 55+, 2014" t:dataTypeName=number

metric m:male p:float l:"Male, 2012" t:dataTypeName=number

metric m:male_2014 p:float l:"Male, 2014" t:dataTypeName=number

metric m:female p:float l:"Female, 2012" t:dataTypeName=number

metric m:female_2014 p:float l:"Female, 2014" t:dataTypeName=number

entity e:rqg5-mkef l:"Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, All States" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/rqg5-mkef

property e:rqg5-mkef t:meta.view v:id=rqg5-mkef v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, All States" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:rqg5-mkef t:meta.view.license v:name="Public Domain"

property e:rqg5-mkef t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:rqg5-mkef t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:rqg5-mkef t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state_not_geocoded | all_ages | all_ages_2014 | age_0_20 | age_0_20_2014 | age_21_34 | age_21_34_2014 | age_35_54 | age_35_54_2014 | age_55 | age_55_2014 | male | male_2014 | female | female_2014        | 
| ================== | ======== | ============= | ======== | ============= | ========= | ============== | ========= | ============== | ====== | =========== | ==== | ========= | ====== | ================== | 
|                    |          |               |          | 4.3           |           |                |           |                |        |             |      |           |        |                    | 
| California         | 4.2      | 4.3           | 2.4      | 2.7           | 6.9       | 6.9            | 4.0       | 3.5            | 4.5    | 4.7         | 5.6  | 5.7       | 2.7    | 2.8                | 
| Massachusetts      | 2.9      | 3.0           | 1.8      | 1.2           | 4.7       | 4.4            | 2.2       | 3.1            | 3.9    | 3.7         | 4.1  | 4.6       | 1.7    | 1.5                | 
| Idaho              | 8.6      | 8.6           | 4.5      | 5.4           | 12.0      | 11.4           | 8.8       | 7.3            | 10.9   | 10.6        | 10.4 | 10.6      | 6.9    | 6.5                | 
| South Dakota       | 12.0     | 12.5          | 9.5      |               | 17.9      | 16.1           | 12.1      | 10.3           | 10.1   | 16.9        | 15.4 | 17.1      | 8.5    | 7.7                | 
| New Jersey         | 3.6      | 3.4           | 2.1      | 2.1           | 6.2       | 4.5            | 2.8       | 2.9            | 4.7    | 4.5         | 5.0  | 4.7       | 2.4    | 2.2000000000000002 | 
| Michigan           | 6.2      | 6.0           | 3.8      | 3.7           | 10.9      | 9.4            | 4.9       | 5.6            | 7.5    | 6.4         | 8.3  | 7.8       | 4.2    | 4.3                | 
| Texas              | 9.1      | 9.5           | 5.2      | 5.1           | 14.5      | 14.7           | 8.9       | 9.0            | 9.5    | 10.5        | 12.2 | 13.0      | 6.0    | 6.1                | 
| Georgia            | 8.5      | 8.3           | 3.9      | 3.7           | 12.1      | 11.1           | 8.2       | 8.5            | 12.1   | 10.6        | 11.7 | 11.3      | 5.5    | 5.5                | 
| Maine              | 9.4      | 7.5           | 6.6      |               | 18.0      | 9.8            | 7.3       | 8.1            | 9.1    | 9.3         | 13.2 | 10.1      | 5.8    | 5.0                | 
```