# CEQR Project Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ceqr-project-locations) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/did2-qzw3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/did2-qzw3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/did2-qzw3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | did2-qzw3 |
| Name | CEQR Project Locations |
| Attribution | Mayor's Office of Sustainability (MOS) |
| Category | City Government |
| Tags | sustainability, mos, ceqr, environment, project |
| Created | 2015-11-25T20:58:08Z |
| Publication Date | 2017-04-20T14:12:26Z |

## Description

CEQR Open Data contains information on projects that are undergoing or have completed review through the City Environmental Quality Review (CEQR) process. Project information available at the Open Data Portal includes the CEQR Number, Project Name, the Project Description, the Lead Agency, project milestones, and geographical locations. CEQR Open Data contains information on CEQR projects, which were filed with the Mayor?s Office from January 1, 2005 to the present.  For associated documents, please follow the links to the CEQR Access Database.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | ceqr               | CEQR               | text      | text        |
| Yes      | series tag  | project_name       | Project Name       | text      | text        |
| Yes      | series tag  | block              | Block              | text      | number      |
| Yes      | series tag  | lot                | Lot                | text      | number      |
| Yes      | series tag  | community_district | Community District | text      | text        |
| Yes      | series tag  | house_number       | House Number       | text      | text        |
| Yes      | series tag  | street_name        | Street Name        | text      | text        |
| Yes      | series tag  | zip_code           | Zip Code           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:did2-qzw3 d:2017-04-20T14:12:14.000Z t:house_number=240 t:project_name="Le Triumphe" t:zip_code=10022 t:ceqr=79-069M t:street_name="EAST   59 STREET" t:community_district=MN08 m:row_number.did2-qzw3=1

series e:did2-qzw3 d:2017-04-20T14:12:14.000Z t:house_number=240 t:project_name="Le Triumphe" t:zip_code=10022 t:ceqr=79-069M t:street_name="EAST   59 STREET" t:community_district=MN06 m:row_number.did2-qzw3=2

series e:did2-qzw3 d:2017-04-20T14:12:14.000Z t:project_name="46-50 Ganesvoort Street Project" t:ceqr=82-270M t:lot=43 t:block=643 t:community_district=MN03 m:row_number.did2-qzw3=3
```

## Meta Commands

```ls
metric m:row_number.did2-qzw3 p:long l:"Row Number"

entity e:did2-qzw3 l:"CEQR Project Locations" t:attribution="Mayor's Office of Sustainability (MOS)" t:url=https://data.cityofnewyork.us/api/views/did2-qzw3

property e:did2-qzw3 t:meta.view v:id=did2-qzw3 v:category="City Government" v:averageRating=0 v:name="CEQR Project Locations" v:attribution="Mayor's Office of Sustainability (MOS)"

property e:did2-qzw3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:did2-qzw3 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | ceqr    | project_name                    | block | lot | community_district | house_number | street_name             | zip_code | 
| =========== | ======= | =============================== | ===== | === | ================== | ============ | ======================= | ======== | 
| 1492697534  | 79-069M | Le Triumphe                     |       |     | MN08               | 240          | EAST 59 STREET          | 10022    | 
| 1492697534  | 79-069M | Le Triumphe                     |       |     | MN06               | 240          | EAST 59 STREET          | 10022    | 
| 1492697534  | 82-270M | 46-50 Ganesvoort Street Project | 643   | 43  | MN03               |              |                         |          | 
| 1492697534  | 82-270M | 46-50 Ganesvoort Street Project | 643   | 43  | MN02               |              |                         |          | 
| 1492697534  | 82-270M | 46-50 Ganesvoort Street Project | 643   | 49  | MN03               |              |                         |          | 
| 1492697534  | 82-270M | 46-50 Ganesvoort Street Project | 643   | 49  | MN02               |              |                         |          | 
| 1492697534  | 82-270M | 46-50 Ganesvoort Street Project | 643   | 54  | MN03               |              | 46-50 GANESVOORT STREET |          | 
| 1492697534  | 82-270M | 46-50 Ganesvoort Street Project | 643   | 54  | MN02               |              | 46-50 GANESVOORT STREET |          | 
| 1492697534  | 85-212M | Solow Management Corp           |       |     | MN04               | 400          | EAST 61 STREET          | 10021    | 
| 1492697534  | 86-082M | 7th Avenue Rezoning             | 798   | 7   | MN04               |              |                         |          | 
```