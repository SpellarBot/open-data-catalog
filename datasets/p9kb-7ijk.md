# Campaign Finance Filers on Record with the New York State Board of Elections: Beginning July 1999

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-filers-on-record-with-the-new-york-state-board-of-elections-beginning-jul) |
| Metadata | [Link](https://data.ny.gov/api/views/p9kb-7ijk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/p9kb-7ijk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/p9kb-7ijk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | p9kb-7ijk |
| Name | Campaign Finance Filers on Record with the New York State Board of Elections: Beginning July 1999 |
| Attribution | NYS Board of Elections |
| Category | Transparency |
| Tags | campaigns, elections, disclosure, politics, integrity |
| Created | 2013-04-08T17:36:34Z |
| Publication Date | 2017-04-10T22:43:17Z |

## Description

This dataset contains information on the candidates and/or committees who file campaign finance disclosure information with the NYS Board of Elections. This data covers the period beginning July 1999. For updated information, please visit http://www.elections.ny.gov

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                                     | Data Type | Render Type |
| ======== | ============== | ==================== | ======================================== | ========= | =========== |
| Yes      | series tag     | filer_id             | Filer ID                                 | text      | text        |
| Yes      | series tag     | filer_name           | Candidate or Committee Name (Filer Name) | text      | text        |
| Yes      | series tag     | filer_type           | Filer Type                               | text      | text        |
| Yes      | series tag     | status               | Status                                   | text      | text        |
| Yes      | series tag     | committee_type       | Committee Type                           | text      | text        |
| Yes      | numeric metric | office               | Office                                   | number    | number      |
| Yes      | series tag     | district             | District                                 | text      | number      |
| Yes      | series tag     | treasurer_first_name | Treasurer First Name                     | text      | text        |
| Yes      | series tag     | treasurer_last_name  | Treasurer Last Name                      | text      | text        |
| No       |                | address              | Address                                  | text      | text        |
| Yes      | series tag     | city                 | City                                     | text      | text        |
| Yes      | series tag     | state                | State                                    | text      | text        |
| Yes      | series tag     | zip                  | Zip                                      | text      | text        |
```

## Time Field

```ls
Value = 1999
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:p9kb-7ijk d:1999-01-01T00:00:00.000Z t:zip=11412 t:filer_name="I. DANEEK MILLER" t:treasurer_last_name=MILLER t:status=ACTIVE t:filer_id=C99294 t:state=NY t:filer_type=CANDIDATE t:district=27 t:treasurer_first_name=I. t:city="ST. ALBANS" m:office=32

series e:p9kb-7ijk d:1999-01-01T00:00:00.000Z t:zip=11510 t:filer_name="FRIENDS OF I. DANEEK MILLER" t:treasurer_last_name=HENRY t:status=ACTIVE t:filer_id=C99293 t:committee_type=1 t:state=NY t:filer_type=COMMITTEE t:district=27 t:treasurer_first_name=MARK t:city=BALDWIN m:office=32

series e:p9kb-7ijk d:1999-01-01T00:00:00.000Z t:zip=14214 t:filer_name="DEBRA LYNN GIVENS" t:treasurer_last_name=GIVENS t:status=ACTIVE t:filer_id=C99292 t:state=NY t:filer_type=CANDIDATE t:treasurer_first_name=DEBRA t:city=BUFFALO m:office=57
```

## Meta Commands

```ls
metric m:office p:integer l:Office t:dataTypeName=number

entity e:p9kb-7ijk l:"Campaign Finance Filers on Record with the New York State Board of Elections: Beginning July 1999" t:attribution="NYS Board of Elections" t:url=https://data.ny.gov/api/views/p9kb-7ijk

property e:p9kb-7ijk t:meta.view v:id=p9kb-7ijk v:category=Transparency v:attributionLink=http://www.elections.ny.gov/CFViewReports.html v:averageRating=0 v:name="Campaign Finance Filers on Record with the New York State Board of Elections: Beginning July 1999" v:attribution="NYS Board of Elections"

property e:p9kb-7ijk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:p9kb-7ijk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:p9kb-7ijk t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| filer_id | filer_name                         | filer_type | status   | committee_type | office | district | treasurer_first_name | treasurer_last_name | address                     | city       | state | zip   | 
| ======== | ================================== | ========== | ======== | ============== | ====== | ======== | ==================== | =================== | =========================== | ========== | ===== | ===== | 
| C99294   | I. DANEEK MILLER                   | CANDIDATE  | ACTIVE   |                | 32     | 27       | I.                   | MILLER              | 191-03 115 AVENUE           | ST. ALBANS | NY    | 11412 | 
| C99293   | FRIENDS OF I. DANEEK MILLER        | COMMITTEE  | ACTIVE   | 1              | 32     | 27       | MARK                 | HENRY               | 1078 CLYDE RD.              | BALDWIN    | NY    | 11510 | 
| C99292   | DEBRA LYNN GIVENS                  | CANDIDATE  | ACTIVE   |                | 57     |          | DEBRA                | GIVENS              | 36 LARCHMONT RD             | BUFFALO    | NY    | 14214 | 
| C99291   | COMMITTEE TO RE-ELECT JUDGE GIVENS | COMMITTEE  | ACTIVE   | 1              | 57     |          | DAVID                | GIVENS              | 62 BLAINE AVE               | BUFFALO    | NY    | 14208 | 
| C99290   | DR. BOLA OMOTOSHO                  | CANDIDATE  | ACTIVE   |                | 32     | 16       | DR. BOLA             | OMOTOSHO            | P.O. BOX 3349               | NEW YORK   | NY    | 10163 | 
| C99289   | FRIENDS OF BOLA OMOTOSHO           | COMMITTEE  | ACTIVE   | 1              | 32     | 16       | ANTHONY              | ADJEI               | 231-28 MERRICK BLVD         | LAURELTON  | NY    | 11413 | 
| C99287   | ADAM SILVERA                       | CANDIDATE  | INACTIVE |                | 60     | 2        | ADAM                 | SILVERA             | 40 FIRST AVENUE APT 5J      | NEW YORK   | NY    | 10009 | 
| C99286   | FRIENDS OF ADAM SILVERA            | COMMITTEE  | INACTIVE | 1              | 60     | 2        | PAUL                 | NEWELL              | 39 BOWERY, SUITE 916        | NEW YORK   | NY    | 10002 | 
| C99285   | ARI KAGAN                          | CANDIDATE  | INACTIVE |                | 32     | 48       | ARI                  | KAGAN               | 3093 BRIGHTON 4 STREET, #2N | BROOKLYN   | NY    | 11235 | 
| C99284   | ARI KAGAN FOR CITY COUNCIL         | COMMITTEE  | INACTIVE | 1              | 32     | 48       | ALYONA               | BADALOVA            | 330 OCEAN PARKWAY #C3       | BROOKLYN   | NY    | 11218 | 
```