# Lobbyist Activity - Political Contributions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-activity-political-contributions-4cd30) |
| Metadata | [Link](https://data.sfgov.org/api/views/sa8r-purn) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/sa8r-purn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/sa8r-purn/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | sa8r-purn |
| Name | Lobbyist Activity - Political Contributions |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, lobbyist, contribution, candidate, ballot measure, committee |
| Created | 2012-04-26T23:35:53Z |
| Publication Date | 2014-08-05T17:41:25Z |

## Description

All political contributions of $100 or more made or delivered by the lobbyist or the lobbyist's employer, or made by a client at the behest of the lobbyist or the lobbyist's employer during the reporting period to an officer of the City and County, a candidate for such office, a committee controlled by such officer or candidate, or a committee primarily formed to support or oppose such officer or candidate, or any committee primarily formed to support or oppose a ballot measure to be voted on only in San Francisco. This includes political contributions arranged by the lobbyist, or for which the lobbyist acted as an agent or intermediary.Political contributions are disclosed by lobbyists registered with the Ethics Commission on a monthly basis.  This dataset updates automatically every night.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | time           | date                | Date                | calendar_date | calendar_date |
| Yes      | series tag     | lobbyist            | Lobbyist            | text          | text          |
| Yes      | series tag     | lobbyist_firm       | Lobbyist_Firm       | text          | text          |
| Yes      | series tag     | official            | Official            | text          | text          |
| Yes      | series tag     | official_department | Official_Department | text          | text          |
| Yes      | series tag     | payee               | Payee               | text          | text          |
| Yes      | series tag     | sourceoffunds       | SourceOfFunds       | text          | text          |
| Yes      | numeric metric | amount              | Amount              | money         | money         |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:sa8r-purn d:2015-12-02T00:00:00.000Z t:lobbyist_firm="Hms Associates" t:lobbyist="Johnston, Karin" t:payee="Re-Elect London Breed For Supervisor 2016" t:official="Breed, London" t:sourceoffunds="Allbin, Eric" m:amount=500

series e:sa8r-purn d:2015-12-01T00:00:00.000Z t:lobbyist_firm="Hanson Bridgett Llp" t:lobbyist="Gladstone, Brett" t:payee="Scott Wiener For State Senate 2016" t:official="Wiener, Scott" t:sourceoffunds="Rrti, Inc." m:amount=1000

series e:sa8r-purn d:2015-12-01T00:00:00.000Z t:lobbyist_firm="Hanson Bridgett Llp" t:lobbyist="Gladstone, Brett" t:payee="Scott Wiener For State Senate 2016" t:official="Wiener, Scott" t:sourceoffunds="Heneghan, Kevin" m:amount=150
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:sa8r-purn l:"Lobbyist Activity - Political Contributions" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/sa8r-purn

property e:sa8r-purn t:meta.view v:id=sa8r-purn v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org/ethics/2012/01/lobbyist-database-api.html v:averageRating=0 v:name="Lobbyist Activity - Political Contributions" v:attribution="San Francisco Ethics Commission"

property e:sa8r-purn t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:sa8r-purn t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:sa8r-purn t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| date                | lobbyist           | lobbyist_firm               | official        | official_department | payee                                     | sourceoffunds      | amount | 
| =================== | ================== | =========================== | =============== | =================== | ========================================= | ================== | ====== | 
| 2015-12-02T00:00:00 | Johnston, Karin    | Hms Associates              | Breed, London   |                     | Re-Elect London Breed For Supervisor 2016 | Allbin, Eric       | 500    | 
| 2015-12-01T00:00:00 | Gladstone, Brett   | Hanson Bridgett Llp         | Wiener, Scott   |                     | Scott Wiener For State Senate 2016        | Rrti, Inc.         | 1000   | 
| 2015-12-01T00:00:00 | Gladstone, Brett   | Hanson Bridgett Llp         | Wiener, Scott   |                     | Scott Wiener For State Senate 2016        | Heneghan, Kevin    | 150    | 
| 2015-12-02T00:00:00 | Johnston, Karin    | Hms Associates              | Breed, London   |                     | Re-Elect London Breed For Supervisor 2016 | Adams, Scott       | 500    | 
| 2015-12-15T00:00:00 | Tourk, Alex        | Ground Floor Public Affairs | Safai, Ahsha    |                     | Ahsha Safai For Supervisor - 2016         | Lazarus, James     | 100    | 
| 2015-12-26T00:00:00 | Johnston, Karin    | Hms Associates              | Breed, London   |                     | Re-Elect London Breed For Supervisor 2016 | Jeffries, Jennifer | 500    | 
| 2015-12-02T00:00:00 | Johnston, Karin    | Hms Associates              | Breed, London   |                     | Re-Elect London Breed For Supervisor 2016 | Mellett, Robert    | 500    | 
| 2015-12-01T00:00:00 | Gladstone, Brett   | Hanson Bridgett Llp         | Wiener, Scott   |                     | Scott Wiener For State Senate 2016        | Zira, Tahir        | 250    | 
| 2015-12-21T00:00:00 | Loeven, Lewis      | Loeven And Associates Llc   | Hennessy, Vicki |                     | Vicki Hennessy For Sheriff                | Loeven, Lewis      | 250    | 
| 2015-12-02T00:00:00 | Smolens, H. Marcia | Hms Associates              | Breed, London   |                     | Re-Elect London Breed For Supervisor 2016 | Smolens, H. Marcia | 500    | 
```