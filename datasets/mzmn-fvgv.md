# Early Voting & Grace Period Registration and Voting - 2014 November 4 Gubernatorial Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/early-voting-grace-period-registration-and-voting-2014-november-4-gubernatorial-election-80f3f) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/mzmn-fvgv) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/mzmn-fvgv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/mzmn-fvgv/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | mzmn-fvgv |
| Name | Early Voting & Grace Period Registration and Voting - 2014 November 4 Gubernatorial Election |
| Attribution | Cook County Clerk |
| Category | Finance & Administration |
| Tags | elections, voting, vote, polling locations, early voting |
| Created | 2014-10-17T15:43:43Z |
| Publication Date | 2014-10-17T16:06:29Z |

## Description

This dataset details the hours and locations for voter registration and voting in
suburban Cook County between Oct. 8 and election day, Nov. 4, 2014. Voters may
visit one of the 18 election day registration sites if they are not already registered 
and eligible to vote in their precinct. For more information on Early Voting see http://www.cookcountyclerk.com/elections/earlyvoting/Pages/default.aspx , For more information on Grace Period Registration and Voting see http://www.cookcountyclerk.com/elections/registertovote/Pages/GracePeriod.aspx . For more information on Election Day Registration and Voting see http://www.cookcountyclerk.com/elections/registertovote/Pages/ElectionDayRegistration.aspx .

## Columns

```ls
| Included | Schema Type | Field Name                       | Name                               | Data Type | Render Type |
| ======== | =========== | ================================ | ================================== | ========= | =========== |
| Yes      | series tag  | site                             | Site                               | text      | text        |
| Yes      | series tag  | early_voting_weekdays            | Early Voting - Weekdays            | text      | text        |
| Yes      | series tag  | early_voting_saturday            | Early Voting - Saturday            | text      | text        |
| Yes      | series tag  | early_voting_sunday              | Early Voting - Sunday              | text      | text        |
| Yes      | series tag  | grace_period_registration_voting | Grace Period Registration & Voting | text      | text        |
| Yes      | series tag  | grace_period_in_person_absentee  | Grace Period & In-Person Absentee  | text      | text        |
| Yes      | series tag  | election_day_registration_voting | Election Day Registration & Voting | text      | text        |
| Yes      | series tag  | street                           | Street                             | text      | text        |
| Yes      | series tag  | city                             | City                               | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mzmn-fvgv d:2014-01-01T00:00:00.000Z t:election_day_registration_voting="Nov. 4 6am-7pm" t:site="Oak Park Village Hall" t:early_voting_sunday="Sun Oct. 26  9am-3pm; Sun Nov. 2  9am-4pm" t:grace_period_in_person_absentee="Nov. 3  9am-5pm" t:street="123 Madison St." t:grace_period_registration_voting="During Early Voting Hours" t:early_voting_saturday="Sat Oct. 25, Nov. 1 9am-5pm" t:early_voting_weekdays="M-F  Oct. 20-24 9am-5pm; M-F Oct. 27-31 9am-7pm" t:city="Oak Park" m:row_number.mzmn-fvgv=1

series e:mzmn-fvgv d:2014-01-01T00:00:00.000Z t:site="Alsip Village Hall" t:street="4500 W. 123rd St." t:grace_period_registration_voting="During Early Voting Hours" t:early_voting_saturday="Sat Oct. 25, Nov. 1 9am-5pm" t:early_voting_weekdays="M-F  Oct. 20-24 9am-5pm; M-F Oct. 27-31 9am-7pm" t:city=Alsip m:row_number.mzmn-fvgv=2

series e:mzmn-fvgv d:2014-01-01T00:00:00.000Z t:site="Park Forest Village Hall" t:street="350 Victory Blvd." t:grace_period_registration_voting="During Early Voting Hours" t:early_voting_saturday="Sat Oct. 25, Nov. 1 9am-5pm" t:early_voting_weekdays="M-F  Oct. 20-24 9am-5pm; M-F Oct. 27-31 9am-7pm" t:city="Park Forest" m:row_number.mzmn-fvgv=3
```

## Meta Commands

```ls
metric m:row_number.mzmn-fvgv p:long l:"Row Number"

entity e:mzmn-fvgv l:"Early Voting & Grace Period Registration and Voting - 2014 November 4 Gubernatorial Election" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/mzmn-fvgv

property e:mzmn-fvgv t:meta.view d:2017-06-09T13:54:36.941Z v:id=mzmn-fvgv v:category="Finance & Administration" v:attributionLink=http://www.cookcountyclerk.com v:averageRating=0 v:name="Early Voting & Grace Period Registration and Voting - 2014 November 4 Gubernatorial Election" v:attribution="Cook County Clerk"

property e:mzmn-fvgv t:meta.view.license d:2017-06-09T13:54:36.941Z v:name="Public Domain"

property e:mzmn-fvgv t:meta.view.owner d:2017-06-09T13:54:36.941Z v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1496243074 v:displayName="Cook County Open Data"

property e:mzmn-fvgv t:meta.view.tableauthor d:2017-06-09T13:54:36.941Z v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1496243074 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| site                         | early_voting_weekdays                          | early_voting_saturday       | early_voting_sunday                     | grace_period_registration_voting                            | grace_period_in_person_absentee | election_day_registration_voting | street                            | city        | 
| ============================ | ============================================== | =========================== | ======================================= | =========================================================== | =============================== | ================================ | ================================= | =========== | 
| Oak Park Village Hall        | M-F Oct. 20-24 9am-5pm; M-F Oct. 27-31 9am-7pm | Sat Oct. 25, Nov. 1 9am-5pm | Sun Oct. 26 9am-3pm; Sun Nov. 2 9am-4pm | During Early Voting Hours                                   | Nov. 3 9am-5pm                  | Nov. 4 6am-7pm                   | 123 Madison St.                   | Oak Park    | 
| Alsip Village Hall           | M-F Oct. 20-24 9am-5pm; M-F Oct. 27-31 9am-7pm | Sat Oct. 25, Nov. 1 9am-5pm |                                         | During Early Voting Hours                                   |                                 |                                  | 4500 W. 123rd St.                 | Alsip       | 
| Park Forest Village Hall     | M-F Oct. 20-24 9am-5pm; M-F Oct. 27-31 9am-7pm | Sat Oct. 25, Nov. 1 9am-5pm |                                         | During Early Voting Hours                                   |                                 |                                  | 350 Victory Blvd.                 | Park Forest | 
| Skokie Courthouse            | M-F Oct. 20-24 9am-5pm; M-F Oct. 27-31 9am-7pm |                             |                                         | During Early Voting Hours and Oct. 8-10, Oct. 14-17 9am-5pm | Nov. 3 9am-5pm                  |                                  | 5600 W. Old Orchard Rd., Room 149 | Skokie      | 
| Palatine Township Hall - NEW | M-F Oct. 20-24 9am-5pm; M-F Oct. 27-31 9am-7pm | Sat Oct. 25, Nov. 1 9am-5pm |                                         | During Early Voting Hours                                   |                                 |                                  | 721 S. Quentin Rd.                | Palatine    | 
| Glenview Village Hall        | M-F Oct. 20-24 9am-5pm; M-F Oct. 27-31 9am-7pm | Sat Oct. 25, Nov. 1 9am-5pm |                                         | During Early Voting Hours                                   |                                 |                                  | 1225 Waukegan Rd.                 | Glenview    | 
| Schaumburg Public Library    | M-F Oct. 20-24 9am-5pm; M-F Oct. 27-31 9am-7pm | Sat Oct. 25, Nov. 1 9am-5pm | Sun Oct. 26 9am-3pm; Sun Nov. 2 9am-4pm | During Early Voting Hours                                   | Nov. 3 9am-5pm                  | Nov. 4 6am-7pm                   | 130 S. Roselle Rd.                | Schaumburg  | 
| Skokie Village Hall          | M-F Oct. 20-24 9am-5pm; M-F Oct. 27-31 9am-7pm | Sat Oct. 25, Nov. 1 9am-5pm |                                         | During Early Voting Hours                                   |                                 |                                  | 5127 Oakton St.                   | Skokie      | 
| Orland Township Hall         | M-F Oct. 20-24 9am-5pm; M-F Oct. 27-31 9am-7pm | Sat Oct. 25, Nov. 1 9am-5pm | Sun Oct. 26 9am-3pm; Sun Nov. 2 9am-4pm | During Early Voting Hours                                   | Nov. 3 9am-5pm                  | Nov. 4 6am-7pm                   | 14807 Ravinia Ave.                | Orland Park | 
| Cicero Community Center      | M-F Oct. 20-24 9am-5pm; M-F Oct. 27-31 9am-7pm | Sat Oct. 25, Nov. 1 9am-5pm | Sun Oct. 26 9am-3pm; Sun Nov. 2 9am-4pm | During Early Voting Hours                                   | Nov. 3 9am-5pm                  | Nov. 4 6am-7pm                   | 2250 S. 49th Ave.                 | Cicero      | 
```