# Ex-Parte via the Clerk

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ex-parte-via-the-clerk) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/sem2-idbn) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/sem2-idbn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/sem2-idbn/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | sem2-idbn |
| Name | Ex-Parte via the Clerk |
| Attribution | King County Superior Court Clerk |
| Category | Legal |
| Tags | superior court clerk, ex parte, unilateral contacts |
| Created | 2015-05-23T00:46:47Z |
| Publication Date | 2015-05-23T00:51:07Z |

## Description

An ex parte decision is one decided by a judge without requiring all of the parties to the controversy to be present. Those matters required to be noted for hearing on a specific Ex Parte calendar are to be presented by the parties directly, in person, regardless of the stated presentation method on this Master List

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | case_type           | Case Type           | text      | text        |
| Yes      | series tag  | case_description    | Case Description    | text      | text        |
| Yes      | series tag  | document_title      | Document Title      | text      | text        |
| Yes      | series tag  | presentation_method | Presentation Method | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:sem2-idbn d:2015-05-22T17:46:51.000Z t:document_title="Agreed Order" t:case_description="Paternity ? Parental Determination" t:presentation_method=Clerk t:case_type=Adoption-Paternity m:row_number.sem2-idbn=1

series e:sem2-idbn d:2015-05-22T17:46:51.000Z t:document_title="Agreed temporary orders for child custody" t:case_description="Paternity ? Parental Determination" t:presentation_method=Clerk t:case_type=Adoption-Paternity m:row_number.sem2-idbn=2

series e:sem2-idbn d:2015-05-22T17:46:51.000Z t:document_title="Amended Decree" t:case_description=Adoption t:presentation_method=Clerk t:case_type=Adoption-Paternity m:row_number.sem2-idbn=3
```

## Meta Commands

```ls
metric m:row_number.sem2-idbn p:long l:"Row Number"

entity e:sem2-idbn l:"Ex-Parte via the Clerk" t:attribution="King County Superior Court Clerk" t:url=https://data.kingcounty.gov/api/views/sem2-idbn

property e:sem2-idbn t:meta.view v:id=sem2-idbn v:category=Legal v:attributionLink=http://www.kingcounty.gov/courts/clerk v:averageRating=0 v:name="Ex-Parte via the Clerk" v:attribution="King County Superior Court Clerk"

property e:sem2-idbn t:meta.view.license v:name="Public Domain"

property e:sem2-idbn t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:sem2-idbn t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | case_type          | case_description                   | document_title                                     | presentation_method | 
| =========== | ================== | ================================== | ================================================== | =================== | 
| 1432316811  | Adoption-Paternity | Paternity ? Parental Determination | Agreed Order                                       | Clerk               | 
| 1432316811  | Adoption-Paternity | Paternity ? Parental Determination | Agreed temporary orders for child custody          | Clerk               | 
| 1432316811  | Adoption-Paternity | Adoption                           | Amended Decree                                     | Clerk               | 
| 1432316811  | Adoption-Paternity | Adoption                           | Change of Venue: Stipulated                        | Clerk               | 
| 1432316811  | Adoption-Paternity | Paternity ? Parental Determination | Change of Venue: Stipulated                        | Clerk               | 
| 1432316811  | Adoption-Paternity | Adoption                           | Decree Of Adoption                                 | Parties             | 
| 1432316811  | Adoption-Paternity | Adoption                           | Decree Of Adoption-Adult ONLY- Noting not required | Parties             | 
| 1432316811  | Adoption-Paternity | Paternity ? Parental Determination | Default Judgment                                   | Clerk               | 
| 1432316811  | Adoption-Paternity | Paternity ? Parental Determination | Final orders for support                           | Clerk               | 
| 1432316811  | Adoption-Paternity | Adoption                           | Findings Of Fact And Conclusions Of Law            | Parties             | 
```