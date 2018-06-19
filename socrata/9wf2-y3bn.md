# Ethics Pledge

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ethics-pledge-8ad6d) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/9wf2-y3bn) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/9wf2-y3bn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/9wf2-y3bn/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 9wf2-y3bn |
| Name | Ethics Pledge |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | personnel |
| Created | 2011-09-22T22:55:39Z |
| Publication Date | 2017-02-08T19:15:43Z |

## Description

On May 16, 2011, Mayor Emanuel enacted Executive Order 2011-1.  It requires Shakman-exempt employees of Executive Departments, department heads, non-clerical employees of the Mayor's Office, and persons appointed by the Mayor to City boards, commissions, authorities or agencies on or after May 16, 2011, to sign an Ethics Pledge http://bit.ly/mSkLU1. On July 28, 2011, this requirement was enacted into law by the City Council, as Section 2-156-015 of the Governmental Ethics Ordinance (effective September 8, 2011) http://bit.ly/qYti7P. The law requires new hires or appointees to sign the pledge within 14 days of starting their employment or appointments.  The pledge obligates signers to abide by a ban on lobbying activity for two years after their City service ends.  The Board of Ethics maintains these signed pledges.  As a convenience, we are pleased to attach a list of persons who have signed this pledge.  This list is sortable by name and department.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | department  | DEPARTMENT | text      | text        |
| Yes      | series tag  | name        | NAME       | text      | text        |
| Yes      | series tag  | job_title   | JOB TITLE  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9wf2-y3bn d:2017-02-08T19:15:26.000Z t:department="BOARD/COMMISSION MEMBER" t:name="ABDUL-ALBRIM, ZAID" m:row_number.9wf2-y3bn=1

series e:9wf2-y3bn d:2017-02-08T19:15:26.000Z t:department="BOARD/COMMISSION MEMBER" t:name="ABERCROMBIE, KARIN MOEN" m:row_number.9wf2-y3bn=2

series e:9wf2-y3bn d:2017-02-08T19:15:26.000Z t:department="BOARD/COMMISSION MEMBER" t:name="ABUAGEL, SAMEH S" m:row_number.9wf2-y3bn=3
```

## Meta Commands

```ls
metric m:row_number.9wf2-y3bn p:long l:"Row Number"

entity e:9wf2-y3bn l:"Ethics Pledge" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/9wf2-y3bn

property e:9wf2-y3bn t:meta.view v:id=9wf2-y3bn v:category=Ethics v:attributionLink=http://www.cityofchicago.org/content/city/en/depts/ethics/dataset/ethics_pledge.html v:averageRating=0 v:name="Ethics Pledge" v:attribution="City of Chicago"

property e:9wf2-y3bn t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:9wf2-y3bn t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | department              | name                    | job_title           | 
| =========== | ======================= | ======================= | =================== | 
| 1486581326  | BOARD/COMMISSION MEMBER | ABDUL-ALBRIM, ZAID      |                     | 
| 1486581326  | BOARD/COMMISSION MEMBER | ABERCROMBIE, KARIN MOEN |                     | 
| 1486581326  | BOARD/COMMISSION MEMBER | ABUAGEL, SAMEH S        |                     | 
| 1486581326  | BOARD/COMMISSION MEMBER | ABUKHDEIR, HANADI       |                     | 
| 1486581326  | BOARD/COMMISSION MEMBER | ACKERMAN, LISA Z        |                     | 
| 1486581326  | BOARD/COMMISSION MEMBER | ADAMS, CAROL L          |                     | 
| 1486581326  | BUSINESS AFFAIRS        | ADELIZZI, JOY A         | DEPUTY COMMISSIONER | 
| 1486581326  | BOARD/COMMISSION MEMBER | AGNIHOTRI, SANHITA      |                     | 
| 1486581326  | BOARD/COMMISSION MEMBER | AHLGRIM, JOHN           |                     | 
| 1486581326  | FINANCE                 | AHMAD, AMER             | CITY COMPTROLLER    | 
```