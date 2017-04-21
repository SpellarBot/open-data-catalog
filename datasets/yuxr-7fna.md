# General Election Results Posting Schedule : Nov 6, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/general-election-results-posting-schedule-nov-6-2012-5311f) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/yuxr-7fna) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/yuxr-7fna/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/yuxr-7fna/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | yuxr-7fna |
| Name | General Election Results Posting Schedule : Nov 6, 2012 |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | king county, elections, general election, 2012 |
| Created | 2012-10-09T19:40:44Z |
| Publication Date | 2012-11-09T22:38:18Z |

## Description

Schedule for posting election results

## Columns

```ls
| Included | Schema Type | Field Name | Name  | Data Type | Render Type |
| ======== | =========== | ========== | ===== | ========= | =========== |
| No       |             | date       | Date  | text      | text        |
| Yes      | series tag  | time       | TIme  | text      | text        |
| Yes      | series tag  | event      | Event | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:yuxr-7fna d:2012-01-01T00:00:00.000Z t:time="8:15 p.m." t:event="Election day results posted to the web." m:row_number.yuxr-7fna=1

series e:yuxr-7fna d:2012-01-01T00:00:00.000Z t:time="6:30 p.m." t:event="Results posted, including votes cast at the accessible voting centers." m:row_number.yuxr-7fna=2

series e:yuxr-7fna d:2012-01-01T00:00:00.000Z t:time="4:30 p.m. and 8:30 pm" t:event="Results posted." m:row_number.yuxr-7fna=3
```

## Meta Commands

```ls
metric m:row_number.yuxr-7fna p:long l:"Row Number"

entity e:yuxr-7fna l:"General Election Results Posting Schedule : Nov 6, 2012" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/yuxr-7fna

property e:yuxr-7fna t:meta.view v:id=yuxr-7fna v:category="Election operations" v:attributionLink=http://kingcounty.gov/elections v:averageRating=0 v:name="General Election Results Posting Schedule : Nov 6, 2012" v:attribution="King County Elections"

property e:yuxr-7fna t:meta.view.license v:name="Public Domain"

property e:yuxr-7fna t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:yuxr-7fna t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| date               | time                  | event                                                                  | 
| ================== | ===================== | ====================================================================== | 
| Tuesday, Nov. 6    | 8:15 p.m.             | Election day results posted to the web.                                | 
| Wednesday, Nov. 7  | 6:30 p.m.             | Results posted, including votes cast at the accessible voting centers. | 
| Thursday, Nov. 8   | 4:30 p.m. and 8:30 pm | Results posted.                                                        | 
| Saturday, Nov. 10  | 4:30 p.m.             | Results posted.                                                        | 
| Monday, Nov. 12    | 4:30 p.m.             | Veteran's Day Holiday (Observed)                                       | 
| Tuesday, Nov. 13   | 4:30 p.m.             | Results posted.                                                        | 
| Wednesday, Nov. 14 | 4:30 p.m.             | Results posted.                                                        | 
| Thursday, Nov. 15  | 4:30 p.m.             | Results posted.                                                        | 
| Friday, Nov. 16    | 4:30 p.m.             | Results posted.                                                        | 
| Monday, Nov. 19    | 4:30 p.m.             | Results posted.                                                        | 
```