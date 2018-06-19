# New Home Builders

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-home-builders) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/c7hs-c9qq) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/c7hs-c9qq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/c7hs-c9qq/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | c7hs-c9qq |
| Name | New Home Builders |
| Category | Consumer/Housing |
| Tags | consumer, business, housing, building, construction, license |
| Created | 2015-12-23T00:49:00Z |
| Publication Date | 2015-12-23T18:15:26Z |

## Description

The Office of Consumer Protection (OCP) licenses builders or anyone acting in the capacity of a building contractor who constructs new homes in Montgomery County. This data consists of all active new home builder license holders. OCP does not license home improvement (ex. repair, remodeling, partial replacement, addition, or modernization, of existing structure) contractors; these contractors are licensed by Maryland Home Improvement Commission.  The license information is deemed to be reliable, but we cannot guarantee the accuracy and completeness of the information. Any information that is shown to be inaccurate will be corrected if brought to the attention of OCP.  Data Update Frequency : Daily

## Columns

```ls
| Included | Schema Type | Field Name          | Name                 | Data Type     | Render Type   |
| ======== | =========== | =================== | ==================== | ============= | ============= |
| Yes      | series tag  | licensetype         | License Type         | text          | text          |
| Yes      | series tag  | licenseno           | License Number       | text          | text          |
| Yes      | time        | issueddate          | Issue Date           | calendar_date | calendar_date |
| No       |             | expiredate          | Expiration Date      | calendar_date | calendar_date |
| Yes      | series tag  | applicant           | Primary Applicant    | text          | text          |
| Yes      | series tag  | additionalapplicant | Additional Applicant | text          | text          |
| Yes      | series tag  | organization        | Business name        | text          | text          |
| Yes      | series tag  | businessname        | Trade Name           | text          | text          |
| No       |             | addr1               | Address              | text          | text          |
| No       |             | addr2               | Address Line 2       | text          | text          |
| Yes      | series tag  | city                | City                 | text          | text          |
| Yes      | series tag  | state               | State                | text          | text          |
| Yes      | series tag  | zip                 | Zip Code             | text          | number        |
| Yes      | series tag  | telephone           | Telephone            | text          | text          |
```

## Time Field

```ls
Value = issueddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expiredate,addr1,addr2
```

## Data Commands

```ls
series e:c7hs-c9qq d:2012-07-05T02:07:31.000Z t:zip=20901 t:organization="HEIRMAN RENOVATIONS" t:applicant="C/O RUDOLF SEBASTIAN HERMAN HEIRMAN RENOVATIONS" t:state=MD t:licenseno=BC203645 t:additionalapplicant=HEIRMAN t:licensetype="BUILDING CONTRACTORS LICENSE" t:telephone=(202)352-8144x t:city="SILVER SPRING" m:row_number.c7hs-c9qq=1

series e:c7hs-c9qq d:2012-03-08T11:03:10.000Z t:zip=21740 t:organization="TRISTATE AFFORDABLE HOMES, LLC" t:applicant="MICHAEL FITZGERALD" t:state=MD t:licenseno=BC4075 t:additionalapplicant="TRISTATE AFFORDABLE HOMES, LLC" t:licensetype="BUILDING CONTRACTORS LICENSE" t:telephone=(301)960-4881x t:city=HAGERSTOWN m:row_number.c7hs-c9qq=2

series e:c7hs-c9qq d:2012-02-14T09:02:54.000Z t:zip=20815 t:organization="QUARRY ASSOCIATES, LLC" t:applicant="THOMAS BRAULT" t:state=MD t:licenseno=BC4073 t:additionalapplicant="QUARRY ASSOCIATES, LLC" t:licensetype="BUILDING CONTRACTORS LICENSE" t:telephone=(301)656-4472x t:city="CHEVY CHASE" m:row_number.c7hs-c9qq=3
```

## Meta Commands

```ls
metric m:row_number.c7hs-c9qq p:long l:"Row Number"

entity e:c7hs-c9qq l:"New Home Builders" t:url=https://data.montgomerycountymd.gov/api/views/c7hs-c9qq

property e:c7hs-c9qq t:meta.view v:id=c7hs-c9qq v:category=Consumer/Housing v:averageRating=0 v:name="New Home Builders"

property e:c7hs-c9qq t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:c7hs-c9qq t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| licensetype                  | licenseno | issueddate          | expiredate          | applicant                                       | additionalapplicant            | organization                   | businessname | addr1                    | addr2     | city          | state | zip   | telephone      | 
| ============================ | ========= | =================== | =================== | =============================================== | ============================== | ============================== | ============ | ======================== | ========= | ============= | ===== | ===== | ============== | 
| BUILDING CONTRACTORS LICENSE | BC203645  | 2012-07-05T02:07:31 | 2014-07-05T02:07:31 | C/O RUDOLF SEBASTIAN HERMAN HEIRMAN RENOVATIONS | HEIRMAN                        | HEIRMAN RENOVATIONS            |              | 1114 DRYDEN ST           |           | SILVER SPRING | MD    | 20901 | (202)352-8144x | 
| BUILDING CONTRACTORS LICENSE | BC4075    | 2012-03-08T11:03:10 | 2014-03-08T11:03:10 | MICHAEL FITZGERALD                              | TRISTATE AFFORDABLE HOMES, LLC | TRISTATE AFFORDABLE HOMES, LLC |              | 1423 DUAL HIGHWAY        | #242      | HAGERSTOWN    | MD    | 21740 | (301)960-4881x | 
| BUILDING CONTRACTORS LICENSE | BC4073    | 2012-02-14T09:02:54 | 2014-02-07T12:02:00 | THOMAS BRAULT                                   | QUARRY ASSOCIATES, LLC         | QUARRY ASSOCIATES, LLC         |              | 6912 WOODSIDE PLACE      |           | CHEVY CHASE   | MD    | 20815 | (301)656-4472x | 
| BUILDING CONTRACTORS LICENSE | BC4065    | 2011-11-09T03:11:29 | 2015-11-04T12:11:00 | TODD COPELAND                                   | TRIANGLE-ORION, LLC            | TRIANGLE-ORION, LLC            |              | 6001 MONTROSE ROAD       | SUITE 710 | ROCKVILLE     | MD    | 20852 | (301)816-4241x | 
| BUILDING CONTRACTORS LICENSE | BC4060    | 2012-02-17T11:02:24 | 2014-10-11T12:10:00 | JAY EICHBERG                                    | EICHBERG CONSTRUCTION CO.      | EICHBERG CONSTRUCTION CO.      |              | 16010 INDUSTRIAL DRIVE   |           | GAITHERSBURG  | MD    | 20877 | (301)330-0332x | 
| BUILDING CONTRACTORS LICENSE | BC4061    | 2011-10-05T11:10:00 | 2013-10-05T12:10:00 | MICHAEL RUSSELL                                 | MD RUSSELL CONSTRUCTION,INC.   | MD RUSSELL CONTRUCTION, INC.   |              | 6015 BOSTON RIDGE COURT  |           | BOSTON        | VA    | 22713 | (540)842-3619x | 
| BUILDING CONTRACTORS LICENSE | BC4056    | 2011-09-21T12:09:22 | 2015-09-21T12:09:22 | BRUCE TROJAN                                    | BUNGALOW HOMES                 | BUNGALOW HOMES                 |              | 601 GLYNDON STREET, S.E. |           | VIENNA        | VA    | 22180 | (703)915-7592x | 
| BUILDING CONTRACTORS LICENSE | BC4058    | 2011-09-14T03:09:11 | 2015-09-14T03:09:11 | CHRIS WORTH                                     | REEL HOMES, LLC                | REEL HOMES, LLC                |              | 10623 JONES STREET       | #201B     | FAIRFAX       | VA    | 22030 | (703)385-7335  | 
| BUILDING CONTRACTORS LICENSE | BC4054    | 2011-09-08T05:09:45 | 2013-09-08T12:09:00 | JOHN DENMAN                                     | CLARK AND LOVELL BUILDERS,LLC  | CLARK AND LOVELL BUILDERS, LLC |              | 217 HOLLAND ROAD         |           | SEVERNA PARK  | MD    | 21146 | (410)703-3420x | 
| BUILDING CONTRACTORS LICENSE | BC4052    | 2011-10-27T09:10:00 | 2013-07-06T12:07:00 | GEORGE DEFALCO                                  | TRADITION HOMES, LLC           | TRADITION HOMES, LLC           |              | 1497 CHAIN BRIDGE ROAD   | SUITE 100 | MCLEAN        | VA    | 22101 | (703)987-3444x | 
```