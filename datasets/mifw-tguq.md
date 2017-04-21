# Voting/Poll Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/voting-poll-sites-as-of-09-05-2013-29c79) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mifw-tguq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mifw-tguq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mifw-tguq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mifw-tguq |
| Name | Voting/Poll Sites |
| Attribution | Board of Elections (BOENY) |
| Category | City Government |
| Tags | vote, votes, voting, poll, polls, polling, poll site, poll sites, site, sites, election, elections |
| Created | 2012-10-18T18:15:30Z |
| Publication Date | 2016-11-01T16:05:28Z |

## Description

Locations of voting/poll sites through the city. This data is correct as of 10/19/16. Please note that this information may not be up-to-date.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | numeric metric | borough           | BOROUGH           | number    | text        |
| Yes      | series tag     | site_status       | SITE_STATUS       | text      | text        |
| Yes      | series tag     | site_name         | SITE_NAME         | text      | text        |
| Yes      | series tag     | site_number       | SITE_NUMBER       | text      | text        |
| Yes      | series tag     | street_number     | STREET_NUMBER     | text      | text        |
| Yes      | series tag     | street_suffix     | STREET_SUFFIX     | text      | text        |
| Yes      | series tag     | street_name       | STREET_NAME       | text      | text        |
| Yes      | series tag     | zip_code          | ZIP_CODE          | text      | text        |
| Yes      | series tag     | city              | CITY              | text      | text        |
| Yes      | series tag     | voter_entrance    | VOTER_ENTRANCE    | text      | text        |
| Yes      | series tag     | handicap_entrance | HANDICAP_ENTRANCE | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mifw-tguq d:2016-11-01T16:03:27.000Z t:voter_entrance="1 Bird S Coler Hospital" t:site_status=A t:zip_code=10044 t:street_name="Main Street" t:site_number=00001 t:street_number=900 t:handicap_entrance="Parking Lot" t:site_name="Coler Hospital" t:city="New York" m:borough=1

series e:mifw-tguq d:2016-11-01T16:03:27.000Z t:voter_entrance="113 East 4 Street" t:site_status=A t:zip_code=10003 t:street_name="East 4 Street" t:site_number=00007 t:street_number=113 t:handicap_entrance="113 East 4 Street" t:site_name="PS 751" t:city="New York" m:borough=1

series e:mifw-tguq d:2016-11-01T16:03:27.000Z t:voter_entrance="525 East Houston Street" t:site_status=A t:zip_code=10002 t:street_name="East Houston Street" t:site_number=00009 t:street_number=525 t:handicap_entrance="Mangin Street" t:site_name="Bard H.S.E.C.- 97" t:city="New York" m:borough=1
```

## Meta Commands

```ls
metric m:borough p:integer l:BOROUGH t:dataTypeName=number

entity e:mifw-tguq l:"Voting/Poll Sites" t:attribution="Board of Elections (BOENY)" t:url=https://data.cityofnewyork.us/api/views/mifw-tguq

property e:mifw-tguq t:meta.view v:id=mifw-tguq v:category="City Government" v:averageRating=0 v:name="Voting/Poll Sites" v:attribution="Board of Elections (BOENY)"

property e:mifw-tguq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mifw-tguq t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough | site_status | site_name           | site_number | street_number | street_suffix | street_name         | zip_code | city     | voter_entrance                          | handicap_entrance                       | 
| =========== | ======= | =========== | =================== | =========== | ============= | ============= | =================== | ======== | ======== | ======================================= | ======================================= | 
| 1478016207  | 1       | A           | Coler Hospital      | 00001       | 900           |               | Main Street         | 10044    | New York | 1 Bird S Coler Hospital                 | Parking Lot                             | 
| 1478016207  | 1       | A           | PS 751              | 00007       | 113           |               | East 4 Street       | 10003    | New York | 113 East 4 Street                       | 113 East 4 Street                       | 
| 1478016207  | 1       | A           | Bard H.S.E.C.- 97   | 00009       | 525           |               | East Houston Street | 10002    | New York | 525 East Houston Street                 | Mangin Street                           | 
| 1478016207  | 1       | A           | Frank McCourt HS    | 00012       | 151           |               | West 84 Street      | 10024    | New York | W. 85 St (Bet Columbus & Amsterdam Ave) | W. 85 St (Bet Columbus & Amsterdam Ave) | 
| 1478016207  | 1       | A           | Westbeth Housing    | 00013       | 155           |               | Bank Street         | 10014    | New York | 155 Bank Street                         | 155 Bank Street                         | 
| 1478016207  | 1       | A           | JASA Community Ctr  | 00016       | 200           |               | East 5 Street       | 10003    | New York | 200 East 5 Street                       | 200 East 5 Street                       | 
| 1478016207  | 1       | A           | HS Fashion Industry | 00019       | 225           |               | West 24 Street      | 10011    | New York | 225 West 24 Street                      | 225 West 24 Street                      | 
| 1478016207  | 1       | A           | PS 206              | 00025       | 508           |               | East 120 Street     | 10035    | New York | 508 East 120 Street                     | 508 East 120 Street                     | 
| 1478016207  | 1       | A           | PS 52               | 00028       | 650           |               | Academy Street      | 10034    | New York | 650 Academy Street                      | Broadway                                | 
| 1478016207  | 1       | A           | Bayard Rustin H S   | 10099       | 351           |               | West 18 Street      | 10011    | New York | 351 West 18 Street                      | 351 West 18 Street                      | 
```