# Transfer Of Guardianship by SFY, DCF Office, Gender and Length of Stay

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transfer-of-guardianship-by-sfy-dcf-office-gender-and-length-of-stay) |
| Metadata | [Link](https://data.ct.gov/api/views/kyc9-zbgf) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/kyc9-zbgf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/kyc9-zbgf/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | kyc9-zbgf |
| Name | Transfer Of Guardianship by SFY, DCF Office, Gender and Length of Stay |
| Attribution | Department of Children and Families, Office for Research and Evaluation |
| Category | Health and Human Services |
| Tags | dcf, department of children and families, children, placement, gender, trend, transfer of guardianship, exit cohort |
| Created | 2016-02-17T22:01:17Z |
| Publication Date | 2016-03-03T20:41:43Z |

## Description

This dataset contains aggregate data concerning the number of children that exited DCF care to a Transfer of Guardianship.  These figures are broken out by the DCF Region and Office responsible for the child's care, by their Gender, and by whether their exit from care occurred within 24 months of their entry to care or not.  It would be appropriate to roll up the data from all variables across multiple time periods, as they represent specific events in the lives of these children.  Please note that these figures do not represent unique children, and so should not be used as the basis for creating a rate based on the child population of the state.  These data form the basis of measurement for the Juan F. Consent Decree Exit Plan Outcome #9: Transfer of Guardianship Within 24 Months, although those figures are reported to the DCF Court Monitor on a quarterly rather than annual schedule.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | time           | data_as_of          | Data_As_Of          | calendar_date | calendar_date |
| Yes      | series tag     | office              | Office              | text          | text          |
| Yes      | series tag     | region              | Region              | text          | text          |
| Yes      | series tag     | demographic         | Demographic         | text          | text          |
| Yes      | numeric metric | sfy                 | SFY                 | number        | number        |
| Yes      | series tag     | exit_type           | Exit_Type           | text          | text          |
| Yes      | numeric metric | los_lessthan24mnths | LOS_LessThan24Mnths | number        | number        |
| Yes      | numeric metric | los_morethan24mnths | LOS_MoreThan24Mnths | number        | number        |
| Yes      | numeric metric | total_tog           | Total_TOG           | number        | number        |
| Yes      | series tag     | demographic_type    | Demographic_Type    | text          | text          |
```

## Time Field

```ls
Value = data_as_of
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:kyc9-zbgf d:2016-02-10T00:00:00.000Z t:region="Region 0" t:office=Other t:exit_type=TransferOfGuardianship t:demographic_type=Gender t:demographic=Female m:los_lessthan24mnths=4 m:total_tog=7 m:los_morethan24mnths=3 m:sfy=2000

series e:kyc9-zbgf d:2016-02-10T00:00:00.000Z t:region="Region 0" t:office=Other t:exit_type=TransferOfGuardianship t:demographic_type=Gender t:demographic=Male m:los_lessthan24mnths=0 m:total_tog=2 m:los_morethan24mnths=2 m:sfy=2000

series e:kyc9-zbgf d:2016-02-10T00:00:00.000Z t:region="Region 1" t:office=Bridgeport t:exit_type=TransferOfGuardianship t:demographic_type=Gender t:demographic=Female m:los_lessthan24mnths=9 m:total_tog=9 m:los_morethan24mnths=0 m:sfy=2000
```

## Meta Commands

```ls
metric m:sfy p:integer l:SFY t:dataTypeName=number

metric m:los_lessthan24mnths p:integer l:LOS_LessThan24Mnths t:dataTypeName=number

metric m:los_morethan24mnths p:integer l:LOS_MoreThan24Mnths t:dataTypeName=number

metric m:total_tog p:integer l:Total_TOG t:dataTypeName=number

entity e:kyc9-zbgf l:"Transfer Of Guardianship by SFY, DCF Office, Gender and Length of Stay" t:attribution="Department of Children and Families, Office for Research and Evaluation" t:url=https://data.ct.gov/api/views/kyc9-zbgf

property e:kyc9-zbgf t:meta.view v:id=kyc9-zbgf v:category="Health and Human Services" v:averageRating=0 v:name="Transfer Of Guardianship by SFY, DCF Office, Gender and Length of Stay" v:attribution="Department of Children and Families, Office for Research and Evaluation"

property e:kyc9-zbgf t:meta.view.license v:name="Public Domain"

property e:kyc9-zbgf t:meta.view.owner v:id=2j7e-cuxc v:screenName="CT DCF" v:displayName="CT DCF"

property e:kyc9-zbgf t:meta.view.tableauthor v:id=2j7e-cuxc v:screenName="CT DCF" v:roleName=editor v:displayName="CT DCF"
```

## Top Records

```ls
| data_as_of          | office     | region   | demographic | sfy  | exit_type              | los_lessthan24mnths | los_morethan24mnths | total_tog | demographic_type | 
| =================== | ========== | ======== | =========== | ==== | ====================== | =================== | =================== | ========= | ================ | 
| 2016-02-10T00:00:00 | Other      | Region 0 | Female      | 2000 | TransferOfGuardianship | 4                   | 3                   | 7         | Gender           | 
| 2016-02-10T00:00:00 | Other      | Region 0 | Male        | 2000 | TransferOfGuardianship | 0                   | 2                   | 2         | Gender           | 
| 2016-02-10T00:00:00 | Bridgeport | Region 1 | Female      | 2000 | TransferOfGuardianship | 9                   | 0                   | 9         | Gender           | 
| 2016-02-10T00:00:00 | Bridgeport | Region 1 | Male        | 2000 | TransferOfGuardianship | 4                   | 0                   | 4         | Gender           | 
| 2016-02-10T00:00:00 | Norwalk    | Region 1 | Female      | 2000 | TransferOfGuardianship | 0                   | 1                   | 1         | Gender           | 
| 2016-02-10T00:00:00 | Norwalk    | Region 1 | Male        | 2000 | TransferOfGuardianship | 2                   | 3                   | 5         | Gender           | 
| 2016-02-10T00:00:00 | Stamford   | Region 1 | Male        | 2000 | TransferOfGuardianship | 0                   | 3                   | 3         | Gender           | 
| 2016-02-10T00:00:00 | Milford    | Region 2 | Male        | 2000 | TransferOfGuardianship | 2                   | 0                   | 2         | Gender           | 
| 2016-02-10T00:00:00 | New Haven  | Region 2 | Female      | 2000 | TransferOfGuardianship | 8                   | 23                  | 31        | Gender           | 
| 2016-02-10T00:00:00 | New Haven  | Region 2 | Male        | 2000 | TransferOfGuardianship | 7                   | 18                  | 25        | Gender           | 
```