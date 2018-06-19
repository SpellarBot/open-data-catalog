# KSC Project Feedback

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ksc-project-feedback-1be57) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/htje-zabz) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/htje-zabz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/htje-zabz/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | htje-zabz |
| Name | KSC Project Feedback |
| Category | Operations |
| Created | 2013-10-04T16:48:03Z |
| Publication Date | 2014-02-01T01:02:55Z |

## Description

KSC Reorganization Project feedback from tenants

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type    |
| ======== | =========== | ===================== | ===================== | ========= | ============== |
| No       | time        | :updated_at           | updated_at            | meta_data | meta_data      |
| No       |             | date_mm_dd_yy         | Date (MM/DD/YY)       | text      | text           |
| Yes      | series tag  | name                  | Name                  | text      | text           |
| Yes      | series tag  | email                 | Email                 | text      | text           |
| Yes      | series tag  | agency                | Agency                | text      | drop_down_list |
| Yes      | series tag  | current_floor         | Current Floor         | text      | text           |
| Yes      | series tag  | comment_or_suggestion | Comment or Suggestion | text      | text           |
| Yes      | series tag  | acknowledged          | Acknowledged          | checkbox  | checkbox       |
| Yes      | series tag  | assigned_to           | Assigned To           | text      | text           |
| Yes      | series tag  | notes                 | Notes                 | text      | text           |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date_mm_dd_yy
```

## Data Commands

```ls
series e:htje-zabz d:2013-10-31T11:32:23.000Z t:current_floor=5 t:email=sally.jones@kingcounty.gov t:name="Sally Jones" t:agency=a4bq-8umk t:comment_or_suggestion="Suggestion text goes here" m:row_number.htje-zabz=1

series e:htje-zabz d:2013-10-31T11:32:35.000Z t:current_floor=2 t:email=testy.mctesterson@kingcounty.gov t:name="Testy McTesterson" t:agency=9jev-9p3u t:comment_or_suggestion="hksdfhl  ahfl khasdfh  s;akjdhf kha k;has dfh ;kask;jdh asjk;hd ;aksjdhf ;kjasdnf as d;kjhnd ;kasdfhasd hsd; khasd;kjf asdf" m:row_number.htje-zabz=2

series e:htje-zabz d:2013-10-31T11:32:35.000Z t:current_floor=12 t:email=another.test@kingcounty.gov t:name="Another Test" t:agency=b7ew-m4sf t:comment_or_suggestion="Testing ksc.project@kingcounty.gov" m:row_number.htje-zabz=3
```

## Meta Commands

```ls
metric m:row_number.htje-zabz p:long l:"Row Number"

entity e:htje-zabz l:"KSC Project Feedback" t:url=https://data.kingcounty.gov/api/views/htje-zabz

property e:htje-zabz t:meta.view v:id=htje-zabz v:category=Operations v:averageRating=0 v:name="KSC Project Feedback"

property e:htje-zabz t:meta.view.license v:name="Public Domain"

property e:htje-zabz t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:htje-zabz t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| :updated_at | date_mm_dd_yy | name              | email                            | agency    | current_floor | comment_or_suggestion                                                                                                                                                                                                                                                                                                                                                                                                     | acknowledged | assigned_to          | notes | 
| =========== | ============= | ================= | ================================ | ========= | ============= | ========================================================================================================================================================================================================================================================================================================================================================================================================================= | ============ | ==================== | ===== | 
| 1383219143  | 10/01/13      | Sally Jones       | sally.jones@kingcounty.gov       | a4bq-8umk | 5             | Suggestion text goes here                                                                                                                                                                                                                                                                                                                                                                                                 |              |                      |       | 
| 1383219155  | 10/01/13      | Testy McTesterson | testy.mctesterson@kingcounty.gov | 9jev-9p3u | 2             | hksdfhl ahfl khasdfh s;akjdhf kha k;has dfh ;kask;jdh asjk;hd ;aksjdhf ;kjasdnf as d;kjhnd ;kasdfhasd hsd; khasd;kjf asdf                                                                                                                                                                                                                                                                                                 |              |                      |       | 
| 1383219155  | 10/01/13      | Another Test      | another.test@kingcounty.gov      | b7ew-m4sf | 12            | Testing ksc.project@kingcounty.gov                                                                                                                                                                                                                                                                                                                                                                                        |              |                      |       | 
| 1383219158  | 10/01/13      | Testy McTesterson | testy.mctesterson@kingcounty.gov | 9jev-9p3u | 13            | This is a test.                                                                                                                                                                                                                                                                                                                                                                                                           |              |                      |       | 
| 1383219161  | 10/01/13      | New Test          | new.test@kingcounty.gov          | 9jev-9p3u | 42            | Let's see how much text we can put in here. Just keep typing. sdklhfkhan skladjhf kl askj hsdafklj hsadkljfh asklhsdf kjsadf kjsdhf sadlkjdhf ass adlkjfh sadlkjfh sadkljfh asdkljfh sadkljfh sadkljfh saldkjhf sadjkhf klsjadhf lkjsahdf laskdjhfs adlkjhf sakljdhfs aldkjfh sdlkfh dfkl hklj fhsdalkjfhsadlkjfh aslkdjfh sdkljf kldjfh sdjklafh skladjfh sakldj asfjklhfklj hsadlkfhsadlkjfh skladjhf ssdfa END END END |              |                      |       | 
| 1383219164  | 10/01/13      | Another Test      | test@kingcounty.gov              | 2yw9-cs54 | 12            | TEST TEST TEST                                                                                                                                                                                                                                                                                                                                                                                                            |              |                      |       | 
| 1383219168  | 10/01/13      | Dave Preugschat   | This is a test                   | a4bq-8umk | None          | Get to work                                                                                                                                                                                                                                                                                                                                                                                                               |              |                      |       | 
| 1383219173  | 10/01/13      | Leo Griffin       | leo.griffin@kingcounty.gov       | b7ew-m4sf | 3             | Test: Thanks for setting up this website! Is there a plan for the surplus?                                                                                                                                                                                                                                                                                                                                                |              |                      |       | 
| 1383221306  | 10/31/2013    | Earl Krygier      | earl.krygier@kingcounty.gov      | 2yw9-cs54 | 7             | Testing testing 123. Testing testing 123. Testing testing 123. Testing testing 123. Testing testing 123. Testing testing 123. Testing testing 123. Testing testing 123. Testing testing 123. Testing testing 123. Testing testing 123. Testing testing 123. Testing testing 123.                                                                                                                                          |              |                      |       | 
| 1458208821  |               | Melisalincwag     | patriciajmesa@dvaar.com          | a4bq-8umk | Inner rage    |                                                                                                                                                                                                                                                                                                                                                                                                                           |              | Curently in A school |       | 
```