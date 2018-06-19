# Excess Property

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/excess-property-f7ef9) |
| Metadata | [Link](https://data.seattle.gov/api/views/yenx-5x5h) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/yenx-5x5h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/yenx-5x5h/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | yenx-5x5h |
| Name | Excess Property |
| Category | Land Base |
| Tags | excess property |
| Created | 2014-03-24T20:46:06Z |
| Publication Date | 2014-09-23T19:15:30Z |

## Description

List of properties in the reuse and disposition review process

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | numeric metric | pma                        | PMA #                      | number    | number      |
| Yes      | series tag     | status                     | Page Type                  | text      | text        |
| Yes      | series tag     | more_information           | More Information           | url       | url         |
| Yes      | series tag     | review_stage               | Review Stage               | text      | text        |
| Yes      | series tag     | property_name              | Property Name              | text      | text        |
| Yes      | series tag     | type                       | Type                       | text      | text        |
| Yes      | series tag     | department                 | Department                 | text      | text        |
| Yes      | numeric metric | neighborhood               | Neighborhood               | number    | number      |
| Yes      | series tag     | e_property_description     | E. Property Description    | document  | document    |
| Yes      | series tag     | e_property_notice          | E. Property Notice         | document  | document    |
| Yes      | series tag     | map                        | Map                        | document  | document    |
| Yes      | series tag     | picture                    | picture                    | photo     | photo       |
| Yes      | series tag     | tmbpictures                | tmbpictures                | photo     | photo       |
| Yes      | series tag     | pma_detail_report          | PMA Detail Report          | document  | document    |
| Yes      | series tag     | ordinances                 | Ordinances                 | document  | document    |
| Yes      | series tag     | documents                  | Ordinance 2                | document  | document    |
| Yes      | series tag     | ordinance_3                | Ordinance_3                | document  | document    |
| Yes      | series tag     | ordinance_4                | Ordinance 4                | document  | document    |
| Yes      | series tag     | ordinance_5                | Ordinance 5                | document  | document    |
| Yes      | series tag     | cma                        | CMA                        | document  | document    |
| Yes      | series tag     | preliminary_report         | Preliminary Report         | document  | document    |
| Yes      | series tag     | public_notice_prelimreport | Public Notice Prelimreport | document  | document    |
| Yes      | series tag     | page_type_select           | Page Type Select           | text      | text        |
| Yes      | series tag     | plans                      | Plans                      | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yenx-5x5h d:2014-03-24T13:46:08.000Z t:property_name="Building at 620 Aurora Ave North" t:status="Under review" t:department=SDOT t:type=Parcel t:review_stage="Pending reuse" m:pma=4186

series e:yenx-5x5h d:2014-03-24T13:46:08.000Z t:property_name="Manning Street Triangle" t:status="Completed/on hold" t:department=FAS t:type=Parcel t:review_stage="Pending transfer to Parks" m:pma=4273

series e:yenx-5x5h d:2014-03-24T13:46:08.000Z t:property_name="Snippets on MLK" t:status="For sale" t:department=FAS t:type=Snippet t:review_stage="For sale" m:pma=4324
```

## Meta Commands

```ls
metric m:pma p:integer l:"PMA #" t:dataTypeName=number

metric m:neighborhood p:long l:Neighborhood t:dataTypeName=number

entity e:yenx-5x5h l:"Excess Property" t:url=https://data.seattle.gov/api/views/yenx-5x5h

property e:yenx-5x5h t:meta.view v:id=yenx-5x5h v:category="Land Base" v:averageRating=0 v:name="Excess Property"

property e:yenx-5x5h t:meta.view.owner v:id=fqtv-q6su v:profileImageUrlMedium=/api/users/fqtv-q6su/profile_images/THUMB v:profileImageUrlLarge=/api/users/fqtv-q6su/profile_images/LARGE v:screenName="FAS - Real Estate Services" v:profileImageUrlSmall=/api/users/fqtv-q6su/profile_images/TINY v:displayName="FAS - Real Estate Services"

property e:yenx-5x5h t:meta.view.tableauthor v:id=fqtv-q6su v:profileImageUrlMedium=/api/users/fqtv-q6su/profile_images/THUMB v:profileImageUrlLarge=/api/users/fqtv-q6su/profile_images/LARGE v:screenName="FAS - Real Estate Services" v:profileImageUrlSmall=/api/users/fqtv-q6su/profile_images/TINY v:roleName=publisher v:displayName="FAS - Real Estate Services"
```

## Top Records

```ls
| :updated_at | pma  | status            | more_information | review_stage              | property_name                    | type    | department | neighborhood | e_property_description   | e_property_notice        | map                      | picture | tmbpictures | pma_detail_report        | ordinances               | documents                | ordinance_3              | ordinance_4              | ordinance_5              | cma                      | preliminary_report       | public_notice_prelimreport | page_type_select | plans                    | 
| =========== | ==== | ================= | ================ | ========================= | ================================ | ======= | ========== | ============ | ======================== | ======================== | ======================== | ======= | =========== | ======================== | ======================== | ======================== | ======================== | ======================== | ======================== | ======================== | ======================== | ========================== | ================ | ======================== | 
| 1395668768  | 4186 | Under review      | [null, null]     | Pending reuse             | Building at 620 Aurora Ave North | Parcel  | SDOT       |              | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] |         |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null]   |                  | [null, null, null, null] | 
| 1395668768  | 4273 | Completed/on hold | [null, null]     | Pending transfer to Parks | Manning Street Triangle          | Parcel  | FAS        |              | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] |         |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null]   |                  | [null, null, null, null] | 
| 1395668768  | 4324 | For sale          | [null, null]     | For sale                  | Snippets on MLK                  | Snippet | FAS        |              | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] |         |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null]   |                  | [null, null, null, null] | 
| 1395668768  | 4325 | Sold              | [null, null]     | Sold                      | Parcel At 200 MLK Jr Way         | Parcel  | FAS        |              | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] |         |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null]   |                  | [null, null, null, null] | 
| 1395668768  | 4539 | Under review      | [null, null]     | Pending reuse             | Myers Way parcels                | Parcel  | FAS        |              | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] |         |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null]   |                  | [null, null, null, null] | 
| 1395668768  | 4540 | Under review      | [null, null]     | Pending reuse             | Myers Way parcels                | Parcel  | FAS        |              | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] |         |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null]   |                  | [null, null, null, null] | 
| 1395668768  | 4541 | Under review      | [null, null]     | Pending reuse             | Myers Way parcels                | Parcel  | FAS        |              | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] |         |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null]   |                  | [null, null, null, null] | 
| 1395668768  | 4542 | Under review      | [null, null]     | Pending reuse             | Myers Way parcels                | Parcel  | FAS        |              | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] |         |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null]   |                  | [null, null, null, null] | 
| 1395668768  | 9040 | Under review      | [null, null]     | Pending reuse             | Red Barn Ranch                   | Parcel  | Parks      |              | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] |         |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null]   |                  | [null, null, null, null] | 
| 1395668768  | 9050 | For sale          | [null, null]     | For sale                  | Kent Highlands Landfill          | Parcel  | SPU        |              | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] |         |             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null]   |                  | [null, null, null, null] | 
```