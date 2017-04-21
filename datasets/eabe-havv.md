# DOB Complaints Received

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dob-complaints-received-5a218) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/eabe-havv) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/eabe-havv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/eabe-havv/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | eabe-havv |
| Name | DOB Complaints Received |
| Attribution | Department of Buildings (DOB) |
| Category | Housing & Development |
| Tags | complaints, dob, buildings |
| Created | 2013-04-18T15:19:10Z |
| Publication Date | 2017-04-20T20:07:37Z |

## Description

A list of complaints received and associated data. Prior monthly reports are archived at DOB and are not available on NYC Open Data.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | complaint_number   | Complaint Number   | text          | text          |
| Yes      | series tag  | status             | Status             | text          | text          |
| No       |             | date_entered       | Date Entered       | text          | text          |
| Yes      | series tag  | house_number       | House Number       | text          | text          |
| Yes      | series tag  | zip_code           | ZIP Code           | text          | text          |
| Yes      | series tag  | house_street       | House Street       | text          | text          |
| Yes      | series tag  | bin                | BIN                | text          | text          |
| Yes      | series tag  | community_board    | Community Board    | text          | text          |
| Yes      | series tag  | special_district   | Special District   | text          | text          |
| Yes      | series tag  | complaint_category | Complaint Category | text          | text          |
| Yes      | series tag  | unit               | Unit               | text          | text          |
| No       |             | disposition_date   | Disposition Date   | text          | text          |
| Yes      | series tag  | disposition_code   | Disposition Code   | text          | text          |
| No       |             | inspection_date    | Inspection Date    | text          | text          |
| Yes      | time        | dobrundate         | DOBRunDate         | calendar_date | calendar_date |
```

## Time Field

```ls
Value = dobrundate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_entered,disposition_date,inspection_date
```

## Data Commands

```ls
series e:eabe-havv d:2013-04-26T00:00:00.000Z t:unit=QNS. t:house_number=10 t:complaint_category=05 t:status=CLOSED t:complaint_number=4483428 t:disposition_code=L3 t:bin=4298330 t:house_street="MUHLEBACH COURT" t:community_board=414 m:row_number.eabe-havv=1

series e:eabe-havv d:2013-04-26T00:00:00.000Z t:unit=SCFLD t:house_number=157 t:complaint_category=23 t:status=CLOSED t:complaint_number=1347475 t:disposition_code=A8 t:bin=1004077 t:house_street="BROOME STREET" t:community_board=103 m:row_number.eabe-havv=2

series e:eabe-havv d:2013-04-26T00:00:00.000Z t:unit=SCFLD t:house_number=157 t:complaint_category=23 t:status=CLOSED t:complaint_number=1347579 t:disposition_code=I1 t:bin=1004077 t:house_street="BROOME STREET" t:community_board=103 m:row_number.eabe-havv=3
```

## Meta Commands

```ls
metric m:row_number.eabe-havv p:long l:"Row Number"

entity e:eabe-havv l:"DOB Complaints Received" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/eabe-havv

property e:eabe-havv t:meta.view v:id=eabe-havv v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/dob/html/codes_and_reference_materials/foilmonthly.shtml#complaint v:averageRating=0 v:name="DOB Complaints Received" v:attribution="Department of Buildings (DOB)"

property e:eabe-havv t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:eabe-havv t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| complaint_number | status | date_entered | house_number | zip_code | house_street    | bin     | community_board | special_district | complaint_category | unit  | disposition_date | disposition_code | inspection_date | dobrundate          | 
| ================ | ====== | ============ | ============ | ======== | =============== | ======= | =============== | ================ | ================== | ===== | ================ | ================ | =============== | =================== | 
| 4483428          | CLOSED | 06/08/2011   | 10           |          | MUHLEBACH COURT | 4298330 | 414             |                  | 05                 | QNS.  | 04/25/2013       | L3               | 04/25/2013      | 2013-04-26T00:00:00 | 
| 1347475          | CLOSED | 04/23/2013   | 157          |          | BROOME STREET   | 1004077 | 103             |                  | 23                 | SCFLD | 04/25/2013       | A8               | 04/25/2013      | 2013-04-26T00:00:00 | 
| 1347579          | CLOSED | 04/25/2013   | 157          |          | BROOME STREET   | 1004077 | 103             |                  | 23                 | SCFLD | 04/25/2013       | I1               | 04/25/2013      | 2013-04-26T00:00:00 | 
| 1347578          | ACTIVE | 04/25/2013   | 157          |          | BROOME STREET   | 1004077 | 103             |                  | 35                 | MAN.  |                  |                  |                 | 2013-04-26T00:00:00 | 
| 1347627          | ACTIVE | 04/25/2013   | 561          |          | BROADWAY        | 1007574 | 102             |                  | 05                 | MAN.  |                  |                  |                 | 2013-04-26T00:00:00 | 
| 1340897          | ACTIVE | 01/08/2013   | 191          |          | WEST 10 STREET  | 1011217 | 102             |                  | 05                 | MAN.  | 04/25/2013       | C1               | 04/23/2013      | 2013-04-26T00:00:00 | 
| 1347635          | ACTIVE | 04/25/2013   | 501          |          | 10 AVENUE       | 1012527 | 104             |                  | 45                 | MAN.  |                  |                  |                 | 2013-04-26T00:00:00 | 
| 1347334          | CLOSED | 04/22/2013   | 599          |          | 6 AVENUE        | 1014658 | 104             |                  | 73                 | MAN.  | 04/25/2013       | I2               | 04/24/2013      | 2013-04-26T00:00:00 | 
| 1347576          | CLOSED | 04/25/2013   | 42           |          | WEST 29 STREET  | 1015742 | 105             |                  | 12                 | BEST  | 04/25/2013       | H1               | 04/25/2013      | 2013-04-26T00:00:00 | 
| 1347612          | ACTIVE | 04/25/2013   | 42           |          | WEST 29 STREET  | 1015742 | 105             |                  | 10                 | ERT   |                  |                  |                 | 2013-04-26T00:00:00 | 
```