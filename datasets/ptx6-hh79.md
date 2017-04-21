# State Inspector General Public Reports and Press Releases: Beginning 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-inspector-general-public-reports-and-press-releases-beginning-2006) |
| Metadata | [Link](https://data.ny.gov/api/views/ptx6-hh79) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ptx6-hh79/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ptx6-hh79/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ptx6-hh79 |
| Name | State Inspector General Public Reports and Press Releases: Beginning 2006 |
| Attribution | Office of the State Inspector General |
| Category | Transparency |
| Tags | ig, inspector general, waste, fraud, abuse, arrest, findings, integrity |
| Created | 2013-04-17T16:37:05Z |
| Publication Date | 2016-04-25T22:01:12Z |

## Description

All Press Releases and Public Reports starting Jan-2006 through present.

## Columns

```ls
| Included | Schema Type | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | =========== | ============================= | ============================= | ============= | ============= |
| No       |             | year                          | Year                          | number        | number        |
| Yes      | series tag  | report_or_press_release_link  | Report or Press Release Link  | url           | url           |
| Yes      | series tag  | report_or_press_release_title | Report or Press Release Title | text          | text          |
| Yes      | time        | date_published                | Date Published                | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_published
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:ptx6-hh79 d:2006-04-17T00:00:00.000Z t:report_or_press_release_title="Arrests Break Vehicle Inspection Sticker Theft Ring" m:row_number.ptx6-hh79=1

series e:ptx6-hh79 d:2006-05-18T00:00:00.000Z t:report_or_press_release_title="Investigation of a Complaint of Improper Conduct by an Employee of the New York State Division of Human Rights" t:report_or_press_release_link=https://ig.ny.gov/sites/default/files/pdfs/Investigation%20of%20Complaint%20of%20Improper%20Conduct.pdf m:row_number.ptx6-hh79=2

series e:ptx6-hh79 d:2006-05-24T00:00:00.000Z t:report_or_press_release_title="Investigation of a Complaint of Misuse of State Resources by the Director of the Governor's Office for Small Cities" t:report_or_press_release_link=https://ig.ny.gov/sites/default/files/pdfs/Investigation%20of%20a%20Complaint%20of%20Misuse%20of%20State%20Resources.pdf m:row_number.ptx6-hh79=3
```

## Meta Commands

```ls
metric m:row_number.ptx6-hh79 p:long l:"Row Number"

entity e:ptx6-hh79 l:"State Inspector General Public Reports and Press Releases: Beginning 2006" t:attribution="Office of the State Inspector General" t:url=https://data.ny.gov/api/views/ptx6-hh79

property e:ptx6-hh79 t:meta.view v:id=ptx6-hh79 v:category=Transparency v:averageRating=0 v:name="State Inspector General Public Reports and Press Releases: Beginning 2006" v:attribution="Office of the State Inspector General"

property e:ptx6-hh79 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ptx6-hh79 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ptx6-hh79 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | report_or_press_release_link                                                                                                                                 | report_or_press_release_title                                                                                       | date_published      | 
| ==== | ============================================================================================================================================================ | =================================================================================================================== | =================== | 
| 2006 | [null, null]                                                                                                                                                 | Arrests Break Vehicle Inspection Sticker Theft Ring                                                                 | 2006-04-17T00:00:00 | 
| 2006 | [https://ig.ny.gov/sites/default/files/pdfs/Investigation%20of%20Complaint%20of%20Improper%20Conduct.pdf, null]                                              | Investigation of a Complaint of Improper Conduct by an Employee of the New York State Division of Human Rights      | 2006-05-18T00:00:00 | 
| 2006 | [https://ig.ny.gov/sites/default/files/pdfs/Investigation%20of%20a%20Complaint%20of%20Misuse%20of%20State%20Resources.pdf, null]                             | Investigation of a Complaint of Misuse of State Resources by the Director of the Governor's Office for Small Cities | 2006-05-24T00:00:00 | 
| 2006 | [https://ig.ny.gov/sites/default/files/pdfs/Investigation%20of%20a%20Complaint%20of%20Abuse%20of%20Authority.pdf, null]                                      | Investigation of a Complaint of Abuse of Authority by Employees of the Department of Taxation and Finance           | 2006-05-30T00:00:00 | 
| 2006 | [null, null]                                                                                                                                                 | Former Montrose Veterans Home Employees Plead Guilty in Fraudulent Overtime Scam                                    | 2006-06-05T00:00:00 | 
| 2006 | [https://ig.ny.gov/sites/default/files/pdfs/Investigation%20of%20Alleged%20Theft%20and%20Other%20Misconduct.pdf, null]                                       | " Investigation of Alleged Theft by Employees of the Office of Parks, Recreation and Historic Preservation"         | 2006-09-20T00:00:00 | 
| 2006 | [null, null]                                                                                                                                                 | State Housing Official Pleads Guilty in Federal Court to Fraud and Theft of Government Funds                        | 2006-09-28T00:00:00 | 
| 2006 | [https://ig.ny.gov/sites/default/files/pdfs/Investigation%20of%20Alleged%20Insurance%20Fraud%20against%20the%20NYS%20DOT.pdf, null]                          | Investigation of Alleged Insurance Fraud Against the NYS Department of Transportation                               | 2006-10-05T00:00:00 | 
| 2006 | [null, null]                                                                                                                                                 | Investigation Results in Theft Conviction of Oneida County DMV Employee                                             | 2006-11-07T00:00:00 | 
| 2006 | [https://ig.ny.gov/sites/default/files/pdfs/Investigations%20of%20Allegations%20of%20Misconduct%20by%20Capt%20Terrance%20Revella%20of%20NYS%20DEC.pdf, null] | Investigation of Allegations of Misconduct by Capt Terrance Revella of NYS DEC                                      | 2006-11-17T00:00:00 | 
```