# MTA Customer Feedback Data: Beginning 2014

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/tppa-s6t6/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/mta-customer-feedback-data-beginning-2014)
* [Metadata URL](https://data.ny.gov/api/views/tppa-s6t6)
* Id = tppa-s6t6
* Name = MTA Customer Feedback Data: Beginning 2014
* Attribution = Metropolitan Transportation Authority (MTA)
* Category = Transportation
* Tags = [transit, customer service, commendation, complaint]
* Created = 2015-09-14T19:43:10Z
* Publication Date = 2016-11-02T23:04:49Z
* Rows Updated = 2016-11-02T23:04:44Z

## Description

This dataset is generated from the Customer Relationship Management System.  This system allows the public to correspond to the MTA about complaints or commendations in a variety of categories.  The dataset contains information about areas of customer service and how that service was rated.

## Columns

```ls
| Name                      | Field Name                | Data Type | Render Type | Schema Type    | Included | 
| ========================= | ========================= | ========= | =========== | ============== | ======== | 
| Agency                    | agency                    | text      | text        | series tag     | Yes      | 
| Commendation or Complaint | commendation_or_complaint | text      | text        | series tag     | Yes      | 
| Subject Matter            | subject_matter            | text      | text        | series tag     | Yes      | 
| Subject Detail            | subject_detail            | text      | text        | series tag     | Yes      | 
| Issue Detail              | issue_detail              | text      | text        | series tag     | Yes      | 
| Year                      | year                      | number    | number      | time           | Yes      | 
| Quarter                   | quarter                   | number    | number      | numeric metric | Yes      | 
| Branch/Line/Route         | branch_line_route         | text      | text        | series tag     | Yes      | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
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
series e:tppa-s6t6 d:2015-01-01T00:00:00.000Z t:subject_detail="CSR - Ambassador" t:commendation_or_complaint=Commendation t:branch_line_route="No Value" t:subject_matter=Employees t:agency="Long Island Rail Road" t:issue_detail="Very Helpful/Friendly" m:quarter=2

series e:tppa-s6t6 d:2015-01-01T00:00:00.000Z t:subject_detail="CSR - Ambassador" t:commendation_or_complaint=Commendation t:branch_line_route="Port Jefferson" t:subject_matter=Employees t:agency="Long Island Rail Road" t:issue_detail="Very Helpful/Friendly" m:quarter=2

series e:tppa-s6t6 d:2015-01-01T00:00:00.000Z t:subject_detail="CSR - Customer Service Office" t:commendation_or_complaint=Commendation t:branch_line_route="No Value" t:subject_matter=Employees t:agency="Long Island Rail Road" m:quarter=1
```

## Meta Commands

```ls
metric m:quarter p:integer l:Quarter d:"The quarter in which the complaint or commendation was entered. 1 = Jan - Mar; 2 = Apr - Jun; 3 = Jul - Sep; 4 = Oct - Dec." t:dataTypeName=number

entity e:tppa-s6t6 l:"MTA Customer Feedback Data: Beginning 2014" t:attribution="Metropolitan Transportation Authority (MTA)" t:url=https://data.ny.gov/api/views/tppa-s6t6

property e:tppa-s6t6 t:meta.view d:2017-03-08T00:17:07.623Z v:id=tppa-s6t6 v:category=Transportation v:averageRating=0 v:name="MTA Customer Feedback Data: Beginning 2014" v:attribution="Metropolitan Transportation Authority (MTA)"

property e:tppa-s6t6 t:meta.view.owner d:2017-03-08T00:17:07.623Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:tppa-s6t6 t:meta.view.tableauthor d:2017-03-08T00:17:07.623Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:tppa-s6t6 t:meta.view.metadata.custom_fields.common_core d:2017-03-08T00:17:07.623Z v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```