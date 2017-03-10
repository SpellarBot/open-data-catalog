# Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 4 - Atlanta

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/motor-vehicle-occupant-death-rate-by-age-and-gender-2012-region-4-atlanta-dd559) |
| Metadata | [Link](https://data.cdc.gov/api/views/rb93-4tgj) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/rb93-4tgj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/rb93-4tgj/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | rb93-4tgj |
| Name | Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 4 - Atlanta |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-16T14:06:12Z |
| Publication Date | 2016-10-18T18:05:34Z |
| Rows Updated | 2016-10-18T18:05:09Z |

## Description

Rate of deaths by age/gender (per 100,000 population) for motor vehicle occupants killed in crashes, 2012 & 2014. 2012 Source: Fatality Analysis Reporting System (FARS). 2014 Source: National Highway Traffic Safety Administration's (NHTSA) Fatality Analysis Reporting System (FARS), 2014 Annual Report File Note: Blank cells indicate data are suppressed. Fatality rates based on fewer than 20 deaths are suppressed.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name            | Data Type | Render Type |
| ======== | ============== | ============== | =============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at      | meta_data | meta_data   |
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
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rb93-4tgj d:2016-10-18T18:05:09.000Z t:state="United States" m:male_2014=9.2 m:female_2014=4.5 m:age_35_54=6.8 m:age_21_34_2014=10.1 m:male=9.4 m:age_0_20_2014=3.7 m:age_55=8.1 m:all_ages_2014=6.8 m:age_35_54_2014=6.6 m:age_21_34=10.8 m:age_55_2014=7.8 m:female=4.7 m:age_0_20=4 m:all_ages=7

series e:rb93-4tgj d:2016-10-18T18:05:09.000Z t:state=Tennessee m:male_2014=15 m:female_2014=7.4 m:age_35_54=12.3 m:age_21_34_2014=15.6 m:male=16.8 m:age_0_20_2014=5.4 m:age_55=15 m:all_ages_2014=11.1 m:age_35_54_2014=11.5 m:age_21_34=16.4 m:age_55_2014=13 m:female=6.9 m:age_0_20=6.1 m:all_ages=11.7

series e:rb93-4tgj d:2016-10-18T18:05:09.000Z t:state="South Carolina" m:male_2014=16 m:female_2014=8.1 m:age_35_54=12.7 m:age_21_34_2014=20.9 m:male=17 m:age_0_20_2014=7.6 m:age_55=11.8 m:all_ages_2014=12 m:age_35_54_2014=10.2 m:age_21_34=19.8 m:age_55_2014=11.7 m:female=7.2 m:age_0_20=6.8 m:all_ages=12
```

## Meta Commands

```ls
metric m:all_ages l:"All Ages, 2012" t:dataTypeName=number

metric m:all_ages_2014 l:"All Ages, 2014" t:dataTypeName=number

metric m:age_0_20 l:"Age 0-20, 2012" t:dataTypeName=number

metric m:age_0_20_2014 l:"Age 0-20, 2014" t:dataTypeName=number

metric m:age_21_34 l:"Age 21-34, 2012" t:dataTypeName=number

metric m:age_21_34_2014 l:"Age 21-34, 2014" t:dataTypeName=number

metric m:age_35_54 l:"Age 35-54, 2012" t:dataTypeName=number

metric m:age_35_54_2014 l:"Age 35-54, 2014" t:dataTypeName=number

metric m:age_55 l:"Age 55+, 2012" t:dataTypeName=number

metric m:age_55_2014 l:"Age 55+, 2014" t:dataTypeName=number

metric m:male l:"Male, 2012" t:dataTypeName=number

metric m:male_2014 l:"Male, 2014" t:dataTypeName=number

metric m:female l:"Female, 2012" t:dataTypeName=number

metric m:female_2014 l:"Female, 2014" t:dataTypeName=number

entity e:rb93-4tgj l:"Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 4 - Atlanta" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/rb93-4tgj

property e:rb93-4tgj t:meta.view d:2017-03-10T14:21:30.096Z v:id=rb93-4tgj v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Motor Vehicle Occupant Death Rate, by Age and Gender, 2012 & 2014, Region 4 - Atlanta" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:rb93-4tgj t:meta.view.license d:2017-03-10T14:21:30.096Z v:name="Public Domain"

property e:rb93-4tgj t:meta.view.owner d:2017-03-10T14:21:30.096Z v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:rb93-4tgj t:meta.view.tableauthor d:2017-03-10T14:21:30.096Z v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:rb93-4tgj t:meta.view.metadata.custom_fields.common_core d:2017-03-10T14:21:30.096Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```