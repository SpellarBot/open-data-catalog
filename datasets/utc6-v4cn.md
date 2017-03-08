# Schedule of Debt for Local Development Corporations

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/utc6-v4cn/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/schedule-of-debt-for-local-development-corporations)
* [Metadata URL](https://data.ny.gov/api/views/utc6-v4cn)
* Id = utc6-v4cn
* Name = Schedule of Debt for Local Development Corporations
* Attribution = Individual Local Development Corporations submitted to the Authorities Budget Office
* [Attribution Link](http://www.abo.ny.gov/)
* Category = Transparency
* Tags = [ldc]
* Created = 2015-02-23T19:35:45Z
* Publication Date = 2016-11-04T14:31:39Z
* Rows Updated = 2016-11-03T22:04:54Z

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include a schedule of the authorities? debt.  The dataset consists of schedule of debt data reported by Local Development Corporations beginning with fiscal years ending in 2011.

## Columns

```ls
| Name                 | Field Name           | Data Type     | Render Type   | Schema Type    | Included | 
| ==================== | ==================== | ============= | ============= | ============== | ======== | 
| Authority Name       | authority_name       | text          | text          | series tag     | Yes      | 
| Fiscal Year End Date | fiscal_year_end_date | calendar_date | calendar_date | time           | Yes      | 
| Has Outstanding Debt | has_outstanding_debt | number        | text          | numeric metric | Yes      | 
| Type Of Debt         | type_of_debt         | text          | text          | series tag     | Yes      | 
| Debt Program         | debt_program         | text          | text          | series tag     | Yes      | 
| Begin Amount Total   | begin_amount_total   | money         | money         | numeric metric | Yes      | 
| New Debt Issuance    | new_debt_issuance    | money         | money         | numeric metric | Yes      | 
| Amount Retired       | amount_retired       | money         | money         | numeric metric | Yes      | 
| End Amount Total     | end_amount_total     | money         | money         | numeric metric | Yes      | 
```

## Time Field

```ls
Value = fiscal_year_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
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
series e:utc6-v4cn d:2011-12-31T00:00:00.000Z t:authority_name="ATC of Buffalo and Erie County, Inc." t:type_of_debt="Authority Debt - Other" t:debt_program="Other Non-State Funded" m:end_amount_total=0 m:begin_amount_total=4588557 m:new_debt_issuance=0 m:amount_retired=4588557

series e:utc6-v4cn d:2014-12-31T00:00:00.000Z t:authority_name="Albany County Capital Resource Corporation" t:type_of_debt="Conduit Debt" t:debt_program="Conduit Debt" m:end_amount_total=87953506 m:begin_amount_total=0 m:new_debt_issuance=88000000 m:amount_retired=46494

series e:utc6-v4cn d:2015-12-31T00:00:00.000Z t:authority_name="Albany County Capital Resource Corporation" t:type_of_debt="Conduit Debt" t:debt_program="Conduit Debt" m:end_amount_total=178592467 m:begin_amount_total=87953506 m:new_debt_issuance=90638961 m:amount_retired=0
```

## Meta Commands

```ls
entity e:utc6-v4cn l:"Schedule of Debt for Local Development Corporations" t:attribution="Individual Local Development Corporations submitted to the Authorities Budget Office" t:url=https://data.ny.gov/api/views/utc6-v4cn

property e:utc6-v4cn t:meta.view d:2017-03-07T20:08:06.874Z v:id=utc6-v4cn v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Schedule of Debt for Local Development Corporations" v:attribution="Individual Local Development Corporations submitted to the Authorities Budget Office"

property e:utc6-v4cn t:meta.view.owner d:2017-03-07T20:08:06.874Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:utc6-v4cn t:meta.view.tableauthor d:2017-03-07T20:08:06.874Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:utc6-v4cn t:meta.view.metadata.custom_fields.common_core d:2017-03-07T20:08:06.874Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```