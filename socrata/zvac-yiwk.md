# IDFPR Illinois Licensed Physicians and Surgeons in Active status by county as of Jan 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idfpr-illinois-licensed-physicians-and-surgeons-in-active-status-by-county-as-of-jan-2012-28b46) |
| Metadata | [Link](https://data.illinois.gov/api/views/zvac-yiwk) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/zvac-yiwk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/zvac-yiwk/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | zvac-yiwk |
| Name | IDFPR Illinois Licensed Physicians and Surgeons in Active status by county as of Jan 2012 |
| Category | Public Health |
| Tags | health |
| Created | 2012-01-24T19:03:55Z |
| Publication Date | 2012-01-24T19:06:18Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | division        | Division        | text      | text        |
| Yes      | series tag     | profession      | Profession      | text      | text        |
| Yes      | series tag     | illinois_county | Illinois County | text      | text        |
| Yes      | numeric metric | count           | Count           | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:zvac-yiwk d:2012-01-01T00:00:00.000Z t:division="Illinois Medical Board" t:illinois_county=ADAMS t:profession="036 LICENSED PHYSICIAN AND SURGEON" m:count=215

series e:zvac-yiwk d:2012-01-01T00:00:00.000Z t:division="Illinois Medical Board" t:illinois_county=ALEXANDER t:profession="036 LICENSED PHYSICIAN AND SURGEON" m:count=3

series e:zvac-yiwk d:2012-01-01T00:00:00.000Z t:division="Illinois Medical Board" t:illinois_county=BOND t:profession="036 LICENSED PHYSICIAN AND SURGEON" m:count=24
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:zvac-yiwk l:"IDFPR Illinois Licensed Physicians and Surgeons in Active status by county as of Jan 2012" t:url=https://data.illinois.gov/api/views/zvac-yiwk

property e:zvac-yiwk t:meta.view v:id=zvac-yiwk v:category="Public Health" v:averageRating=0 v:name="IDFPR Illinois Licensed Physicians and Surgeons in Active status by county as of Jan 2012"

property e:zvac-yiwk t:meta.view.owner v:id=2jwj-ihvp v:screenName=Dfee v:displayName=Dfee

property e:zvac-yiwk t:meta.view.tableauthor v:id=2jwj-ihvp v:screenName=Dfee v:displayName=Dfee
```

## Top Records

```ls
| division               | profession                         | illinois_county | count | 
| ====================== | ================================== | =============== | ===== | 
| Illinois Medical Board | 036 LICENSED PHYSICIAN AND SURGEON | ADAMS           | 215   | 
| Illinois Medical Board | 036 LICENSED PHYSICIAN AND SURGEON | ALEXANDER       | 3     | 
| Illinois Medical Board | 036 LICENSED PHYSICIAN AND SURGEON | BOND            | 24    | 
| Illinois Medical Board | 036 LICENSED PHYSICIAN AND SURGEON | BOONE           | 72    | 
| Illinois Medical Board | 036 LICENSED PHYSICIAN AND SURGEON | BROWN           | 5     | 
| Illinois Medical Board | 036 LICENSED PHYSICIAN AND SURGEON | BUREAU          | 39    | 
| Illinois Medical Board | 036 LICENSED PHYSICIAN AND SURGEON | CALHOUN         | 4     | 
| Illinois Medical Board | 036 LICENSED PHYSICIAN AND SURGEON | CARROLL         | 7     | 
| Illinois Medical Board | 036 LICENSED PHYSICIAN AND SURGEON | CASS            | 4     | 
| Illinois Medical Board | 036 LICENSED PHYSICIAN AND SURGEON | CHAMPAIGN       | 579   | 
```