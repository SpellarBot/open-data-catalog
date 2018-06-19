# Recidivism: Beginning 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recidivism-beginning-2008) |
| Metadata | [Link](https://data.ny.gov/api/views/y7pw-wrny) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/y7pw-wrny/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/y7pw-wrny/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | y7pw-wrny |
| Name | Recidivism: Beginning 2008 |
| Attribution | NYS Department of Corrections and Community Supervision |
| Category | Public Safety |
| Tags | prison releases, county of indictment, inmates, gender, age, recidivism |
| Created | 2014-06-10T14:53:16Z |
| Publication Date | 2016-04-15T22:10:35Z |

## Description

Represents return status within three years of release among inmates released to the community during a particular calendar year.  Each data record represents a release to the community as a result of completing maximum sentence, reaching conditional release date, or being approved for release by the Board of Parole.  The dataset includes data about release year, county of indictment, gender, age at release, and return status.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | release_year         | Release Year         | number    | number      |
| Yes      | series tag     | county_of_indictment | County of Indictment | text      | text        |
| Yes      | series tag     | gender               | Gender               | text      | text        |
| Yes      | numeric metric | age_at_release       | Age at Release       | number    | number      |
| Yes      | series tag     | return_status        | Return Status        | text      | text        |
```

## Time Field

```ls
Value = release_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:y7pw-wrny d:2008-01-01T00:00:00.000Z t:county_of_indictment=UNKNOWN t:gender=MALE t:return_status="Not Returned" m:age_at_release=55

series e:y7pw-wrny d:2008-01-01T00:00:00.000Z t:county_of_indictment=ALBANY t:gender=MALE t:return_status="Returned Parole Violation" m:age_at_release=16

series e:y7pw-wrny d:2008-01-01T00:00:00.000Z t:county_of_indictment=ALBANY t:gender=MALE t:return_status="Not Returned" m:age_at_release=17
```

## Meta Commands

```ls
metric m:age_at_release p:integer l:"Age at Release" d:"Inmate age as of the release date" t:dataTypeName=number

entity e:y7pw-wrny l:"Recidivism: Beginning 2008" t:attribution="NYS Department of Corrections and Community Supervision" t:url=https://data.ny.gov/api/views/y7pw-wrny

property e:y7pw-wrny t:meta.view v:id=y7pw-wrny v:category="Public Safety" v:averageRating=0 v:name="Recidivism: Beginning 2008" v:attribution="NYS Department of Corrections and Community Supervision"

property e:y7pw-wrny t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:y7pw-wrny t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:y7pw-wrny t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| release_year | county_of_indictment | gender | age_at_release | return_status             | 
| ============ | ==================== | ====== | ============== | ========================= | 
| 2008         | UNKNOWN              | MALE   | 55             | Not Returned              | 
| 2008         | ALBANY               | MALE   | 16             | Returned Parole Violation | 
| 2008         | ALBANY               | MALE   | 17             | Not Returned              | 
| 2008         | ALBANY               | MALE   | 17             | Returned Parole Violation | 
| 2008         | ALBANY               | MALE   | 18             | Not Returned              | 
| 2008         | ALBANY               | MALE   | 18             | Returned Parole Violation | 
| 2008         | ALBANY               | MALE   | 18             | Returned Parole Violation | 
| 2008         | ALBANY               | MALE   | 18             | Returned Parole Violation | 
| 2008         | ALBANY               | MALE   | 18             | Returned Parole Violation | 
| 2008         | ALBANY               | MALE   | 18             | Returned Parole Violation | 
```