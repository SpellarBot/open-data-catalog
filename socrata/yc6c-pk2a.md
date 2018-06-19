# Directory of City Resources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-city-resources-32c50) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yc6c-pk2a) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yc6c-pk2a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yc6c-pk2a/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yc6c-pk2a |
| Name | Directory of City Resources |
| Attribution | Mayor's Office to Combat Domestic Violence (OCDV) |
| Category | Social Services |
| Tags | ocdv, combat, domestic violence, jobs, economic mobility, city services, jobs and economic mobility |
| Created | 2013-03-19T18:37:20Z |
| Publication Date | 2013-03-19T20:50:28Z |

## Description

List of resources that address the domestic violence issues

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | facility_name   | Facility Name   | text      | text        |
| Yes      | series tag  | phone_number    | Phone Number    | text      | text        |
| Yes      | series tag  | website_address | Website Address | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yc6c-pk2a d:2013-03-19T11:37:25.000Z t:phone_number=212-788-3156 t:facility_name="NYC Mayor's Office to Combat Domestic Violence" t:website_address=http://www.nyc.gov/html/ocdv/html/home/home.shtml m:row_number.yc6c-pk2a=1

series e:yc6c-pk2a d:2013-03-19T11:37:25.000Z t:phone_number=311 t:facility_name="City of New York Resources" m:row_number.yc6c-pk2a=2

series e:yc6c-pk2a d:2013-03-19T11:37:25.000Z t:facility_name="Directory of Domestic Violence Services" t:website_address=http://www.nyc.gov/html/ocdv/html/directory/directory.shtml m:row_number.yc6c-pk2a=3
```

## Meta Commands

```ls
metric m:row_number.yc6c-pk2a p:long l:"Row Number"

entity e:yc6c-pk2a l:"Directory of City Resources" t:attribution="Mayor's Office to Combat Domestic Violence (OCDV)" t:url=https://data.cityofnewyork.us/api/views/yc6c-pk2a

property e:yc6c-pk2a t:meta.view v:id=yc6c-pk2a v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/ocdv/html/statistics_resources/providers.shtml v:averageRating=0 v:name="Directory of City Resources" v:attribution="Mayor's Office to Combat Domestic Violence (OCDV)"

property e:yc6c-pk2a t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yc6c-pk2a t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | facility_name                                  | phone_number | website_address                                             | 
| =========== | ============================================== | ============ | =========================================================== | 
| 1363693045  | NYC Mayor's Office to Combat Domestic Violence | 212-788-3156 | http://www.nyc.gov/html/ocdv/html/home/home.shtml           | 
| 1363693045  | City of New York Resources                     | 311          |                                                             | 
| 1363693045  | Directory of Domestic Violence Services        |              | http://www.nyc.gov/html/ocdv/html/directory/directory.shtml | 
| 1363693045  | NYC Alliance Against Sexual Assault            | 212-523-4344 | www.nycagainstrape.org                                      | 
```