# Early Voting & Grace Period Registration and Voting - 2014 November 4 Gubernatorial Election

## Dataset

* [Dataset URL](https://datacatalog.cookcountyil.gov/api/views/mzmn-fvgv/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/early-voting-grace-period-registration-and-voting-2014-november-4-gubernatorial-election-80f3f)
* Id = mzmn-fvgv
* Name = Early Voting & Grace Period Registration and Voting - 2014 November 4 Gubernatorial Election
* Attribution = Cook County Clerk
* Attribution Link = http://www.cookcountyclerk.com
* Category = Finance & Administration
* Tags = [elections, voting, vote, polling locations, early voting]
* Created = 2014-10-17T15:43:43Z
* Publication Date = 2014-10-17T16:06:29Z
* Rows Updated = 2014-10-17T15:59:39Z

## Description

This dataset details the hours and locations for voter registration and voting in
suburban Cook County between Oct. 8 and election day, Nov. 4, 2014. Voters may
visit one of the 18 election day registration sites if they are not already registered 
and eligible to vote in their precinct. For more information on Early Voting see http://www.cookcountyclerk.com/elections/earlyvoting/Pages/default.aspx , For more information on Grace Period Registration and Voting see http://www.cookcountyclerk.com/elections/registertovote/Pages/GracePeriod.aspx . For more information on Election Day Registration and Voting see http://www.cookcountyclerk.com/elections/registertovote/Pages/ElectionDayRegistration.aspx .

## Columns

```ls
| Name                               | Field Name                       | Data Type | Render Type | Schema Type | Included | 
| ================================== | ================================ | ========= | =========== | =========== | ======== | 
| updated_at                         | :updated_at                      | meta_data | meta_data   | time        | Yes      | 
| Site                               | site                             | text      | text        | series tag  | Yes      | 
| Early Voting - Weekdays            | early_voting_weekdays            | text      | text        | series tag  | Yes      | 
| Early Voting - Saturday            | early_voting_saturday            | text      | text        | series tag  | Yes      | 
| Early Voting - Sunday              | early_voting_sunday              | text      | text        | series tag  | Yes      | 
| Grace Period Registration & Voting | grace_period_registration_voting | text      | text        | series tag  | Yes      | 
| Grace Period & In-Person Absentee  | grace_period_in_person_absentee  | text      | text        | series tag  | Yes      | 
| Election Day Registration & Voting | election_day_registration_voting | text      | text        | series tag  | Yes      | 
| Street                             | street                           | text      | text        | series tag  | Yes      | 
| City                               | city                             | text      | text        | series tag  | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:mzmn-fvgv l:"Early Voting & Grace Period Registration and Voting - 2014 November 4 Gubernatorial Election" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/mzmn-fvgv

property e:mzmn-fvgv t:meta.view d:2017-03-03T14:35:37.602Z v:id=mzmn-fvgv v:category="Finance & Administration" v:attributionLink=http://www.cookcountyclerk.com v:averageRating=0 v:name="Early Voting & Grace Period Registration and Voting - 2014 November 4 Gubernatorial Election" v:attribution="Cook County Clerk"

property e:mzmn-fvgv t:meta.view.license d:2017-03-03T14:35:37.602Z v:name="Public Domain"

property e:mzmn-fvgv t:meta.view.owner d:2017-03-03T14:35:37.602Z v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:displayName="Cook County Open Data"

property e:mzmn-fvgv t:meta.view.tableauthor d:2017-03-03T14:35:37.602Z v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:displayName="Cook County Open Data"
```