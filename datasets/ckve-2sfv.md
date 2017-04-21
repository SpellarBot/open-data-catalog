# Grant Information Collection Act FY13

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grant-information-collection-act-fy13-9c0d5) |
| Metadata | [Link](https://data.illinois.gov/api/views/ckve-2sfv) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ckve-2sfv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ckve-2sfv/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ckve-2sfv |
| Name | Grant Information Collection Act FY13 |
| Tags | illinois arts council agency, illinois arts council, iac, iaca, fy13 |
| Created | 2014-04-07T21:25:07Z |
| Publication Date | 2014-04-07T21:37:42Z |

## Description

IACA Grants awarded in FY13

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type     | Render Type   |
| ======== | ============== | ========== | ====== | ============= | ============= |
| No       |                | fy         | FY     | number        | number        |
| Yes      | series tag     | flname     | FLName | text          | text          |
| Yes      | series tag     | zip        | ZIP    | text          | text          |
| Yes      | series tag     | title      | Title  | text          | text          |
| Yes      | numeric metric | grant      | Grant  | money         | money         |
| Yes      | time           | dvo        | Dvo    | calendar_date | calendar_date |
| No       |                | beg        | Beg    | calendar_date | calendar_date |
| No       |                | end        | End    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = dvo
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fy,beg,end
```

## Data Commands

```ls
series e:ckve-2sfv d:2012-10-31T00:00:00.000Z t:zip=60661-2391 t:title="for general operating support" t:flname="137 Films NFP" m:grant=2500

series e:ckve-2sfv d:2012-12-10T00:00:00.000Z t:zip=61820-4910 t:title="for general operating support" t:flname="40 North/88 West Inc" m:grant=4750

series e:ckve-2sfv d:2013-01-13T00:00:00.000Z t:zip=61820-4910 t:title="for Poetry Out Loud project support" t:flname="40 North/88 West Inc" m:grant=3300
```

## Meta Commands

```ls
metric m:grant p:integer l:Grant t:dataTypeName=money

entity e:ckve-2sfv l:"Grant Information Collection Act FY13" t:url=https://data.illinois.gov/api/views/ckve-2sfv

property e:ckve-2sfv t:meta.view v:id=ckve-2sfv v:averageRating=0 v:name="Grant Information Collection Act FY13"

property e:ckve-2sfv t:meta.view.owner v:id=5ugp-negb v:screenName="George Tarasuk" v:displayName="George Tarasuk"

property e:ckve-2sfv t:meta.view.tableauthor v:id=5ugp-negb v:screenName="George Tarasuk" v:displayName="George Tarasuk"
```

## Top Records

```ls
| fy | flname                         | zip        | title                               | grant | dvo                 | beg                 | end                 | 
| == | ============================== | ========== | =================================== | ===== | =================== | =================== | =================== | 
| 13 | 137 Films NFP                  | 60661-2391 | for general operating support       | 2500  | 2012-10-31T00:00:00 | 2012-09-15T00:00:00 | 2013-08-31T00:00:00 | 
| 13 | 40 North/88 West Inc           | 61820-4910 | for general operating support       | 4750  | 2012-12-10T00:00:00 | 2012-09-15T00:00:00 | 2013-09-30T00:00:00 | 
| 13 | 40 North/88 West Inc           | 61820-4910 | for Poetry Out Loud project support | 3300  | 2013-01-13T00:00:00 | 2012-10-19T00:00:00 | 2013-06-30T00:00:00 | 
| 13 | 826CHI Inc NFP                 | 60622      | for general operating support       | 5500  | 2012-11-09T00:00:00 | 2012-09-15T00:00:00 | 2013-09-30T00:00:00 | 
| 13 | A Red Orchid Theatre           | 60610      | for general operating support       | 6500  | 2012-10-16T00:00:00 | 2012-09-15T00:00:00 | 2013-08-31T00:00:00 | 
| 13 | About Face Theatre Collective  | 60640      | for general operating support       | 9000  | 2012-10-25T00:00:00 | 2012-09-15T00:00:00 | 2013-08-31T00:00:00 | 
| 13 | Acappellago NFP                | 60402-4237 | for general operating support       | 1050  | 2012-11-23T00:00:00 | 2012-09-15T00:00:00 | 2013-08-31T00:00:00 | 
| 13 | Access Living of Metro Chicago | 60654      | for Arts & Culture Project support  | 4750  | 2012-11-23T00:00:00 | 2012-09-15T00:00:00 | 2013-08-31T00:00:00 | 
| 13 | Acess Contemporary Music       | 60640-7212 | for general operating support       | 4000  | 2012-11-26T00:00:00 | 2012-09-15T00:00:00 | 2013-08-31T00:00:00 | 
| 13 | Acting Out Theatre Co          | 60914      | for general operating support       | 1500  | 2012-10-31T00:00:00 | 2012-09-15T00:00:00 | 2013-08-31T00:00:00 | 
```