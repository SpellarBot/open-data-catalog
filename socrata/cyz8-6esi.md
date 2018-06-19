# Adoptions by SFY, DCF Office, Gender and Length of Stay

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adoptions-by-sfy-dcf-office-gender-and-length-of-stay) |
| Metadata | [Link](https://data.ct.gov/api/views/cyz8-6esi) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/cyz8-6esi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/cyz8-6esi/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | cyz8-6esi |
| Name | Adoptions by SFY, DCF Office, Gender and Length of Stay |
| Category | Health and Human Services |
| Tags | dcf, department of children and families, children, placement, gender, trend, adoption, exit cohort |
| Created | 2016-02-11T21:34:04Z |
| Publication Date | 2016-03-03T20:43:49Z |

## Description

This dataset contains aggregate data concerning the number of children that exited DCF care to an Adoption.  These figures are broken out by the DCF Region and Office responsible for the child's care, by their Gender, and by whether their exit from care occurred within 24 months of their entry to care or not.  It would be appropriate to roll up the data from all variables across multiple time periods, as they represent specific events in the lives of these children.  Please note that these figures do not represent unique children, and so should not be used as the basis for creating a rate based on the child population of the state.  These data form the basis of measurement for the Juan F. Consent Decree Exit Plan Outcome #8: Adoption Within 24 Months, although those figures are reported to the DCF Court Monitor on a quarterly rather than annual schedule.

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
| Yes      | numeric metric | los_lessthan24mnths | LOS_LessThan24Mnths | number        | number        |
| Yes      | numeric metric | los_morethan24mnths | LOS_MoreThan24Mnths | number        | number        |
| Yes      | numeric metric | total_adoptions     | Total_Adoptions     | number        | number        |
| Yes      | series tag     | demographic_type    | Demographic_Type    | text          | text          |
```

## Time Field

```ls
Value = data_as_of
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:cyz8-6esi d:2016-02-10T00:00:00.000Z t:region="Region 0" t:office=Other t:exit_type=Adoption t:demographic_type=Gender t:demographic=Male m:los_lessthan24mnths=0 m:los_morethan24mnths=2 m:sfy=2000 m:total_adoptions=2

series e:cyz8-6esi d:2016-02-10T00:00:00.000Z t:region="Region 1" t:office=Bridgeport t:exit_type=Adoption t:demographic_type=Gender t:demographic=Female m:los_lessthan24mnths=2 m:los_morethan24mnths=6 m:sfy=2000 m:total_adoptions=8

series e:cyz8-6esi d:2016-02-10T00:00:00.000Z t:region="Region 1" t:office=Bridgeport t:exit_type=Adoption t:demographic_type=Gender t:demographic=Male m:los_lessthan24mnths=0 m:los_morethan24mnths=4 m:sfy=2000 m:total_adoptions=4
```

## Meta Commands

```ls
metric m:sfy p:integer l:SFY t:dataTypeName=number

metric m:los_lessthan24mnths p:integer l:LOS_LessThan24Mnths t:dataTypeName=number

metric m:los_morethan24mnths p:integer l:LOS_MoreThan24Mnths t:dataTypeName=number

metric m:total_adoptions p:integer l:Total_Adoptions t:dataTypeName=number

entity e:cyz8-6esi l:"Adoptions by SFY, DCF Office, Gender and Length of Stay" t:url=https://data.ct.gov/api/views/cyz8-6esi

property e:cyz8-6esi t:meta.view v:id=cyz8-6esi v:category="Health and Human Services" v:averageRating=0 v:name="Adoptions by SFY, DCF Office, Gender and Length of Stay"

property e:cyz8-6esi t:meta.view.license v:name="Public Domain"

property e:cyz8-6esi t:meta.view.owner v:id=2j7e-cuxc v:screenName="CT DCF" v:displayName="CT DCF"

property e:cyz8-6esi t:meta.view.tableauthor v:id=2j7e-cuxc v:screenName="CT DCF" v:roleName=editor v:displayName="CT DCF"
```

## Top Records

```ls
| data_as_of          | sfy  | office     | region   | demographic | exit_type | los_lessthan24mnths | los_morethan24mnths | total_adoptions | demographic_type | 
| =================== | ==== | ========== | ======== | =========== | ========= | =================== | =================== | =============== | ================ | 
| 2016-02-10T00:00:00 | 2000 | Other      | Region 0 | Male        | Adoption  | 0                   | 2                   | 2               | Gender           | 
| 2016-02-10T00:00:00 | 2000 | Bridgeport | Region 1 | Female      | Adoption  | 2                   | 6                   | 8               | Gender           | 
| 2016-02-10T00:00:00 | 2000 | Bridgeport | Region 1 | Male        | Adoption  | 0                   | 4                   | 4               | Gender           | 
| 2016-02-10T00:00:00 | 2000 | Norwalk    | Region 1 | Female      | Adoption  | 0                   | 2                   | 2               | Gender           | 
| 2016-02-10T00:00:00 | 2000 | New Haven  | Region 2 | Female      | Adoption  | 3                   | 18                  | 21              | Gender           | 
| 2016-02-10T00:00:00 | 2000 | New Haven  | Region 2 | Male        | Adoption  | 1                   | 10                  | 11              | Gender           | 
| 2016-02-10T00:00:00 | 2000 | Middletown | Region 3 | Female      | Adoption  | 0                   | 8                   | 8               | Gender           | 
| 2016-02-10T00:00:00 | 2000 | Middletown | Region 3 | Male        | Adoption  | 0                   | 6                   | 6               | Gender           | 
| 2016-02-10T00:00:00 | 2000 | Norwich    | Region 3 | Female      | Adoption  | 1                   | 13                  | 14              | Gender           | 
| 2016-02-10T00:00:00 | 2000 | Norwich    | Region 3 | Male        | Adoption  | 2                   | 16                  | 18              | Gender           | 
```