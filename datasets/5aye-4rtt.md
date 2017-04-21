# Streets Data - Pavement Condition Index (PCI) Scores

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/paving-pci-scores-bdb93) |
| Metadata | [Link](https://data.sfgov.org/api/views/5aye-4rtt) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/5aye-4rtt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/5aye-4rtt/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 5aye-4rtt |
| Name | Streets Data - Pavement Condition Index (PCI) Scores |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | paving, pci, score, streets, condition, index |
| Created | 2012-09-25T00:53:03Z |
| Publication Date | 2016-12-06T03:37:36Z |

## Description

Pavement Condition Index (PCI) Scores by location.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| Yes      | numeric metric | cnn                             | CNN                             | number        | number        |
| Yes      | series tag     | street_name                     | Street_Name                     | text          | text          |
| Yes      | numeric metric | pci_score                       | PCI_Score                       | number        | number        |
| Yes      | series tag     | from_street                     | From_Street                     | text          | text          |
| Yes      | series tag     | to_street                       | To_Street                       | text          | text          |
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
series e:5aye-4rtt d:2002-11-19T00:00:00.000Z t:treatment_or_survey=Survey t:to_street="TRANSBAY HUMP" t:street_name="01ST ST" t:street_accepted_for_maintenance=Yes t:from_street="MISSION ST" m:pci_score=100 m:cnn=104001

series e:5aye-4rtt d:2002-11-19T00:00:00.000Z t:treatment_or_survey=Survey t:to_street="MINNA ST" t:street_name="01ST ST" t:street_accepted_for_maintenance=Yes t:from_street="TRANSBAY HUMP" m:pci_score=100 m:cnn=104002

series e:5aye-4rtt d:2002-11-19T00:00:00.000Z t:treatment_or_survey=Survey t:to_street="CLEMENTINA ST" t:street_name="01ST ST" t:street_accepted_for_maintenance=Yes t:from_street="TEHAMA ST" m:pci_score=80 m:cnn=108001
```

## Meta Commands

```ls
metric m:cnn p:integer l:CNN t:dataTypeName=number

metric m:pci_score p:integer l:PCI_Score t:dataTypeName=number

entity e:5aye-4rtt l:"Streets Data - Pavement Condition Index (PCI) Scores" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/5aye-4rtt

property e:5aye-4rtt t:meta.view v:id=5aye-4rtt v:category="City Infrastructure" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="Streets Data - Pavement Condition Index (PCI) Scores" v:attribution="San Francisco Department of Public Works"

property e:5aye-4rtt t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:5aye-4rtt t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:5aye-4rtt t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| cnn      | street_name   | pci_score | from_street                  | to_street          | pci_change_date     | treatment_or_survey | street_accepted_for_maintenance | functional_class | 
| ======== | ============= | ========= | ============================ | ================== | =================== | =================== | =============================== | ================ | 
| 104001   | 01ST ST       | 100       | MISSION ST                   | TRANSBAY HUMP      | 2002-11-19T00:00:00 | Survey              | Yes                             |                  | 
| 104002   | 01ST ST       | 100       | TRANSBAY HUMP                | MINNA ST           | 2002-11-19T00:00:00 | Survey              | Yes                             |                  | 
| 108001   | 01ST ST       | 80        | TEHAMA ST                    | CLEMENTINA ST      | 2002-11-19T00:00:00 | Survey              | Yes                             |                  | 
| 110000   | 01ST ST       | 74        | CLEMENTINA ST                | FOLSOM ST          | 2009-08-10T15:43:09 | Survey              | No                              |                  | 
| 114000   | 01ST ST       | 100       | HARRISON ST \ I-80 E ON RAMP | END                | 2008-10-29T13:59:27 | Survey              | No                              |                  | 
| 12883000 | University St | 27        | Burrows St                   | Bacon St           | 2015-09-30T01:03:39 | Survey              | Yes                             | Collector        | 
| 116001   | DELANCEY ST   | 67        | FEDERAL ST                   | BAYSIDE VILLAGE PL | 1997-09-09T00:00:00 | Survey              | Yes                             |                  | 
| 116002   | DELANCEY ST   | 67        | BAYSIDE VILLAGE PL           | BRANNAN ST         | 1997-09-09T00:00:00 | Survey              | Yes                             |                  | 
| 140000   | 02ND ST       | 54        | HARRISON ST                  | STILLMAN ST        | 2009-08-10T15:43:09 | Survey              | No                              |                  | 
| 159000   | 03RD AVE      | 100       | KEZAR DR \ LINCOLN WAY       | LINCOLN WAY        | 2008-10-29T13:59:27 | Survey              | No                              |                  | 
```