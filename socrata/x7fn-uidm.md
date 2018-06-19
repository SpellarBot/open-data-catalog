# DCP - Planning Case Filing and Completion - Monthly GOVSTAT

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dcp-planning-case-filing-and-completion-monthly-govstat) |
| Metadata | [Link](https://data.lacity.org/api/views/x7fn-uidm) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/x7fn-uidm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/x7fn-uidm/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | x7fn-uidm |
| Name | DCP - Planning Case Filing and Completion - Monthly GOVSTAT |
| Category | A Prosperous City |
| Tags | planning, dcp, case completion |
| Created | 2014-05-30T20:32:22Z |
| Publication Date | 2015-12-16T01:11:27Z |

## Description

DCP total cases filed and completed each month (includes both entitlement and environmental cases)

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| No       |                | date_name       | Date Name       | text          | text          |
| Yes      | time           | date            | Date            | calendar_date | calendar_date |
| Yes      | numeric metric | cases_completed | Cases Completed | number        | number        |
| Yes      | numeric metric | cases_filed     | Cases Filed     | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_name
```

## Data Commands

```ls
series e:x7fn-uidm d:2012-01-31T00:00:00.000Z m:cases_completed=125 m:cases_filed=153

series e:x7fn-uidm d:2012-02-29T00:00:00.000Z m:cases_completed=169 m:cases_filed=202

series e:x7fn-uidm d:2012-03-31T00:00:00.000Z m:cases_completed=175 m:cases_filed=152
```

## Meta Commands

```ls
metric m:cases_completed p:integer l:"Cases Completed" t:dataTypeName=number

metric m:cases_filed p:integer l:"Cases Filed" t:dataTypeName=number

entity e:x7fn-uidm l:"DCP - Planning Case Filing and Completion - Monthly GOVSTAT" t:url=https://data.lacity.org/api/views/x7fn-uidm

property e:x7fn-uidm t:meta.view v:id=x7fn-uidm v:category="A Prosperous City" v:averageRating=0 v:name="DCP - Planning Case Filing and Completion - Monthly GOVSTAT"

property e:x7fn-uidm t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:x7fn-uidm t:meta.view.owner v:id=tgn6-4379 v:profileImageUrlMedium=/api/users/tgn6-4379/profile_images/THUMB v:profileImageUrlLarge=/api/users/tgn6-4379/profile_images/LARGE v:screenName="Mayor's Office OpenData" v:profileImageUrlSmall=/api/users/tgn6-4379/profile_images/TINY v:displayName="Mayor's Office OpenData"

property e:x7fn-uidm t:meta.view.tableauthor v:id=tgn6-4379 v:profileImageUrlMedium=/api/users/tgn6-4379/profile_images/THUMB v:profileImageUrlLarge=/api/users/tgn6-4379/profile_images/LARGE v:screenName="Mayor's Office OpenData" v:profileImageUrlSmall=/api/users/tgn6-4379/profile_images/TINY v:roleName=administrator v:displayName="Mayor's Office OpenData"
```

## Top Records

```ls
| date_name | date                | cases_completed | cases_filed | 
| ========= | =================== | =============== | =========== | 
| Jan-12    | 2012-01-31T00:00:00 | 125             | 153         | 
| Feb-12    | 2012-02-29T00:00:00 | 169             | 202         | 
| Mar-12    | 2012-03-31T00:00:00 | 175             | 152         | 
| Apr-12    | 2012-04-30T00:00:00 | 149             | 187         | 
| May-12    | 2012-05-31T00:00:00 | 162             | 242         | 
| Jun-12    | 2012-06-30T00:00:00 | 141             | 157         | 
| Jul-12    | 2012-07-31T00:00:00 | 162             | 146         | 
| Aug-12    | 2012-08-31T00:00:00 | 142             | 196         | 
| Sep-12    | 2012-09-30T00:00:00 | 168             | 182         | 
| Oct-12    | 2012-10-31T00:00:00 | 154             | 201         | 
```