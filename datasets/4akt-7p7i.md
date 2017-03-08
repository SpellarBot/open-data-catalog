# City of Hartford Business Listing

## Dataset

* [Dataset URL](https://data.hartford.gov/api/views/4akt-7p7i/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/city-of-hartford-business-listing)
* [Metadata URL](https://data.hartford.gov/api/views/4akt-7p7i)
* Id = 4akt-7p7i
* Name = City of Hartford Business Listing
* Attribution = City of Hartford
* [Attribution Link](http://www.hartford.gov)
* Category = Financial
* Tags = [financial, business, property, hartford]
* Created = 2015-09-23T14:49:51Z
* Publication Date = 2015-09-23T18:02:05Z
* Rows Updated = 2015-09-24T05:00:22Z

## Description

The source of this data set is the working file Personal Property Database that is maintained in the Assessor's Office.  This is a listing of all of the active businesses registered in the City. If the business was added to the assessment role after October 1st of the previous year, the Assessment value may be $0.  If you observe any errors or omissions please contact the City Assessor's office at (860) 757-9630. Updated nightly.

## Columns

```ls
| Name       | Field Name | Data Type     | Render Type   | Schema Type    | Included | 
| ========== | ========== | ============= | ============= | ============== | ======== | 
| Account    | account    | number        | text          | numeric metric | Yes      | 
| Owner      | owner      | text          | text          | series tag     | Yes      | 
| Owner2     | owner2     | text          | text          | series tag     | Yes      | 
| DBA        | dba        | text          | text          | series tag     | Yes      | 
| Address    | address    | text          | text          |                | No       | 
| Address2   | address2   | text          | text          | series tag     | Yes      | 
| Location   | location   | text          | text          | series tag     | Yes      | 
| City       | city       | text          | text          | series tag     | Yes      | 
| State      | state      | text          | text          | series tag     | Yes      | 
| Zip        | zip        | text          | text          | series tag     | Yes      | 
| Source     | source     | text          | text          | series tag     | Yes      | 
| Date_a     | date_a     | calendar_date | calendar_date | time           | Yes      | 
| Assessment | assessment | money         | money         | numeric metric | Yes      | 
| St_Number  | st_number  | number        | number        | numeric metric | Yes      | 
| St_Name    | st_name    | text          | text          | series tag     | Yes      | 
| Locunit    | locunit    | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = date_a
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = address
Annotation Fields = 
```

## Data Commands

```ls
series e:4akt-7p7i d:2014-12-17T00:00:00.000Z t:zip=06105-3177 t:source="2014 DECLARATION" t:location="242 SISSON AV" t:dba="DEVARS-PHILLIPS FLORIST" t:owner="PAPERWHITES LLC" t:state=CT t:st_name="SISSON AV" t:city=HARTFORD m:st_number=242 m:account=562460 m:assessment=4370

series e:4akt-7p7i d:2014-12-16T00:00:00.000Z t:zip=06032 t:source="2014 DECLARATION" t:location="85 SEYMOUR ST SUITE 607" t:dba="ORTHOPEDIC ASSOCIATES OF HARTFORD P" t:owner="ORTHOPEDIC ASSOCIATES OF HARTFORD P" t:state=CT t:st_name="SEYMOUR ST" t:locunit="SUITE 607" t:city=FARMINGTON m:st_number=85 m:account=556275 m:assessment=913320

series e:4akt-7p7i d:2014-12-05T00:00:00.000Z t:zip=06106-8003 t:source="2014  DECLARATION" t:location="21 OAK ST 6TH FL" t:dba="KAINEN ESCALERA & MCHALE PC" t:owner="KAINEN ESCALERA & MCHALE PC" t:state=CT t:st_name="OAK ST" t:address2="SUITE  601" t:locunit="6TH FL" t:city=HARTFORD m:st_number=21 m:account=383200 m:assessment=33570
```

## Meta Commands

```ls
metric m:account p:integer l:Account t:dataTypeName=number

metric m:st_number p:integer l:St_Number t:dataTypeName=number

entity e:4akt-7p7i l:"City of Hartford Business Listing" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/4akt-7p7i

property e:4akt-7p7i t:meta.view d:2017-03-07T18:03:45.827Z v:id=4akt-7p7i v:category=Financial v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="City of Hartford Business Listing" v:attribution="City of Hartford"

property e:4akt-7p7i t:meta.view.license d:2017-03-07T18:03:45.827Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:4akt-7p7i t:meta.view.owner d:2017-03-07T18:03:45.827Z v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett

property e:4akt-7p7i t:meta.view.tableauthor d:2017-03-07T18:03:45.827Z v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```