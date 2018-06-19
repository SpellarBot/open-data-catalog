# [DEPRECATED] Austin Animal Center Outcomes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-animal-center-outcomes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/jpst-ix7f) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/jpst-ix7f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/jpst-ix7f/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | jpst-ix7f |
| Name | [DEPRECATED] Austin Animal Center Outcomes |
| Attribution | Austin Animal Center |
| Category | Health |
| Created | 2015-10-19T22:15:37Z |
| Publication Date | 2017-01-11T17:06:15Z |

## Description

This data has a new home! https://data.austintexas.gov/d/9t4d-g238

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | animal_id        | Animal ID        | text          | text          |
| Yes      | series tag  | name             | Name             | text          | text          |
| Yes      | time        | datetime         | DateTime         | calendar_date | calendar_date |
| No       |             | datetime2        | MonthYear        | calendar_date | calendar_date |
| Yes      | series tag  | outcome_type     | Outcome Type     | text          | text          |
| Yes      | series tag  | outcome_subtype  | Outcome Subtype  | text          | text          |
| Yes      | series tag  | animal_type      | Animal Type      | text          | text          |
| Yes      | series tag  | sex_upon_outcome | Sex upon Outcome | text          | text          |
| Yes      | series tag  | age_upon_outcome | Age upon Outcome | text          | text          |
| Yes      | series tag  | breed            | Breed            | text          | text          |
| Yes      | series tag  | color            | Color            | text          | text          |
```

## Time Field

```ls
Value = datetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = datetime2
```

## Data Commands

```ls
series e:jpst-ix7f d:2013-10-01T09:31:00.000Z t:breed="Labrador Retriever Mix" t:age_upon_outcome="2 months" t:color=Black t:sex_upon_outcome="Neutered Male" t:outcome_type=Adoption t:name=*Dudley t:outcome_subtype=Foster t:animal_type=Dog t:animal_id=A659834 m:row_number.jpst-ix7f=1

series e:jpst-ix7f d:2013-10-01T10:39:00.000Z t:breed="Domestic Shorthair Mix" t:age_upon_outcome="1 week" t:color=Orange/White t:sex_upon_outcome=Unknown t:outcome_type=Transfer t:outcome_subtype=Partner t:animal_type=Cat t:animal_id=A664235 m:row_number.jpst-ix7f=2

series e:jpst-ix7f d:2013-10-01T10:44:00.000Z t:breed="Domestic Shorthair Mix" t:age_upon_outcome="1 week" t:color=Orange/White t:sex_upon_outcome=Unknown t:outcome_type=Transfer t:outcome_subtype=Partner t:animal_type=Cat t:animal_id=A664237 m:row_number.jpst-ix7f=3
```

## Meta Commands

```ls
metric m:row_number.jpst-ix7f p:long l:"Row Number"

entity e:jpst-ix7f l:"[DEPRECATED] Austin Animal Center Outcomes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/jpst-ix7f

property e:jpst-ix7f t:meta.view v:id=jpst-ix7f v:category=Health v:attributionLink=http://www.austintexas.gov/department/animal-services v:averageRating=0 v:name="[DEPRECATED] Austin Animal Center Outcomes" v:attribution="Austin Animal Center"

property e:jpst-ix7f t:meta.view.license v:name="Public Domain"

property e:jpst-ix7f t:meta.view.owner v:id=nc6h-vjxb v:screenName=duron v:displayName=duron

property e:jpst-ix7f t:meta.view.tableauthor v:id=nc6h-vjxb v:screenName=duron v:roleName=editor v:displayName=duron
```

## Top Records

```ls
| animal_id | name      | datetime            | datetime2           | outcome_type    | outcome_subtype | animal_type | sex_upon_outcome | age_upon_outcome | breed                  | color        | 
| ========= | ========= | =================== | =================== | =============== | =============== | =========== | ================ | ================ | ====================== | ============ | 
| A659834   | *Dudley   | 2013-10-01T09:31:00 | 2013-10-01T09:31:00 | Adoption        | Foster          | Dog         | Neutered Male    | 2 months         | Labrador Retriever Mix | Black        | 
| A664235   |           | 2013-10-01T10:39:00 | 2013-10-01T10:39:00 | Transfer        | Partner         | Cat         | Unknown          | 1 week           | Domestic Shorthair Mix | Orange/White | 
| A664237   |           | 2013-10-01T10:44:00 | 2013-10-01T10:44:00 | Transfer        | Partner         | Cat         | Unknown          | 1 week           | Domestic Shorthair Mix | Orange/White | 
| A664236   |           | 2013-10-01T10:44:00 | 2013-10-01T10:44:00 | Transfer        | Partner         | Cat         | Unknown          | 1 week           | Domestic Shorthair Mix | Orange/White | 
| A664223   | Moby      | 2013-10-01T11:03:00 | 2013-10-01T11:03:00 | Return to Owner |                 | Dog         | Neutered Male    | 4 years          | Bulldog Mix            | White        | 
| A663646   |           | 2013-10-01T11:12:00 | 2013-10-01T11:12:00 | Transfer        | Partner         | Dog         | Neutered Male    | 3 years          | Toy Poodle Mix         | White        | 
| A663888   |           | 2013-10-01T11:13:00 | 2013-10-01T11:13:00 | Transfer        | Partner         | Dog         | Spayed Female    | 2 years          | Boxer Mix              | Red/White    | 
| A663572   | *Starla   | 2013-10-01T11:42:00 | 2013-10-01T11:42:00 | Adoption        |                 | Dog         | Spayed Female    | 3 years          | Anatol Shepherd Mix    | White/Brown  | 
| A663833   | Baby Girl | 2013-10-01T11:50:00 | 2013-10-01T11:50:00 | Return to Owner |                 | Dog         | Spayed Female    | 9 years          | Labrador Retriever Mix | Black        | 
| A661795   | Blakie    | 2013-10-01T11:53:00 | 2013-10-01T11:53:00 | Adoption        |                 | Cat         | Spayed Female    | 6 months         | Domestic Shorthair Mix | Tortie       | 
```