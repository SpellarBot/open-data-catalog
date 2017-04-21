# Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 7 - Kansas City

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/motor-vehicle-occupant-death-rate-by-age-and-gender-2012-region-7-kansas-city) |
| Metadata | [Link](https://data.cdc.gov/api/views/u5yv-9uts) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/u5yv-9uts/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/u5yv-9uts/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | u5yv-9uts |
| Name | Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 7 - Kansas City |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-16T14:13:24Z |
| Publication Date | 2016-10-18T18:11:54Z |

## Description

Rate of deaths by age/gender (per 100,000 population) for motor vehicle occupants killed in crashes, 2012 & 2014. 2012 Source: Fatality Analysis Reporting System (FARS). 2014 Source: National Highway Traffic Safety Administration's (NHTSA) Fatality Analysis Reporting System (FARS), 2014 Annual Report File Note: Blank cells indicate data are suppressed. Fatality rates based on fewer than 20 deaths are suppressed.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name            | Data Type | Render Type |
| ======== | ============== | ============== | =============== | ========= | =========== |
| Yes      | series tag     | state          | State           | text      | text        |
| Yes      | numeric metric | all_ages       | All Ages, 2012  | number    | number      |
| Yes      | numeric metric | all_ages_2014  | All Ages, 2014  | number    | number      |
| Yes      | numeric metric | age_0_20       | Age 0-20, 2012  | number    | number      |
| Yes      | numeric metric | age_0_20_2014  | Age 0-20, 2014  | number    | number      |
| Yes      | numeric metric | age_21_34      | Age 21-34, 2012 | number    | number      |
| Yes      | numeric metric | age_21_34_2014 | Age 21-34, 2014 | number    | number      |
| Yes      | numeric metric | age_35_54      | Age 35-54, 2012 | number    | number      |
| Yes      | numeric metric | age_35_54_2014 | Age 35-54, 2014 | number    | number      |
| Yes      | numeric metric | age_55         | Age 55+, 2012   | number    | number      |
| Yes      | numeric metric | age_55_2014    | Age 55+, 2014   | number    | number      |
| Yes      | numeric metric | male           | Male, 2012      | number    | number      |
| Yes      | numeric metric | male_2014      | Male, 2014      | number    | number      |
| Yes      | numeric metric | female         | Female, 2012    | number    | number      |
| Yes      | numeric metric | female_2014    | Female, 2014    | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:u5yv-9uts d:2012-01-01T00:00:00.000Z t:state=Iowa m:male_2014=9.7 m:female_2014=5 m:age_35_54=9.6 m:age_21_34_2014=8.5 m:male=11.3 m:age_0_20_2014=4.5 m:age_55=10.3 m:all_ages_2014=7.4 m:age_35_54_2014=8.2 m:age_21_34=11.7 m:age_55_2014=8.8 m:female=6 m:age_0_20=4.4 m:all_ages=8.7

series e:u5yv-9uts d:2012-01-01T00:00:00.000Z t:state=Kansas m:male_2014=14.7 m:female_2014=6.2 m:age_35_54=10.7 m:age_21_34_2014=14.6 m:male=15.1 m:age_0_20_2014=5.8 m:age_55=13.1 m:all_ages_2014=10.4 m:age_35_54_2014=8.8 m:age_21_34=13.9 m:age_55_2014=13.6 m:female=6.7 m:age_0_20=7.5 m:all_ages=11

series e:u5yv-9uts d:2012-01-01T00:00:00.000Z t:state="United States" m:male_2014=9.2 m:female_2014=4.5 m:age_35_54=6.8 m:age_21_34_2014=10.1 m:male=9.4 m:age_0_20_2014=3.7 m:age_55=8.1 m:all_ages_2014=6.8 m:age_35_54_2014=6.6 m:age_21_34=10.8 m:age_55_2014=7.8 m:female=4.7 m:age_0_20=4 m:all_ages=7
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

entity e:u5yv-9uts l:"Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 7 - Kansas City" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/u5yv-9uts

property e:u5yv-9uts t:meta.view v:id=u5yv-9uts v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 7 - Kansas City" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:u5yv-9uts t:meta.view.license v:name="Public Domain"

property e:u5yv-9uts t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:u5yv-9uts t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:u5yv-9uts t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state         | all_ages | all_ages_2014 | age_0_20 | age_0_20_2014 | age_21_34 | age_21_34_2014 | age_35_54 | age_35_54_2014 | age_55 | age_55_2014 | male | male_2014 | female | female_2014 | 
| ============= | ======== | ============= | ======== | ============= | ========= | ============== | ========= | ============== | ====== | =========== | ==== | ========= | ====== | =========== | 
| Iowa          | 8.7      | 7.4           | 4.4      | 4.5           | 11.7      | 8.5            | 9.6       | 8.2            | 10.3   | 8.8         | 11.3 | 9.7       | 6.0    | 5.0         | 
| Kansas        | 11.0     | 10.4          | 7.5      | 5.8           | 13.9      | 14.6           | 10.7      | 8.8            | 13.1   | 13.6        | 15.1 | 14.7      | 6.7    | 6.2         | 
| United States | 7.0      | 6.8           | 4.0      | 3.7           | 10.8      | 10.1           | 6.8       | 6.6            | 8.1    | 7.8         | 9.4  | 9.2       | 4.7    | 4.5         | 
| Nebraska      | 9.2      | 10.3          | 7.7      | 4.7           | 13.6      | 16.8           | 8.1       | 11.6           | 9.1    | 9.7         | 12.8 | 14.3      | 5.7    | 6.2         | 
| Missouri      | 10.2     | 9.5           | 5.5      | 6.2           | 15.3      | 12.8           | 11.6      | 9.2            | 10.4   | 10.7        | 14.2 | 13.8      | 6.3    | 5.3         | 
```