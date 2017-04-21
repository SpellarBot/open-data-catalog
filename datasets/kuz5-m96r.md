# Missouri Works Assistance Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-works-assistance-locations) |
| Metadata | [Link](https://data.mo.gov/api/views/kuz5-m96r) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/kuz5-m96r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/kuz5-m96r/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | kuz5-m96r |
| Name | Missouri Works Assistance Locations |
| Category | Social Services |
| Created | 2015-08-26T18:53:47Z |
| Publication Date | 2017-02-27T23:35:34Z |

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | center                 | Center                 | text      | text        |
| Yes      | series tag  | additional_information | Additional Information | text      | text        |
| Yes      | series tag  | phone_number           | Phone Number           | text      | text        |
| No       |             | address_2              | Address 2              | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_2
```

## Data Commands

```ls
series e:kuz5-m96r d:2015-08-26T11:54:10.000Z t:center="LINCWORKS                             EAST" t:phone_number="(816) 303-0660" m:row_number.kuz5-m96r=1

series e:kuz5-m96r d:2015-08-26T11:54:10.000Z t:center="WEST CENTRAL MISSOURI COMMUNITY ACTION AGENCY- VERNON" t:phone_number="(417) 667-5976" m:row_number.kuz5-m96r=2

series e:kuz5-m96r d:2015-08-26T11:54:10.000Z t:center=MERS/GOODWILL-MADISON t:phone_number="(573) 783-4215" m:row_number.kuz5-m96r=3
```

## Meta Commands

```ls
metric m:row_number.kuz5-m96r p:long l:"Row Number"

entity e:kuz5-m96r l:"Missouri Works Assistance Locations" t:url=https://data.mo.gov/api/views/kuz5-m96r

property e:kuz5-m96r t:meta.view v:id=kuz5-m96r v:category="Social Services" v:averageRating=0 v:name="Missouri Works Assistance Locations"

property e:kuz5-m96r t:meta.view.owner v:id=jzbz-iqr6 v:screenName=Breanna v:lastNotificationSeenAt=1492723347 v:displayName=Breanna

property e:kuz5-m96r t:meta.view.tableauthor v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:lastNotificationSeenAt=1492723347 v:displayName=Breanna
```

## Top Records

```ls
| :updated_at | center                                                | additional_information  | phone_number   | address_2 | 
| =========== | ===================================================== | ======================= | ============== | ========= | 
| 1440590050  | LINCWORKS EAST                                        |                         | (816) 303-0660 |           | 
| 1440590050  | WEST CENTRAL MISSOURI COMMUNITY ACTION AGENCY- VERNON |                         | (417) 667-5976 |           | 
| 1440590050  | MERS/GOODWILL-MADISON                                 |                         | (573) 783-4215 |           | 
| 1440590050  | LINCOLN COUNTY                                        | FAMILY SUPPORT DIVISION | (636) 528-8521 |           | 
| 1440590050  | GREEN HILLS COMMUNITY ACTION AGENCY-PUTNAM            | FSD OFFICE              | (660) 365-0561 |           | 
| 1440590050  | MERS/GOODWILL- WASHINGTON                             |                         | (573) 438-0302 |           | 
| 1440590050  | LEWIS COUNTY NECAC                                    |                         | (573) 719-9423 |           | 
| 1440590050  | MISSOURI VALLEY COMMUNITY ACTION AGENCY-PETTIS        |                         | (660) 826-0804 | SUITE A   | 
| 1440590050  | MERS/GOODWILL OUTREACH-PHELPS                         | BOURBON CITY HALL       | (573) 732-5550 |           | 
| 1440590050  | MERS/GOODWILL OUTREACH-MILLER                         | ELDON PUBLIC LIBRARY    | (573) 392-6657 |           | 
```