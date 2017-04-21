# Data Requestsfor Drugs Data 05082012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/data-requestsfor-drugs-data-05082012-e2ceb) |
| Metadata | [Link](https://data.illinois.gov/api/views/py8c-kjud) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/py8c-kjud/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/py8c-kjud/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | py8c-kjud |
| Name | Data Requestsfor Drugs Data 05082012 |
| Category | Health-Medicaid |
| Tags | medicaid |
| Created | 2012-05-09T19:48:13Z |
| Publication Date | 2012-05-09T19:49:34Z |

## Columns

```ls
| Included | Schema Type | Field Name               | Name                       | Data Type     | Render Type   |
| ======== | =========== | ======================== | ========================== | ============= | ============= |
| No       |             | _                        | #                          | number        | number        |
| Yes      | series tag  | of_original_data_request | # of Original Data Request | text          | text          |
| Yes      | series tag  | organization_name        | Organization Name          | text          | text          |
| Yes      | series tag  | data_requested           | Data Requested             | text          | text          |
| Yes      | series tag  | notes                    | Notes                      | text          | text          |
| Yes      | time        | date_requested           | Date Requested             | calendar_date | calendar_date |
| No       |             | links_sent               | Links Sent                 | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_requested
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = _,links_sent
```

## Data Commands

```ls
series e:py8c-kjud d:2012-05-09T12:48:14.000Z t:data_requested="Data Requested" t:of_original_data_request="# of Original Data Request" t:notes=Notes t:organization_name="Organization Name" m:row_number.py8c-kjud=1

series e:py8c-kjud d:2012-04-13T00:00:00.000Z t:data_requested="Developmentally Disabled persons (DDM and DDL)" t:of_original_data_request=29 t:notes="hold -- do not pull yet" t:organization_name="Dupage County" m:row_number.py8c-kjud=2

series e:py8c-kjud d:2012-04-13T00:00:00.000Z t:data_requested="Dupage County - County Code 30" t:of_original_data_request=30 t:notes="hold -- do not pull yet" t:organization_name="Dupage County" m:row_number.py8c-kjud=3
```

## Meta Commands

```ls
metric m:row_number.py8c-kjud p:long l:"Row Number"

entity e:py8c-kjud l:"Data Requestsfor Drugs Data 05082012" t:url=https://data.illinois.gov/api/views/py8c-kjud

property e:py8c-kjud t:meta.view v:id=py8c-kjud v:category=Health-Medicaid v:averageRating=0 v:name="Data Requestsfor Drugs Data 05082012"

property e:py8c-kjud t:meta.view.owner v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:displayName="HFS - Administrator"

property e:py8c-kjud t:meta.view.tableauthor v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:roleName=publisher v:displayName="HFS - Administrator"
```

## Top Records

```ls
| _ | of_original_data_request   | organization_name             | data_requested                                                                                                                                                                                                                                                                                                                                                           | notes                   | date_requested      | links_sent          | 
| = | ========================== | ============================= | ======================================================================================================================================================================================================================================================================================================================================================================== | ======================= | =================== | =================== | 
|   | # of Original Data Request | Organization Name             | Data Requested                                                                                                                                                                                                                                                                                                                                                           | Notes                   |                     |                     | 
| 1 | 29                         | Dupage County                 | Developmentally Disabled persons (DDM and DDL)                                                                                                                                                                                                                                                                                                                           | hold -- do not pull yet | 2012-04-13T00:00:00 | 2012-04-27T00:00:00 | 
| 1 | 30                         | Dupage County                 | Dupage County - County Code 30                                                                                                                                                                                                                                                                                                                                           | hold -- do not pull yet | 2012-04-13T00:00:00 | 2012-04-27T00:00:00 | 
| 2 | 54                         | KishHealth                    | 60115, 60112, 60178, 60135, 60145, 60146, 60109, 60140, 60151, 60520, 60550, 60556, 60150, 61068, and 60111                                                                                                                                                                                                                                                              |                         | 2012-04-13T00:00:00 | 2012-04-27T00:00:00 | 
| 2 | 55                         | KishHealth                    | 60531, 60545, 60548, 60552, 60511, 60512, 60518, 60541, 60549, 60551, and 60560                                                                                                                                                                                                                                                                                          |                         | 2012-04-13T00:00:00 | 2012-04-27T00:00:00 | 
| 3 | 58                         | Illinois Hospital Association | Crawford (025), Richland (088), Mason (068), Hamilton (041), Shelby (094), Vermilion (100), Washington (103), McDonough (070), Whiteside (106), Wayne (104), Schuyler (092), Grundy (040), Saline (090), Henry (045), Jo Daviess (051), Macoupin (064), Bureau (015), Fulton (037), Christian (020), Jersey (050), LaSalle (058), Randolph (087), Ford (035), Bond (012) |                         | 2012-04-13T00:00:00 | 2012-04-27T00:00:00 | 
| 3 | 59                         | Illinois Hospital Association | Whole state minus (Cook [200], Kane [053], Kankakee [054], Kendall [055], Lake [057], Will [107], Dupage [030], Ogle [079], Boone [013], Mercer [074], Sangamon [091], Madison [065], St. Clair [096], and invalid [001])                                                                                                                                                |                         | 2012-04-13T00:00:00 | 2012-04-27T00:00:00 | 
| 4 | 60                         | UIHHS                         | entire state                                                                                                                                                                                                                                                                                                                                                             |                         | 2012-04-16T00:00:00 | 2012-04-27T00:00:00 | 
| 4 | 61                         | UIHHS                         | see second sheet for list of 103 zip codes                                                                                                                                                                                                                                                                                                                               |                         | 2012-04-16T00:00:00 | 2012-04-27T00:00:00 | 
| 5 | 90                         | Ingalls                       | zip codes                                                                                                                                                                                                                                                                                                                                                                |                         | 2012-04-17T00:00:00 | 2012-04-27T00:00:00 | 
```