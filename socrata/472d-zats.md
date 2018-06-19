# Total Property Insurance Premiums Written Annually in New York: Beginning 1998

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-property-insurance-premiums-written-annually-in-new-york-beginning-1998) |
| Metadata | [Link](https://data.ny.gov/api/views/472d-zats) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/472d-zats/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/472d-zats/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 472d-zats |
| Name | Total Property Insurance Premiums Written Annually in New York: Beginning 1998 |
| Attribution | Insurance Division - Property Bureau |
| Category | Government & Finance |
| Tags | insurance, property, casualty, licensed |
| Created | 2013-04-15T15:10:45Z |
| Publication Date | 2016-11-28T23:20:11Z |

## Description

Listings of total direct written premiums for insurers authorized to write Property & Casualty lines of business in New York State.  These insurers are required under Article 41 of the New York Insurance Law to meet minimum financial security requirements.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | naic_code            | NAIC Code            | text      | number      |
| Yes      | series tag     | company_name         | Company Name         | text      | text        |
| Yes      | time           | calendar_year_year   | Calendar Year        | number    | number      |
| Yes      | numeric metric | net_premiums_written | Net Premiums Written | money     | money       |
```

## Time Field

```ls
Value = calendar_year_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:472d-zats d:2015-01-01T00:00:00.000Z t:company_name="21st Century Assurance Company" t:naic_code=44245 m:net_premiums_written=0

series e:472d-zats d:2015-01-01T00:00:00.000Z t:company_name="21st Century Casualty Company" t:naic_code=36404 m:net_premiums_written=0

series e:472d-zats d:2015-01-01T00:00:00.000Z t:company_name="21st Century Centennial Insurance Company" t:naic_code=34789 m:net_premiums_written=15962474
```

## Meta Commands

```ls
metric m:net_premiums_written p:double l:"Net Premiums Written" t:dataTypeName=money

entity e:472d-zats l:"Total Property Insurance Premiums Written Annually in New York: Beginning 1998" t:attribution="Insurance Division - Property Bureau" t:url=https://data.ny.gov/api/views/472d-zats

property e:472d-zats t:meta.view v:id=472d-zats v:category="Government & Finance" v:attributionLink=http://www.dfs.ny.gov v:averageRating=0 v:name="Total Property Insurance Premiums Written Annually in New York: Beginning 1998" v:attribution="Insurance Division - Property Bureau"

property e:472d-zats t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:472d-zats t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:472d-zats t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| naic_code | company_name                                 | calendar_year_year | net_premiums_written | 
| ========= | ============================================ | ================== | ==================== | 
| 44245     | 21st Century Assurance Company               | 2015               | 0.00                 | 
| 36404     | 21st Century Casualty Company                | 2015               | 0.00                 | 
| 34789     | 21st Century Centennial Insurance Company    | 2015               | 15962474.00          | 
| 43974     | 21st Century Indemnity Insurance Company     | 2015               | 4592157.00           | 
| 12963     | 21st Century Insurance Company               | 2015               | 0.00                 | 
| 36587     | 21st Century National Insurance Company      | 2015               | 17908577.00          | 
| 32220     | 21st Century North America Insurance Company | 2015               | 14984616.00          | 
| 22225     | 21st Century Preferred Insurance Company     | 2015               | 843756.00            | 
| 20796     | 21st Century Premier Insurance Company       | 2015               | 3253610.00           | 
| 23833     | 21st Century Security Insurance Company      | 2015               | 4843216.00           | 
```