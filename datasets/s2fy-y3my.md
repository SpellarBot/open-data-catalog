# Lobbyist Activity - Payments Promised By Clients

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-activity-payments-promised-by-clients-cbf37) |
| Metadata | [Link](https://data.sfgov.org/api/views/s2fy-y3my) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/s2fy-y3my/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/s2fy-y3my/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | s2fy-y3my |
| Name | Lobbyist Activity - Payments Promised By Clients |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, lobbyist, payments, promised, clients |
| Created | 2012-04-27T00:02:56Z |
| Publication Date | 2014-08-05T17:41:11Z |

## Description

The amount of economic consideration received or expected by the lobbyist or the lobbyist's employer from each client during the reporting period.Promised payments are disclosed by lobbyists registered with the Ethics Commission on a monthly basis.  This dataset updates automatically every night.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | time           | date            | Date            | calendar_date | calendar_date |
| Yes      | series tag     | lobbyist        | Lobbyist        | text          | text          |
| Yes      | series tag     | lobbyist_firm   | Lobbyist_Firm   | text          | text          |
| Yes      | numeric metric | amount          | Amount          | money         | money         |
| Yes      | series tag     | lobbyist_client | Lobbyist_Client | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:s2fy-y3my d:2014-07-31T00:00:00.000Z t:lobbyist_firm="Pershing Square Capital Management, L.p." t:lobbyist="Symonds, Stephen" t:lobbyist_client="Pershing Square Capital Management, L.p." m:amount=618.29

series e:s2fy-y3my d:2011-12-31T00:00:00.000Z t:lobbyist_firm="Barbary Coast Consulting" t:lobbyist="Smith, Alexis" t:lobbyist_client="Orange Barrel Media" m:amount=9631.25

series e:s2fy-y3my d:2011-11-30T00:00:00.000Z t:lobbyist_firm="Barbary Coast Consulting" t:lobbyist="Smith, Alexis" t:lobbyist_client="Orange Barrel Media" m:amount=12118.75
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

entity e:s2fy-y3my l:"Lobbyist Activity - Payments Promised By Clients" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/s2fy-y3my

property e:s2fy-y3my t:meta.view v:id=s2fy-y3my v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org/ethics/2012/01/lobbyist-database-api.html v:averageRating=0 v:name="Lobbyist Activity - Payments Promised By Clients" v:attribution="San Francisco Ethics Commission"

property e:s2fy-y3my t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:s2fy-y3my t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:s2fy-y3my t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| date                | lobbyist           | lobbyist_firm                               | amount   | lobbyist_client                             | 
| =================== | ================== | =========================================== | ======== | =========================================== | 
| 2014-07-31T00:00:00 | Symonds, Stephen   | Pershing Square Capital Management, L.p.    | 618.29   | Pershing Square Capital Management, L.p.    | 
| 2011-12-31T00:00:00 | Smith, Alexis      | Barbary Coast Consulting                    | 9631.25  | Orange Barrel Media                         | 
| 2011-11-30T00:00:00 | Smith, Alexis      | Barbary Coast Consulting                    | 12118.75 | Orange Barrel Media                         | 
| 2011-08-31T00:00:00 | Smith, Alexis      | Barbary Coast Consulting                    | 5206.25  | Orange Barrel Media                         | 
| 2011-07-31T00:00:00 | Smith, Alexis      | Barbary Coast Consulting                    | 11106.25 | Orange Barrel Media                         | 
| 2014-07-17T00:00:00 | Sanders, Elizabeth | Ubs Global Asset Management (Americas) Inc. | 57.69    | Ubs Global Asset Management (Americas) Inc. | 
| 2014-06-15T00:00:00 | Sanders, Elizabeth | Ubs Global Asset Management (Americas) Inc. | 115.39   | Ubs Global Asset Management (Americas) Inc. | 
| 2014-06-16T00:00:00 | Sanders, Elizabeth | Ubs Global Asset Management (Americas) Inc. | 537.84   | Ubs Global Asset Management (Americas) Inc. | 
| 2014-05-05T00:00:00 | Sanders, Elizabeth | Ubs Global Asset Management (Americas) Inc. | 115.38   | Ubs Global Asset Management (Americas) Inc. | 
| 2014-05-07T00:00:00 | Sanders, Elizabeth | Ubs Global Asset Management (Americas) Inc. | 115.38   | Ubs Global Asset Management (Americas) Inc. | 
```