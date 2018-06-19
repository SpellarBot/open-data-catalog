# Referral Centers For High School Alternatives

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/referral-centers-for-high-school-alternatives-e4110) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/w8dz-xpjh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/w8dz-xpjh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/w8dz-xpjh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | w8dz-xpjh |
| Name | Referral Centers For High School Alternatives |
| Attribution | Department of Education (DOE) |
| Category | Social Services |
| Tags | referral centers for high school alternatives, doe, jobs and economic mobility |
| Created | 2013-03-19T21:07:16Z |
| Publication Date | 2013-03-19T21:08:35Z |

## Description

Listing of referral Centers For High School Alternatives

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | location       | Location       | text      | text        |
| No       |             | address        | Address        | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
| Yes      | series tag  | state          | State          | text      | text        |
| Yes      | series tag  | zip_code       | Zip Code       | text      | number      |
| Yes      | series tag  | contact_number | Contact Number | text      | text        |
| Yes      | series tag  | notes          | Notes          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:w8dz-xpjh d:2013-03-19T14:07:17.000Z t:contact_number="718 842 9200" t:zip_code=10459 t:location="Bronx Regional High School" t:state="New York" t:notes="3rd Floor" t:city=Bronx m:row_number.w8dz-xpjh=1

series e:w8dz-xpjh d:2013-03-19T14:07:17.000Z t:contact_number="718 636 5770" t:zip_code=11216 t:location="Marcy Avenue Complex" t:state="New York" t:notes="Room 501A" t:city=Brooklyn m:row_number.w8dz-xpjh=2

series e:w8dz-xpjh d:2013-03-19T14:07:17.000Z t:contact_number="212 224 1793" t:zip_code=10018 t:location="Alternative Learning Complex" t:state="New York" t:notes="7th Floor" t:city="New York" m:row_number.w8dz-xpjh=3
```

## Meta Commands

```ls
metric m:row_number.w8dz-xpjh p:long l:"Row Number"

entity e:w8dz-xpjh l:"Referral Centers For High School Alternatives" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/w8dz-xpjh

property e:w8dz-xpjh t:meta.view v:id=w8dz-xpjh v:category="Social Services" v:averageRating=0 v:name="Referral Centers For High School Alternatives" v:attribution="Department of Education (DOE)"

property e:w8dz-xpjh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:w8dz-xpjh t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | location                     | address                              | city          | state    | zip_code | contact_number | notes     | 
| =========== | ============================ | ==================================== | ============= | ======== | ======== | ============== | ========= | 
| 1363702037  | Bronx Regional High School   | 1010 Reverend James A. Polite Avenue | Bronx         | New York | 10459    | 718 842 9200   | 3rd Floor | 
| 1363702037  | Marcy Avenue Complex         | 832 Marcy Avenue                     | Brooklyn      | New York | 11216    | 718 636 5770   | Room 501A | 
| 1363702037  | Alternative Learning Complex | 269 West 35th Street                 | New York      | New York | 10018    | 212 224 1793   | 7th Floor | 
| 1363702037  | Jamaica Learning Center      | 162-02 Hillside Avenue               | Jamaica       | New York | 11432    | 718 739 2100   | Room 109  | 
| 1363702037  | St. George                   | 450 St. Marks Place                  | Staten Island | New York | 10301    | 718 273 3225   |           | 
```