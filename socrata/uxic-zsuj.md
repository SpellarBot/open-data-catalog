# 311 Service Requests - Tree Trims

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-tree-trims-0b313) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/uxic-zsuj) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/uxic-zsuj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/uxic-zsuj/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | uxic-zsuj |
| Name | 311 Service Requests - Tree Trims |
| Attribution | City of Chicago |
| Category | Service Requests |
| Tags | trees |
| Created | 2011-09-30T09:03:58Z |
| Publication Date | 2017-04-20T08:43:28Z |

## Description

All open and completed tree trim requests made to 311 since January 1, 2011. The Department of Streets and Sanitation maintains all trees growing in the public way and performs regular maintenance trimming in response to 311 requests. Crisis trimming is performed on an emergency basis in response to hazardous conditions such as broken or hanging branches. Requests that have been labeled as Duplicates are in the same geographic area and have been entered into 311?s Customer Service Requests (CSR) system at around the same time as a previous request. Duplicate requests are labeled as such in the Status field, as either "Open - Dup" or "Completed - Dup." Data is updated daily.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | time        | creation_date           | Creation Date           | calendar_date | calendar_date |
| Yes      | series tag  | status                  | Status                  | text          | text          |
| No       |             | completion_date         | Completion Date         | calendar_date | calendar_date |
| Yes      | series tag  | service_request_number  | Service Request Number  | text          | text          |
| Yes      | series tag  | type_of_service_request | Type of Service Request | text          | text          |
| Yes      | series tag  | location_of_trees       | Location of Trees       | text          | text          |
| Yes      | series tag  | street_address          | Street Address          | text          | text          |
| Yes      | series tag  | zip_code                | ZIP Code                | text          | number        |
| No       |             | x_coordinate            | X Coordinate            | number        | number        |
| No       |             | y_coordinate            | Y Coordinate            | number        | number        |
| Yes      | series tag  | ward                    | Ward                    | text          | number        |
| Yes      | series tag  | police_district         | Police District         | text          | number        |
| Yes      | series tag  | community_area          | Community Area          | text          | number        |
| No       |             | latitude                | Latitude                | number        | number        |
| No       |             | longitude               | Longitude               | number        | number        |
```

## Time Field

```ls
Value = creation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = completion_date,x_coordinate,y_coordinate,latitude,longitude
```

## Data Commands

```ls
series e:uxic-zsuj d:2017-04-20T08:41:21.000Z t:location_of_trees="LOCATION OF TREE(S)" t:status=STATUS t:service_request_number="SERVICE REQUEST NUMBER" t:type_of_service_request="TYPE OF SERVICE REQUEST" t:street_address="STREET ADDRESS" m:row_number.uxic-zsuj=1

series e:uxic-zsuj d:2010-06-15T00:00:00.000Z t:ward=13 t:zip_code=60629 t:police_district=8 t:status=Completed t:service_request_number=10-00862558 t:community_area=65 t:type_of_service_request="Tree Trim" t:street_address="7237 S AVERS AVE" m:row_number.uxic-zsuj=2

series e:uxic-zsuj d:2010-06-15T00:00:00.000Z t:location_of_trees=Parkway t:ward=18 t:zip_code=60652 t:police_district=8 t:status=Completed t:service_request_number=10-00861435 t:community_area=70 t:type_of_service_request="Tree Trim" t:street_address="7827 S TRUMBULL AVE" m:row_number.uxic-zsuj=3
```

## Meta Commands

```ls
metric m:row_number.uxic-zsuj p:long l:"Row Number"

entity e:uxic-zsuj l:"311 Service Requests - Tree Trims" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/uxic-zsuj

property e:uxic-zsuj t:meta.view v:id=uxic-zsuj v:category="Service Requests" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="311 Service Requests - Tree Trims" v:attribution="City of Chicago"

property e:uxic-zsuj t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:uxic-zsuj t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| creation_date       | status    | completion_date     | service_request_number | type_of_service_request | location_of_trees   | street_address       | zip_code | x_coordinate     | y_coordinate     | ward | police_district | community_area | latitude           | longitude          | 
| =================== | ========= | =================== | ====================== | ======================= | =================== | ==================== | ======== | ================ | ================ | ==== | =============== | ============== | ================== | ================== | 
|                     | STATUS    |                     | SERVICE REQUEST NUMBER | TYPE OF SERVICE REQUEST | LOCATION OF TREE(S) | STREET ADDRESS       |          |                  |                  |      |                 |                |                    |                    | 
| 2010-06-15T00:00:00 | Completed | 2011-10-21T00:00:00 | 10-00862558            | Tree Trim               |                     | 7237 S AVERS AVE     | 60629    | 1151953.62467509 | 1856339.87741701 | 13   | 8               | 65             | 41.761662537751896 | -87.71864092116586 | 
| 2010-06-15T00:00:00 | Completed | 2012-10-24T00:00:00 | 10-00861435            | Tree Trim               | Parkway             | 7827 S TRUMBULL AVE  | 60652    | 1154740.32239948 | 1852493.35850165 | 18   | 8               | 70             | 41.75105196947029  | -87.70852966806123 | 
| 2010-06-15T00:00:00 | Completed | 2011-10-25T00:00:00 | 10-00853312            | Tree Trim               | Parkway             | 1821 W EDDY ST       | 60657    | 1163494.90581942 | 1923598.31991667 | 47   | 19              | 5              | 41.94599213964815  | -87.67444914936094 | 
| 2010-06-15T00:00:00 | Completed | 2011-10-26T00:00:00 | 10-00856362            | Tree Trim               | Parkway             | 10053 S EBERHART AVE | 60628    | 1181349.96050284 | 1838413.81057416 | 9    | 5               | 49             | 41.711844378036105 | -87.61145178817645 | 
| 2010-06-15T00:00:00 | Completed | 2011-10-26T00:00:00 | 10-00858764            | Tree Trim               | Parkway             | 5234 W PENSACOLA AVE | 60641    | 1140676.79589838 | 1928421.76690904 | 38   | 16              | 15             | 41.95967881175858  | -87.75820260590397 | 
| 2010-06-15T00:00:00 | Completed | 2011-10-27T00:00:00 | 10-00860705            | Tree Trim               | Parkway             | 4504 N HAZEL ST      | 60640    | 1169450.42570757 | 1930124.74318279 | 46   | 23              | 3              | 41.96377316813134  | -87.65236817807583 | 
| 2010-06-15T00:00:00 | Completed | 2011-10-31T00:00:00 | 10-00857478            | Tree Trim               | Parkway             | 9157 S UNION AVE     | 60620    | 1173246.53016976 | 1844142.6461135  | 21   | 22              | 73             | 41.72774771271878  | -87.64095985991771 | 
| 2010-06-15T00:00:00 | Completed | 2011-10-31T00:00:00 | 10-00860381            | Tree Trim               | Parkway             | 8854 S LOWE AVE      | 60620    | 1173521.04801317 | 1846194.93280289 | 21   | 22              | 71             | 41.73337340306709  | -87.63989369033915 | 
| 2010-06-15T00:00:00 | Completed | 2011-11-01T00:00:00 | 10-00855789            | Tree Trim               | Parkway             | 9124 S LUELLA AVE    | 60617    | 1192762.4966149  | 1844910.16292461 | 7    | 4               | 48             | 41.72940084764093  | -87.56944558250703 | 
```