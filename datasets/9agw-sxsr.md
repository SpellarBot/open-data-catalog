# 311 Customer Service Requests

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-customer-service-requests-7e16d) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/9agw-sxsr) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/9agw-sxsr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/9agw-sxsr/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 9agw-sxsr |
| Name | 311 Customer Service Requests |
| Attribution | MOIT |
| Category | City Services |
| Tags | 311, csr |
| Created | 2011-01-25T03:50:56Z |
| Publication Date | 2017-01-19T16:18:46Z |

## Columns

```ls
| Included | Schema Type | Field Name        | Name             | Data Type | Render Type |
| ======== | =========== | ================= | ================ | ========= | =========== |
| Yes      | series tag  | srrecordid        | SRRecordID       | text      | number      |
| Yes      | series tag  | servicerequestnum | ServiceRequesNum | text      | text        |
| Yes      | series tag  | codedescription   | SRType           | text      | text        |
| Yes      | series tag  | agency            | Agency           | text      | text        |
| Yes      | series tag  | neighborhood      | Neighborhood     | text      | text        |
| No       |             | address           | StreetAddress    | text      | text        |
| Yes      | series tag  | zip               | ZipCode          | text      | text        |
| Yes      | series tag  | methodreceived    | MethodReceived   | text      | text        |
| Yes      | series tag  | status            | SRStatus         | text      | text        |
| Yes      | time        | createddate       | CreatedDate      | date      | date        |
| No       |             | statusdate        | StatusDate       | date      | date        |
| No       |             | duedate           | DueDate          | date      | date        |
| Yes      | series tag  | activity          | LastActivity     | text      | text        |
| Yes      | series tag  | outcome           | Outcome          | text      | text        |
| No       |             | updateddate       | LastActivityDate | date      | date        |
```

## Time Field

```ls
Value = createddate
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,statusdate,duedate,updateddate
```

## Data Commands

```ls
series e:9agw-sxsr d:2015-02-01T08:12:00.000Z t:zip=21224 t:methodreceived=Interface t:status=CLOSED t:codedescription="WW Water Leak (Exterior)" t:neighborhood=CANTON t:srrecordid=1094344940 t:agency="Bureau of Water and Waste Water" t:outcome=UPDATED t:activity="Cityworks SR Comments" t:servicerequestnum=15-00072082 m:row_number.9agw-sxsr=1

series e:9agw-sxsr d:2015-02-01T08:48:00.000Z t:zip=21224 t:methodreceived=Interface t:status=CLOSED t:codedescription="BCLB-Liquor License Complaint" t:neighborhood=GREEKTOWN t:srrecordid=1094344982 t:agency="Liquor License Board" t:outcome=Closed t:activity="Dispatch Investigator" t:servicerequestnum=15-00072083 m:row_number.9agw-sxsr=2

series e:9agw-sxsr d:2015-02-01T09:13:00.000Z t:zip=21223 t:methodreceived=Phone t:status=HOLDLOCK t:codedescription="WW Hydrant Open" t:neighborhood=MILLHILL t:srrecordid=1094345013 t:agency="Bureau of Water and Waste Water" t:outcome=UPDATED t:activity="Cityworks SR Comments" t:servicerequestnum=15-00072084 m:row_number.9agw-sxsr=3
```

## Meta Commands

```ls
metric m:row_number.9agw-sxsr p:long l:"Row Number"

entity e:9agw-sxsr l:"311 Customer Service Requests" t:attribution=MOIT t:url=https://data.baltimorecity.gov/api/views/9agw-sxsr

property e:9agw-sxsr t:meta.view v:id=9agw-sxsr v:category="City Services" v:attributionLink=http://www.baltimorecity.gov/OfficeoftheMayor/MayoralOffices/InformationTechnology.aspx v:averageRating=0 v:name="311 Customer Service Requests" v:attribution=MOIT

property e:9agw-sxsr t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:9agw-sxsr t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:9agw-sxsr t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| srrecordid | servicerequestnum | codedescription               | agency                                  | neighborhood                     | address             | zip   | methodreceived | status   | createddate | statusdate | duedate    | activity              | outcome                            | updateddate | 
| ========== | ================= | ============================= | ======================================= | ================================ | =================== | ===== | ============== | ======== | =========== | ========== | ========== | ===================== | ================================== | =========== | 
| 1094344940 | 15-00072082       | WW Water Leak (Exterior)      | Bureau of Water and Waste Water         | CANTON                           | 1013 S CLINTON ST   | 21224 | Interface      | CLOSED   | 1422778320  | 1422814980 | 1422951120 | Cityworks SR Comments | UPDATED                            |             | 
| 1094344982 | 15-00072083       | BCLB-Liquor License Complaint | Liquor License Board                    | GREEKTOWN                        | 500 S LEHIGH ST     | 21224 | Interface      | CLOSED   | 1422780480  | 1424293920 | 1426924080 | Dispatch Investigator | Closed                             |             | 
| 1094345013 | 15-00072084       | WW Hydrant Open               | Bureau of Water and Waste Water         | MILLHILL                         | 2600 WILKENS AVE    | 21223 | Phone          | HOLDLOCK | 1422781980  | 1422788820 | 1422868380 | Cityworks SR Comments | UPDATED                            |             | 
| 1094345094 | 15-00072085       | TRM-Snow/Icy Conditions       | Department of Transportation            | MEDFIELD                         | 4496 83 N           | 21209 | Phone          | CLOSED   | 1422782640  | 1423089660 | 1422869040 | Cityworks SR Comments | UPDATED                            |             | 
| 1094345124 | 15-00072086       | TRM-Snow/Icy Conditions       | Department of Transportation            | EAST BALTIMORE MIDWAY            | 732 BARTLETT AVE    | 21218 | Phone          | CLOSED   | 1422782940  | 1422997740 | 1422869340 | Cityworks SR Comments | UPDATED                            |             | 
| 1094345153 | 15-00072087       | TRM-Snow/Icy Conditions       | Department of Transportation            | HARFORD-ECHODALE/PERRING PARKWAY | 7308 OLD HARFORD RD | 21234 | Interface      | DUPCLOSD | 1422783000  | 1423049400 | 1422869400 | NULL                  | NULL                               |             | 
| 1094345221 | 15-00072089       | TRT-Traffic Signal Repairs    | Department of Transportation            | MADISON PARK                     | 900 MADISON AVE     | 21201 | Phone          | CLOSED   | 1422783360  | 1422795780 | 1422869760 | Work Completed        | No Trouble Found                   |             | 
| 1094345314 | 15-00072090       | SW-Dirty Alley                | Bureau of Solid Waste                   | FOUR BY FOUR                     | 3331 RAVENWOOD AVE  | 21213 | Phone          | CLOSED   | 1422789600  | 1423013100 | 1423394400 | Dispatch Work Crew    | Cleaned and removed debris (Close) |             | 
| 1094345372 | 15-00072091       | ECC-Miscellaneous Request     | Mayors Office of Information Technology | HOLLINS MARKET                   | 1100 W LOMBARD ST   | 21223 | Interface      | CLOSED   | 1422791400  | 1422811860 | 1423223400 | Abate                 | Police issues must be called in.   |             | 
| 1094345398 | 15-00072092       | BGE-StLight(s) Out Rear       | Department of Transportation            | BELAIR-EDISON                    | 3434 BELAIR RD      | 21213 | Interface      | CLOSED   | 1422792420  | 1422862740 | 1423138020 | NULL                  | NULL                               |             | 
```