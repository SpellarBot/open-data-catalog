# Campaign Finance - Summary of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2011 Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-summary-of-third-party-disclosure-forms-regarding-san-francisco-candidate-8c24b) |
| Metadata | [Link](https://data.sfgov.org/api/views/6xiy-xib3) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/6xiy-xib3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/6xiy-xib3/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 6xiy-xib3 |
| Name | Campaign Finance - Summary of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2011 Election |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | campaign, finance, third-party, disclosure, mayor, 2011, election |
| Created | 2012-03-19T17:35:17Z |
| Publication Date | 2012-03-19T23:14:01Z |

## Description

San Francisco Campaign and Governmental Conduct Code ("S.F. C&GC Code") sections 1.143(c), 1.152(a)(3), 1.161(b), 1.161.5, and 1.160.5 require persons who make any independent expenditure, electioneering communication, or member communication that clearly identifies a candidate for City elective office or who authorizes, administers or pays for a persuasion poll to file disclosure statements with the Ethics Commission. For detailed instructions, please see Third Party Disclosure Form Regarding Candidates.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | reference_no           | Reference No.          | text          | text          |
| Yes      | time           | date_filed             | Date Filed             | calendar_date | calendar_date |
| Yes      | series tag     | filer                  | Filer                  | text          | text          |
| Yes      | series tag     | filerid                | FilerID                | text          | number        |
| Yes      | numeric metric | amount                 | Amount                 | money         | money         |
| Yes      | series tag     | candidate_identified   | Candidate Identified   | text          | text          |
| Yes      | series tag     | support_oppose_neutral | Support/Oppose/Neutral | text          | text          |
| Yes      | series tag     | notes                  | Notes                  | text          | text          |
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:6xiy-xib3 d:2011-08-01T00:00:00.000Z t:filer="Support Drafting Ed Lee for SF Mayor 2011" t:support_oppose_neutral=Support t:candidate_identified="Lee, Ed" t:reference_no=1 t:filerid=1339973 m:amount=6707

series e:6xiy-xib3 d:2011-09-14T00:00:00.000Z t:filer="Yes on Prop. D, supported by Public Defender Jeff Adachi, Basic American Foods executive George Hume & business investor, Michael Moritz" t:support_oppose_neutral=Support t:candidate_identified="Adachi, Jeff" t:reference_no=2 t:filerid=1336704 m:amount=25302

series e:6xiy-xib3 d:2011-09-21T00:00:00.000Z t:filer="Yes on Prop. D, supported by Public Defender Jeff Adachi, Basic American Foods executive George Hume & business investor, Michael Moritz" t:support_oppose_neutral=Support t:candidate_identified="Adachi, Jeff" t:reference_no=3 t:filerid=1336704 t:notes="The amounts listed on this webpage are different from the amounts reported by the committee on the Third Party Disclosure form because the amounts listed here reflect the cost allocated to the candidate(s) referenced above, whereas the amounts reported by the committee reflect the total cost of the communications." m:amount=742
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

entity e:6xiy-xib3 l:"Campaign Finance - Summary of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2011 Election" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/6xiy-xib3

property e:6xiy-xib3 t:meta.view v:id=6xiy-xib3 v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org/ethics/2011/03/campaign-finance-summary-of-third-party-disclosure-form-regarding-san-francisco-candidates-november-.html v:averageRating=0 v:name="Campaign Finance - Summary of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2011 Election" v:attribution="San Francisco Ethics Commission"

property e:6xiy-xib3 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:6xiy-xib3 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:6xiy-xib3 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| reference_no | date_filed          | filer                                                                                                                                    | filerid | amount | candidate_identified | support_oppose_neutral | notes                                                                                                                                                                                                                                                                                                                       | 
| ============ | =================== | ======================================================================================================================================== | ======= | ====== | ==================== | ====================== | =========================================================================================================================================================================================================================================================================================================================== | 
|  1           | 2011-08-01T00:00:00 | Support Drafting Ed Lee for SF Mayor 2011                                                                                                | 1339973 | 6707   | Lee, Ed              | Support                |                                                                                                                                                                                                                                                                                                                             | 
|  2           | 2011-09-14T00:00:00 | Yes on Prop. D, supported by Public Defender Jeff Adachi, Basic American Foods executive George Hume & business investor, Michael Moritz | 1336704 | 25302  | Adachi, Jeff         | Support                |                                                                                                                                                                                                                                                                                                                             | 
|  3           | 2011-09-21T00:00:00 | Yes on Prop. D, supported by Public Defender Jeff Adachi, Basic American Foods executive George Hume & business investor, Michael Moritz | 1336704 | 742    | Adachi, Jeff         | Support                | The amounts listed on this webpage are different from the amounts reported by the committee on the Third Party Disclosure form because the amounts listed here reflect the cost allocated to the candidate(s) referenced above, whereas the amounts reported by the committee reflect the total cost of the communications. | 
|  3           | 2011-09-21T00:00:00 | Yes on Prop. D, supported by Public Defender Jeff Adachi, Basic American Foods executive George Hume & business investor, Michael Moritz | 1336704 | 406    | Lee, Ed              | Oppose                 | The amounts listed on this webpage are different from the amounts reported by the committee on the Third Party Disclosure form because the amounts listed here reflect the cost allocated to the candidate(s) referenced above, whereas the amounts reported by the committee reflect the total cost of the communications. | 
|  4           | 2011-09-22T00:00:00 | City Residents Supporting Leland Yee for Mayor 2011                                                                                      | 1338191 | 89300  | Lee, Ed              | Oppose                 |                                                                                                                                                                                                                                                                                                                             | 
|  5           | 2011-09-22T00:00:00 | SEIU Local 1021 Independent Expenditure PAC                                                                                              | 1296949 | 10133  | Avalos, John         | Support                |                                                                                                                                                                                                                                                                                                                             | 
|  5           | 2011-09-22T00:00:00 | SEIU Local 1021 Independent Expenditure PAC                                                                                              | 1296949 | 10054  | Dufty, Bevan         | Support                |                                                                                                                                                                                                                                                                                                                             | 
|  5           | 2011-09-22T00:00:00 | SEIU Local 1021 Independent Expenditure PAC                                                                                              | 1296949 | 10133  | Yee, Leland          | Support                |                                                                                                                                                                                                                                                                                                                             | 
|  6           | 2011-09-23T00:00:00 | City Residents Supporting Leland Yee for Mayor 2011                                                                                      | 1338191 | 10000  | Lee, Ed              | Oppose                 |                                                                                                                                                                                                                                                                                                                             | 
|  7           | 2011-09-26T00:00:00 | San Franciscans for Jobs and Good Government, Supporting Ed Lee for Mayor 2011                                                           | 1340750 | 112456 | Lee, Ed              | Support                |                                                                                                                                                                                                                                                                                                                             | 
```