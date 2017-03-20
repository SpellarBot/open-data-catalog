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
| Rows Updated | 2015-09-24T05:00:22Z |

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
series e:4akt-7p7i d:2014-12-17T00:00:00.000Z t:zip=06105-3177 t:source="2014 DECLARATION" t:location="242 SISSON AV" t:dba="DEVARS-PHILLIPS FLORIST" t:owner="PAPERWHITES LLC" t:st_number=242 t:state=CT t:account=562460 t:st_name="SISSON AV" t:city=HARTFORD m:assessment=4370

series e:4akt-7p7i d:2014-12-16T00:00:00.000Z t:zip=06032 t:source="2014 DECLARATION" t:location="85 SEYMOUR ST SUITE 607" t:dba="ORTHOPEDIC ASSOCIATES OF HARTFORD P" t:owner="ORTHOPEDIC ASSOCIATES OF HARTFORD P" t:st_number=85 t:state=CT t:account=556275 t:st_name="SEYMOUR ST" t:locunit="SUITE 607" t:city=FARMINGTON m:assessment=913320

series e:4akt-7p7i d:2014-12-05T00:00:00.000Z t:zip=06106-8003 t:source="2014  DECLARATION" t:location="21 OAK ST 6TH FL" t:dba="KAINEN ESCALERA & MCHALE PC" t:owner="KAINEN ESCALERA & MCHALE PC" t:st_number=21 t:state=CT t:account=383200 t:st_name="OAK ST" t:locunit="6TH FL" t:city=HARTFORD m:assessment=33570
```

## Meta Commands

```ls
metric m:assessment p:integer l:Assessment t:dataTypeName=money

entity e:4akt-7p7i l:"City of Hartford Business Listing" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/4akt-7p7i

property e:4akt-7p7i t:meta.view v:id=4akt-7p7i v:category=Financial v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="City of Hartford Business Listing" v:attribution="City of Hartford"

property e:4akt-7p7i t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:4akt-7p7i t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett

property e:4akt-7p7i t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```