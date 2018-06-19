# MASTER KCE: King County Accessible Voting Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/master-kce-king-county-accessible-voting-centers-6b786) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/nv8f-b8na) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/nv8f-b8na/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/nv8f-b8na/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | nv8f-b8na |
| Name | MASTER KCE: King County Accessible Voting Centers |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | elections, king county, voting |
| Created | 2012-06-22T06:18:25Z |
| Publication Date | 2013-11-01T01:04:35Z |

## Description

Master dataset for accessible voting centers (AVC) in King County. All AVC locations are not open for every election.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | avc_name           | AVC Name           | text      | text        |
| Yes      | series tag  | in_use             | In Use             | checkbox  | checkbox    |
| Yes      | series tag  | dates_open         | Dates open         | text      | text        |
| Yes      | series tag  | hours_of_operation | Hours of operation | text      | text        |
| Yes      | series tag  | election_day_hours | Election Day hours | text      | text        |
| Yes      | series tag  | room               | Room               | text      | text        |
| Yes      | series tag  | ch_name            | CH-name            | text      | text        |
| Yes      | series tag  | ch_dates           | CH-Dates           | text      | text        |
| Yes      | series tag  | ch_times           | CH-Hours           | text      | text        |
| Yes      | series tag  | ch_election_day    | CH-Election Day    | text      | text        |
| Yes      | series tag  | vi_name            | VI-Name            | text      | text        |
| Yes      | series tag  | vi_dates           | VI-Dates           | text      | text        |
| Yes      | series tag  | vi_hours           | VI-Hours           | text      | text        |
| Yes      | series tag  | vi_election_day    | VI-Election Day    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nv8f-b8na d:2013-10-31T18:04:01.000Z t:vi_hours="10 gi? s?ng ? 5 gi? chi?u" t:election_day_hours="10:00 am - 8:00 pm" t:ch_election_day=??10????8? t:hours_of_operation="10:00 am - 5:00 pm" t:ch_name=????Bellevue???? t:avc_name="Bellevue City Hall" t:vi_dates="Ng?y 4, 5 th?ng 11" t:in_use=true t:ch_times=??10????5? t:vi_name="T?a Th? Ch?nh Bellevue" t:dates_open="Nov 4, 5" t:vi_election_day="10 gi? s?ng ? 8 gi? t?i" t:ch_dates="11? 4?? 5?" m:row_number.nv8f-b8na=1

series e:nv8f-b8na d:2013-10-31T18:04:01.000Z t:vi_hours="8 gi? 30 s?ng ? 4 gi? 30 chi?u" t:election_day_hours="8:30 am - 8:00 pm" t:ch_election_day=??8?30????8? t:hours_of_operation="8:30 am - 4:30 pm" t:ch_name=?????? t:avc_name="Elections Headquarters" t:vi_dates="Ng?y 18 th?ng 10 ? ng?y 4 th?ng 11 (c?c ng?y trong tu?n)" t:in_use=true t:ch_times=??8?30????4?30? t:vi_name="Tr? S? Ch?nh c?a B? B?u C?" t:dates_open="Oct 18 - Nov 4 (weekdays)" t:vi_election_day="8 gi? 30 s?ng ? 8 gi? t?i" t:ch_dates="10?18??11?4? (??)" m:row_number.nv8f-b8na=2

series e:nv8f-b8na d:2013-10-31T18:04:01.000Z t:election_day_hours="7:00 am - 8:00 pm" t:avc_name="Green River Community College" t:hours_of_operation="10:00 am - 5:00 pm" t:dates_open=2012 t:vi_name="Ng?y m? c?a" t:room="Lindbloom Student Center Glacier Room" m:row_number.nv8f-b8na=3
```

## Meta Commands

```ls
metric m:row_number.nv8f-b8na p:long l:"Row Number"

entity e:nv8f-b8na l:"MASTER KCE: King County Accessible Voting Centers" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/nv8f-b8na

property e:nv8f-b8na t:meta.view v:id=nv8f-b8na v:category="Election operations" v:attributionLink=http://kingcounty.gov/elections v:averageRating=0 v:name="MASTER KCE: King County Accessible Voting Centers" v:attribution="King County Elections"

property e:nv8f-b8na t:meta.view.license v:name="Public Domain"

property e:nv8f-b8na t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:nv8f-b8na t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| :updated_at | avc_name                        | in_use | dates_open                | hours_of_operation | election_day_hours | room                                  | ch_name          | ch_dates          | ch_times        | ch_election_day | vi_name                    | vi_dates                                                  | vi_hours                        | vi_election_day            | 
| =========== | =============================== | ====== | ========================= | ================== | ================== | ===================================== | ================ | ================= | =============== | =============== | ========================== | ========================================================= | =============================== | ========================== | 
| 1383242641  | Bellevue City Hall              | true   | Nov 4, 5                  | 10:00 am - 5:00 pm | 10:00 am - 8:00 pm |                                       | ????Bellevue???? | 11? 4?? 5?        | ??10????5?      | ??10????8?      | T?a Th? Ch?nh Bellevue     | Ng?y 4, 5 th?ng 11                                        | 10 gi? s?ng ? 5 gi? chi?u       | 10 gi? s?ng ? 8 gi? t?i    | 
| 1383242641  | Elections Headquarters          | true   | Oct 18 - Nov 4 (weekdays) | 8:30 am - 4:30 pm  | 8:30 am - 8:00 pm  |                                       | ??????           | 10?18??11?4? (??) | ??8?30????4?30? | ??8?30????8?    | Tr? S? Ch?nh c?a B? B?u C? | Ng?y 18 th?ng 10 ? ng?y 4 th?ng 11 (c?c ng?y trong tu?n)  | 8 gi? 30 s?ng ? 4 gi? 30 chi?u  | 8 gi? 30 s?ng ? 8 gi? t?i  | 
| 1383242641  | Green River Community College   |        | 2012                      | 10:00 am - 5:00 pm | 7:00 am - 8:00 pm  | Lindbloom Student Center Glacier Room |                  |                   |                 |                 | Ng?y m? c?a                |                                                           |                                 |                            | 
| 1383242641  | North Seattle Community College |        | 2012                      | 10:00 am - 5:00 pm | 7:00 am - 8:00 pm  | College Center Room 1360              |                  |                   |                 |                 |                            |                                                           |                                 |                            | 
| 1383242641  | Seattle Union Station           | true   | Nov 4, 5                  | 10:00 am - 5:00 pm | 10:00 am - 8:00 pm |                                       | ???Union??       | 11? 4?? 5?        | ??10????5?      | ??10????8?      | Tr?m Seattle Union         | Ng?y 4, 5 th?ng 11                                        | 10 gi? s?ng ? 5 gi? chi?u       | 10 gi? s?ng ? 8 gi? t?i    | 
```