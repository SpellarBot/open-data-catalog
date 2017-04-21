# Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 5 - Chicago

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/impaired-driving-death-rate-by-age-and-gender-2012-region-5-chicago) |
| Metadata | [Link](https://data.cdc.gov/api/views/68ej-h5ze) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/68ej-h5ze/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/68ej-h5ze/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 68ej-h5ze |
| Name | Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 5 - Chicago |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-17T15:48:51Z |
| Publication Date | 2016-09-14T15:11:35Z |

## Description

Rate of deaths by age/gender (per 100,000 population) for people killed in crashes involving a driver with BAC =>0.08%, 2012, 2014. 2012 Source: Fatality Analysis Reporting System (FARS). 2014 Source: National Highway Traffic Administration's (NHTSA) Fatality Analysis Reporting System (FARS), 2014 Annual Report File. Note: Blank cells indicate data are suppressed. Fatality rates based on fewer than 20 deaths are suppressed.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type | Render Type |
| ======== | ============== | =============== | ================ | ========= | =========== |
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
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:68ej-h5ze d:2012-01-01T00:00:00.000Z t:state="United States" m:ages_21_34_2014=6.2 m:ages_0_20_2014=1.2 m:male_2014=4.9 m:female_2014=1.4 m:female=1.5 m:ages_21_34=6.7 m:male=5.2 m:ages_0_20=1.3 m:ages_35=3.1 m:all_ages_2014=3.1 m:all_ages=3.3 m:ages_35_2014=3

series e:68ej-h5ze d:2012-01-01T00:00:00.000Z t:state=Illinois m:ages_21_34_2014=5.5 m:ages_0_20_2014=0.7 m:male_2014=3.7 m:female_2014=1.3 m:female=1 m:ages_21_34=6 m:male=4 m:ages_0_20=0.7 m:ages_35=2.1 m:all_ages_2014=2.4 m:all_ages=2.5 m:ages_35_2014=2.2

series e:68ej-h5ze d:2012-01-01T00:00:00.000Z t:state=Indiana m:ages_21_34_2014=6.3 m:male_2014=5.1 m:female_2014=1.3 m:female=1.3 m:ages_21_34=7.2 m:male=6 m:ages_0_20=1.2 m:ages_35=3.5 m:all_ages_2014=3.2 m:all_ages=3.6 m:ages_35_2014=3.2
```

## Meta Commands

```ls
metric m:all_ages p:float l:"All Ages, 2012" t:dataTypeName=number

metric m:ages_0_20 p:float l:"Ages 0-20, 2012" t:dataTypeName=number

metric m:ages_21_34 p:float l:"Ages 21-34, 2012" t:dataTypeName=number

metric m:ages_35 p:float l:"Ages 35+, 2012" t:dataTypeName=number

metric m:male p:float l:"Male, 2012" t:dataTypeName=number

metric m:female p:float l:"Female, 2012" t:dataTypeName=number

metric m:all_ages_2014 p:float l:"All Ages, 2014" t:dataTypeName=number

metric m:ages_0_20_2014 p:float l:"Ages 0-20, 2014" t:dataTypeName=number

metric m:ages_21_34_2014 p:float l:"Ages 21-34, 2014" t:dataTypeName=number

metric m:ages_35_2014 p:float l:"Ages 35+, 2014" t:dataTypeName=number

metric m:male_2014 p:float l:"Male, 2014" t:dataTypeName=number

metric m:female_2014 p:float l:"Female, 2014" t:dataTypeName=number

entity e:68ej-h5ze l:"Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 5 - Chicago" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/68ej-h5ze

property e:68ej-h5ze t:meta.view v:id=68ej-h5ze v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 5 - Chicago" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:68ej-h5ze t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:68ej-h5ze t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:68ej-h5ze t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state         | all_ages | ages_0_20 | ages_21_34 | ages_35 | male | female | all_ages_2014 | ages_0_20_2014 | ages_21_34_2014 | ages_35_2014 | male_2014 | female_2014 | 
| ============= | ======== | ========= | ========== | ======= | ==== | ====== | ============= | ============== | =============== | ============ | ========= | =========== | 
| United States | 3.3      | 1.3       | 6.7        | 3.1     | 5.2  | 1.5    | 3.1           | 1.2            | 6.2             | 3            | 4.9       | 1.4         | 
| Illinois      | 2.5      | 0.7       | 6.0        | 2.1     | 4.0  | 1.0    | 2.4           | 0.7            | 5.5             | 2.2          | 3.7       | 1.3         | 
| Indiana       | 3.6      | 1.2       | 7.2        | 3.5     | 6.0  | 1.3    | 3.2           |                | 6.3             | 3.2          | 5.1       | 1.3         | 
| Michigan      | 2.7      | 1.1       | 6.8        | 2.0     | 4.3  | 1.2    | 2.2           | 1              | 5.1             | 1.8          | 3.3       | 1.1         | 
| Minnesota     | 2.1      |           | 3.7        | 2.2     | 3.2  | 1.2    | 1.9           |                | 3.5             | 2.1          | 3         | 0.9         | 
| Ohio          | 3.5      | 1.2       | 6.8        | 3.3     | 5.5  | 1.6    | 2.7           | 0.8            | 5.6             | 2.6          | 4.2       | 1.3         | 
| Wisconsin     | 3.6      | 1.6       | 6.5        | 3.5     | 5.6  | 1.6    | 2.9           |                | 7.5             | 2.3          | 4.8       | 1.2         | 
```