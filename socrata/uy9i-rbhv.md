# CASPER / ASPEN Contacts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/casper-aspen-contacts-5bbc1) |
| Metadata | [Link](https://data.medicare.gov/api/views/uy9i-rbhv) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/uy9i-rbhv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/uy9i-rbhv/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | uy9i-rbhv |
| Name | CASPER / ASPEN Contacts |
| Tags | hospice care, hospice, care |
| Created | 2012-12-03T20:33:23Z |
| Publication Date | 2016-10-25T12:45:29Z |

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | compare_tool   | Compare Tool   | text      | text        |
| Yes      | series tag  | state          | State          | text      | text        |
| No       |             | e_mail_address | E-mail Address | email     | email       |
| Yes      | series tag  | phone          | Phone          | phone     | phone       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = e_mail_address
```

## Data Commands

```ls
series e:uy9i-rbhv d:2016-05-19T12:40:25.000Z t:phone_number=334-206-7916 t:state=Alabama t:compare_tool="Home Health" m:row_number.uy9i-rbhv=1

series e:uy9i-rbhv d:2016-05-19T12:40:25.000Z t:phone_number=334-206-7916 t:state=Alabama t:compare_tool=Hospital m:row_number.uy9i-rbhv=2

series e:uy9i-rbhv d:2016-05-19T12:40:25.000Z t:phone_number=334-206-5164 t:state=Alabama t:compare_tool="Nursing Home" m:row_number.uy9i-rbhv=3
```

## Meta Commands

```ls
metric m:row_number.uy9i-rbhv p:long l:"Row Number"

entity e:uy9i-rbhv l:"CASPER / ASPEN Contacts" t:url=https://data.medicare.gov/api/views/uy9i-rbhv

property e:uy9i-rbhv t:meta.view v:id=uy9i-rbhv v:averageRating=0 v:name="CASPER / ASPEN Contacts"

property e:uy9i-rbhv t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:uy9i-rbhv t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:uy9i-rbhv t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=Gregory.Goetzel@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | compare_tool | state    | e_mail_address                    | phone                | 
| =========== | ============ | ======== | ================================= | ==================== | 
| 1463661625  | Home Health  | Alabama  | carter.sims@adph.state.al.us      | [334-206-7916, null] | 
| 1463661625  | Hospital     | Alabama  | carter.sims@adph.state.al.us      | [334-206-7916, null] | 
| 1463661625  | Nursing Home | Alabama  | pamela.carpenter@adph.state.al.us | [334-206-5164, null] | 
| 1463661625  | Home Health  | Alaska   | angela.rick@alaska.gov            | [907-334-2491, null] | 
| 1463661625  | Hospital     | Alaska   | angela.rick@alaska.gov            | [907-334-2491, null] | 
| 1463661625  | Nursing Home | Alaska   | angela.rick@alaska.gov            | [907-334-2491, null] | 
| 1463661625  | Home Health  | Arizona  | AZLICENSE@AZDHS.GOV               | [602-364-2948, null] | 
| 1463661625  | Hospital     | Arizona  | AZLICENSE@AZDHS.GOV               | [602-364-2948, null] | 
| 1463661625  | Nursing Home | Arizona  | AZLICENSE@AZDHS.GOV               | [602-364-2948, null] | 
| 1463661625  | Home Health  | Arkansas | debra.tyler@arkansas.gov          | [501-661-2533, null] | 
```