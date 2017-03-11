# Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2016

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/7i7v-m2wn/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/campaign-finance-summary-of-third-party-disclosure-forms-regarding-san-francisco-candidat-)
* [Metadata URL](https://data.sfgov.org/api/views/7i7v-m2wn)
* Id = 7i7v-m2wn
* Name = Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2016
* Attribution = San Francisco Ethics Commission
* [Attribution Link](http://www.sfethics.org)
* Category = City Management and Ethics
* Tags = [campaign finance dashboards 2016]
* Created = 2016-08-18T20:50:38Z
* Publication Date = 2016-08-18T21:00:00Z
* Rows Updated = 2017-03-07T01:30:29Z

## Description



## Columns

```ls
| Name                             | Field Name                       | Data Type     | Render Type   | Schema Type    | Included | 
| ================================ | ================================ | ============= | ============= | ============== | ======== | 
| Form Type                        | form_type                        | number        | text          | numeric metric | Yes      | 
| Report Number                    | report_number                    | text          | text          | series tag     | Yes      | 
| Date Filed                       | date_filed                       | calendar_date | calendar_date | time           | Yes      | 
| Filer                            | filer                            | text          | text          | series tag     | Yes      | 
| Filer Id                         | filer_id                         | text          | text          | series tag     | Yes      | 
| Amount                           | amount                           | money         | money         | numeric metric | Yes      | 
| Candidate Identified             | candidate_identified             | text          | text          | series tag     | Yes      | 
| District                         | district                         | text          | text          | series tag     | Yes      | 
| Support Oppose or Neutral        | support_oppose_or_neutral        | text          | text          | series tag     | Yes      | 
| Start Date of Distribution       | start_date_of_distribution       | calendar_date | calendar_date |                | No       | 
| End or Only Date of Distribution | end_or_only_date_of_distribution | calendar_date | calendar_date |                | No       | 
| Notes                            | notes                            | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = end_or_only_date_of_distribution,start_date_of_distribution
Annotation Fields = 
```

## Data Commands

```ls
series e:7i7v-m2wn d:2016-08-26T00:00:00.000Z t:filer="San Franciscans for a City that Works" t:report_number=VA-G16-013 t:candidate_identified="Joshua Arce" t:support_oppose_or_neutral=Support t:filer_id=1384192 t:notes="Web Ads" t:district="Board of Supervisors District 9" m:amount=5000 m:form_type=496

series e:7i7v-m2wn d:2016-08-18T00:00:00.000Z t:filer="San Franciscans for a City that Works" t:report_number=VA-G16-008 t:candidate_identified="Marjan Philhour" t:support_oppose_or_neutral=Support t:filer_id=1384192 t:notes="Web Ads" t:district="Board of Supervisors District 1" m:amount=5000 m:form_type=496

series e:7i7v-m2wn d:2016-08-26T00:00:00.000Z t:filer="San Franciscans for a City that Works" t:report_number=VA-G16-012 t:candidate_identified="Marjan Philhour" t:support_oppose_or_neutral=Support t:filer_id=1384192 t:notes="Web Ads" t:district="Board of Supervisors District 1" m:amount=5000 m:form_type=496
```

## Meta Commands

```ls
metric m:form_type p:integer l:"Form Type" t:dataTypeName=number

entity e:7i7v-m2wn l:"Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2016" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/7i7v-m2wn

property e:7i7v-m2wn t:meta.view d:2017-03-07T19:13:45.288Z v:id=7i7v-m2wn v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2016" v:attribution="San Francisco Ethics Commission"

property e:7i7v-m2wn t:meta.view.license d:2017-03-07T19:13:45.288Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:7i7v-m2wn t:meta.view.owner d:2017-03-07T19:13:45.288Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"

property e:7i7v-m2wn t:meta.view.tableauthor d:2017-03-07T19:13:45.288Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```