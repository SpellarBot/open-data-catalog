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
| Rows Updated | 2014-10-17T15:59:39Z |

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
Value = 
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:mzmn-fvgv l:"Early Voting & Grace Period Registration and Voting - 2014 November 4 Gubernatorial Election" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/mzmn-fvgv

property e:mzmn-fvgv t:meta.view v:id=mzmn-fvgv v:category="Finance & Administration" v:attributionLink=http://www.cookcountyclerk.com v:averageRating=0 v:name="Early Voting & Grace Period Registration and Voting - 2014 November 4 Gubernatorial Election" v:attribution="Cook County Clerk"

property e:mzmn-fvgv t:meta.view.license v:name="Public Domain"

property e:mzmn-fvgv t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:displayName="Cook County Open Data"

property e:mzmn-fvgv t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:displayName="Cook County Open Data"
```