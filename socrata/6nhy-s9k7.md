# 2015 Candidate Sites: Mid Columbia Status and Trends Region

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-candidate-sites-mid-columbia-status-and-trends-region-002ec) |
| Metadata | [Link](https://data.wa.gov/api/views/6nhy-s9k7) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/6nhy-s9k7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/6nhy-s9k7/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 6nhy-s9k7 |
| Name | 2015 Candidate Sites: Mid Columbia Status and Trends Region |
| Attribution | Washington Department of Ecology, Environmental Assessment Program |
| Category | Natural Resources & Environment |
| Tags | watershed health monitoring |
| Created | 2014-11-13T22:37:49Z |
| Publication Date | 2014-11-13T22:39:39Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | site_id              | SITE_ID              | text      | text        |
| Yes      | series tag     | salmon_rr            | SALMON_RR            | text      | text        |
| Yes      | series tag     | targetstatus_2       | TargetStatus_2       | text      | text        |
| Yes      | numeric metric | sizeclass            | SizeClass            | number    | number      |
| Yes      | numeric metric | revisedstrahlerorder | RevisedStrahlerOrder | number    | number      |
| No       |                | lat_dd               | LAT_DD               | number    | number      |
| Yes      | series tag     | county_nm            | COUNTY_NM            | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = lat_dd
```

## Data Commands

```ls
series e:6nhy-s9k7 d:2015-01-01T00:00:00.000Z t:targetstatus_2=repeat t:site_id=WAM06600-012453 t:salmon_rr="Mid Columbia" t:county_nm="Yakima County" m:sizeclass=0 m:revisedstrahlerorder=0

series e:6nhy-s9k7 d:2015-01-01T00:00:00.000Z t:targetstatus_2=repeat t:site_id=WAM06600-034366 t:salmon_rr="Mid Columbia" t:county_nm="Kittitas County" m:sizeclass=0 m:revisedstrahlerorder=0

series e:6nhy-s9k7 d:2015-01-01T00:00:00.000Z t:targetstatus_2=repeat t:site_id=WAM06600-034965 t:salmon_rr="Mid Columbia" t:county_nm="Yakima County" m:sizeclass=0 m:revisedstrahlerorder=0
```

## Meta Commands

```ls
metric m:sizeclass p:integer l:SizeClass t:dataTypeName=number

metric m:revisedstrahlerorder p:integer l:RevisedStrahlerOrder t:dataTypeName=number

entity e:6nhy-s9k7 l:"2015 Candidate Sites: Mid Columbia Status and Trends Region" t:attribution="Washington Department of Ecology, Environmental Assessment Program" t:url=https://data.wa.gov/api/views/6nhy-s9k7

property e:6nhy-s9k7 t:meta.view v:id=6nhy-s9k7 v:category="Natural Resources & Environment" v:attributionLink=http://tinyurl.com/WatershedHealth v:averageRating=0 v:name="2015 Candidate Sites: Mid Columbia Status and Trends Region" v:attribution="Washington Department of Ecology, Environmental Assessment Program"

property e:6nhy-s9k7 t:meta.view.owner v:id=h9w5-qfr2 v:profileImageUrlMedium=/api/users/h9w5-qfr2/profile_images/THUMB v:profileImageUrlLarge=/api/users/h9w5-qfr2/profile_images/LARGE v:screenName=glenn.merritt@ecy.wa.gov v:profileImageUrlSmall=/api/users/h9w5-qfr2/profile_images/TINY v:displayName=glenn.merritt@ecy.wa.gov

property e:6nhy-s9k7 t:meta.view.tableauthor v:id=h9w5-qfr2 v:profileImageUrlMedium=/api/users/h9w5-qfr2/profile_images/THUMB v:profileImageUrlLarge=/api/users/h9w5-qfr2/profile_images/LARGE v:screenName=glenn.merritt@ecy.wa.gov v:profileImageUrlSmall=/api/users/h9w5-qfr2/profile_images/TINY v:roleName=publisher v:displayName=glenn.merritt@ecy.wa.gov
```

## Top Records

```ls
| site_id         | salmon_rr    | targetstatus_2 | sizeclass | revisedstrahlerorder | lat_dd         | county_nm        | 
| =============== | ============ | ============== | ========= | ==================== | ============== | ================ | 
| WAM06600-012453 | Mid Columbia | repeat         | 0         | 0                    | 46.19307088430 | Yakima County    | 
| WAM06600-034366 | Mid Columbia | repeat         | 0         | 0                    | 47.19256609400 | Kittitas County  | 
| WAM06600-034965 | Mid Columbia | repeat         | 0         | 0                    | 46.25438045090 | Yakima County    | 
| WAM06600-037710 | Mid Columbia | repeat         | 0         | 0                    | 47.16095146240 | Kittitas County  | 
| WAM06600-038094 | Mid Columbia | repeat         | 0         | 0                    | 47.22423327890 | Kittitas County  | 
| WAM06600-040922 | Mid Columbia | repeat         | 0         | 0                    | 46.98412691080 | Kittitas County  | 
| WAM06600-040961 | Mid Columbia | target         | 0         | 0                    | 45.77917670420 | Klickitat County | 
| WAM06600-041066 | Mid Columbia | target         | 0         | 0                    | 47.00943239730 | Kittitas County  | 
| WAM06600-041070 | Mid Columbia | target         | 0         | 0                    | 47.23679574600 | Kittitas County  | 
| WAM06600-041518 | Mid Columbia | target         | 0         | 0                    | 47.29163006530 | Kittitas County  | 
```