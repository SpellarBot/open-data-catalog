# State Licenses and Credentials

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-licenses-and-credentials) |
| Metadata | [Link](https://data.ct.gov/api/views/ngch-56tr) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/ngch-56tr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/ngch-56tr/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | ngch-56tr |
| Name | State Licenses and Credentials |
| Attribution | Department of Consumer Protection |
| Category | Business |
| Tags | license, credential |
| Created | 2015-04-23T19:02:01Z |
| Publication Date | 2015-05-06T16:50:35Z |

## Description

Licenses and Credentials recorded in Connecticut's eLicensing system. Updated daily.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | credentialid          | CredentialId          | text          | number        |
| Yes      | series tag     | name                  | Name                  | text          | text          |
| Yes      | series tag     | type                  | Type                  | text          | text          |
| Yes      | series tag     | businessname          | BusinessName          | text          | text          |
| Yes      | series tag     | dba                   | DBA                   | text          | text          |
| Yes      | series tag     | fullcredentialcode    | FullCredentialCode    | text          | text          |
| Yes      | series tag     | credentialtype        | CredentialType        | text          | text          |
| Yes      | series tag     | credentialnumber      | CredentialNumber      | text          | text          |
| Yes      | series tag     | credentialsubcategory | CredentialSubCategory | text          | text          |
| Yes      | series tag     | credential            | Credential            | text          | text          |
| Yes      | series tag     | status                | Status                | text          | text          |
| Yes      | series tag     | statusreason          | StatusReason          | text          | text          |
| Yes      | numeric metric | active                | Active                | number        | number        |
| No       |                | issuedate             | IssueDate             | calendar_date | calendar_date |
| No       |                | effectivedate         | EffectiveDate         | calendar_date | calendar_date |
| No       |                | expirationdate        | ExpirationDate        | calendar_date | calendar_date |
| No       |                | address               | Address               | text          | text          |
| Yes      | series tag     | city                  | City                  | text          | text          |
| Yes      | series tag     | state                 | State                 | text          | text          |
| Yes      | series tag     | zip                   | Zip                   | text          | text          |
| Yes      | time           | recordrefreshedon     | RecordRefreshedOn     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = recordrefreshedon
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = issuedate,effectivedate,address,expirationdate
```

## Data Commands

```ls
series e:ngch-56tr d:2013-11-27T00:00:00.000Z t:zip=063405834 t:credentialnumber=2249 t:credentialid=928712 t:status=INACTIVE t:name="HANNA A GREENLEE" t:state=CT t:fullcredentialcode=LIS.0002249 t:type=INDIVIDUAL t:credentialtype=LIS t:credential="WHOLESALER SALESMAN" t:city=GROTON m:active=0

series e:ngch-56tr d:2013-11-27T00:00:00.000Z t:zip=064241851 t:credentialnumber=2255 t:credentialid=936096 t:status=INACTIVE t:name="CHRISTOPHER MARTEL" t:state=CT t:fullcredentialcode=LIS.0002255 t:type=INDIVIDUAL t:credentialtype=LIS t:credential="WHOLESALER SALESMAN" t:city="EAST HAMPTON" m:active=0

series e:ngch-56tr d:2013-11-27T00:00:00.000Z t:zip=061121358 t:credentialnumber=2256 t:credentialid=936545 t:status=INACTIVE t:name="THOMAS J CLARKE II" t:state=CT t:fullcredentialcode=LIS.0002256 t:type=INDIVIDUAL t:credentialtype=LIS t:credential="WHOLESALER SALESMAN" t:city=HARTFORD m:active=0
```

## Meta Commands

```ls
metric m:active p:integer l:Active d:"Boolean value. Either 0 or 1." t:dataTypeName=number

entity e:ngch-56tr l:"State Licenses and Credentials" t:attribution="Department of Consumer Protection" t:url=https://data.ct.gov/api/views/ngch-56tr

property e:ngch-56tr t:meta.view v:id=ngch-56tr v:category=Business v:attributionLink=https://www.elicense.ct.gov/ v:averageRating=0 v:name="State Licenses and Credentials" v:attribution="Department of Consumer Protection"

property e:ngch-56tr t:meta.view.license v:name="Public Domain"

property e:ngch-56tr t:meta.view.owner v:id=cb78-zcxy v:screenName="Matt Shea" v:displayName="Matt Shea"

property e:ngch-56tr t:meta.view.tableauthor v:id=cb78-zcxy v:screenName="Matt Shea" v:roleName=publisher v:displayName="Matt Shea"
```

## Top Records

```ls
| credentialid | name                               | type                      | businessname                       | dba                     | fullcredentialcode | credentialtype | credentialnumber | credentialsubcategory | credential                    | status              | statusreason        | active | issuedate           | effectivedate       | expirationdate      | address                | city         | state | zip       | recordrefreshedon   | 
| ============ | ================================== | ========================= | ================================== | ======================= | ================== | ============== | ================ | ===================== | ============================= | =================== | =================== | ====== | =================== | =================== | =================== | ====================== | ============ | ===== | ========= | =================== | 
| 928712       | HANNA A GREENLEE                   | INDIVIDUAL                |                                    |                         | LIS.0002249        | LIS            | 2249             |                       | WHOLESALER SALESMAN           | INACTIVE            |                     | 0      | 2010-05-28T00:00:00 | 2010-05-28T00:00:00 | 2013-01-31T00:00:00 | 130 SHENNECOSSETT PKWY | GROTON       | CT    | 063405834 | 2013-11-27T00:00:00 | 
| 936096       | CHRISTOPHER MARTEL                 | INDIVIDUAL                |                                    |                         | LIS.0002255        | LIS            | 2255             |                       | WHOLESALER SALESMAN           | INACTIVE            |                     | 0      | 2010-06-25T00:00:00 | 2010-06-25T00:00:00 | 2013-01-31T00:00:00 | 74 CHESTNUT HILL RD    | EAST HAMPTON | CT    | 064241851 | 2013-11-27T00:00:00 | 
| 936545       | THOMAS J CLARKE II                 | INDIVIDUAL                |                                    |                         | LIS.0002256        | LIS            | 2256             |                       | WHOLESALER SALESMAN           | INACTIVE            |                     | 0      | 2010-06-25T00:00:00 | 2010-06-25T00:00:00 | 2013-01-31T00:00:00 | 192 PALM ST            | HARTFORD     | CT    | 061121358 | 2013-11-27T00:00:00 | 
| 63723        | LEROY BARRETT                      | INDIVIDUAL                | SUBURBAN WELL DRILLING             |                         | WWC.0000083-W1     | WWC            | 83               | W1                    | WATER SUPPLY CONTRACTOR       | INACTIVE            |                     | 0      |                     | 2000-05-01T00:00:00 | 2001-04-30T00:00:00 | 4 DANA RD              | DANBURY      | CT    | 06810     | 2009-02-05T00:00:00 | 
| 1294321      | SOLAR YOUTH STEWARD ADVENTURE CAMP | BUSINESS                  | SOLAR YOUTH STEWARD ADVENTURE CAMP |                         | YCYC.01217         | YCYC           | 1217             |                       | Youth Camp                    | INACTIVE            | LAPSED              | 0      | 2015-07-13T00:00:00 | 2015-07-13T00:00:00 | 2016-07-31T00:00:00 | 200 WILMOT RD # 199    | NEW HAVEN    | CT    | 065151009 | 2016-08-07T00:00:00 | 
| 904357       | NANCY JANE DEANS                   | INDIVIDUAL                |                                    |                         | 10                 | 10             |                  |                       | Registered Nurse              | EXPIRED APPLICATION | EXPIRED APPLICATION | 0      |                     |                     |                     | 308 BRADY ST           | BRADY        | TX    | 768258602 | 2014-09-30T00:00:00 | 
| 63724        | RALPH P BISCIOTTI                  | INDIVIDUAL                | DICK'S ARTESIAN WELL CO INC        | DICK'S ARTESIAN WELL CO | WWC.0000089-W1     | WWC            | 89               | W1                    | WATER SUPPLY CONTRACTOR       | INACTIVE            |                     | 0      | 2005-06-08T00:00:00 | 2011-05-05T00:00:00 | 2012-04-30T00:00:00 | 315 HARMONY HILL RD    | HARWINTON    | CT    | 067911417 | 2013-03-26T00:00:00 | 
| 801228       | TIMOTHY J CARNEY                   | INDIVIDUAL                |                                    |                         | 66.002128          | 66             | 2128             |                       | Lead Planner/Project Designer | ACTIVE              | CURRENT             | 1      | 2004-03-30T00:00:00 | 2016-11-29T00:00:00 | 2018-02-28T00:00:00 | 1 Rochelle Road        | Norwalk      | CT    | 068542403 | 2016-12-01T00:00:00 | 
| 500004       | SG CARPENTRY LLC                   | LIMITED LIABILITY COMPANY | SG CARPENTRY LLC                   |                         | HIC.0620898        | HIC            | 620898           |                       | HOME IMPROVEMENT CONTRACTOR   | INACTIVE            |                     | 0      | 2008-04-11T00:00:00 | 2009-12-29T00:00:00 | 2010-11-30T00:00:00 | 147 REDDING RD         | REDDING      | CT    | 068963213 | 2011-12-07T00:00:00 | 
| 65432        | GRAN CENTRAL MARKETS               | BUSINESS                  | GRAN CENTRAL MARKETS               | THE HARTFORD PROVIS CO  | VMA.0000419        | VMA            | 419              |                       | VENDING MACHINE OPERATOR      | INACTIVE            |                     | 0      |                     | 1997-09-23T00:00:00 | 1998-06-30T00:00:00 | 159 MAIN ST            | STAMFORD     | CT    | 06901     | 2004-04-23T00:00:00 | 
```