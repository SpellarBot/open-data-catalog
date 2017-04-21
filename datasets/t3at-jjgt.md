# Administrative Hearings - Top 5 Animal Control Violations - Sept 2011 To March 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/administrative-hearings-top-5-animal-control-violations-sept-2011-to-march-2012-aa375) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/t3at-jjgt) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/t3at-jjgt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/t3at-jjgt/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | t3at-jjgt |
| Name | Administrative Hearings - Top 5 Animal Control Violations - Sept 2011 To March 2012 |
| Attribution | Cook County Department of Administrative Hearings |
| Category | Courts |
| Created | 2012-05-21T17:28:01Z |
| Publication Date | 2014-10-09T22:19:36Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | violation_code       | Violation Code       | text      | text        |
| Yes      | series tag     | violation_text       | Violation Text       | text      | text        |
| Yes      | numeric metric | number_of_violations | Number of Violations | number    | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:t3at-jjgt d:2011-01-01T00:00:00.000Z t:violation_text="Not Current With Rabies Vaccination Ordinance Section" t:violation_code=10-41 m:number_of_violations=58

series e:t3at-jjgt d:2011-01-01T00:00:00.000Z t:violation_text="Failure to Take Animal To Vet For Ten Day Rabies Observation" t:violation_code=10-42B2 m:number_of_violations=52

series e:t3at-jjgt d:2011-01-01T00:00:00.000Z t:violation_text="Failure to Take Animal To Vet For Ten Day Rabies Observation" t:violation_code=10-42B1 m:number_of_violations=28
```

## Meta Commands

```ls
metric m:number_of_violations p:integer l:"Number of Violations" t:dataTypeName=number

entity e:t3at-jjgt l:"Administrative Hearings - Top 5 Animal Control Violations - Sept 2011 To March 2012" t:attribution="Cook County Department of Administrative Hearings" t:url=https://datacatalog.cookcountyil.gov/api/views/t3at-jjgt

property e:t3at-jjgt t:meta.view v:id=t3at-jjgt v:category=Courts v:attributionLink=http://www.cookcountyildoah.org/ v:averageRating=0 v:name="Administrative Hearings - Top 5 Animal Control Violations - Sept 2011 To March 2012" v:attribution="Cook County Department of Administrative Hearings"

property e:t3at-jjgt t:meta.view.license v:name="Public Domain"

property e:t3at-jjgt t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:t3at-jjgt t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| violation_code | violation_text                                                    | number_of_violations | 
| ============== | ================================================================= | ==================== | 
| 10-41          | Not Current With Rabies Vaccination Ordinance Section             | 58                   | 
| 10-42B2        | Failure to Take Animal To Vet For Ten Day Rabies Observation      | 52                   | 
| 10-42B1        | Failure to Take Animal To Vet For Ten Day Rabies Observation      | 28                   | 
| 10-42B         | Failure to Take Animal Back To Vet For Ten Day Rabies Observation | 13                   | 
| 10-42F         | Biting Animal Capable Of Transmitting Rabies                      | 3                    | 
```