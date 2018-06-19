# Hotels, Motels, B&Bs, and Boarding Houses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nola-short-term-rentals) |
| Metadata | [Link](https://data.nola.gov/api/views/ipcn-rszc) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/ipcn-rszc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/ipcn-rszc/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | ipcn-rszc |
| Name | Hotels, Motels, B&Bs, and Boarding Houses |
| Attribution | City of New Orleans ? Bureau of Revenue |
| Category | Economy and Workforce |
| Tags | hotel, motel, bed and breakfast, room, board |
| Created | 2015-08-07T16:11:26Z |
| Publication Date | 2017-02-20T19:16:11Z |

## Description

Names and locations of facilities within the City of New Orleans offering lodging accommodations. Facilities include hotels, motels, bed and breakfasts and room and board houses. Data provided by Bureau of Revenue.

## Columns

```ls
| Included | Schema Type | Field Name     | Name         | Data Type | Render Type |
| ======== | =========== | ============== | ============ | ========= | =========== |
| No       | time        | :updated_at    | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | name           | BusinessName | text      | text        |
| No       |             | street_address | Address      | text      | text        |
| Yes      | series tag  | suite          | Suite        | text      | text        |
| Yes      | series tag  | city           | City         | text      | text        |
| Yes      | series tag  | state          | State        | text      | text        |
| Yes      | series tag  | zip            | Zip          | text      | text        |
| Yes      | series tag  | occ_code       | BusinessType | text      | text        |
| Yes      | series tag  | ownername      | OwnerName    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = street_address
```

## Data Commands

```ls
series e:ipcn-rszc d:2017-02-20T19:15:11.000Z t:zip=70130 t:ownername="CREOLE GARDENS,LLC" t:name="1415 CREOLE GARDENS" t:state=LA t:occ_code="4701 - HOTELS (EXC CASINO HOTELS) & MOTELS" t:city="NEW ORLEANS" m:row_number.ipcn-rszc=1

series e:ipcn-rszc d:2017-02-20T19:15:11.000Z t:zip=70130 t:ownername="1503 GUEST HOUSE LLC" t:name="1503 GUEST HOUSE LLC" t:state=LA t:occ_code="4703 - BED & BREAKFAST INNS" t:city="NEW ORLEANS" m:row_number.ipcn-rszc=2

series e:ipcn-rszc d:2017-02-20T19:15:11.000Z t:zip=70116-1927 t:ownername="JEFFRIES KAREN" t:name="1830 DAUPHINE HOUSE" t:state=LA t:occ_code="4703 - BED & BREAKFAST INNS" t:city="NEW ORLEANS" m:row_number.ipcn-rszc=3
```

## Meta Commands

```ls
metric m:row_number.ipcn-rszc p:long l:"Row Number"

entity e:ipcn-rszc l:"Hotels, Motels, B&Bs, and Boarding Houses" t:attribution="City of New Orleans ? Bureau of Revenue" t:url=https://data.nola.gov/api/views/ipcn-rszc

property e:ipcn-rszc t:meta.view v:id=ipcn-rszc v:category="Economy and Workforce" v:averageRating=0 v:name="Hotels, Motels, B&Bs, and Boarding Houses" v:attribution="City of New Orleans ? Bureau of Revenue"

property e:ipcn-rszc t:meta.view.owner v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:ipcn-rszc t:meta.view.tableauthor v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:roleName=administrator v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:ipcn-rszc t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| :updated_at | name                           | street_address        | suite | city        | state | zip        | occ_code                                     | ownername                  | 
| =========== | ============================== | ===================== | ===== | =========== | ===== | ========== | ============================================ | ========================== | 
| 1487618111  | 1415 CREOLE GARDENS            | 1415 PRYTANIA ST      |       | NEW ORLEANS | LA    | 70130      | 4701 - HOTELS (EXC CASINO HOTELS) & MOTELS   | CREOLE GARDENS,LLC         | 
| 1487618111  | 1503 GUEST HOUSE LLC           | 1503 TCHOUPITOULAS ST |       | NEW ORLEANS | LA    | 70130      | 4703 - BED & BREAKFAST INNS                  | 1503 GUEST HOUSE LLC       | 
| 1487618111  | 1830 DAUPHINE HOUSE            | 1830 DAUPHINE ST      |       | NEW ORLEANS | LA    | 70116-1927 | 4703 - BED & BREAKFAST INNS                  | JEFFRIES KAREN             | 
| 1487618111  | 1851 INN ON ST CHARLES         | 2409 ST CHARLES AVE   |       | NEW ORLEANS | LA    | 70130-5825 | 4703 - BED & BREAKFAST INNS                  | PAULA R GEORGE             | 
| 1487618111  | 1896 O'MALLEY HOUSE            | 120 S PIERCE ST       |       | NEW ORLEANS | LA    | 70119-6033 | 4701 - HOTELS (EXC CASINO HOTELS) & MOTELS   | WATTS LARRY                | 
| 1487618111  | 2241 CHARTRES LLC              | 2241 CHARTRES ST      |       | NEW ORLEANS | LA    | 70117      | 4701 - HOTELS (EXC CASINO HOTELS) & MOTELS   | ROBERT F. CHEEK            | 
| 1487618111  | 2532 N RAMPART STREET, LLC     | 2532 N RAMPART ST     |       | NEW ORLEANS | LA    | 70117      | 8806 - .1(43) BED AND BREAKFAST 1 TO 2 ROOMS | 2532 N RAMPART STREET, LLC | 
| 1487618111  | 723 MARIGNY                    | 723 MARIGNY ST        |       | NEW ORLEANS | LA    | 70117      | 4703 - BED & BREAKFAST INNS                  | BENOIT, MICHELLE A.        | 
| 1487618111  | 735 MANDEVILLE                 | 735 MANDEVILLE ST     |       | NEW ORLEANS | LA    | 70117      | 4703 - BED & BREAKFAST INNS                  | LANDRY MERRITT D.          | 
| 1487618111  | 929 MARIGNY PAINTED LADY'S INN | 929 MARIGNY ST        |       | NEW ORLEANS | LA    | 70117-8539 | 4703 - BED & BREAKFAST INNS                  | TISKUS,PETER               | 
```