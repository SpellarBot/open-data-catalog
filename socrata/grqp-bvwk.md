# Historical Inspection Requests

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historical-inspection-requests) |
| Metadata | [Link](https://data.nola.gov/api/views/grqp-bvwk) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/grqp-bvwk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/grqp-bvwk/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | grqp-bvwk |
| Name | Historical Inspection Requests |
| Category | Housing, Land Use, and Blight |
| Tags | permit, violation, inspection, code enforcement, abo, zoning, legacy |
| Created | 2015-04-24T21:05:19Z |
| Publication Date | 2015-05-20T19:55:37Z |

## Description

This dataset includes requests for inspections not associated with issuance of a permit, beginning in November 1997 and ending in March 2005, from the Safety and Permits Information Network (SPIN). Inspection requests include complaints about violations of City code reported to Safety and Permits (e.g. building, zoning, and health codes) as well as non-complaint-related inspection requests for new business applications, alcoholic beverage outlets (ABO), zoning verifications, subdivisions, and address changes.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | complaintnumber  | ComplaintNumber  | text          | text          |
| Yes      | time           | recieveddate     | RecievedDate     | calendar_date | calendar_date |
| Yes      | numeric metric | housenum         | HouseNum         | number        | text          |
| Yes      | series tag     | streetdir        | StreetDir        | text          | text          |
| Yes      | series tag     | streetname       | StreetName       | text          | text          |
| Yes      | series tag     | streetsuffix     | StreetSuffix     | text          | text          |
| Yes      | series tag     | unitnumber       | UnitNumber       | text          | text          |
| No       |                | violationaddress | ViolationAddress | text          | text          |
| Yes      | series tag     | category         | Category         | text          | text          |
| Yes      | series tag     | violatorname     | ViolatorName     | text          | text          |
| Yes      | series tag     | parcelowner      | ParcelOwner      | text          | text          |
| Yes      | series tag     | zoning           | Zoning           | text          | text          |
| Yes      | series tag     | complaintmeth    | ComplaintMeth    | text          | text          |
| Yes      | series tag     | complainttype    | ComplaintType    | text          | text          |
| Yes      | series tag     | complaintclass   | ComplaintClass   | text          | text          |
| Yes      | series tag     | stopworkissued   | StopWorkIssued   | text          | text          |
| Yes      | series tag     | description      | Description      | text          | text          |
| Yes      | numeric metric | inspector        | Inspector        | number        | text          |
| Yes      | series tag     | resolutiontype   | ResolutionType   | text          | text          |
| No       |                | createdatetime   | CreateDateTime   | calendar_date | calendar_date |
| Yes      | series tag     | createopid       | CreateOpID       | text          | text          |
| No       |                | updatedatetime   | UpdateDateTime   | calendar_date | calendar_date |
| Yes      | series tag     | updateopid       | UpdateOpID       | text          | text          |
| Yes      | series tag     | propertykey      | PropertyKey      | text          | text          |
| No       |                | x                | X                | number        | number        |
| No       |                | y                | Y                | number        | number        |
```

## Time Field

```ls
Value = recieveddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = violationaddress,createdatetime,updatedatetime,x,y
```

## Data Commands

```ls
series e:grqp-bvwk d:2000-01-05T00:00:00.000Z t:propertykey=71643101700001 t:category=NEI t:createopid=MJC t:parcelowner="BENTLEY, YOLANDA" t:stopworkissued=N t:complaintnumber=T00000007 t:complaintclass=Z t:streetsuffix=ST t:complainttype=USE t:complaintmeth=TEL t:zoning=RD2 t:resolutiontype=OK t:streetname="HOLLY GROVE" m:housenum=4227

series e:grqp-bvwk d:2000-01-05T00:00:00.000Z t:createopid=JBJ t:complaintnumber=T00000023 t:resolutiontype=OK t:propertykey=20810170300005 t:parcelowner="CARBON, MARK B" t:category=NEI t:stopworkissued=N t:description="ILLEGAL B & B" t:complaintclass=Z t:streetsuffix=ST t:complainttype=USE t:complaintmeth=INS t:zoning=VCR1 t:streetname=BOURBON m:inspector=116 m:housenum=1209

series e:grqp-bvwk d:2000-01-07T00:00:00.000Z t:propertykey=37W41550600004 t:category=ANO t:createopid=LGW t:parcelowner="DAVIS, KLYDENITTA L" t:stopworkissued=N t:description="OPERATING BARBER SHOP FROM ACCESSORY BUILDING IN REAR YARD" t:complaintnumber=T00000025 t:complaintclass=Z t:streetsuffix=AV t:complainttype=ZON t:complaintmeth=LTR t:zoning=RD2 t:streetname=PARIS m:inspector=121 m:housenum=3817
```

## Meta Commands

```ls
metric m:housenum p:integer l:HouseNum t:dataTypeName=number

metric m:inspector p:integer l:Inspector t:dataTypeName=number

entity e:grqp-bvwk l:"Historical Inspection Requests" t:url=https://data.nola.gov/api/views/grqp-bvwk

property e:grqp-bvwk t:meta.view v:id=grqp-bvwk v:category="Housing, Land Use, and Blight" v:averageRating=0 v:name="Historical Inspection Requests"

property e:grqp-bvwk t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:grqp-bvwk t:meta.view.owner v:id=7kk9-bewq v:screenName="J.B. Raasch" v:displayName="J.B. Raasch"

property e:grqp-bvwk t:meta.view.tableauthor v:id=7kk9-bewq v:screenName="J.B. Raasch" v:roleName=administrator v:displayName="J.B. Raasch"

property e:grqp-bvwk t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| complaintnumber | recieveddate        | housenum | streetdir | streetname  | streetsuffix | unitnumber | violationaddress                           | category | violatorname | parcelowner                   | zoning | complaintmeth | complainttype | complaintclass | stopworkissued | description                                                | inspector | resolutiontype | createdatetime      | createopid | updatedatetime | updateopid | propertykey    | x                   | y                  | 
| =============== | =================== | ======== | ========= | =========== | ============ | ========== | ========================================== | ======== | ============ | ============================= | ====== | ============= | ============= | ============== | ============== | ========================================================== | ========= | ============== | =================== | ========== | ============== | ========== | ============== | =================== | ================== | 
| T00000007       | 2000-01-05T00:00:00 | 4227     |           | HOLLY GROVE | ST           |            | 4227 HOLLY GROVE ST, NEW ORLEANS, LA 70118 | NEI      |              | BENTLEY, YOLANDA              | RD2    | TEL           | USE           | Z              | N              |                                                            |           | OK             | 2000-01-05T08:00:00 | MJC        |                |            | 71643101700001 | 3666992.08133000000 | 538492.08454900000 | 
| T00000023       | 2000-01-05T00:00:00 | 1209     |           | BOURBON     | ST           |            | 1209 BOURBON ST, NEW ORLEANS, LA 6611      | NEI      |              | CARBON, MARK B                | VCR1   | INS           | USE           | Z              | N              | ILLEGAL B & B                                              | 116       | OK             | 2000-01-07T08:57:00 | JBJ        |                |            | 20810170300005 | 3683377.38058000000 | 534250.47000100000 | 
| T00000025       | 2000-01-07T00:00:00 | 3817     |           | PARIS       | AV           |            | 3817 PARIS AV, NEW ORLEANS, LA 70122       | ANO      |              | DAVIS, KLYDENITTA L           | RD2    | LTR           | ZON           | Z              | N              | OPERATING BARBER SHOP FROM ACCESSORY BUILDING IN REAR YARD | 121       |                | 2000-01-07T09:54:00 | LGW        |                |            | 37W41550600004 | 3679729.09096000000 | 546396.21408200000 | 
| T00000026       | 2000-01-07T00:00:00 | 3817     |           | PARIS       | AV           |            | 3817 PARIS AV, NEW ORLEANS, LA 70122       | ANO      |              | DAVIS, KLYDENITTA L           | RD2    | LTR           | ZON           | Z              | N              | OPERATING BARBER SHOP FROM ACCESSORY BUILDING IN REAR YARD | 121       |                | 2000-01-07T10:25:00 | LGW        |                |            | 37W41550600004 | 3679729.09096000000 | 546396.21408200000 | 
| T00000028       | 2000-01-07T00:00:00 | 3817     |           | PARIS       | AV           |            | 3817 PARIS AV, NEW ORLEANS, LA 70122       | ANO      |              | DAVIS, KLYDENITTA L           | RD2    | LTR           | ZON           | Z              | N              | OPERATING BARBER SHOP FROM ACCESSORY BUILDING IN REAR YARD | 121       | OK             | 2000-01-07T10:50:00 | LGW        |                |            | 37W41550600004 | 3679729.09096000000 | 546396.21408200000 | 
| T00000031       | 2000-01-07T00:00:00 | 1741     |           | FORSTALL    | ST           |            | 1741 FORSTALL ST, NEW ORLEANS, LA 70125    | INS      |              | JENKINS, WILLIAM              | B1A    | INS           | LIC           | Z              | N              | GROCERY STORE                                              | 121       |                | 2000-01-07T11:40:00 | LGW        |                |            | 39W40970900001 | 3697040.06848000000 | 536736.82920100000 | 
| T00000055       | 2000-01-11T00:00:00 | 2824     |           | URQUHART    | ST           |            | 2824 URQUHART ST, NEW ORLEANS, LA 70119    | INS      |              | MORGAN, FRED                  | HI     | INS           | ZON           | Z              | N              | ILLEGAL ROOMING HOUST                                      | 115       | OK             | 2000-01-11T09:45:00 | JBJ        |                |            | 39W30381100001 | 3688048.60648000000 | 536900.40433300000 | 
| T00000088       | 2000-01-13T00:00:00 | 1641     |           | FORSTALL    | ST           |            | 1641 FORSTALL ST, NEW ORLEANS, LA 70117    | INS      |              | SIMON, MATTIE M               | NCZ    | INS           | LIC           | Z              | N              | ALCOHOLIC BEVERAGE APPLICATION                             | 121       |                | 2000-01-13T10:54:00 | LGW        |                |            | 39W40521600001 | 3696941.06573000000 | 536360.45068900000 | 
| T00000089       | 2000-01-13T00:00:00 | 5600     | N         | JOHNSON     | ST           |            | 5600 N JOHNSON ST, NEW ORLEANS, LA 70117   | INS      |              | DANNY & REBECCA, NC A LA CORP | NZC    | INS           | LIC           | Z              | N              | RETAIL GROCERY                                             | 121       |                | 2000-01-13T10:57:00 | LGW        |                |            | 39W50281100003 | 3698953.64208000000 | 537099.49776700000 | 
| T00000090       | 2000-01-13T00:00:00 | 3815     |           | FRENCHMEN   | ST           |            | 3815 FRENCHMEN ST, NEW ORLEANS, LA 70122   | INS      |              | WILLIAMS, AUGUST              | C1A    | INS           | LIC           | Z              | N              | PERSONAL TRAINING CENTER                                   | 121       |                | 2000-01-13T10:58:00 | LGW        |                |            | 37W41511000001 | 3683833.49089000000 | 546733.65599200000 | 
```