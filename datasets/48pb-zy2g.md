# Directory Of NYC Cable Providers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-nyc-cable-providers-7da18) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/48pb-zy2g) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/48pb-zy2g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/48pb-zy2g/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 48pb-zy2g |
| Name | Directory Of NYC Cable Providers |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Category | Recreation |
| Tags | doitt, cable, service, provider |
| Created | 2013-02-06T22:59:13Z |
| Publication Date | 2013-06-21T20:27:44Z |

## Description

List of Cable Service Providers in New York City

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | cable_provider_name | Cable Provider Name | text      | text        |
| Yes      | series tag  | street_address      | Street Address      | text      | text        |
| Yes      | series tag  | city_state_zip      | City, State, Zip    | text      | text        |
| Yes      | series tag  | phone               | Phone               | text      | text        |
| Yes      | series tag  | fax                 | Fax                 | text      | text        |
| Yes      | series tag  | web_site            | Web Site            | url       | url         |
| Yes      | series tag  | comments            | Comments            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:48pb-zy2g d:2013-02-06T14:59:15.000Z t:phone="(718) 617-3500" t:city_state_zip="Melville, NY 11747" t:cable_provider_name=Cablevision t:street_address="6 Corporate Center Drive" t:web_site=http://www.optimum.com m:row_number.48pb-zy2g=1

series e:48pb-zy2g d:2013-02-06T14:59:15.000Z t:phone="800-RING-RCN (800-746-4726)" t:city_state_zip="Wilkes-Barre, PA 18702" t:cable_provider_name="RCN Telecom Services of New York" t:street_address="100 Baltimore Drive" t:web_site=http://www.rcn.com m:row_number.48pb-zy2g=2

series e:48pb-zy2g d:2013-02-06T14:59:15.000Z t:phone="(718) 816-8686" t:city_state_zip="Staten Island, NY 10303" t:fax="Fax: (718) 447-2638" t:cable_provider_name="Staten Island Cable" t:street_address="100 Cable Way" t:web_site=http://www.timewarnercable.com m:row_number.48pb-zy2g=3
```

## Meta Commands

```ls
metric m:row_number.48pb-zy2g p:long l:"Row Number"

entity e:48pb-zy2g l:"Directory Of NYC Cable Providers" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/48pb-zy2g

property e:48pb-zy2g t:meta.view v:id=48pb-zy2g v:category=Recreation v:attributionLink=http://www.nyc.gov/html/doitt/html/residents/cable.shtml v:averageRating=0 v:name="Directory Of NYC Cable Providers" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:48pb-zy2g t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:48pb-zy2g t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | cable_provider_name                                      | street_address           | city_state_zip          | phone                          | fax                 | web_site                               | comments                                                                                                                       | 
| =========== | ======================================================== | ======================== | ======================= | ============================== | =================== | ====================================== | ============================================================================================================================== | 
| 1360162755  | Cablevision                                              | 6 Corporate Center Drive | Melville, NY 11747      | (718) 617-3500                 |                     | [http://www.optimum.com, null]         |                                                                                                                                | 
| 1360162755  | RCN Telecom Services of New York                         | 100 Baltimore Drive      | Wilkes-Barre, PA 18702  | 800-RING-RCN (800-746-4726)    |                     | [http://www.rcn.com, null]             |                                                                                                                                | 
| 1360162755  | Staten Island Cable                                      | 100 Cable Way            | Staten Island, NY 10303 | (718) 816-8686                 | Fax: (718) 447-2638 | [http://www.timewarnercable.com, null] |                                                                                                                                | 
| 1360162755  | Time Warner Cable of New York City (Citywide)            | 46 East 23rd Street      | New York, NY 10010      | (212) 358-0900                 |                     | [http://www.timewarnercable.com, null] |                                                                                                                                | 
| 1360162755  | Time Warner Cable of New York City (Brooklyn and Queens) | 4161 Kissena Boulevard   | Flushing, NY 11355      | (718) 358-0900                 |                     | [http://www.timewarnercable.com, null] |                                                                                                                                | 
| 1360162755  | Verizon New York Inc.                                    |                          |                         | 1-800-VERIZON (1-800-837-4966) |                     | [http://www.verizon.com/fiostv, null]  | To order Verizon FiOS cable service, for technical support, billing inquiries and customer care Call the Phone Number provided | 
```