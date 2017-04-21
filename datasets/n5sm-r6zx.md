# Police - Selected Quality of Life Calls

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/police-quality-of-life-calls) |
| Metadata | [Link](https://data.somervillema.gov/api/views/n5sm-r6zx) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/n5sm-r6zx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/n5sm-r6zx/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | n5sm-r6zx |
| Name | Police - Selected Quality of Life Calls |
| Attribution | Police Department |
| Category | Public Safety |
| Tags | police, quality of life, groups, noise, vandalism |
| Created | 2016-02-02T17:54:59Z |
| Publication Date | 2016-02-02T18:08:01Z |

## Description

Selected calls since 2005, such as large groups, noise or unwanted persons. Exact addresses are not displayed for privacy reasons.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type     | Render Type   |
| ======== | ============== | =========== | =========== | ============= | ============= |
| Yes      | numeric metric | incnum      | incnum      | number        | number        |
| Yes      | series tag     | inctype     | inctype     | text          | text          |
| Yes      | series tag     | inctypecode | inctypecode | text          | number        |
| Yes      | time           | dtreceived  | dtreceived  | calendar_date | calendar_date |
| Yes      | series tag     | loctype     | loctype     | text          | text          |
| Yes      | series tag     | stnum       | stnum       | text          | text          |
| Yes      | series tag     | stname1     | stname1     | text          | text          |
| Yes      | series tag     | stname2     | stname2     | text          | text          |
| No       |                | ra          | ra          | number        | number        |
| No       |                | x           | X           | number        | number        |
| No       |                | y           | Y           | number        | number        |
```

## Time Field

```ls
Value = dtreceived
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = ra,x,y
```

## Data Commands

```ls
series e:n5sm-r6zx d:2008-09-23T18:37:05.000Z t:loctype=S t:stname1="WARREN AVE" t:stnum=-XX t:inctype=GROUPS t:inctypecode=242 m:incnum=8034131

series e:n5sm-r6zx d:2013-04-16T21:19:12.000Z t:loctype=S t:stname1="WARREN AVE" t:stnum=-XX t:inctype=UNWANTED t:inctypecode=703 m:incnum=13014955

series e:n5sm-r6zx d:2012-04-02T18:54:45.000Z t:loctype=S t:stname1="WARREN AVE" t:stnum=-XX t:inctype=UNWANTED t:inctypecode=703 m:incnum=12012313
```

## Meta Commands

```ls
metric m:incnum p:integer l:incnum t:dataTypeName=number

entity e:n5sm-r6zx l:"Police - Selected Quality of Life Calls" t:attribution="Police Department" t:url=https://data.somervillema.gov/api/views/n5sm-r6zx

property e:n5sm-r6zx t:meta.view v:id=n5sm-r6zx v:category="Public Safety" v:averageRating=0 v:name="Police - Selected Quality of Life Calls" v:attribution="Police Department"

property e:n5sm-r6zx t:meta.view.license v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:n5sm-r6zx t:meta.view.owner v:id=ta4g-utcf v:profileImageUrlMedium=/api/users/ta4g-utcf/profile_images/THUMB v:profileImageUrlLarge=/api/users/ta4g-utcf/profile_images/LARGE v:screenName="Steve Craig" v:profileImageUrlSmall=/api/users/ta4g-utcf/profile_images/TINY v:displayName="Steve Craig"

property e:n5sm-r6zx t:meta.view.tableauthor v:id=ta4g-utcf v:profileImageUrlMedium=/api/users/ta4g-utcf/profile_images/THUMB v:profileImageUrlLarge=/api/users/ta4g-utcf/profile_images/LARGE v:screenName="Steve Craig" v:profileImageUrlSmall=/api/users/ta4g-utcf/profile_images/TINY v:roleName=administrator v:displayName="Steve Craig"
```

## Top Records

```ls
| incnum   | inctype  | inctypecode | dtreceived          | loctype | stnum | stname1                        | stname2 | ra  | x           | y          | 
| ======== | ======== | =========== | =================== | ======= | ===== | ============================== | ======= | === | =========== | ========== | 
| 8034131  | GROUPS   | 242         | 2008-09-23T18:37:05 | S       | -XX   | WARREN AVE                     |         | 24  | -71.096835  | 42.380345  | 
| 13014955 | UNWANTED | 703         | 2013-04-16T21:19:12 | S       | -XX   | WARREN AVE                     |         | 22  | -71.096835  | 42.380345  | 
| 12012313 | UNWANTED | 703         | 2012-04-02T18:54:45 | S       | -XX   | WARREN AVE                     |         | 24  | -71.096835  | 42.380345  | 
| 10009299 | UNWANTED | 703         | 2010-03-24T16:21:31 | S       | -XX   | WARREN AVE                     |         | 22  | -71.096835  | 42.380345  | 
| 10023136 | NOISE    | 243         | 2010-07-10T00:21:20 | S       | XX    | 31 WHITMAN ST                  |         | 120 | -71.1233902 | 42.4025284 | 
| 10008902 | NOISE    | 243         | 2010-03-21T00:20:56 | S       | XX    | 6 WATSON ST                    |         | 128 | -71.1290674 | 42.4047934 | 
| 7038500  | DRUNK    | 23          | 2007-10-17T21:54:58 | S       | XX    | A ALFRED LOMBARDI ST & BROADWA |         | 11  | -71.0783489 | 42.3866409 | 
| 10004176 | GRAFITI  | 141         | 2010-02-09T11:47:17 | S       | XX    | A ALFRED LOMBARDI ST           |         | 11  | -71.0783489 | 42.3866409 | 
| 5032260  | NOISE    | 243         | 2005-10-02T00:37:00 | S       | XX    | ABERDEEN RD                    |         | 97  | -71.1135465 | 42.3920485 | 
| 14029983 | NOISE    | 243         | 2014-09-04T21:18:51 | S       | XX    | ACADIA PK                      |         | 99  | -71.1169224 | 42.3882612 | 
```