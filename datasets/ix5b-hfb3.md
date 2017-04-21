# Chief Judge--Directory Of Judges

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chief-judge-directory-of-judges-b9656) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/ix5b-hfb3) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ix5b-hfb3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ix5b-hfb3/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | ix5b-hfb3 |
| Name | Chief Judge--Directory Of Judges |
| Attribution | Timothy Evans, Chief Judge of the Cook County Court System |
| Category | Courts |
| Created | 2011-10-11T10:23:55Z |
| Publication Date | 2014-10-27T16:44:52Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | last_name   | Last Name  | text      | text        |
| Yes      | series tag     | first_name  | First Name | text      | text        |
| Yes      | series tag     | position    | Position   | text      | text        |
| Yes      | series tag     | state       | State      | text      | text        |
| Yes      | series tag     | room_       | Room #     | text      | text        |
| Yes      | numeric metric | area        | Area       | number    | number      |
| Yes      | series tag     | work_phone  | Work Phone | text      | text        |
| Yes      | series tag     | division    | Division   | text      | text        |
| Yes      | series tag     | section     | Section    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ix5b-hfb3 d:2011-10-11T03:23:56.000Z t:position=Judge t:first_name=Martin t:room_=204 t:division=Municipal t:work_phone=818-2287 t:state=IL t:last_name=Agran t:section="District 3" m:area=847

series e:ix5b-hfb3 d:2011-10-11T03:23:56.000Z t:position=Judge t:first_name=Carmen t:room_=295 t:division=Municipal t:work_phone=865-6060 t:state=IL t:last_name=Aguilar t:section="District 4" m:area=708

series e:ix5b-hfb3 d:2011-10-11T03:23:56.000Z t:position=Judge t:first_name=Thomas t:room_=1812 t:division=Probate t:work_phone=603-5964 t:state=IL t:last_name=Allen m:area=312
```

## Meta Commands

```ls
metric m:area p:integer l:Area t:dataTypeName=number

entity e:ix5b-hfb3 l:"Chief Judge--Directory Of Judges" t:attribution="Timothy Evans, Chief Judge of the Cook County Court System" t:url=https://datacatalog.cookcountyil.gov/api/views/ix5b-hfb3

property e:ix5b-hfb3 t:meta.view v:id=ix5b-hfb3 v:category=Courts v:averageRating=0 v:name="Chief Judge--Directory Of Judges" v:attribution="Timothy Evans, Chief Judge of the Cook County Court System"

property e:ix5b-hfb3 t:meta.view.license v:name="Public Domain"

property e:ix5b-hfb3 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:ix5b-hfb3 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| :updated_at | last_name | first_name | position | state | room_ | area | work_phone | division          | section    | 
| =========== | ========= | ========== | ======== | ===== | ===== | ==== | ========== | ================= | ========== | 
| 1318303436  | Agran     | Martin     | Judge    | IL    | 204   | 847  | 818-2287   | Municipal         | District 3 | 
| 1318303436  | Aguilar   | Carmen     | Judge    | IL    | 295   | 708  | 865-6060   | Municipal         | District 4 | 
| 1318303436  | Allen     | Thomas     | Judge    | IL    | 1812  | 312  | 603-5964   | Probate           |            | 
| 1318303436  | Alonso    | Jorge      | Judge    | IL    | 207   | 773  | 674-7425   | Criminal          |            | 
| 1318303436  | Araujo    | Mauricio   | Judge    | IL    | 4400  | 312  | 325-9000   | Domestic Violence |            | 
| 1318303436  | Arce      | Edward     | Judge    | IL    | 102   | 708  | 232-4225   | Domestic Relation |            | 
| 1318303436  | Arnold    | Nancy      | Judge    | IL    | 2502  | 312  | 603-6008   | Chancery          |            | 
| 1318303436  | Atkins    | David      | Judge    | IL    | 2801  | 312  | 603-3893   | Chancery          |            | 
| 1318303436  | Axelrood  | Larry      | Judge    | IL    | 219   | 847  | 470-7200   | Municipal         | District 2 | 
| 1318303436  | Baird     | Callie     | Judge    | IL    | 219   | 847  | 470-7200   | Municipal         | District 2 | 
```