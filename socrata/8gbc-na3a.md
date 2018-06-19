# Missouri First Reports of Injury by Body Parts - Trunk

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-first-reports-of-injury-by-body-parts-trunk-97387) |
| Metadata | [Link](https://data.mo.gov/api/views/8gbc-na3a) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/8gbc-na3a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/8gbc-na3a/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 8gbc-na3a |
| Name | Missouri First Reports of Injury by Body Parts - Trunk |
| Category | Labor |
| Tags | labor, injury, employment, froi |
| Created | 2012-10-03T12:35:44Z |
| Publication Date | 2013-01-03T20:53:28Z |

## Description

First reports of injury filed reporting an injury to the trunk.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                         | Data Type | Render Type |
| ======== | ============== | ========================== | ============================ | ========= | =========== |
| Yes      | series tag     | recordid                   | recordid                     | text      | text        |
| No       |                | year                       | year                         | number    | number      |
| No       |                | month                      | month                        | number    | number      |
| Yes      | numeric metric | abdomen_including_groin    | abdomen including groin      | number    | number      |
| Yes      | numeric metric | disc                       | disc                         | number    | number      |
| Yes      | numeric metric | internal_organs            | internal organs              | number    | number      |
| Yes      | numeric metric | lower_back_area            | lower back area              | number    | number      |
| Yes      | numeric metric | lumbar_or_sacral_vertebrae | lumbar & or sacral vertebrae | number    | number      |
| Yes      | numeric metric | heart                      | heart                        | number    | number      |
| Yes      | numeric metric | lungs                      | lungs                        | number    | number      |
| Yes      | numeric metric | spinal_cord                | spinal cord                  | number    | number      |
| Yes      | numeric metric | buttocks                   | buttocks                     | number    | number      |
| Yes      | numeric metric | pelvis                     | pelvis                       | number    | number      |
| Yes      | numeric metric | chest                      | chest                        | number    | number      |
| Yes      | numeric metric | multiple_trunk             | multiple trunk               | number    | number      |
| Yes      | numeric metric | upper_back_area            | upper back area              | number    | number      |
| Yes      | numeric metric | sacrum_and_coccyx          | sacrum and coccyx            | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:8gbc-na3a d:2005-04-01T00:00:00.000Z t:recordid=42005 m:buttocks=20 m:lumbar_or_sacral_vertebrae=12 m:sacrum_and_coccyx=12 m:lower_back_area=1005 m:heart=3 m:abdomen_including_groin=143 m:pelvis=20 m:lungs=58 m:multiple_trunk=50 m:spinal_cord=4 m:chest=156 m:internal_organs=30 m:upper_back_area=164 m:disc=8

series e:8gbc-na3a d:2004-04-01T00:00:00.000Z t:recordid=42004 m:buttocks=25 m:lumbar_or_sacral_vertebrae=11 m:sacrum_and_coccyx=15 m:lower_back_area=1296 m:heart=5 m:abdomen_including_groin=178 m:pelvis=22 m:lungs=45 m:multiple_trunk=66 m:spinal_cord=1 m:chest=150 m:internal_organs=25 m:upper_back_area=182 m:disc=12

series e:8gbc-na3a d:2007-04-01T00:00:00.000Z t:recordid=42007 m:buttocks=20 m:lumbar_or_sacral_vertebrae=27 m:sacrum_and_coccyx=16 m:lower_back_area=1005 m:heart=10 m:abdomen_including_groin=154 m:pelvis=8 m:lungs=42 m:multiple_trunk=77 m:spinal_cord=1 m:chest=132 m:internal_organs=28 m:upper_back_area=138 m:disc=8
```

## Meta Commands

```ls
metric m:abdomen_including_groin p:integer l:"abdomen including groin" t:dataTypeName=number

metric m:disc p:integer l:disc t:dataTypeName=number

metric m:internal_organs p:integer l:"internal organs" t:dataTypeName=number

metric m:lower_back_area p:integer l:"lower back area" t:dataTypeName=number

metric m:lumbar_or_sacral_vertebrae p:integer l:"lumbar & or sacral vertebrae" t:dataTypeName=number

metric m:heart p:integer l:heart t:dataTypeName=number

metric m:lungs p:integer l:lungs t:dataTypeName=number

metric m:spinal_cord p:integer l:"spinal cord" t:dataTypeName=number

metric m:buttocks p:integer l:buttocks t:dataTypeName=number

metric m:pelvis p:integer l:pelvis t:dataTypeName=number

metric m:chest p:integer l:chest t:dataTypeName=number

metric m:multiple_trunk p:integer l:"multiple trunk" t:dataTypeName=number

metric m:upper_back_area p:integer l:"upper back area" t:dataTypeName=number

metric m:sacrum_and_coccyx p:integer l:"sacrum and coccyx" t:dataTypeName=number

entity e:8gbc-na3a l:"Missouri First Reports of Injury by Body Parts - Trunk" t:url=https://data.mo.gov/api/views/8gbc-na3a

property e:8gbc-na3a t:meta.view v:id=8gbc-na3a v:category=Labor v:averageRating=0 v:name="Missouri First Reports of Injury by Body Parts - Trunk"

property e:8gbc-na3a t:meta.view.owner v:id=fq9d-b9a3 v:screenName=Jolene v:displayName=Jolene

property e:8gbc-na3a t:meta.view.tableauthor v:id=fq9d-b9a3 v:screenName=Jolene v:roleName=editor v:displayName=Jolene
```

## Top Records

```ls
| recordid | year | month | abdomen_including_groin | disc | internal_organs | lower_back_area | lumbar_or_sacral_vertebrae | heart | lungs | spinal_cord | buttocks | pelvis | chest | multiple_trunk | upper_back_area | sacrum_and_coccyx | 
| ======== | ==== | ===== | ======================= | ==== | =============== | =============== | ========================== | ===== | ===== | =========== | ======== | ====== | ===== | ============== | =============== | ================= | 
| 42005    | 2005 | 4     | 143                     | 8    | 30              | 1005            | 12                         | 3     | 58    | 4           | 20       | 20     | 156   | 50             | 164             | 12                | 
| 42004    | 2004 | 4     | 178                     | 12   | 25              | 1296            | 11                         | 5     | 45    | 1           | 25       | 22     | 150   | 66             | 182             | 15                | 
| 42007    | 2007 | 4     | 154                     | 8    | 28              | 1005            | 27                         | 10    | 42    | 1           | 20       | 8      | 132   | 77             | 138             | 16                | 
| 42006    | 2006 | 4     | 138                     | 6    | 32              | 1023            | 14                         | 3     | 19    | 3           | 23       | 7      | 124   | 71             | 138             | 11                | 
| 42009    | 2009 | 4     | 122                     | 5    | 19              | 834             | 19                         | 7     | 31    | 3           | 20       | 10     | 121   | 58             | 146             | 8                 | 
| 42008    | 2008 | 4     | 143                     | 10   | 34              | 1065            | 36                         | 7     | 72    | 2           | 30       | 9      | 156   | 49             | 193             | 16                | 
| 42001    | 2001 | 4     | 186                     | 13   | 26              | 1535            | 20                         | 11    | 55    | 3           | 22       | 42     | 175   | 74             | 168             | 18                | 
| 42003    | 2003 | 4     | 154                     | 13   | 23              | 1237            | 19                         | 11    | 49    | 1           | 29       | 23     | 176   | 67             | 145             | 12                | 
| 42002    | 2002 | 4     | 194                     | 10   | 31              | 1590            | 26                         | 12    | 60    | 1           | 49       | 26     | 181   | 54             | 217             | 18                | 
| 102009   | 2009 | 10    | 118                     | 7    | 68              | 943             | 28                         | 6     | 56    | 1           | 21       | 8      | 125   | 50             | 119             | 9                 | 
```