# FOIA Request Log - Water Management

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-water-management-4bb3b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/cxfr-dd4a) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/cxfr-dd4a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/cxfr-dd4a/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | cxfr-dd4a |
| Name | FOIA Request Log - Water Management |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2011-09-29T20:47:06Z |
| Publication Date | 2017-03-24T21:07:55Z |

## Description

FOIA requests received by Water Management as of May 1, 2010

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | requestor_name         | REQUESTOR NAME         | text          | text          |
| Yes      | series tag  | organization           | ORGANIZATION           | text          | text          |
| Yes      | series tag  | description_of_request | DESCRIPTION OF REQUEST | text          | text          |
| No       |             | date_received          | DATE RECEIVED          | calendar_date | calendar_date |
| Yes      | time        | due_date               | DUE DATE               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = due_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_received
```

## Data Commands

```ls
series e:cxfr-dd4a d:2012-04-02T00:00:00.000Z t:description_of_request="Contractor invoice, contractor and subcontractor...for City of Chicago Contract #3547 titled...payment vouchers submitted to the City of Chicago...voucher# PV88108801301 pay date: 4/16/10, voucher# PV88108802914 pay date 6/29/10?" t:organization="Ancor Mechanical Inc" t:requestor_name="Kevin Kenzinger" m:row_number.cxfr-dd4a=1

series e:cxfr-dd4a d:2012-04-02T00:00:00.000Z t:description_of_request="? 525 W 56th Place
? 539 W 56th Place
? 401 W 57th Street
? 407 , 414, 415, 424 W 57th Place
? 402, 410 W 58th Street
? 501, 513, and 547 W 58th Street
Are these properties are connected to the municipal sanitary sewer?" t:organization=AECOM t:requestor_name="Leann Ippolito" m:row_number.cxfr-dd4a=2

series e:cxfr-dd4a d:2012-04-23T00:00:00.000Z t:description_of_request="Any and all requests for water and sewer work, including
but not limited to requests for dis-continuation of service and reports of a water main
or other pipes leaking or broken?" t:organization=Attorney t:requestor_name="David M. Jankura" m:row_number.cxfr-dd4a=3
```

## Meta Commands

```ls
metric m:row_number.cxfr-dd4a p:long l:"Row Number"

entity e:cxfr-dd4a l:"FOIA Request Log - Water Management" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/cxfr-dd4a

property e:cxfr-dd4a t:meta.view v:id=cxfr-dd4a v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Water Management" v:attribution="City of Chicago"

property e:cxfr-dd4a t:meta.view.owner v:id=yjrp-dnam v:screenName=garyl v:displayName=garyl

property e:cxfr-dd4a t:meta.view.tableauthor v:id=yjrp-dnam v:screenName=garyl v:roleName=editor v:displayName=garyl
```

## Top Records

```ls
| requestor_name               | organization                  | description_of_request                                                                                                                                                                                                                | date_received | due_date            | 
| ============================ | ============================= | ===================================================================================================================================================================================================================================== | ============= | =================== | 
| Kevin Kenzinger              | Ancor Mechanical Inc          | Contractor invoice, contractor and subcontractor...for City of Chicago Contract #3547 titled...payment vouchers submitted to the City of Chicago...voucher# PV88108801301 pay date: 4/16/10, voucher# PV88108802914 pay date 6/29/10? |               | 2012-04-02T00:00:00 | 
| Leann Ippolito               | AECOM                         | ? 525 W 56th Place ? 539 W 56th Place ? 401 W 57th Street ? 407 , 414, 415, 424 W 57th Place ? 402, 410 W 58th Street ? 501, 513, and 547 W 58th Street Are these properties are connected to the municipal sanitary sewer?           |               | 2012-04-02T00:00:00 | 
| David M. Jankura             | Attorney                      | Any and all requests for water and sewer work, including but not limited to requests for dis-continuation of service and reports of a water main or other pipes leaking or broken?                                                    |               | 2012-04-23T00:00:00 | 
| Austin Hahn                  | Austin J. Hahn, P.E., LEED-AP | the SW corner of Broadway and Devon Water and Sewer Main Atlasses Water and Sewer Main Inspection Reports Water and Sewer Project and Construction Reports                                                                            |               | 2012-04-03T00:00:00 | 
| David Durham                 | Self                          | had a new water line installed from the water main to my house last November. I am trying to verify through public records that all necessary permits and inspections were performed as the contractor indicated                      |               | 2012-04-04T00:00:00 | 
| Michael R. Schumann          | Cohon Raizes & Regal LLP      | any records made after receiving phone calls to the City of Chicago Department of Water Management from a Mr. Joseph Valentino II or Patricia Valentino about their property located at 5954 N. Ozanam Ave...deemed "vacant"          |               | 2012-04-05T00:00:00 | 
| Brittany Hanlon              | Nielsen, Zehe & Antas, PC     | could please provide copies of any investigative reports, shift work reports, contract between the City and Kenny Construction, as well as video footage of the completed lining work.                                                |               | 2012-04-06T00:00:00 | 
| Joseph Star / Frank Gagliano | Self                          | Water sewer and SR records for the address of 4633 N. Leamington, Chicago IL for 2005-2007.                                                                                                                                           |               | 2012-04-09T00:00:00 | 
| Aaron Surrain                | self                          | water management department to help me determine whether or not the following 3 properties are legal (or can be legal) 2 flats. 4236 N Sawyer 4052 N Francisco 4057 N Whipple                                                         |               | 2012-04-10T00:00:00 | 
| GINA LAROCCO                 | Self                          | ADRESS 1500-1502 E 73RD PLACE CHICAGO I L 60619 REQUESTING HOW MANY UNITS YOU SHOW FOR THIS BUILDING THRUOUT THE ALL THE YEARS                                                                                                        |               | 2012-04-11T00:00:00 | 
```