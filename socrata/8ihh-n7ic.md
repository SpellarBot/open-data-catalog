# Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 6 - Dallas

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/motor-vehicle-occupant-death-rate-by-age-and-gender-2012-region-6-dallas-f4c8a) |
| Metadata | [Link](https://data.cdc.gov/api/views/8ihh-n7ic) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/8ihh-n7ic/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/8ihh-n7ic/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 8ihh-n7ic |
| Name | Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 6 - Dallas |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-16T14:11:56Z |
| Publication Date | 2016-10-18T18:09:59Z |

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
series e:8ihh-n7ic d:2012-01-01T00:00:00.000Z t:state=Oklahoma m:male_2014=18.9 m:female_2014=9.7 m:age_35_54=15.7 m:age_21_34_2014=16.1 m:male=19.2 m:age_0_20_2014=7.9 m:age_55=15.9 m:all_ages_2014=14.2 m:age_35_54_2014=15.7 m:age_21_34=22.7 m:age_55_2014=17.6 m:female=9.6 m:age_0_20=6 m:all_ages=14.3

series e:8ihh-n7ic d:2012-01-01T00:00:00.000Z t:state=Texas m:male_2014=13 m:female_2014=6.1 m:age_35_54=8.9 m:age_21_34_2014=14.7 m:male=12.2 m:age_0_20_2014=5.1 m:age_55=9.5 m:all_ages_2014=9.5 m:age_35_54_2014=9 m:age_21_34=14.5 m:age_55_2014=10.5 m:female=6 m:age_0_20=5.2 m:all_ages=9.1

series e:8ihh-n7ic d:2012-01-01T00:00:00.000Z t:state="United States" m:male_2014=9.2 m:female_2014=4.5 m:age_35_54=6.8 m:age_21_34_2014=10.1 m:male=9.4 m:age_0_20_2014=3.7 m:age_55=8.1 m:all_ages_2014=6.8 m:age_35_54_2014=6.6 m:age_21_34=10.8 m:age_55_2014=7.8 m:female=4.7 m:age_0_20=4 m:all_ages=7
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

entity e:8ihh-n7ic l:"Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 6 - Dallas" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/8ihh-n7ic

property e:8ihh-n7ic t:meta.view v:id=8ihh-n7ic v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 6 - Dallas" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:8ihh-n7ic t:meta.view.license v:name="Public Domain"

property e:8ihh-n7ic t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:8ihh-n7ic t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:8ihh-n7ic t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state         | all_ages | all_ages_2014 | age_0_20 | age_0_20_2014 | age_21_34 | age_21_34_2014 | age_35_54 | age_35_54_2014 | age_55 | age_55_2014 | male | male_2014 | female | female_2014 | 
| ============= | ======== | ============= | ======== | ============= | ========= | ============== | ========= | ============== | ====== | =========== | ==== | ========= | ====== | =========== | 
| Oklahoma      | 14.3     | 14.2          | 6.0      | 7.9           | 22.7      | 16.1           | 15.7      | 15.7           | 15.9   | 17.6        | 19.2 | 18.9      | 9.6    | 9.7         | 
| Texas         | 9.1      | 9.5           | 5.2      | 5.1           | 14.5      | 14.7           | 8.9       | 9.0            | 9.5    | 10.5        | 12.2 | 13.0      | 6.0    | 6.1         | 
| United States | 7.0      | 6.8           | 4.0      | 3.7           | 10.8      | 10.1           | 6.8       | 6.6            | 8.1    | 7.8         | 9.4  | 9.2       | 4.7    | 4.5         | 
| New Mexico    | 11.1     | 11.9          | 6.0      | 7.0           | 14.3      | 21.6           | 13.7      | 13.2           | 11.0   | 8.5         | 15.1 | 15.6      | 6.9    | 8.2         | 
| Arkansas      | 13.8     | 12.0          | 8.0      | 6.2           | 20.3      | 15.1           | 13.8      | 13.6           | 16.2   | 14.0        | 17.3 | 16.0      | 10.4   | 8.1         | 
| Louisiana     | 10.4     | 11.2          | 6.9      | 5.9           | 15.6      | 16.9           | 10.3      | 12.6           | 10.5   | 11.0        | 13.9 | 16.4      | 7.1    | 6.4         | 
```