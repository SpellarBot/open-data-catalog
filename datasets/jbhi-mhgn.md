# Directory Of Judges 9.19.11

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-judges-9-19-11-07684) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/jbhi-mhgn) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/jbhi-mhgn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/jbhi-mhgn/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | jbhi-mhgn |
| Name | Directory Of Judges 9.19.11 |
| Created | 2011-10-11T10:19:30Z |
| Publication Date | 2014-10-27T16:42:38Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | last        | LAST       | text      | text        |
| Yes      | series tag     | first       | FIRST      | text      | text        |
| Yes      | series tag     | type        | TYPE       | text      | text        |
| No       |                | st          | ST         | text      | text        |
| Yes      | numeric metric | area        | AREA       | number    | number      |
| Yes      | series tag     | phone_      | PHONE#     | text      | text        |
| Yes      | series tag     | division    | DIVISION   | text      | text        |
| Yes      | series tag     | section     | SECTION    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = st
```

## Data Commands

```ls
series e:jbhi-mhgn d:2011-10-11T03:19:31.000Z t:division=Municipal t:last=Agran t:phone_=818-2287 t:type=Judge t:first=Martin t:section="District 3" m:area=847

series e:jbhi-mhgn d:2011-10-11T03:19:31.000Z t:division=Municipal t:last=Aguilar t:phone_=865-6060 t:type=Judge t:first=Carmen t:section="District 4" m:area=708

series e:jbhi-mhgn d:2011-10-11T03:19:31.000Z t:division=Probate t:last=Allen t:phone_=603-5964 t:type=Judge t:first=Thomas m:area=312
```

## Meta Commands

```ls
metric m:area p:integer l:AREA t:dataTypeName=number

entity e:jbhi-mhgn l:"Directory Of Judges 9.19.11" t:url=https://datacatalog.cookcountyil.gov/api/views/jbhi-mhgn

property e:jbhi-mhgn t:meta.view v:id=jbhi-mhgn v:averageRating=0 v:name="Directory Of Judges 9.19.11"

property e:jbhi-mhgn t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:jbhi-mhgn t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| :updated_at | last     | first    | type  | st | area | phone_   | division          | section    | 
| =========== | ======== | ======== | ===== | == | ==== | ======== | ================= | ========== | 
| 1318303171  | Agran    | Martin   | Judge | IL | 847  | 818-2287 | Municipal         | District 3 | 
| 1318303171  | Aguilar  | Carmen   | Judge | IL | 708  | 865-6060 | Municipal         | District 4 | 
| 1318303171  | Allen    | Thomas   | Judge | IL | 312  | 603-5964 | Probate           |            | 
| 1318303171  | Alonso   | Jorge    | Judge | IL | 773  | 674-7425 | Criminal          |            | 
| 1318303171  | Araujo   | Mauricio | Judge | IL | 312  | 325-9000 | Domestic Violence |            | 
| 1318303171  | Arce     | Edward   | Judge | IL | 708  | 232-4225 | Domestic Relation |            | 
| 1318303171  | Arnold   | Nancy    | Judge | IL | 312  | 603-6008 | Chancery          |            | 
| 1318303171  | Atkins   | David    | Judge | IL | 312  | 603-3893 | Chancery          |            | 
| 1318303171  | Axelrood | Larry    | Judge | IL | 847  | 470-7200 | Municipal         | District 2 | 
| 1318303171  | Baird    | Callie   | Judge | IL | 847  | 470-7200 | Municipal         | District 2 | 
```