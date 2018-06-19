# Cook County Clerk -- Statement of Economic Interests Filers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-clerk-statement-of-economic-interests-filers-59bd0) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/hr5r-c6db) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hr5r-c6db/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hr5r-c6db/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | hr5r-c6db |
| Name | Cook County Clerk -- Statement of Economic Interests Filers |
| Attribution | Cook County Clerk |
| Created | 2011-09-30T08:22:19Z |
| Publication Date | 2014-10-09T23:15:20Z |

## Description

The update script for this dataset is currently broken. Please see the Cook County Clerk SEI Search for recent filings. For extended information about Statements of Economic Interests in Cook County IL, visit the Cook County Clerk's SEI search: http://ethics.cookcountyclerk.com/PublicSearch/

## Columns

```ls
| Included | Schema Type | Field Name | Name       | Data Type | Render Type |
| ======== | =========== | ========== | ========== | ========= | =========== |
| No       |             | year       | Year       | number    | number      |
| Yes      | series tag  | filingid   | FilingID   | text      | number      |
| Yes      | series tag  | filerid    | FilerID    | text      | number      |
| Yes      | series tag  | firstname  | FirstName  | text      | text        |
| Yes      | series tag  | lastname   | LastName   | text      | text        |
| Yes      | series tag  | agencytype | AgencyType | text      | text        |
| Yes      | series tag  | agency     | Agency     | text      | text        |
| Yes      | time        | filed      | Filed      | date      | date        |
| Yes      | series tag  | title      | Title      | text      | text        |
```

## Time Field

```ls
Value = filed
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:hr5r-c6db d:2012-05-23T23:23:33.000Z t:title="COMMISSIONER STAFF" t:agencytype="Cook County" t:agency="BOARD OF COMMISSIONERS & SECRETARY TO BOARD" t:lastname=CURRAN t:firstname="MOIRA O." t:filerid=35281 t:filingid=128503 m:row_number.hr5r-c6db=1

series e:hr5r-c6db d:2013-04-18T16:53:27.000Z t:title="COMMISSIONER STAFF" t:agencytype="Cook County" t:agency="BOARD OF COMMISSIONERS & SECRETARY TO BOARD" t:lastname=CURRAN t:firstname="MOIRA O." t:filerid=35281 t:filingid=150261 m:row_number.hr5r-c6db=2

series e:hr5r-c6db d:2014-04-23T19:16:47.000Z t:title=DEAN t:agencytype=Suburban t:agency="NILES TOWNSHIP HIGH SCHOOL DISTRICT219" t:lastname="(TINSLEY) LAURY" t:firstname=ALANA t:filerid=42020 t:filingid=182646 m:row_number.hr5r-c6db=3
```

## Meta Commands

```ls
metric m:row_number.hr5r-c6db p:long l:"Row Number"

entity e:hr5r-c6db l:"Cook County Clerk -- Statement of Economic Interests Filers" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/hr5r-c6db

property e:hr5r-c6db t:meta.view v:id=hr5r-c6db v:attributionLink=http://ethics.cookcountyclerk.com/PublicSearch/ v:averageRating=0 v:name="Cook County Clerk -- Statement of Economic Interests Filers" v:attribution="Cook County Clerk"

property e:hr5r-c6db t:meta.view.license v:name="Public Domain"

property e:hr5r-c6db t:meta.view.owner v:id=g8dv-kipf v:screenName=malexander v:displayName=malexander

property e:hr5r-c6db t:meta.view.tableauthor v:id=g8dv-kipf v:screenName=malexander v:roleName=publisher v:displayName=malexander
```

## Top Records

```ls
| year | filingid | filerid | firstname | lastname        | agencytype  | agency                                      | filed      | title                    | 
| ==== | ======== | ======= | ========= | =============== | =========== | =========================================== | ========== | ======================== | 
| 2011 | 128503   | 35281   | MOIRA O.  | CURRAN          | Cook County | BOARD OF COMMISSIONERS & SECRETARY TO BOARD | 1337815413 | COMMISSIONER STAFF       | 
| 2012 | 150261   | 35281   | MOIRA O.  | CURRAN          | Cook County | BOARD OF COMMISSIONERS & SECRETARY TO BOARD | 1366304007 | COMMISSIONER STAFF       | 
| 2013 | 182646   | 42020   | ALANA     | (TINSLEY) LAURY | Suburban    | NILES TOWNSHIP HIGH SCHOOL DISTRICT219      | 1398280607 | DEAN                     | 
| 2013 | 183535   | 42886   | MARK      | AANERUD         | Suburban    | EVANSTON SKOKIE SCHOOL DISTRICT 65          | 1395950761 | SERVER ADMINISTRATOR     | 
| 2010 | 64297    | 222     | STEVEN J  | AARDEMA         | Other       | METRA                                       | 1301173061 | FOREMAN MECHANICAL       | 
| 2011 | 110997   | 222     | STEVEN J  | AARDEMA         | Other       | METRA                                       | 1334873836 | FOREMAN MECHANICAL       | 
| 2012 | 140446   | 222     | STEVEN J  | AARDEMA         | Other       | METRA                                       | 1366321520 | FOREMAN MECHANICAL       | 
| 2012 | 148111   | 240     | KIMBERLEI | AARON           | Chicago     | FLEET AND FACILITY MANAGEMENT               | 1364401173 | CHIEF CONTRACT EXPEDITER | 
| 2013 | 174192   | 240     | KIMBERLEI | AARON           | Chicago     | FLEET AND FACILITY MANAGEMENT               | 1395768811 | CHIEF CONTRACT EXPEDITER | 
| 2011 | 121615   | 240     | KIMBERLEI | AARON           | Chicago     | FLEET AND FACILITY MANAGEMENT               | 1333128589 | CHIEF CONTRACT EXPEDITER | 
```