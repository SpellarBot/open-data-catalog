# Grand Central Partnership (GCP) Business Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grand-central-partnership-gcp-business-directory-e6ce1) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/k26i-s5bd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/k26i-s5bd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/k26i-s5bd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | k26i-s5bd |
| Name | Grand Central Partnership (GCP) Business Directory |
| Attribution | Grand Central Partnership (GCP) |
| Category | Business |
| Tags | grand central partnership, business, directory, address |
| Created | 2011-10-11T04:13:23Z |
| Publication Date | 2013-06-21T19:28:28Z |

## Description

Businesses in the GCP district

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | business_name  | Business Name  | text      | text        |
| Yes      | series tag  | industry_group | Industry Group | text      | text        |
| Yes      | series tag  | type           | Type           | text      | text        |
| Yes      | series tag  | telephone      | Telephone      | text      | text        |
| Yes      | series tag  | cross_streets  | Cross Streets  | text      | text        |
| Yes      | series tag  | zip_code       | Zip Code       | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:k26i-s5bd d:2011-10-10T21:13:31.000Z t:business_name=Cibo t:cross_streets="between 41st - 42nd St" t:zip_code=10017 t:industry_group="Food & Drink" t:type=Restaurant t:telephone=212-681-1616 m:row_number.k26i-s5bd=1

series e:k26i-s5bd d:2011-10-10T21:13:31.000Z t:business_name="Dor L' Dor" t:cross_streets="between 41st - 42nd St" t:zip_code=10017 t:industry_group=AA&F t:type="Women's Apparel" m:row_number.k26i-s5bd=2

series e:k26i-s5bd d:2011-10-10T21:13:31.000Z t:business_name="Verizon Wireless (Metro Wireless)" t:cross_streets="between 41st - 42nd St" t:zip_code=10017 t:industry_group="Misc. Retail" t:type="Elec. & Telecom." m:row_number.k26i-s5bd=3
```

## Meta Commands

```ls
metric m:row_number.k26i-s5bd p:long l:"Row Number"

entity e:k26i-s5bd l:"Grand Central Partnership (GCP) Business Directory" t:attribution="Grand Central Partnership (GCP)" t:url=https://data.cityofnewyork.us/api/views/k26i-s5bd

property e:k26i-s5bd t:meta.view v:id=k26i-s5bd v:category=Business v:averageRating=0 v:name="Grand Central Partnership (GCP) Business Directory" v:attribution="Grand Central Partnership (GCP)"

property e:k26i-s5bd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:k26i-s5bd t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | business_name                     | industry_group     | type                | telephone    | cross_streets          | zip_code | 
| =========== | ================================= | ================== | =================== | ============ | ====================== | ======== | 
| 1318281211  | Cibo                              | Food & Drink       | Restaurant          | 212-681-1616 | between 41st - 42nd St | 10017    | 
| 1318281211  | Dor L' Dor                        | AA&F               | Women's Apparel     |              | between 41st - 42nd St | 10017    | 
| 1318281211  | Verizon Wireless (Metro Wireless) | Misc. Retail       | Elec. & Telecom.    |              | between 41st - 42nd St | 10017    | 
| 1318281211  | Sussex Wines & Spirits            | Food & Drink       | Wine & Liquor Store | 212-867-5838 | between 41st - 42nd St | 10017    | 
| 1318281211  | Innovation Luggage                | Misc. Retail       | Luggage             | 212-599-2998 | between 41st - 42nd St | 10017    | 
| 1318281211  | Dean's Family Style Restaurant    | Food & Drink       | Restaurant          | 212-878-9600 | between 42nd - 43rd St | 10017    | 
| 1318281211  | Chase                             | Financial Services | Full-Service Branch | 212-661-7519 | between 42nd - 43rd St | 10017    | 
| 1318281211  | McFadden's Saloon                 | Food & Drink       | Restaurant          | 646-461-6837 | between 42nd - 43rd St | 10017    | 
| 1318281211  | Calico Jack's Cantina             | Food & Drink       | Bars & Lounges      | 212-557-4300 | between 42nd - 43rd St | 10017    | 
| 1318281211  | Bar Kuz 925                       | Food & Drink       | Bars & Lounges      |              | between 42nd - 43rd St | 10017    | 
```