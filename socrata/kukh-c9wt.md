# Annual Taxpayer Location Address List 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/annual-taxpayer-location-address-list-2014) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/kukh-c9wt) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/kukh-c9wt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/kukh-c9wt/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | kukh-c9wt |
| Name | Annual Taxpayer Location Address List 2014 |
| Attribution | City of Chicago |
| Category | Community & Economic Development |
| Created | 2015-02-27T05:18:30Z |
| Publication Date | 2016-06-16T21:43:53Z |

## Description

List of businesses registered with the State of Illinois that may levy retail sales taxes in the Chicago area.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | illinois_business_tax_number | ILLINOIS BUSINESS TAX NUMBER | text      | text        |
| Yes      | series tag     | sequence_number              | SEQUENCE NUMBER              | text      | text        |
| Yes      | series tag     | type_of_filer                | TYPE OF FILER                | text      | text        |
| Yes      | numeric metric | sic                          | SIC                          | number    | text        |
| Yes      | series tag     | dba_name                     | DBA NAME                     | text      | text        |
| Yes      | series tag     | owning_entity                | OWNING ENTITY                | text      | text        |
| No       |                | address                      | ADDRESS                      | text      | text        |
| No       |                | address_secondary            | ADDRESS SECONDARY            | text      | text        |
| Yes      | series tag     | city                         | CITY                         | text      | text        |
| Yes      | series tag     | state                        | STATE                        | text      | text        |
| Yes      | series tag     | zip                          | ZIP                          | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address,address_secondary
```

## Data Commands

```ls
series e:kukh-c9wt d:2014-01-01T00:00:00.000Z t:sequence_number=0 t:type_of_filer=CL t:illinois_business_tax_number=4016-2311 t:dba_name="STACI DANCONALEVY" m:sic=5944

series e:kukh-c9wt d:2014-01-01T00:00:00.000Z t:sequence_number=0 t:type_of_filer=CL t:illinois_business_tax_number=4071-6112 t:dba_name="MARGARITA PORTILLOSERRANO" m:sic=5812

series e:kukh-c9wt d:2014-01-01T00:00:00.000Z t:sequence_number=0 t:type_of_filer=CL t:illinois_business_tax_number=4105-0061 t:dba_name="DENNIS CERRITO" m:sic=5942
```

## Meta Commands

```ls
metric m:sic p:integer l:SIC d:"Standard Industrial Classification code indicated by the business: https://www.osha.gov/pls/imis/sicsearch.html. SIC may not comprehensively describe the operation of the business." t:dataTypeName=number

entity e:kukh-c9wt l:"Annual Taxpayer Location Address List 2014" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/kukh-c9wt

property e:kukh-c9wt t:meta.view v:id=kukh-c9wt v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Annual Taxpayer Location Address List 2014" v:attribution="City of Chicago"

property e:kukh-c9wt t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:kukh-c9wt t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| illinois_business_tax_number | sequence_number | type_of_filer | sic  | dba_name                     | owning_entity | address                      | address_secondary | city        | state | zip        | 
| ============================ | =============== | ============= | ==== | ============================ | ============= | ============================ | ================= | =========== | ===== | ========== | 
| 4016-2311                    | 0               | CL            | 5944 | STACI DANCONALEVY            |               |                              |                   |             |       |            | 
| 4071-6112                    | 0               | CL            | 5812 | MARGARITA PORTILLOSERRANO    |               |                              |                   |             |       |            | 
| 4105-0061                    | 0               | CL            | 5942 | DENNIS CERRITO               |               |                              |                   |             |       |            | 
| 0109-7301                    | 1               | PL            | 5813 | OC SANDERS                   |               | 700 W 59TH ST                |                   | CHICAGO     | IL    | 60621      | 
| 0213-1714                    | 0               | CL            | 5149 | DOMTAR INDUSTRIES INC        |               | 395 DE MAISONNEUVE BLVD WEST |                   | MONTREAL    | QC    | H3A1L6     | 
| 2429-2028                    | 0               | CL            | 5999 | KAMP GEORGE INC              |               | PO BOX 231                   |                   | ROME        | IL    | 61562-0231 | 
| 2499-0132                    | 1               | CL            | 5045 | FINANCIAL MODELS CO LTD      |               | 5255 ORBITOR DRIVE           |                   | MISSISSUGA  | ON    | L4W5M6     | 
| 2658-4069                    | 0               | CL            | 5734 | EVANS CONSOLES INC           |               | 1616 27TH AVE NE             |                   | CALGARY     | AB    | T2E8W4     | 
| 2833-1303                    | 1               | CL            | 5932 | RICHARD RUMI                 |               | 55 WOODLAWN AVE              |                   | MISSISSAUGA | ON    | L6G3K7     | 
| 2866-5554                    | 0               | CL            | 7929 | CIRQUE DU SOLEIL AMERICA INC |               | 8400 2ND AVE                 |                   | MONTREAL    | QC    | H1Z4M6     | 
```