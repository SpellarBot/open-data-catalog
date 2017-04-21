# Streets Data -Historical Pavement Condition Index (PCI) Scores

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/paving-pci-scores-historical-data) |
| Metadata | [Link](https://data.sfgov.org/api/views/78va-8dhi) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/78va-8dhi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/78va-8dhi/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 78va-8dhi |
| Name | Streets Data -Historical Pavement Condition Index (PCI) Scores |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | paving, pci, score, historical, streets, condition, index |
| Created | 2016-02-03T01:54:27Z |
| Publication Date | 2016-12-06T03:37:39Z |

## Description

Historical Pavement Condition Index (PCI) Scores by location.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| Yes      | numeric metric | cnn                             | CNN                             | number        | number        |
| Yes      | series tag     | street_name                     | Street_Name                     | text          | text          |
| Yes      | series tag     | from_street                     | From_Street                     | text          | text          |
| Yes      | series tag     | to_street                       | To_Street                       | text          | text          |
| Yes      | numeric metric | pci_score                       | PCI_Score                       | number        | number        |
| Yes      | time           | pci_change_date                 | PCI_Change_Date                 | calendar_date | calendar_date |
| Yes      | series tag     | treatment_or_survey             | Treatment_or_Survey             | text          | text          |
| Yes      | series tag     | street_accepted_for_maintenance | Street_Accepted_For_Maintenance | text          | text          |
| Yes      | series tag     | functional_class                | Functional_Class                | text          | text          |
```

## Time Field

```ls
Value = pci_change_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:78va-8dhi d:2014-04-16T10:22:28.000Z t:treatment_or_survey=Treatment t:to_street=Intersection t:street_name="01st St" t:street_accepted_for_maintenance=No t:from_street="Bush St \ Market St" m:pci_score=100 m:cnn=30731000

series e:78va-8dhi d:1977-05-01T00:00:00.000Z t:treatment_or_survey=Treatment t:to_street="FOLSOM ST" t:street_name="01ST ST" t:street_accepted_for_maintenance=No t:from_street="CLEMENTINA ST" m:pci_score=100 m:cnn=110000

series e:78va-8dhi d:1992-01-01T00:00:00.000Z t:treatment_or_survey=Survey t:to_street="FOLSOM ST" t:street_name="01ST ST" t:street_accepted_for_maintenance=No t:from_street="CLEMENTINA ST" m:pci_score=51 m:cnn=110000
```

## Meta Commands

```ls
metric m:cnn p:integer l:CNN t:dataTypeName=number

metric m:pci_score p:integer l:PCI_Score t:dataTypeName=number

entity e:78va-8dhi l:"Streets Data -Historical Pavement Condition Index (PCI) Scores" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/78va-8dhi

property e:78va-8dhi t:meta.view v:id=78va-8dhi v:category="City Infrastructure" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="Streets Data -Historical Pavement Condition Index (PCI) Scores" v:attribution="San Francisco Department of Public Works"

property e:78va-8dhi t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:78va-8dhi t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:78va-8dhi t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| cnn      | street_name | from_street         | to_street    | pci_score | pci_change_date     | treatment_or_survey | street_accepted_for_maintenance | functional_class | 
| ======== | =========== | =================== | ============ | ========= | =================== | =================== | =============================== | ================ | 
| 30731000 | 01st St     | Bush St \ Market St | Intersection | 100       | 2014-04-16T10:22:28 | Treatment           | No                              |                  | 
| 110000   | 01ST ST     | CLEMENTINA ST       | FOLSOM ST    | 100       | 1977-05-01T00:00:00 | Treatment           | No                              |                  | 
| 110000   | 01ST ST     | CLEMENTINA ST       | FOLSOM ST    | 51        | 1992-01-01T00:00:00 | Survey              | No                              |                  | 
| 110000   | 01ST ST     | CLEMENTINA ST       | FOLSOM ST    | 51        | 1993-01-01T00:00:00 | Survey              | No                              |                  | 
| 110000   | 01ST ST     | CLEMENTINA ST       | FOLSOM ST    | 71        | 1994-01-01T00:00:00 | Survey              | No                              |                  | 
| 110000   | 01ST ST     | CLEMENTINA ST       | FOLSOM ST    | 67        | 1995-01-13T00:00:00 | Survey              | No                              |                  | 
| 110000   | 01ST ST     | CLEMENTINA ST       | FOLSOM ST    | 57        | 1996-08-03T00:00:00 | Survey              | No                              |                  | 
| 110000   | 01ST ST     | CLEMENTINA ST       | FOLSOM ST    | 41        | 1997-09-05T00:00:00 | Survey              | No                              |                  | 
| 110000   | 01ST ST     | CLEMENTINA ST       | FOLSOM ST    | 80        | 2002-11-19T00:00:00 | Survey              | No                              |                  | 
| 110000   | 01ST ST     | CLEMENTINA ST       | FOLSOM ST    | 74        | 2007-07-26T16:21:27 | Survey              | No                              |                  | 
```