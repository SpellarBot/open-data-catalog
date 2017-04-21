# Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 4 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-summary-of-third-party-disclosure-forms-regarding-san-francisco-candidat--069fa) |
| Metadata | [Link](https://data.sfgov.org/api/views/htai-xw5t) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/htai-xw5t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/htai-xw5t/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | htai-xw5t |
| Name | Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 4 2014 |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, third-party, disclosure, candidates, november, election, 2014 |
| Created | 2013-11-25T18:15:34Z |
| Publication Date | 2015-03-02T16:44:14Z |

## Description

San Francisco Campaign and Governmental Conduct Code ("S.F. C&GC Code") sections 1.143(c), 1.152(a)(3), 1.161(b), 1.161.5, and 1.160.5 require persons who make any independent expenditure, electioneering communication, or member communication that clearly identifies a candidate for City elective office or who authorizes, administers or pays for a persuasion poll to file disclosure statements with the Ethics Commission. For detailed instructions, please see Third Party Disclosure Form Regarding Candidates.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | ============== | ================================ | ================================ | ============= | ============= |
| Yes      | series tag     | reference_no                     | Reference No.                    | text          | text          |
| Yes      | time           | date_filed                       | Date filed                       | calendar_date | calendar_date |
| Yes      | series tag     | filer                            | Filer                            | text          | text          |
| Yes      | series tag     | filer_id                         | Filer Id                         | text          | text          |
| Yes      | numeric metric | amount                           | Amount                           | money         | money         |
| Yes      | series tag     | candidate_identified             | Candidate Identified             | text          | text          |
| Yes      | series tag     | district                         | District                         | text          | text          |
| Yes      | series tag     | support_oppose_or_neutral        | Support, Oppose or Neutral       | text          | text          |
| No       |                | start_date_of_distribution       | Start Date of Distribution       | calendar_date | calendar_date |
| No       |                | end_or_only_date_of_distribution | End or Only Date of Distribution | calendar_date | calendar_date |
| Yes      | series tag     | notes                            | Notes                            | text          | text          |
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = start_date_of_distribution,end_or_only_date_of_distribution
```

## Data Commands

```ls
series e:htai-xw5t d:2014-09-06T00:00:00.000Z t:filer="Stop the Housing Tax, No on G" t:candidate_identified="Carmen Chu" t:support_oppose_or_neutral=Neutral t:filer_id=1369949 t:reference_no=1 t:district=Assessor-Recorder m:amount=379

series e:htai-xw5t d:2014-09-06T00:00:00.000Z t:filer="Stop the Housing Tax, No on G" t:candidate_identified="Mark Farrell" t:support_oppose_or_neutral=Neutral t:filer_id=1369949 t:reference_no=1 t:district=2 m:amount=379

series e:htai-xw5t d:2014-09-06T00:00:00.000Z t:filer="Stop the Housing Tax, No on G" t:candidate_identified="Scott Weiner" t:support_oppose_or_neutral=Neutral t:filer_id=1369949 t:reference_no=1 t:district=8 m:amount=379
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:htai-xw5t l:"Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 4 2014" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/htai-xw5t

property e:htai-xw5t t:meta.view v:id=htai-xw5t v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 4 2014" v:attribution="San Francisco Ethics Commission"

property e:htai-xw5t t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:htai-xw5t t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:htai-xw5t t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| reference_no | date_filed          | filer                         | filer_id | amount | candidate_identified | district          | support_oppose_or_neutral | start_date_of_distribution | end_or_only_date_of_distribution | notes | 
| ============ | =================== | ============================= | ======== | ====== | ==================== | ================= | ========================= | ========================== | ================================ | ===== | 
| 1            | 2014-09-06T00:00:00 | Stop the Housing Tax, No on G | 1369949  | 379    | Carmen Chu           | Assessor-Recorder | Neutral                   | 2014-09-04T00:00:00        | 2014-09-04T00:00:00              |       | 
| 1            | 2014-09-06T00:00:00 | Stop the Housing Tax, No on G | 1369949  | 379    | Mark Farrell         | 2                 | Neutral                   | 2014-09-04T00:00:00        | 2014-09-04T00:00:00              |       | 
| 1            | 2014-09-06T00:00:00 | Stop the Housing Tax, No on G | 1369949  | 379    | Scott Weiner         | 8                 | Neutral                   | 2014-09-04T00:00:00        | 2014-09-04T00:00:00              |       | 
| 1            | 2014-09-06T00:00:00 | Stop the Housing Tax, No on G | 1369949  | 379    | Katy Tang            | 4                 | Neutral                   | 2014-09-04T00:00:00        | 2014-09-04T00:00:00              |       | 
| 2            | 2014-09-17T00:00:00 | Stop the Housing Tax, No on G | 1369949  | 256.27 | Carmen Chu           | Assessor-Recorder | Neutral                   | 2014-09-15T00:00:00        | 2014-09-15T00:00:00              |       | 
| 2            | 2014-09-17T00:00:00 | Stop the Housing Tax, No on G | 1369949  | 256.27 | Mark Farrell         | 2                 | Neutral                   | 2014-09-15T00:00:00        | 2014-09-15T00:00:00              |       | 
| 2            | 2014-09-17T00:00:00 | Stop the Housing Tax, No on G | 1369949  | 256.27 | Scott Weiner         | 8                 | Neutral                   | 2014-09-15T00:00:00        | 2014-09-15T00:00:00              |       | 
| 2            | 2014-09-17T00:00:00 | Stop the Housing Tax, No on G | 1369949  | 256.27 | Katy Tang            | 4                 | Neutral                   | 2014-09-15T00:00:00        | 2014-09-15T00:00:00              |       | 
| 3            | 2014-09-21T00:00:00 | Stop the Housing Tax, No on G | 1369949  | 156.65 | Carmen Chu           | Assessor-Recorder | Neutral                   | 2014-09-19T00:00:00        | 2014-09-19T00:00:00              |       | 
| 3            | 2014-09-21T00:00:00 | Stop the Housing Tax, No on G | 1369949  | 156.65 | Mark Farrell         | 2                 | Neutral                   | 2014-09-19T00:00:00        | 2014-09-19T00:00:00              |       | 
```