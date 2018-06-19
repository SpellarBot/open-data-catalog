# Reunifications by SFY, DCF Office, Race and Length of Stay

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/reunifications-by-sfy-dcf-office-race-and-length-of-stay) |
| Metadata | [Link](https://data.ct.gov/api/views/9x74-djtb) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/9x74-djtb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/9x74-djtb/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 9x74-djtb |
| Name | Reunifications by SFY, DCF Office, Race and Length of Stay |
| Attribution | Department of Children and Families, Office for Research and Evaluation |
| Category | Health and Human Services |
| Tags | dcf, department of children and families, children, placement, race, ethnicity, race/ethnicity, trend, reunified, reunification, exit cohort |
| Created | 2016-02-17T21:51:58Z |
| Publication Date | 2016-03-03T20:42:18Z |

## Description

This dataset contains aggregate data concerning the number of children that exited DCF care to be Reunified with a parent/guardian from whom they had been removed.  These figures are broken out by the DCF Region and Office responsible for the child's care, by their Age Group, and by whether they had been Reunified within 12 months of their entry to care or not.  It would be appropriate to roll up the data from all variables across multiple time periods, as they represent specific events in the lives of these children.  Please note that these figures do not represent unique children, and so should not be used as the basis for creating a rate based on the child population of the state.  These data form the basis of measurement for the Juan F. Consent Decree Exit Plan Outcome #7: Reunification Within 12 Months, although those figures are reported to the DCF Court Monitor on a quarterly rather than annual schedule.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | time           | data_as_of          | Data_As_Of          | calendar_date | calendar_date |
| Yes      | numeric metric | sfy                 | SFY                 | number        | number        |
| Yes      | series tag     | office              | Office              | text          | text          |
| Yes      | series tag     | region              | Region              | text          | text          |
| Yes      | series tag     | demographic         | Demographic         | text          | text          |
| Yes      | series tag     | exit_type           | Exit_Type           | text          | text          |
| Yes      | numeric metric | los_lessthan12mnths | LOS_LessThan12Mnths | number        | number        |
| Yes      | numeric metric | los_morethan12mnths | LOS_MoreThan12Mnths | number        | number        |
| Yes      | numeric metric | total_reunified     | Total_Reunified     | number        | number        |
| Yes      | series tag     | demographic_type    | Demographic_Type    | text          | text          |
```

## Time Field

```ls
Value = data_as_of
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:9x74-djtb d:2016-02-10T00:00:00.000Z t:region="Region 0" t:office=Other t:exit_type=Reunification t:demographic_type=Race t:demographic="Hispanic of any Race" m:total_reunified=13 m:sfy=2000 m:los_lessthan12mnths=8 m:los_morethan12mnths=5

series e:9x74-djtb d:2016-02-10T00:00:00.000Z t:region="Region 0" t:office=Other t:exit_type=Reunification t:demographic_type=Race t:demographic="Non-Hispanic Black" m:total_reunified=20 m:sfy=2000 m:los_lessthan12mnths=18 m:los_morethan12mnths=2

series e:9x74-djtb d:2016-02-10T00:00:00.000Z t:region="Region 0" t:office=Other t:exit_type=Reunification t:demographic_type=Race t:demographic="Non-Hispanic Other" m:total_reunified=6 m:sfy=2000 m:los_lessthan12mnths=4 m:los_morethan12mnths=2
```

## Meta Commands

```ls
metric m:sfy p:integer l:SFY t:dataTypeName=number

metric m:los_lessthan12mnths p:integer l:LOS_LessThan12Mnths t:dataTypeName=number

metric m:los_morethan12mnths p:integer l:LOS_MoreThan12Mnths t:dataTypeName=number

metric m:total_reunified p:integer l:Total_Reunified t:dataTypeName=number

entity e:9x74-djtb l:"Reunifications by SFY, DCF Office, Race and Length of Stay" t:attribution="Department of Children and Families, Office for Research and Evaluation" t:url=https://data.ct.gov/api/views/9x74-djtb

property e:9x74-djtb t:meta.view v:id=9x74-djtb v:category="Health and Human Services" v:averageRating=0 v:name="Reunifications by SFY, DCF Office, Race and Length of Stay" v:attribution="Department of Children and Families, Office for Research and Evaluation"

property e:9x74-djtb t:meta.view.license v:name="Public Domain"

property e:9x74-djtb t:meta.view.owner v:id=2j7e-cuxc v:screenName="CT DCF" v:displayName="CT DCF"

property e:9x74-djtb t:meta.view.tableauthor v:id=2j7e-cuxc v:screenName="CT DCF" v:roleName=editor v:displayName="CT DCF"
```

## Top Records

```ls
| data_as_of          | sfy  | office     | region   | demographic          | exit_type     | los_lessthan12mnths | los_morethan12mnths | total_reunified | demographic_type | 
| =================== | ==== | ========== | ======== | ==================== | ============= | =================== | =================== | =============== | ================ | 
| 2016-02-10T00:00:00 | 2000 | Other      | Region 0 | Hispanic of any Race | Reunification | 8                   | 5                   | 13              | Race             | 
| 2016-02-10T00:00:00 | 2000 | Other      | Region 0 | Non-Hispanic Black   | Reunification | 18                  | 2                   | 20              | Race             | 
| 2016-02-10T00:00:00 | 2000 | Other      | Region 0 | Non-Hispanic Other   | Reunification | 4                   | 2                   | 6               | Race             | 
| 2016-02-10T00:00:00 | 2000 | Other      | Region 0 | Non-Hispanic White   | Reunification | 10                  | 2                   | 12              | Race             | 
| 2016-02-10T00:00:00 | 2000 | Bridgeport | Region 1 | Hispanic of any Race | Reunification | 26                  | 11                  | 37              | Race             | 
| 2016-02-10T00:00:00 | 2000 | Bridgeport | Region 1 | Non-Hispanic Black   | Reunification | 17                  | 19                  | 36              | Race             | 
| 2016-02-10T00:00:00 | 2000 | Bridgeport | Region 1 | Non-Hispanic Other   | Reunification | 1                   | 1                   | 2               | Race             | 
| 2016-02-10T00:00:00 | 2000 | Bridgeport | Region 1 | Non-Hispanic White   | Reunification | 7                   | 2                   | 9               | Race             | 
| 2016-02-10T00:00:00 | 2000 | Norwalk    | Region 1 | Hispanic of any Race | Reunification | 3                   | 0                   | 3               | Race             | 
| 2016-02-10T00:00:00 | 2000 | Norwalk    | Region 1 | Non-Hispanic Black   | Reunification | 4                   | 1                   | 5               | Race             | 
```