# MTA Customer Feedback Data: Beginning 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mta-customer-feedback-data-beginning-2014) |
| Metadata | [Link](https://data.ny.gov/api/views/tppa-s6t6) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/tppa-s6t6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/tppa-s6t6/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | tppa-s6t6 |
| Name | MTA Customer Feedback Data: Beginning 2014 |
| Attribution | Metropolitan Transportation Authority (MTA) |
| Category | Transportation |
| Tags | transit, customer service, commendation, complaint |
| Created | 2015-09-14T19:43:10Z |
| Publication Date | 2016-11-02T23:04:49Z |

## Description

This dataset is generated from the Customer Relationship Management System.  This system allows the public to correspond to the MTA about complaints or commendations in a variety of categories.  The dataset contains information about areas of customer service and how that service was rated.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag  | agency                    | Agency                    | text      | text        |
| Yes      | series tag  | commendation_or_complaint | Commendation or Complaint | text      | text        |
| Yes      | series tag  | subject_matter            | Subject Matter            | text      | text        |
| Yes      | series tag  | subject_detail            | Subject Detail            | text      | text        |
| Yes      | series tag  | issue_detail              | Issue Detail              | text      | text        |
| No       |             | year                      | Year                      | number    | number      |
| No       |             | quarter                   | Quarter                   | number    | number      |
| Yes      | series tag  | branch_line_route         | Branch/Line/Route         | text      | text        |
```

## Time Field

```ls
Value = year-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = year,quarter
```

## Data Commands

```ls
series e:tppa-s6t6 d:2015-04-01T00:00:00.000Z t:branch_line_route="No Value" t:commendation_or_complaint=Commendation t:agency="Long Island Rail Road" t:subject_matter=Employees t:issue_detail="Very Helpful/Friendly" t:subject_detail="CSR - Ambassador" m:row_number.tppa-s6t6=1

series e:tppa-s6t6 d:2015-04-01T00:00:00.000Z t:branch_line_route="Port Jefferson" t:commendation_or_complaint=Commendation t:agency="Long Island Rail Road" t:subject_matter=Employees t:issue_detail="Very Helpful/Friendly" t:subject_detail="CSR - Ambassador" m:row_number.tppa-s6t6=2

series e:tppa-s6t6 d:2015-01-01T00:00:00.000Z t:branch_line_route="No Value" t:commendation_or_complaint=Commendation t:agency="Long Island Rail Road" t:subject_matter=Employees t:subject_detail="CSR - Customer Service Office" m:row_number.tppa-s6t6=3
```

## Meta Commands

```ls
metric m:row_number.tppa-s6t6 p:long l:"Row Number"

entity e:tppa-s6t6 l:"MTA Customer Feedback Data: Beginning 2014" t:attribution="Metropolitan Transportation Authority (MTA)" t:url=https://data.ny.gov/api/views/tppa-s6t6

property e:tppa-s6t6 t:meta.view d:2017-09-25T07:23:05.393Z v:averageRating=0 v:name="MTA Customer Feedback Data: Beginning 2014" v:attribution="Metropolitan Transportation Authority (MTA)" v:id=tppa-s6t6 v:category=Transportation

property e:tppa-s6t6 t:meta.view.owner d:2017-09-25T07:23:05.393Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:tppa-s6t6 t:meta.view.tableauthor d:2017-09-25T07:23:05.393Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:tppa-s6t6 t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:23:05.393Z v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY" v:Publisher="State of New York"
```

## Top Records

```ls
| agency                | commendation_or_complaint | subject_matter | subject_detail                | issue_detail            | year | quarter | branch_line_route  | 
| ===================== | ========================= | ============== | ============================= | ======================= | ==== | ======= | ================== | 
| Long Island Rail Road | Commendation              | Employees      | CSR - Ambassador              | Very Helpful/Friendly   | 2015 | 2       | No Value           | 
| Long Island Rail Road | Commendation              | Employees      | CSR - Ambassador              | Very Helpful/Friendly   | 2015 | 2       | Port Jefferson     | 
| Long Island Rail Road | Commendation              | Employees      | CSR - Customer Service Office |                         | 2015 | 1       | No Value           | 
| Long Island Rail Road | Commendation              | Employees      | CSR - Customer Service Office | Other                   | 2015 | 2       | Far Rockaway       | 
| Long Island Rail Road | Commendation              | Employees      | CSR - Customer Service Office | Very Helpful / Friendly | 2015 | 2       | No Value           | 
| Long Island Rail Road | Commendation              | Employees      | CSR - Customer Service Office | Very Helpful / Friendly | 2014 | 3       | No Value           | 
| Long Island Rail Road | Commendation              | Employees      | CSR - Customer Service Office | Very Helpful / Friendly | 2015 | 1       | No Value           | 
| Long Island Rail Road | Commendation              | Employees      | CSR - Information Booth       | Very Helpful / Friendly | 2015 | 1       | City Terminal Zone | 
| Long Island Rail Road | Commendation              | Employees      | CSR - Telephone               | Very Helpful / Friendly | 2014 | 3       | No Value           | 
| Long Island Rail Road | Commendation              | Employees      | CSR - Telephone               | Very Helpful / Friendly | 2015 | 1       | Ronkonkoma         | 
```