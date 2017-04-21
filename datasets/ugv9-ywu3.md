# Requests for Information Regarding Protected Status Related to Owner Move-In Evictions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/requests-for-information-regarding-protected-status-related-to-owner-move-in-evictions) |
| Metadata | [Link](https://data.sfgov.org/api/views/ugv9-ywu3) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/ugv9-ywu3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/ugv9-ywu3/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | ugv9-ywu3 |
| Name | Requests for Information Regarding Protected Status Related to Owner Move-In Evictions |
| Category | Housing and Buildings |
| Tags | estoppel notices, rent control, protected status, eviction |
| Created | 2014-12-23T19:10:50Z |
| Publication Date | 2016-05-03T18:36:01Z |

## Description

This dataset includes requests for information filed with the San Francisco Rent Board under SF Admin. Code 37.9(i) or (j). Under the Code, residents receiving an eviction notice may claim protected status either due to age and/or disability and length of tenancy or based on length of tenancy and occupancy of a child under the age of 18 during the school year. They need not be filed as estoppels. However, it has become common practice to add the request pursuant to (I) or (j) to estoppels, which is a legal term for limiting a legal action that could normally be taken, e.g. evicting. Data are available starting in January 1999.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                                | Data Type     | Render Type   |
| ======== | =========== | =================== | =================================== | ============= | ============= |
| Yes      | series tag  | estoppel_id         | Estoppel ID                         | text          | text          |
| No       |             | address             | Address                             | text          | text          |
| Yes      | series tag  | city                | City                                | text          | text          |
| Yes      | series tag  | state               | State                               | text          | text          |
| Yes      | series tag  | zip                 | Estoppel Notice Source Zipcode      | text          | text          |
| Yes      | time        | file_date           | File Date                           | calendar_date | calendar_date |
| Yes      | series tag  | supervisor_district | Supervisor District                 | text          | number        |
| Yes      | series tag  | neighborhood        | Neighborhoods - Analysis Boundaries | text          | text          |
```

## Time Field

```ls
Value = file_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:ugv9-ywu3 d:1999-09-20T00:00:00.000Z t:zip=94118 t:neighborhood="Inner Richmond" t:state=CA t:supervisor_district=1 t:estoppel_id=M034273 t:city="San Francisco" m:row_number.ugv9-ywu3=1

series e:ugv9-ywu3 d:2006-01-31T00:00:00.000Z t:zip=94110 t:neighborhood="Bernal Heights" t:state=CA t:supervisor_district=9 t:estoppel_id=M060245 t:city="San Francisco" m:row_number.ugv9-ywu3=2

series e:ugv9-ywu3 d:2005-03-24T00:00:00.000Z t:zip=94117 t:neighborhood="Haight Ashbury" t:state=CA t:supervisor_district=5 t:estoppel_id=M050536 t:city="San Francisco" m:row_number.ugv9-ywu3=3
```

## Meta Commands

```ls
metric m:row_number.ugv9-ywu3 p:long l:"Row Number"

entity e:ugv9-ywu3 l:"Requests for Information Regarding Protected Status Related to Owner Move-In Evictions" t:url=https://data.sfgov.org/api/views/ugv9-ywu3

property e:ugv9-ywu3 t:meta.view v:id=ugv9-ywu3 v:category="Housing and Buildings" v:averageRating=0 v:name="Requests for Information Regarding Protected Status Related to Owner Move-In Evictions"

property e:ugv9-ywu3 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ugv9-ywu3 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:ugv9-ywu3 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| estoppel_id | address                      | city          | state | zip   | file_date           | supervisor_district | neighborhood      | 
| =========== | ============================ | ============= | ===== | ===== | =================== | =================== | ================= | 
| M034273     | 600 Block Of 8th Avenue      | San Francisco | CA    | 94118 | 1999-09-20T00:00:00 | 1                   | Inner Richmond    | 
| M060245     | 800 Block Of Moultrie Street | San Francisco | CA    | 94110 | 2006-01-31T00:00:00 | 9                   | Bernal Heights    | 
| M050536     | 600 Block Of Waller Street   | San Francisco | CA    | 94117 | 2005-03-24T00:00:00 | 5                   | Haight Ashbury    | 
| M060899     | 0 Block Of Broderick Street  | San Francisco | CA    | 94117 | 2006-04-21T00:00:00 | 5                   | Haight Ashbury    | 
| M031765     | 3000 Block Of Turk Boulevard | San Francisco | CA    | 94118 | 2001-06-15T00:00:00 | 1                   | Lone Mountain/USF | 
| M062266     | 1700 Block Of Oak Street     | San Francisco | CA    | 94117 | 2006-10-23T00:00:00 | 5                   | Haight Ashbury    | 
| M050515     | 700 Block Of Moultrie Street | San Francisco | CA    | 94110 | 2005-03-18T00:00:00 | 9                   | Bernal Heights    | 
| M061660     | 3700 Block Of 26th Street    | San Francisco | CA    | 94110 | 2006-07-28T00:00:00 | 8                   | Mission           | 
| M041473     | 400 Block Of 7th Avenue      | San Francisco | CA    | 94118 | 2004-08-11T00:00:00 | 1                   | Inner Richmond    | 
| M130716     | 500 Block Of Nevada Street   | San Francisco | CA    | 94110 | 2013-04-22T00:00:00 | 9                   | Bernal Heights    | 
```