# Housing Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housing-permits) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/fesm-tgxf) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/fesm-tgxf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/fesm-tgxf/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | fesm-tgxf |
| Name | Housing Permits |
| Attribution | Baltimore Housing's Office of Permits & Building Inspections |
| Category | Housing & Development |
| Tags | permits, housing |
| Created | 2015-06-01T15:18:20Z |
| Publication Date | 2016-01-08T22:54:10Z |

## Description

Baltimore Housing's Office of Permits & Building Inspections enforces the Baltimore City Building Code, as well as state laws pertaining to construction and occupancy. This office issues building permits and provides subsequent inspections for; construction, alteration, electrical, mechanical and plumbing work in both commercial and residential structures. File your completed application in person at: The One- Stop Shop, 417 E. Fayette St., Room 100. Not sure if your project requires a permit? Call us at 410-396-3360

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | casenum           | CaseNum           | text          | text          |
| Yes      | series tag     | block             | Block             | text          | text          |
| Yes      | series tag     | lot               | Lot               | text          | text          |
| No       |                | propertyaddress   | PropertyAddress   | text          | text          |
| Yes      | series tag     | permitnum         | PermitNum         | text          | text          |
| Yes      | time           | dateissue         | DateIssue         | calendar_date | calendar_date |
| Yes      | series tag     | permitdescription | PermitDescription | text          | text          |
| Yes      | numeric metric | cost_est          | Cost_Est          | money         | money         |
| No       |                | dateexpire        | DateExpire        | calendar_date | calendar_date |
| Yes      | series tag     | prop_use          | Prop_Use          | text          | text          |
| Yes      | series tag     | existing_use      | Existing_Use      | text          | text          |
| Yes      | series tag     | neighborhood      | Neighborhood      | text          | text          |
| Yes      | series tag     | policedistrict    | PoliceDistrict    | text          | text          |
| Yes      | series tag     | councildistrict   | CouncilDistrict   | text          | text          |
```

## Time Field

```ls
Value = dateissue
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = propertyaddress,dateexpire
```

## Data Commands

```ls
series e:fesm-tgxf d:2007-08-21T00:00:00.000Z t:casenum=COM2007-25403 t:neighborhood=BELAIR-EDISON t:lot=091 t:block=4150 t:permitdescription="supply and install solar hot water heater" t:prop_use=SF t:permitnum=COM2007-25403 t:existing_use=SF m:cost_est=8000

series e:fesm-tgxf d:2011-10-27T00:00:00.000Z t:casenum=COM2011-23540 t:neighborhood=CEDONIA t:lot=017 t:block=6072F t:permitdescription="*loan grant* replace 4"" pvc sewer from house to connection as per code." t:prop_use=SF t:permitnum=COM2011-23540 t:existing_use=SF m:cost_est=6286

series e:fesm-tgxf d:2011-10-28T00:00:00.000Z t:casenum=COM2011-23541 t:neighborhood=REMINGTON t:lot=044 t:block=3630B t:permitdescription="10 points of protection for low voltage security equipment. work done to code" t:prop_use=COM t:permitnum=COM2011-23541 t:existing_use=COM m:cost_est=500
```

## Meta Commands

```ls
metric m:cost_est p:double l:Cost_Est t:dataTypeName=money

entity e:fesm-tgxf l:"Housing Permits" t:attribution="Baltimore Housing's Office of Permits & Building Inspections" t:url=https://data.baltimorecity.gov/api/views/fesm-tgxf

property e:fesm-tgxf t:meta.view v:id=fesm-tgxf v:category="Housing & Development" v:attributionLink=http://www.baltimorehousing.org/permits v:averageRating=0 v:name="Housing Permits" v:attribution="Baltimore Housing's Office of Permits & Building Inspections"

property e:fesm-tgxf t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:fesm-tgxf t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:fesm-tgxf t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| casenum       | block | lot | propertyaddress       | permitnum     | dateissue           | permitdescription                                                             | cost_est | dateexpire          | prop_use | existing_use | neighborhood     | policedistrict | councildistrict | 
| ============= | ===== | === | ===================== | ============= | =================== | ============================================================================= | ======== | =================== | ======== | ============ | ================ | ============== | =============== | 
| COM2007-25403 | 4150  | 091 | 2801 CHESTERFIELD AVE | COM2007-25403 | 2007-08-21T00:00:00 | supply and install solar hot water heater                                     | 8000.00  | 2008-02-20T00:00:00 | SF       | SF           | BELAIR-EDISON    |                |                 | 
| PLM2011-00710 | 4979  | 067 | 135 FIRESIDE CIR      | PLM2011-00710 | 2011-03-24T00:00:00 | water heater replacement                                                      |          | 2012-09-24T11:37:00 |          |              | BELLONA-GITTINGS |                |                 | 
| PLM2011-00711 | 4074  | 007 | 601 E 31ST ST         | PLM2011-00711 | 2011-03-24T00:00:00 | water heater replacement                                                      |          | 2012-09-24T11:37:00 |          |              | BETTER WAVERLY   |                |                 | 
| COM2011-23540 | 6072F | 017 | 5533 WHITWOOD ROAD    | COM2011-23540 | 2011-10-27T00:00:00 | *loan grant* replace 4" pvc sewer from house to connection as per code.       | 6286.00  | 2012-04-27T00:00:00 | SF       | SF           | CEDONIA          |                |                 | 
| PLM2011-00712 | 0340  | 017 | 1730 MCCULLOH ST      | PLM2011-00712 | 2011-03-24T00:00:00 | water heater replacement                                                      |          | 2012-09-24T11:37:00 |          |              | UPTON            |                |                 | 
| COM2011-23541 | 3630B | 044 | 401 W 26TH ST         | COM2011-23541 | 2011-10-28T00:00:00 | 10 points of protection for low voltage security equipment. work done to code | 500.00   | 2012-04-28T00:00:00 | COM      | COM          | REMINGTON        |                |                 | 
| COM2011-23542 | 1831  | 004 | 2007 FLEET ST         | COM2011-23542 | 2011-10-27T00:00:00 | rewire existing ckt for two lights & two receptacles. as per code.            | 250.00   | 2012-04-27T00:00:00 | SF       | SF           | FELLS POINT      |                |                 | 
| PLM2011-00713 | 4044  | 014 | 1116 GORSUCH AVE      | PLM2011-00713 | 2011-03-24T00:00:00 | water heater replacement                                                      |          | 2012-09-24T11:37:00 |          |              | BETTER WAVERLY   |                |                 | 
| PLM2011-00714 | 3423  | 002 | 2222 MADISON AVE      | PLM2011-00714 | 2011-03-24T00:00:00 | water heater replacement                                                      |          | 2012-09-24T11:37:00 |          |              | RESERVOIR HILL   |                |                 | 
| PLM2011-00715 | 2018B | 037 | 1456 DECATUR ST       | PLM2011-00715 | 2011-03-24T00:00:00 | water heater replacement                                                      |          | 2012-09-24T11:37:00 |          |              | LOCUST POINT     |                |                 | 
```