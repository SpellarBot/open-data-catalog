# LCB Marijuana Renewal

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lcb-marijuana-renewal) |
| Metadata | [Link](https://data.wa.gov/api/views/brpd-b6zd) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/brpd-b6zd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/brpd-b6zd/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | brpd-b6zd |
| Name | LCB Marijuana Renewal |
| Category | Public Safety |
| Tags | lcb, renewal |
| Created | 2015-03-17T14:23:35Z |
| Publication Date | 2015-05-15T13:33:34Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | license          | License#         | text      | text        |
| Yes      | numeric metric | ubi              | UBI              | number    | text        |
| Yes      | series tag     | designatedsignee | DesignatedSignee | text      | text        |
| Yes      | series tag     | countycode       | CountyCode       | text      | text        |
| Yes      | series tag     | countyname       | CountyName       | text      | text        |
| Yes      | series tag     | citycode         | CityCode         | text      | text        |
| Yes      | series tag     | cityname         | CityName         | text      | text        |
| Yes      | series tag     | dayphone         | DayPhone         | text      | text        |
| Yes      | series tag     | l_a_type         | L/A Type         | text      | text        |
| Yes      | series tag     | tradename        | TradeName        | text      | text        |
| Yes      | series tag     | streetaddress    | StreetAddress    | text      | text        |
| Yes      | series tag     | roomnumber       | RoomNumber       | text      | text        |
| Yes      | series tag     | city             | City             | text      | text        |
| Yes      | series tag     | state            | State            | text      | text        |
| Yes      | series tag     | zipcode          | ZipCode          | text      | text        |
| No       |                | mailaddress      | MailAddress      | text      | text        |
| Yes      | series tag     | mailroom         | MailRoom         | text      | text        |
| Yes      | series tag     | mailcity         | MailCity         | text      | text        |
| Yes      | series tag     | mailstate        | MailState        | text      | text        |
| Yes      | series tag     | mailzip          | MailZip          | text      | text        |
| Yes      | series tag     | privdesc01       | PrivDesc01       | text      | text        |
| Yes      | series tag     | privdesc02       | PrivDesc02       | text      | text        |
| Yes      | series tag     | privdesc03       | PrivDesc03       | text      | text        |
| Yes      | series tag     | privdesc04       | PrivDesc04       | text      | text        |
| Yes      | series tag     | privdesc05       | PrivDesc05       | text      | text        |
| Yes      | series tag     | privdesc06       | PrivDesc06       | text      | text        |
| Yes      | series tag     | privdesc07       | PrivDesc07       | text      | text        |
| Yes      | series tag     | privdesc08       | PrivDesc08       | text      | text        |
| Yes      | series tag     | applicants       | Applicants       | text      | text        |
| Yes      | numeric metric | renewaldate      | RenewalDate      | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = mailaddress
```

## Data Commands

```ls
series e:brpd-b6zd d:2017-04-03T11:30:08.000Z t:applicants="LC CANNABIS SALES, LLC" t:zipcode=994030000 t:state=WA t:designatedsignee="CITY OF CLARKSTON" t:city=CLARKSTON t:citycode=2 t:streetaddress="2797 TURNING POINTE LOOP" t:countyname=ASOTIN t:privdesc02="MARIJUANA PROCESSOR" t:tradename="HELLS CANYON CANNABIS COMPANY" t:privdesc01="MARIJUANA PRODUCER TIER 1" t:l_a_type="MARIJUANA RENEWAL" t:countycode=2 t:cityname=CLARKSTON t:license=417202 m:ubi=6034406110010001 m:renewaldate=20170930

series e:brpd-b6zd d:2017-04-04T11:30:10.000Z t:applicants="GRAYBEARD HOLDINGS LLC" t:zipcode=984440000 t:state=WA t:city=TACOMA t:citycode=0 t:streetaddress="13005 PACIFIC AVE SOUTH" t:countyname=PIERCE t:privdesc02="MEDICAL MARIJUANA" t:tradename="THE GALLERY" t:privdesc01="MARIJUANA RETAILER" t:l_a_type="MARIJUANA RENEWAL" t:countycode=27 t:cityname="UNINCORP. AREAS" t:license=413258 m:ubi=6033367320010001 m:renewaldate=20170930

series e:brpd-b6zd d:2017-04-04T11:30:10.000Z t:applicants="COOKIE CUTTER FARMS LLC" t:zipcode=982523600 t:state=WA t:designatedsignee="SNOHOMISH COUNTY EXECUTIVE" t:city="GRANITE FALLS" t:citycode=0 t:streetaddress="23410 HIDDEN VALLEY RD STE A" t:countyname=SNOHOMISH t:tradename="COOKIE CUTTER FARMS, LLC" t:privdesc01="MARIJUANA PRODUCER TIER 1" t:l_a_type="MARIJUANA RENEWAL" t:countycode=31 t:cityname="UNINCORP. AREAS" t:license=412698 m:ubi=6040431000010001 m:renewaldate=20170930
```

## Meta Commands

```ls
metric m:ubi p:long l:UBI t:dataTypeName=number

metric m:renewaldate p:integer l:RenewalDate t:dataTypeName=number

entity e:brpd-b6zd l:"LCB Marijuana Renewal" t:url=https://data.wa.gov/api/views/brpd-b6zd

property e:brpd-b6zd t:meta.view v:id=brpd-b6zd v:category="Public Safety" v:averageRating=0 v:name="LCB Marijuana Renewal"

property e:brpd-b6zd t:meta.view.owner v:id=v3pq-y2y4 v:screenName="Cameron McGee" v:displayName="Cameron McGee"

property e:brpd-b6zd t:meta.view.tableauthor v:id=v3pq-y2y4 v:screenName="Cameron McGee" v:roleName=publisher v:displayName="Cameron McGee"
```

## Top Records

```ls
| :updated_at | license | ubi              | designatedsignee                | countycode | countyname | citycode | cityname        | dayphone | l_a_type          | tradename                     | streetaddress                | roomnumber | city           | state | zipcode   | mailaddress | mailroom | mailcity | mailstate | mailzip | privdesc01                | privdesc02          | privdesc03 | privdesc04 | privdesc05 | privdesc06 | privdesc07 | privdesc08 | applicants              | renewaldate | 
| =========== | ======= | ================ | =============================== | ========== | ========== | ======== | =============== | ======== | ================= | ============================= | ============================ | ========== | ============== | ===== | ========= | =========== | ======== | ======== | ========= | ======= | ========================= | =================== | ========== | ========== | ========== | ========== | ========== | ========== | ======================= | =========== | 
| 1491219008  | 417202  | 6034406110010001 | CITY OF CLARKSTON               | 2          | ASOTIN     | 2        | CLARKSTON       |          | MARIJUANA RENEWAL | HELLS CANYON CANNABIS COMPANY | 2797 TURNING POINTE LOOP     |            | CLARKSTON      | WA    | 994030000 |             |          |          |           |         | MARIJUANA PRODUCER TIER 1 | MARIJUANA PROCESSOR |            |            |            |            |            |            | LC CANNABIS SALES, LLC  | 20170930    | 
| 1491305410  | 413258  | 6033367320010001 |                                 | 27         | PIERCE     | 0        | UNINCORP. AREAS |          | MARIJUANA RENEWAL | THE GALLERY                   | 13005 PACIFIC AVE SOUTH      |            | TACOMA         | WA    | 984440000 |             |          |          |           |         | MARIJUANA RETAILER        | MEDICAL MARIJUANA   |            |            |            |            |            |            | GRAYBEARD HOLDINGS LLC  | 20170930    | 
| 1491305410  | 412698  | 6040431000010001 | SNOHOMISH COUNTY EXECUTIVE      | 31         | SNOHOMISH  | 0        | UNINCORP. AREAS |          | MARIJUANA RENEWAL | COOKIE CUTTER FARMS, LLC      | 23410 HIDDEN VALLEY RD STE A |            | GRANITE FALLS  | WA    | 982523600 |             |          |          |           |         | MARIJUANA PRODUCER TIER 1 |                     |            |            |            |            |            |            | COOKIE CUTTER FARMS LLC | 20170930    | 
| 1491305410  | 416493  | 6034358530010001 | ATTN: SIU DET TERRY KRAUSE      | 27         | PIERCE     | 17       | TACOMA          |          | MARIJUANA RENEWAL | SWEET PACK                    | 3311 S LAWRENCE ST           |            | TACOMA         | WA    | 984094712 |             |          |          |           |         | MARIJUANA PROCESSOR       |                     |            |            |            |            |            |            | SWEET PACK, LLC.        | 20170930    | 
| 1491305410  | 412984  | 6030492380010002 | COUNTY MANAGER                  | 34         | THURSTON   | 0        | UNINCORP. AREAS |          | MARIJUANA RENEWAL | WAREHOUSE 420                 | 21847 LEE RD SW              |            | CENTRALIA      | WA    | 985319700 |             |          |          |           |         | MARIJUANA PRODUCER TIER 2 | MARIJUANA PROCESSOR |            |            |            |            |            |            | A MAGICAL GARDEN LLC    | 20170930    | 
| 1491305410  | 413479  | 6033364470010001 | ATTN: TERESA EIDEM              | 17         | KING       | 26       | SEATTLE         |          | MARIJUANA RENEWAL | QUEEN ANNE CANNABIS CO        | 312 W REPUBLICAN ST          |            | SEATTLE        | WA    | 981194009 |             |          |          |           |         | MARIJUANA RETAILER        | MEDICAL MARIJUANA   |            |            |            |            |            |            | GREEN ANNE LLC          | 20170930    | 
| 1491305410  | 413427  | 6027629820010002 |                                 | 18         | KITSAP     | 0        | UNINCORP. AREAS |          | MARIJUANA RENEWAL | HWY 420                       | 11493 CLEAR CREEK RD         |            | SILVERDALE     | WA    | 983839657 |             |          |          |           |         | MARIJUANA RETAILER        | MEDICAL MARIJUANA   |            |            |            |            |            |            | A.A.C.E. THERAPY LLC    | 20170930    | 
| 1491305410  | 414042  | 6033303330010002 | SNOHOMISH COUNTY EXECUTIVE      | 31         | SNOHOMISH  | 0        | UNINCORP. AREAS |          | MARIJUANA RENEWAL | PROHIBITION BRANDS            | 22521 100TH ST SE STE A      |            | MONROE         | WA    | 982727794 |             |          |          |           |         | MARIJUANA PRODUCER TIER 3 | MARIJUANA PROCESSOR |            |            |            |            |            |            | PROHIBITION BRANDS INC  | 20170930    | 
| 1491305410  | 412527  | 6040334580010001 | CITY CLERK OF SPOKANE VALLEY    | 32         | SPOKANE    | 13       | SPOKANE VALLEY  |          | MARIJUANA RENEWAL | PINNACLE CANNABIS LLC         | 3524 N EDEN RD STE B         |            | SPOKANE VALLEY | WA    | 992161740 |             |          |          |           |         | MARIJUANA PRODUCER TIER 1 | MARIJUANA PROCESSOR |            |            |            |            |            |            | PINNACLE CANNABIS, LLC  | 20170930    | 
| 1491305410  | 417227  | 6033586870010002 | SEDRO-WOOLLEY POLICE DEPARTMENT | 29         | SKAGIT     | 8        | SEDRO WOOLLEY   |          | MARIJUANA RENEWAL | GREEN RIDGE PRODUCTIONS       | 1578 MOORE ST                |            | SEDRO WOOLLEY  | WA    | 982047523 |             |          |          |           |         | MARIJUANA PRODUCER TIER 3 | MARIJUANA PROCESSOR |            |            |            |            |            |            | GREEN RIDGE PRODUCTIONS | 20170930    | 
```