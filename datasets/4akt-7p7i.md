# City of Hartford Business Listing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-hartford-business-listing) |
| Metadata | [Link](https://data.hartford.gov/api/views/4akt-7p7i) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/4akt-7p7i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/4akt-7p7i/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | 4akt-7p7i |
| Name | City of Hartford Business Listing |
| Attribution | City of Hartford |
| Category | Financial |
| Tags | financial, business, property, hartford |
| Created | 2015-09-23T14:49:51Z |
| Publication Date | 2015-09-23T18:02:05Z |

## Description

The source of this data set is the working file Personal Property Database that is maintained in the Assessor's Office.  This is a listing of all of the active businesses registered in the City. If the business was added to the assessment role after October 1st of the previous year, the Assessment value may be $0.  If you observe any errors or omissions please contact the City Assessor's office at (860) 757-9630. Updated nightly.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | series tag     | account    | Account    | text          | text          |
| Yes      | series tag     | owner      | Owner      | text          | text          |
| Yes      | series tag     | owner2     | Owner2     | text          | text          |
| Yes      | series tag     | dba        | DBA        | text          | text          |
| No       |                | address    | Address    | text          | text          |
| No       |                | address2   | Address2   | text          | text          |
| Yes      | series tag     | location   | Location   | text          | text          |
| Yes      | series tag     | city       | City       | text          | text          |
| Yes      | series tag     | state      | State      | text          | text          |
| Yes      | series tag     | zip        | Zip        | text          | text          |
| Yes      | series tag     | source     | Source     | text          | text          |
| Yes      | time           | date_a     | Date_a     | calendar_date | calendar_date |
| Yes      | numeric metric | assessment | Assessment | money         | money         |
| Yes      | series tag     | st_number  | St_Number  | text          | number        |
| Yes      | series tag     | st_name    | St_Name    | text          | text          |
| Yes      | series tag     | locunit    | Locunit    | text          | text          |
```

## Time Field

```ls
Value = date_a
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,address2
```

## Data Commands

```ls
series e:4akt-7p7i d:2014-12-17T00:00:00.000Z t:owner="PAPERWHITES LLC" t:zip=06105-3177 t:dba="DEVARS-PHILLIPS FLORIST" t:city=HARTFORD t:st_name="SISSON AV" t:st_number=242 t:location="242 SISSON AV" t:source="2014 DECLARATION" t:state=CT t:account=562460 m:assessment=4370

series e:4akt-7p7i d:2014-12-16T00:00:00.000Z t:owner="ORTHOPEDIC ASSOCIATES OF HARTFORD P" t:zip=06032 t:locunit="SUITE 607" t:dba="ORTHOPEDIC ASSOCIATES OF HARTFORD P" t:city=FARMINGTON t:st_name="SEYMOUR ST" t:st_number=85 t:location="85 SEYMOUR ST SUITE 607" t:source="2014 DECLARATION" t:state=CT t:account=556275 m:assessment=913320

series e:4akt-7p7i d:2014-12-05T00:00:00.000Z t:owner="KAINEN ESCALERA & MCHALE PC" t:zip=06106-8003 t:locunit="6TH FL" t:dba="KAINEN ESCALERA & MCHALE PC" t:city=HARTFORD t:st_name="OAK ST" t:st_number=21 t:location="21 OAK ST 6TH FL" t:source="2014  DECLARATION" t:state=CT t:account=383200 m:assessment=33570
```

## Meta Commands

```ls
metric m:assessment p:integer l:Assessment t:dataTypeName=money

entity e:4akt-7p7i l:"City of Hartford Business Listing" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/4akt-7p7i

property e:4akt-7p7i t:meta.view d:2017-09-25T07:29:16.811Z v:averageRating=0 v:name="City of Hartford Business Listing" v:attribution="City of Hartford" v:attributionLink=http://www.hartford.gov v:id=4akt-7p7i v:category=Financial

property e:4akt-7p7i t:meta.view.license d:2017-09-25T07:29:16.811Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:4akt-7p7i t:meta.view.owner d:2017-09-25T07:29:16.811Z v:displayName=Brett v:id=cdqe-xcn5 v:screenName=Brett

property e:4akt-7p7i t:meta.view.tableauthor d:2017-09-25T07:29:16.811Z v:displayName=Brett v:roleName=administrator v:id=cdqe-xcn5 v:screenName=Brett
```

## Top Records

```ls
| account | owner                               | owner2 | dba                                 | address                     | address2  | location                | city        | state | zip        | source               | date_a              | assessment | st_number | st_name              | locunit   | 
| ======= | =================================== | ====== | =================================== | =========================== | ========= | ======================= | =========== | ===== | ========== | ==================== | =================== | ========== | ========= | ==================== | ========= | 
| 562460  | PAPERWHITES LLC                     |        | DEVARS-PHILLIPS FLORIST             | 242 SISSON AV               |           | 242 SISSON AV           | HARTFORD    | CT    | 06105-3177 | 2014 DECLARATION     | 2014-12-17T00:00:00 | 4370       | 242       | SISSON AV            |           | 
| 556275  | ORTHOPEDIC ASSOCIATES OF HARTFORD P |        | ORTHOPEDIC ASSOCIATES OF HARTFORD P | 270 FARMINGTON AV SUITE 102 |           | 85 SEYMOUR ST SUITE 607 | FARMINGTON  | CT    | 06032      | 2014 DECLARATION     | 2014-12-16T00:00:00 | 913320     | 85        | SEYMOUR ST           | SUITE 607 | 
| 383200  | KAINEN ESCALERA & MCHALE PC         |        | KAINEN ESCALERA & MCHALE PC         | 21 OAK ST 6TH FL            | SUITE 601 | 21 OAK ST 6TH FL        | HARTFORD    | CT    | 06106-8003 | 2014 DECLARATION     | 2014-12-05T00:00:00 | 33570      | 21        | OAK ST               | 6TH FL    | 
| 930912  | HUYNH PHUOC-HUY P                   |        | SOOSKY MARKETING                    | 183 GILMAN ST               |           | 183 GILMAN ST           | HARTFORD    | CT    | 06114      | TRADE / VERIFIED/ TP | 2015-09-10T00:00:00 | 0          | 183       | GILMAN ST            |           | 
| 046100  | BEACON - BIOMEDICAL ENGINEERING ALL |        | BEACON - BIOMEDICAL ENGINEERING ALL | 1 CONGRESS ST SUITE 201     |           | 1 CONGRESS ST SUITE 201 | HARTFORD    | CT    | 06114-1067 | 2014 DECLARATION     | 2014-10-06T00:00:00 | 3390       | 1         | CONGRESS ST          | SUITE 201 | 
| 926355  | YANKEE LIQUORS LLC                  |        | YANKEE LIQUORS LLC                  | 35 WILLIAM SHORTY CAMPB     |           | 35 WILLIAM SHORTY CAMPB | HARTFORD    | CT    | 06106      | 2014 DECLARATION     | 2015-01-06T00:00:00 | 14650      | 35        | WILLIAM SHORTY CAMPB |           | 
| 930144  | DE LEON HERNANDEZ WILSON            |        | LANGUAGE SPECIALIST LINK            | 52 CHATHAM ST               |           | 52 CHATHAM ST           | HARTFORD    | CT    | 06112      | TRADE NAME           | 2013-08-26T00:00:00 | 480        | 52        | CHATHAM ST           |           | 
| 928893  | CONNECTICUT HEALTH MSO LLC          |        | CONNECTICUT HEALTH MSO LLC          | 2110 SILAS DEANE HIGHWAY    |           | 3580 MAIN ST            | HARTFORD    | CT    | 06067      | 2014 DECLARATION     | 2015-01-08T00:00:00 | 62490      | 3580      | MAIN ST              |           | 
| 929191  | MEJIA AUTO REPAIR LLC               |        | MEJIA AUTO REPAIR LLC               | 57 HOPE ST                  |           | 375 LEDYARD ST UNT B    | WILLIMANTIC | CT    | 06226      |                      | 2010-08-03T00:00:00 | 7960       | 375       | LEDYARD ST           | UNT B     | 
| 240775  | FICARA SEBASTIANO                   |        | FICARA'S RESTAURANT                 | 577 FRANKLIN AV             |           | 577 FRANKLIN AV         | HARTFORD    | CT    | 06114-3019 | 2013 DECLARATION     | 2013-12-18T00:00:00 | 9560       | 577       | FRANKLIN AV          |           | 
```