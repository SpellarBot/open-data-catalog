# SPD Offense Codes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/spd-offense-codes) |
| Metadata | [Link](https://data.seattle.gov/api/views/22zb-azac) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/22zb-azac/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/22zb-azac/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 22zb-azac |
| Name | SPD Offense Codes |
| Attribution | open.data@seattle.gov |
| Category | Public Safety |
| Tags | spd, incident, police, code, definition |
| Created | 2016-05-03T17:58:20Z |
| Publication Date | 2016-05-03T18:02:21Z |

## Description

Code Descriptions for the Seattle Police Department Police Incident Report in the dataset https://data.seattle.gov/Public-Safety/Seattle-Police-Department-Police-Report-Incident/7ais-f98f

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | offense_code                   | OFFENSE_CODE                   | text          | number        |
| Yes      | numeric metric | offense_code_extension         | OFFENSE_CODE_EXTENSION         | number        | number        |
| Yes      | series tag     | offense_type_description       | OFFENSE_TYPE_DESCRIPTION       | text          | text          |
| Yes      | time           | effective_date                 | EFFECTIVE_DATE                 | calendar_date | calendar_date |
| No       |                | expiry_date                    | EXPIRY_DATE                    | calendar_date | calendar_date |
| Yes      | series tag     | summary_offense_code           | SUMMARY_OFFENSE_CODE           | text          | number        |
| Yes      | series tag     | summarized_offense_description | SUMMARIZED_OFFENSE_DESCRIPTION | text          | text          |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expiry_date
```

## Data Commands

```ls
series e:22zb-azac d:2008-01-01T00:00:00.000Z t:offense_code=909 t:offense_type_description=HOMICIDE-NEG-MANS-VEHICLE t:summarized_offense_description=HOMICIDE t:summary_offense_code=900 m:offense_code_extension=0

series e:22zb-azac d:2008-01-01T00:00:00.000Z t:offense_code=910 t:offense_type_description=HOMICIDE-NEG-MANS-WEAPON t:summarized_offense_description=HOMICIDE t:summary_offense_code=900 m:offense_code_extension=0

series e:22zb-azac d:2008-01-01T00:00:00.000Z t:offense_code=911 t:offense_type_description=HOMICIDE-PREMEDITATED-GUN t:summarized_offense_description=HOMICIDE t:summary_offense_code=900 m:offense_code_extension=0
```

## Meta Commands

```ls
metric m:offense_code_extension p:integer l:OFFENSE_CODE_EXTENSION t:dataTypeName=number

entity e:22zb-azac l:"SPD Offense Codes" t:attribution=open.data@seattle.gov t:url=https://data.seattle.gov/api/views/22zb-azac

property e:22zb-azac t:meta.view v:id=22zb-azac v:category="Public Safety" v:averageRating=0 v:name="SPD Offense Codes" v:attribution=open.data@seattle.gov

property e:22zb-azac t:meta.view.license v:name="Public Domain"

property e:22zb-azac t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:22zb-azac t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| offense_code | offense_code_extension | offense_type_description       | effective_date      | expiry_date | summary_offense_code | summarized_offense_description | 
| ============ | ====================== | ============================== | =================== | =========== | ==================== | ============================== | 
| 909          | 0                      | HOMICIDE-NEG-MANS-VEHICLE      | 2008-01-01T00:00:00 |             | 900                  | HOMICIDE                       | 
| 910          | 0                      | HOMICIDE-NEG-MANS-WEAPON       | 2008-01-01T00:00:00 |             | 900                  | HOMICIDE                       | 
| 911          | 0                      | HOMICIDE-PREMEDITATED-GUN      | 2008-01-01T00:00:00 |             | 900                  | HOMICIDE                       | 
| 912          | 0                      | HOMICIDE-PREMEDITATED-WEAPON   | 2008-01-01T00:00:00 |             | 900                  | HOMICIDE                       | 
| 999          | 1                      | HOMICIDE-JUST-GUN              | 2008-01-01T00:00:00 |             | 900                  | HOMICIDE                       | 
| 999          | 2                      | HOMICIDE-JUST-STRONGARM        | 2008-01-01T00:00:00 |             | 900                  | HOMICIDE                       | 
| 999          | 3                      | HOMICIDE-JUST-WEAPON           | 2008-01-01T00:00:00 |             | 900                  | HOMICIDE                       | 
| 999          | 4                      | HOMICIDE-NEG-MANS-BODYFORCE    | 2008-01-01T00:00:00 |             | 900                  | HOMICIDE                       | 
| 999          | 5                      | HOMICIDE-NEG-MANS-GUN          | 2008-01-01T00:00:00 |             | 900                  | HOMICIDE                       | 
| 999          | 6                      | HOMICIDE-PREMEDITATED-BODYFORC | 2008-01-01T00:00:00 |             | 900                  | HOMICIDE                       | 
```