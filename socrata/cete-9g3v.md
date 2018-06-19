# Directory Of DHS Contacts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-dhs-contacts-cdb6c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/cete-9g3v) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/cete-9g3v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/cete-9g3v/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | cete-9g3v |
| Name | Directory Of DHS Contacts |
| Attribution | Department of Homeless Services (DHS) |
| Category | Social Services |
| Tags | dhs, contact, phone, department, homeless |
| Created | 2013-01-30T22:26:12Z |
| Publication Date | 2013-01-30T22:34:58Z |

## Description

Important Phone Numbers of DHS Departments

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | department_name | Department Name | text      | text        |
| Yes      | series tag  | phone_number    | Phone Number    | text      | text        |
| Yes      | series tag  | comments        | Comments        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cete-9g3v d:2013-01-30T14:26:14.000Z t:phone_number="(212) 361-8000" t:department_name="DHS Main Number" t:comments="Please call the main number to be directed to the appropriate office." m:row_number.cete-9g3v=1

series e:cete-9g3v d:2013-01-30T14:26:14.000Z t:phone_number="(212) 361-8000" t:department_name="Office of the Commissioner" m:row_number.cete-9g3v=2

series e:cete-9g3v d:2013-01-30T14:26:14.000Z t:phone_number=1-800-994-6494 t:department_name="Office of Client Advocacy" m:row_number.cete-9g3v=3
```

## Meta Commands

```ls
metric m:row_number.cete-9g3v p:long l:"Row Number"

entity e:cete-9g3v l:"Directory Of DHS Contacts" t:attribution="Department of Homeless Services (DHS)" t:url=https://data.cityofnewyork.us/api/views/cete-9g3v

property e:cete-9g3v t:meta.view v:id=cete-9g3v v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/dhs/html/contact/contact.shtml v:averageRating=0 v:name="Directory Of DHS Contacts" v:attribution="Department of Homeless Services (DHS)"

property e:cete-9g3v t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:cete-9g3v t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | department_name                                              | phone_number   | comments                                                                                                | 
| =========== | ============================================================ | ============== | ======================================================================================================= | 
| 1359555974  | DHS Main Number                                              | (212) 361-8000 | Please call the main number to be directed to the appropriate office.                                   | 
| 1359555974  | Office of the Commissioner                                   | (212) 361-8000 |                                                                                                         | 
| 1359555974  | Office of Client Advocacy                                    | 1-800-994-6494 |                                                                                                         | 
| 1359555974  | Office of Communications and External Affairs - Press Office | (212) 361-7973 |                                                                                                         | 
| 1359555974  | Community Relations & Government Affairs Unit                | (212) 361-7900 |                                                                                                         | 
| 1359555974  | Office of Diversity & Equal Opportunity Affairs              | (212) 361-7914 |                                                                                                         | 
| 1359555974  | Legal Affairs                                                | (212) 361-7996 |                                                                                                         | 
| 1359555974  | Freedom of Information Law (FOIL) Requests                   |                | Please direct all Freedom of Information Law (FOIL) records requests to: Cynthia Stallard, FOIL Officer | 
| 1359555974  | Kim Bruno, Records Access Officer                            | (212) 607-5236 | For all other requests for information or documents, including subpoenas                                | 
```