# Election 2014 August LAUSD District 1 Voting Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-2014-august-lausd-district-1-voting-results-96df2) |
| Metadata | [Link](https://data.lacity.org/api/views/v5uj-jj3r) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/v5uj-jj3r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/v5uj-jj3r/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | v5uj-jj3r |
| Name | Election 2014 August LAUSD District 1 Voting Results |
| Category | A Well Run City |
| Created | 2014-08-20T17:14:19Z |
| Publication Date | 2014-08-22T14:18:41Z |

## Description

Statement of Votes Cast of the Election Results for the Los Angeles Unifed School District 1 Runoff Election

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | precinct       | PRECINCT       | text      | text        |
| Yes      | series tag     | name           | NAME           | text      | text        |
| Yes      | numeric metric | voters         | VOTERS         | number    | number      |
| Yes      | numeric metric | ballots        | BALLOTS        | number    | number      |
| Yes      | numeric metric | george_mckenna | GEORGE MCKENNA | number    | number      |
| Yes      | numeric metric | alex_johnson   | ALEX JOHNSON   | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:v5uj-jj3r d:2014-01-01T00:00:00.000Z t:precinct=2500001A t:name=GARDENA m:ballots=101 m:alex_johnson=44 m:george_mckenna=55 m:voters=863

series e:v5uj-jj3r d:2014-01-01T00:00:00.000Z t:precinct=2500002A t:name=GARDENA m:ballots=153 m:alex_johnson=61 m:george_mckenna=90 m:voters=1024

series e:v5uj-jj3r d:2014-01-01T00:00:00.000Z t:precinct=2500005A t:name=GARDENA m:ballots=95 m:alex_johnson=47 m:george_mckenna=48 m:voters=815
```

## Meta Commands

```ls
metric m:voters p:integer l:VOTERS t:dataTypeName=number

metric m:ballots p:integer l:BALLOTS t:dataTypeName=number

metric m:george_mckenna p:integer l:"GEORGE MCKENNA" t:dataTypeName=number

metric m:alex_johnson p:integer l:"ALEX JOHNSON" t:dataTypeName=number

entity e:v5uj-jj3r l:"Election 2014 August LAUSD District 1 Voting Results" t:url=https://data.lacity.org/api/views/v5uj-jj3r

property e:v5uj-jj3r t:meta.view v:id=v5uj-jj3r v:category="A Well Run City" v:averageRating=0 v:name="Election 2014 August LAUSD District 1 Voting Results"

property e:v5uj-jj3r t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:v5uj-jj3r t:meta.view.owner v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:displayName="City Clerk OpenData"

property e:v5uj-jj3r t:meta.view.tableauthor v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:roleName=publisher v:displayName="City Clerk OpenData"
```

## Top Records

```ls
| precinct | name      | voters | ballots | george_mckenna | alex_johnson | 
| ======== | ========= | ====== | ======= | ============== | ============ | 
| 2500001A | GARDENA   | 863    | 101     | 55             | 44           | 
| 2500002A | GARDENA   | 1024   | 153     | 90             | 61           | 
| 2500005A | GARDENA   | 815    | 95      | 48             | 47           | 
| 2500007A | GARDENA   | 1025   | 111     | 53             | 58           | 
| 2500008A | GARDENA   | 1165   | 120     | 53             | 67           | 
| 2500041A | GARDENA   | 1143   | 73      | 33             | 40           | 
| 2500046A | GARDENA   | 1108   | 127     | 57             | 70           | 
| 2700092A | HAWTHORNE | 1140   | 135     | 86             | 49           | 
| 2700094A | HAWTHORNE | 1015   | 136     | 80             | 55           | 
| 2950022B | INGLEWOOD | 257    | 38      | 26             | 12           | 
```