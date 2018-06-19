# Science Festival Company Sponsors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/science-festival-company-sponsors) |
| Metadata | [Link](https://data.austintexas.gov/api/views/3p9m-wp4t) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/3p9m-wp4t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/3p9m-wp4t/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 3p9m-wp4t |
| Name | Science Festival Company Sponsors |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | science festival, austin energy regional science festival, energy, science, fair |
| Created | 2016-09-19T15:28:04Z |
| Publication Date | 2016-10-14T19:55:24Z |

## Description

The Austin Energy Regional Science Festival is one of the largest regional science festivals held in Texas and the nation. Middle and high school students who win at their respective schools compete at the regional festival to advance to the state science fair competition. Five senior level projects receive Best of Fair awards and the winners of those projects have the option to advance directly to the international competition. 

Central Texas middle and high school students have performed very well at past state and international competitions. Between 2004 and 2016, 100 students representing 71 projects advanced to the international level. Of those, 44 students representing 29 projects won 73 category and special awards. Since 2004, more than 1,225 students have advanced to the state level, where about 20% have won awards.

In 2016, the Austin Energy Regional Science Festival showcased 755 middle and high school projects. Unlike most regional events, Austin Energy also hosts elementary school students.  Nearly 4,000 students and their families turn out for the event which includes a public viewing of the science projects as well as educational booths and scientific demonstrations. 
Over 550 judges and 180 volunteers from the City of Austin, local businesses, colleges, and elementary/middle/high schools contribute annually to the event?s success. Revenues to fund the event come from fees paid by participating schools and companies that provide sponsorships.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | time           | fiscal_year     | Fiscal Year     | calendar_date | calendar_date |
| Yes      | series tag     | company_sponsor | Company Sponsor | text          | text          |
| Yes      | numeric metric | contribution    | Contribution    | money         | money         |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:3p9m-wp4t d:2007-01-01T00:00:00.000Z t:company_sponsor="Intel Foundation" m:contribution=10000

series e:3p9m-wp4t d:2007-01-01T00:00:00.000Z t:company_sponsor=Synopsys m:contribution=10000

series e:3p9m-wp4t d:2007-01-01T00:00:00.000Z t:company_sponsor="Holt, Rinehart and Winston" m:contribution=3000
```

## Meta Commands

```ls
metric m:contribution p:integer l:Contribution t:dataTypeName=money

entity e:3p9m-wp4t l:"Science Festival Company Sponsors" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/3p9m-wp4t

property e:3p9m-wp4t t:meta.view v:id=3p9m-wp4t v:category=Utility v:averageRating=0 v:name="Science Festival Company Sponsors" v:attribution="Austin Energy"

property e:3p9m-wp4t t:meta.view.license v:name="Public Domain"

property e:3p9m-wp4t t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:3p9m-wp4t t:meta.view.tableauthor v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"
```

## Top Records

```ls
| fiscal_year         | company_sponsor            | contribution | 
| =================== | ========================== | ============ | 
| 2007-01-01T00:00:00 | Intel Foundation           | 10000        | 
| 2007-01-01T00:00:00 | Synopsys                   | 10000        | 
| 2007-01-01T00:00:00 | Holt, Rinehart and Winston | 3000         | 
| 2007-01-01T00:00:00 | Austin Water Utility       | 1000         | 
| 2007-01-01T00:00:00 | BAE Systems                | 2000         | 
| 2007-01-01T00:00:00 | Ambion                     | 1500         | 
| 2007-01-01T00:00:00 | Applied Materials          | 1000         | 
| 2008-01-01T00:00:00 | Synopsys                   | 10000        | 
| 2008-01-01T00:00:00 | Intel Foundation           | 10000        | 
| 2008-01-01T00:00:00 | BAE Systems                | 2000         | 
```