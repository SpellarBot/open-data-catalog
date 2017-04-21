# Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 2 - New York

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/motor-vehicle-occupant-death-rate-by-age-and-gender-2012-region-2-new-york-5a403) |
| Metadata | [Link](https://data.cdc.gov/api/views/fj6s-ssz6) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/fj6s-ssz6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/fj6s-ssz6/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | fj6s-ssz6 |
| Name | Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 2 - New York |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-16T14:02:02Z |
| Publication Date | 2016-10-18T18:03:24Z |

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
series e:fj6s-ssz6 d:2012-01-01T00:00:00.000Z t:state="New York" m:male_2014=3.8 m:female_2014=1.8 m:age_35_54=2.9 m:age_21_34_2014=3.9 m:male=4.2 m:age_0_20_2014=1.3 m:age_55=4.4 m:all_ages_2014=2.8 m:age_35_54_2014=2.6 m:age_21_34=4.1 m:age_55_2014=3.7 m:female=2 m:age_0_20=1.7 m:all_ages=3.1

series e:fj6s-ssz6 d:2012-01-01T00:00:00.000Z t:state="New Jersey" m:male_2014=4.7 m:female_2014=2.2 m:age_35_54=2.8 m:age_21_34_2014=4.5 m:male=5 m:age_0_20_2014=2.1 m:age_55=4.7 m:all_ages_2014=3.4 m:age_35_54_2014=2.9 m:age_21_34=6.2 m:age_55_2014=4.5 m:female=2.4 m:age_0_20=2.1 m:all_ages=3.6

series e:fj6s-ssz6 d:2012-01-01T00:00:00.000Z t:state="United States" m:male_2014=9.2 m:female_2014=4.5 m:age_35_54=6.8 m:age_21_34_2014=10.1 m:male=9.4 m:age_0_20_2014=3.7 m:age_55=8.1 m:all_ages_2014=6.8 m:age_35_54_2014=6.6 m:age_21_34=10.8 m:age_55_2014=7.8 m:female=4.7 m:age_0_20=4 m:all_ages=7
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

entity e:fj6s-ssz6 l:"Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 2 - New York" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/fj6s-ssz6

property e:fj6s-ssz6 t:meta.view v:id=fj6s-ssz6 v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 2 - New York" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:fj6s-ssz6 t:meta.view.license v:name="Public Domain"

property e:fj6s-ssz6 t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:fj6s-ssz6 t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:fj6s-ssz6 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state         | all_ages | all_ages_2014 | age_0_20 | age_0_20_2014 | age_21_34 | age_21_34_2014 | age_35_54 | age_35_54_2014 | age_55 | age_55_2014 | male | male_2014 | female | female_2014 | 
| ============= | ======== | ============= | ======== | ============= | ========= | ============== | ========= | ============== | ====== | =========== | ==== | ========= | ====== | =========== | 
| New York      | 3.1      | 2.8           | 1.7      | 1.3           | 4.1       | 3.9            | 2.9       | 2.6            | 4.4    | 3.7         | 4.2  | 3.8       | 2.0    | 1.8         | 
| New Jersey    | 3.6      | 3.4           | 2.1      | 2.1           | 6.2       | 4.5            | 2.8       | 2.9            | 4.7    | 4.5         | 5.0  | 4.7       | 2.4    | 2.2         | 
| United States | 7.0      | 6.8           | 4.0      | 3.7           | 10.8      | 10.1           | 6.8       | 6.6            | 8.1    | 7.8         | 9.4  | 9.2       | 4.7    | 4.5         | 
```