# IDPH Ambulatory Surgical Treatment Center Directory with Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-ambulatory-surgical-treatment-center-directory-with-location-cb1dc) |
| Metadata | [Link](https://data.illinois.gov/api/views/if58-xnpz) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/if58-xnpz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/if58-xnpz/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | if58-xnpz |
| Name | IDPH Ambulatory Surgical Treatment Center Directory with Location |
| Category | Recreation |
| Created | 2013-02-01T23:04:16Z |
| Publication Date | 2013-02-01T23:08:07Z |

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| No       | time           | :updated_at                          | updated_at                           | meta_data | meta_data   |
| Yes      | series tag     | ambulatory_surgical_treatment_center | Ambulatory Surgical Treatment Center | text      | text        |
| Yes      | series tag     | dba                                  | DBA                                  | text      | text        |
| Yes      | series tag     | county                               | County                               | text      | text        |
| Yes      | series tag     | phone                                | Phone                                | text      | text        |
| Yes      | numeric metric | license                              | License #                            | number    | number      |
| Yes      | series tag     | city                                 | City                                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:if58-xnpz d:2013-02-01T15:04:23.000Z t:phone="(708) 570-2490" t:ambulatory_surgical_treatment_center="Southwest Ambulatory Surgery Center" t:county=Cook t:dba="Tinley Woods Surgery Center" t:city="Tinley Park" m:license=7002652

series e:if58-xnpz d:2013-02-01T15:04:23.000Z t:phone="(773) 445-9696" t:ambulatory_surgical_treatment_center="Southwestern Medical Center, LLC" t:county=Cook t:dba="Magna Surgical Center" t:city="Bedford Park" m:license=7003159

series e:if58-xnpz d:2013-02-01T15:04:23.000Z t:phone="(847) 367-8100" t:ambulatory_surgical_treatment_center="Hawthorn Place Outpatient Surgery Center, L.P." t:county=Lake t:dba="Hawthorn Surgery Center" t:city=Libertyville m:license=7001795
```

## Meta Commands

```ls
metric m:license p:integer l:"License #" t:dataTypeName=number

entity e:if58-xnpz l:"IDPH Ambulatory Surgical Treatment Center Directory with Location" t:url=https://data.illinois.gov/api/views/if58-xnpz

property e:if58-xnpz t:meta.view v:id=if58-xnpz v:category=Recreation v:averageRating=0 v:name="IDPH Ambulatory Surgical Treatment Center Directory with Location"

property e:if58-xnpz t:meta.view.owner v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"

property e:if58-xnpz t:meta.view.tableauthor v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"
```

## Top Records

```ls
| :updated_at | ambulatory_surgical_treatment_center           | dba                                         | county   | phone          | license | city          | 
| =========== | ============================================== | =========================================== | ======== | ============== | ======= | ============= | 
| 1359731063  | Southwest Ambulatory Surgery Center            | Tinley Woods Surgery Center                 | Cook     | (708) 570-2490 | 7002652 | Tinley Park   | 
| 1359731063  | Southwestern Medical Center, LLC               | Magna Surgical Center                       | Cook     | (773) 445-9696 | 7003159 | Bedford Park  | 
| 1359731063  | Hawthorn Place Outpatient Surgery Center, L.P. | Hawthorn Surgery Center                     | Lake     | (847) 367-8100 | 7001795 | Libertyville  | 
| 1359731063  | 25 East Same Day Surgery                       |                                             | Cook     | (312) 726-3329 | 7001969 | Chicago       | 
| 1359731063  | Ambulatory Surgicenter of Downers Grove, Ltd.  |                                             | Cook     | (630) 322-9451 | 7002082 | Downers Grove | 
| 1359731063  | Prairieland Outpatient Diagnostic Center, LLC  | Digestive Disease Endoscopy Center          | Mc Lean  | (309) 268-3400 | 7002710 | Normal        | 
| 1359731063  | Cadence Ambulatory Surgery Center              |                                             | Du Page  | (630) 225-2700 | 7003173 | Warrenville   | 
| 1359731063  | CMP Surgicenter                                | Fullerton Kimball Medical & Surgical Center | Cook     | (773) 235-8000 | 7001720 | Chicago       | 
| 1359731063  | Belleville Surgical Center Ltd.                | Belleville Surgical Center                  | St Clair | (618) 398-5705 | 7001175 | Belleville    | 
| 1359731063  | Westmont Surg Ctr, LLC                         | Salt Creek Surgery Center                   | Du Page  | (630) 968-1800 | 7002587 | Westmont      | 
```