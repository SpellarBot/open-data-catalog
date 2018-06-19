# Crisis Residential Center (CRC), Responsible Living Skills Program (RLSP) and Hope Center Beds by County (2014)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/crisis-residential-center-crc-responsible-living-skills-program-rlsp-and-hope-center-beds-) |
| Metadata | [Link](https://data.wa.gov/api/views/c6fd-kz2a) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/c6fd-kz2a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/c6fd-kz2a/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | c6fd-kz2a |
| Name | Crisis Residential Center (CRC), Responsible Living Skills Program (RLSP) and Hope Center Beds by County (2014) |
| Attribution | Office of Juvenile Justice |
| Category | Public Safety |
| Tags | juvenile justice, annual report, wa-pcjj report, office of juvenile justice, dshs, hope center, living skills, youth |
| Created | 2015-12-14T15:04:32Z |
| Publication Date | 2016-01-21T02:34:56Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | county            | County            | text      | text        |
| Yes      | numeric metric | regional_crc_beds | Regional CRC Beds | number    | number      |
| Yes      | numeric metric | secure_crc_beds   | Secure CRC Beds   | number    | number      |
| Yes      | numeric metric | rlsp_beds         | RLSP Beds         | number    | number      |
| Yes      | numeric metric | hope_ctr_beds     | Hope Ctr Beds     | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:c6fd-kz2a d:2014-01-01T00:00:00.000Z t:county=Chelan m:secure_crc_beds=4

series e:c6fd-kz2a d:2014-01-01T00:00:00.000Z t:county=Clallam m:secure_crc_beds=4

series e:c6fd-kz2a d:2014-01-01T00:00:00.000Z t:county=Clark m:regional_crc_beds=4 m:secure_crc_beds=6 m:hope_ctr_beds=3
```

## Meta Commands

```ls
metric m:regional_crc_beds p:integer l:"Regional CRC Beds" t:dataTypeName=number

metric m:secure_crc_beds p:integer l:"Secure CRC Beds" t:dataTypeName=number

metric m:rlsp_beds p:integer l:"RLSP Beds" t:dataTypeName=number

metric m:hope_ctr_beds p:integer l:"Hope Ctr Beds" t:dataTypeName=number

entity e:c6fd-kz2a l:"Crisis Residential Center (CRC), Responsible Living Skills Program (RLSP) and Hope Center Beds by County (2014)" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/c6fd-kz2a

property e:c6fd-kz2a t:meta.view v:id=c6fd-kz2a v:category="Public Safety" v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=0 v:name="Crisis Residential Center (CRC), Responsible Living Skills Program (RLSP) and Hope Center Beds by County (2014)" v:attribution="Office of Juvenile Justice"

property e:c6fd-kz2a t:meta.view.license v:name="Public Domain"

property e:c6fd-kz2a t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:c6fd-kz2a t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```

## Top Records

```ls
| county    | regional_crc_beds | secure_crc_beds | rlsp_beds | hope_ctr_beds | 
| ========= | ================= | =============== | ========= | ============= | 
| Chelan    |                   | 4               |           |               | 
| Clallam   |                   | 4               |           |               | 
| Clark     | 4                 | 6               |           | 3             | 
| King      | 3                 | 15              | 4         | 4             | 
| Pierce    |                   |                 | 7         |               | 
| Skagit    |                   |                 | 3         |               | 
| Snohomish | 6                 |                 | 4         | 4             | 
| Spokane   | 8                 |                 | 4         | 5             | 
| Thurston  | 7                 |                 | 6         | 3             | 
| Whatcom   |                   |                 |           | 1             | 
```