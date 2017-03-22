# Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-summary-of-third-party-disclosure-forms-regarding-san-francisco-candidat-) |
| Metadata | [Link](https://data.sfgov.org/api/views/7i7v-m2wn) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/7i7v-m2wn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/7i7v-m2wn/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 7i7v-m2wn |
| Name | Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2016 |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | campaign finance dashboards 2016 |
| Created | 2016-08-18T20:50:38Z |
| Publication Date | 2016-08-18T21:00:00Z |
| Rows Updated | 2017-03-22T00:30:25Z |

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | ============== | ================================ | ================================ | ============= | ============= |
| Yes      | series tag     | form_type                        | Form Type                        | text          | text          |
| Yes      | series tag     | report_number                    | Report Number                    | text          | text          |
| Yes      | time           | date_filed                       | Date Filed                       | calendar_date | calendar_date |
| Yes      | series tag     | filer                            | Filer                            | text          | text          |
| Yes      | series tag     | filer_id                         | Filer Id                         | text          | text          |
| Yes      | numeric metric | amount                           | Amount                           | money         | money         |
| Yes      | series tag     | candidate_identified             | Candidate Identified             | text          | text          |
| Yes      | series tag     | district                         | District                         | text          | text          |
| Yes      | series tag     | support_oppose_or_neutral        | Support Oppose or Neutral        | text          | text          |
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
series e:7i7v-m2wn d:2016-08-26T00:00:00.000Z t:filer="San Franciscans for a City that Works" t:report_number=VA-G16-013 t:form_type=496 t:candidate_identified="Joshua Arce" t:support_oppose_or_neutral=Support t:filer_id=1384192 t:notes="Web Ads" t:district="Board of Supervisors District 9" m:amount=5000

series e:7i7v-m2wn d:2016-08-18T00:00:00.000Z t:filer="San Franciscans for a City that Works" t:report_number=VA-G16-008 t:form_type=496 t:candidate_identified="Marjan Philhour" t:support_oppose_or_neutral=Support t:filer_id=1384192 t:notes="Web Ads" t:district="Board of Supervisors District 1" m:amount=5000

series e:7i7v-m2wn d:2016-08-26T00:00:00.000Z t:filer="San Franciscans for a City that Works" t:report_number=VA-G16-012 t:form_type=496 t:candidate_identified="Marjan Philhour" t:support_oppose_or_neutral=Support t:filer_id=1384192 t:notes="Web Ads" t:district="Board of Supervisors District 1" m:amount=5000
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:7i7v-m2wn l:"Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2016" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/7i7v-m2wn

property e:7i7v-m2wn t:meta.view v:id=7i7v-m2wn v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2016" v:attribution="San Francisco Ethics Commission"

property e:7i7v-m2wn t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:7i7v-m2wn t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:7i7v-m2wn t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```