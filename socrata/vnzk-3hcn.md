# 2011 August primary election results schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-august-primary-election-results-schedule-ad91e) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/vnzk-3hcn) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/vnzk-3hcn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/vnzk-3hcn/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | vnzk-3hcn |
| Name | 2011 August primary election results schedule |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | election results, voting, elections, voter |
| Created | 2011-07-21T17:42:33Z |
| Publication Date | 2011-07-21T17:42:33Z |

## Description

All times are approximate and subject to change

## Columns

```ls
| Included | Schema Type | Field Name | Name    | Data Type     | Render Type   |
| ======== | =========== | ========== | ======= | ============= | ============= |
| Yes      | time        | date       | Date    | calendar_date | calendar_date |
| Yes      | series tag  | time       | Time    | text          | text          |
| Yes      | series tag  | posting    | Posting | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:vnzk-3hcn d:2011-08-16T00:00:00.000Z t:time="8:15 p.m." t:posting="Mail ballots counted on election day results posted to the Web." m:row_number.vnzk-3hcn=1

series e:vnzk-3hcn d:2011-08-17T00:00:00.000Z t:time="4:30 p.m." t:posting="Results posted including votes cast at the accessible voting centers." m:row_number.vnzk-3hcn=2

series e:vnzk-3hcn d:2011-08-18T00:00:00.000Z t:time="4:30 p.m." t:posting="Results posted" m:row_number.vnzk-3hcn=3
```

## Meta Commands

```ls
metric m:row_number.vnzk-3hcn p:long l:"Row Number"

entity e:vnzk-3hcn l:"2011 August primary election results schedule" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/vnzk-3hcn

property e:vnzk-3hcn t:meta.view v:id=vnzk-3hcn v:category="Election operations" v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name="2011 August primary election results schedule" v:attribution="King County Elections"

property e:vnzk-3hcn t:meta.view.license v:name="Public Domain"

property e:vnzk-3hcn t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"
```

## Top Records

```ls
| date                | time      | posting                                                                                                  | 
| =================== | ========= | ======================================================================================================== | 
| 2011-08-16T00:00:00 | 8:15 p.m. | Mail ballots counted on election day results posted to the Web.                                          | 
| 2011-08-17T00:00:00 | 4:30 p.m. | Results posted including votes cast at the accessible voting centers.                                    | 
| 2011-08-18T00:00:00 | 4:30 p.m. | Results posted                                                                                           | 
| 2011-08-19T00:00:00 | 4:30 p.m. | Results posted                                                                                           | 
| 2011-08-19T00:00:00 |           | Unofficial abstract of results as of August 16th, broken down by legislative district posted to the Web. | 
| 2011-08-22T00:00:00 | 4:30 p.m. | Results posted                                                                                           | 
| 2011-08-23T00:00:00 | 4:30 p.m. | Results posted                                                                                           | 
| 2011-08-24T00:00:00 | 4:30 p.m. | Results posted                                                                                           | 
| 2011-08-25T00:00:00 | 4:30 p.m. | Results posted                                                                                           | 
| 2011-08-26T00:00:00 | 4:30 p.m. | Results posted                                                                                           | 
```