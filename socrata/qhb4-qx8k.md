# CDPH Asbestos and Demolition Notification

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdph-asbestos-and-demolition-notification-627a5) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/qhb4-qx8k) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/qhb4-qx8k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/qhb4-qx8k/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | qhb4-qx8k |
| Name | CDPH Asbestos and Demolition Notification |
| Category | Environment & Sustainable Development |
| Created | 2012-10-08T02:48:02Z |
| Publication Date | 2017-04-19T17:36:09Z |

## Description

CDPH Asbetos and Demolition Notification
Notices of Intent (NOI) for demolition and asbestos abatement per Chapter 11 -4  Article XVIII of the Municipal Code ( see http://tinyurl.com/crvyb29) submitted to the Department of Environment (DOE) for work started January, 1993 to December 31, 2011 or submitted to the Department of Public Health (CDPH) for work beginning on or after January 1, 2012. On January 1, 2012, the DOE was disbanded and all its inspection, permitting, and enforcement authorities were transferred to the CDPH.   
Data fields requiring description are detailed below. 
NOTIFICATION TYPE: Specifies the type of NOI submitted: NOI DEMO/RENOVATIONion or  NOI NESHAP (National Emission Standards for Hazardous Air Pollutants).   
MAPPED LOCATION: Contains latitude/longitude coordinates of the site as determined through the Chicago Open Data Portal?s geocoding engine. In instances where the facility address is a range, the lower number (the value in the ?Street Number From? column) is used for geocoding. For example, for the range address 1000-1005 S Wabash Ave, the Mapped Location would be the coordinates for 1000 S Wabash Ave. 
 OWNER/APPLICANT:  The owner or entity that submitted the NOI.  
START DATE: The proposed start date of work as reported in the NOI.  
END DATE: The proposed finish date of work as reported in the NOI.  
COMMENT: Additional information relating to the NOI that may include location information, property description, actual start and finish dates, field observations, and status of work. 
DATA SOURCE: The city department that collected the data.

## Columns

```ls
| Included | Schema Type | Field Name        | Name               | Data Type     | Render Type   |
| ======== | =========== | ================= | ================== | ============= | ============= |
| Yes      | series tag  | notification_type | NOTIFICATION TYPE  | text          | text          |
| Yes      | series tag  | street_number     | STREET NUMBER FROM | text          | number        |
| Yes      | series tag  | street_number_to  | STREET NUMBER TO   | text          | number        |
| Yes      | series tag  | direction         | DIRECTION          | text          | text          |
| Yes      | series tag  | street_name       | STREET NAME        | text          | text          |
| Yes      | series tag  | street_type       | STREET TYPE        | text          | text          |
| Yes      | series tag  | notification_from | OWNER/APPLICANT    | text          | text          |
| Yes      | time        | start_date        | START DATE         | calendar_date | calendar_date |
| No       |             | end_date          | END DATE           | calendar_date | calendar_date |
| Yes      | series tag  | comment           | COMMENT            | text          | text          |
| Yes      | series tag  | data_source       | DATA SOURCE        | text          | text          |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date
```

## Data Commands

```ls
series e:qhb4-qx8k d:2017-04-19T16:29:25.000Z t:direction=Direction t:notification_type="Notification Type" t:data_source="Data Source" t:street_name="Street Name" t:comment=Comment t:notification_from=Applicant t:street_type="Street Type" m:row_number.qhb4-qx8k=1

series e:qhb4-qx8k d:2000-06-09T00:00:00.000Z t:direction=W t:notification_type="NOI DEMO/RENOVATION" t:data_source="HISTORIC DEPT. OF ENVIRONMENT" t:street_name="IRVING PARK" t:street_number=1 t:notification_from="PUBLIC BLDG. COMM. OF CHICAGO" t:street_type=RD m:row_number.qhb4-qx8k=2

series e:qhb4-qx8k d:2015-07-01T00:00:00.000Z t:direction=W t:notification_type="NOI DEMO/RENOVATION" t:data_source="DEPT. OF PUBLIC HEALTH" t:street_name=O'HARE t:street_number=10000 t:comment="10000 W O'HARE AVE  DEMOLITION NOTICE COMMERCIAL/INDUSTRIAL" t:notification_from="MIDWEST REM ENTERPRISES" m:row_number.qhb4-qx8k=3
```

## Meta Commands

```ls
metric m:row_number.qhb4-qx8k p:long l:"Row Number"

entity e:qhb4-qx8k l:"CDPH Asbestos and Demolition Notification" t:url=https://data.cityofchicago.org/api/views/qhb4-qx8k

property e:qhb4-qx8k t:meta.view v:id=qhb4-qx8k v:category="Environment & Sustainable Development" v:averageRating=0 v:name="CDPH Asbestos and Demolition Notification"

property e:qhb4-qx8k t:meta.view.owner v:id=e3v2-km8a v:screenName=Renante v:displayName=Renante

property e:qhb4-qx8k t:meta.view.tableauthor v:id=e3v2-km8a v:screenName=Renante v:roleName=publisher v:displayName=Renante
```

## Top Records

```ls
| notification_type   | street_number | street_number_to | direction | street_name | street_type | notification_from                   | start_date          | end_date            | comment                                                    | data_source                   | 
| =================== | ============= | ================ | ========= | =========== | =========== | =================================== | =================== | =================== | ========================================================== | ============================= | 
| Notification Type   |               |                  | Direction | Street Name | Street Type | Applicant                           |                     |                     | Comment                                                    | Data Source                   | 
| NOI DEMO/RENOVATION | 1             |                  | W         | IRVING PARK | RD          | PUBLIC BLDG. COMM. OF CHICAGO       | 2000-06-09T00:00:00 | 2000-06-19T00:00:00 |                                                            | HISTORIC DEPT. OF ENVIRONMENT | 
| NOI DEMO/RENOVATION | 10000         |                  | W         | O'HARE      |             | MIDWEST REM ENTERPRISES             | 2015-07-01T00:00:00 | 2015-07-15T00:00:00 | 10000 W O'HARE AVE DEMOLITION NOTICE COMMERCIAL/INDUSTRIAL | DEPT. OF PUBLIC HEALTH        | 
| NOI DEMO/RENOVATION | 10000         |                  | W         | O'HARE      |             |                                     | 2015-07-01T00:00:00 | 2015-07-15T00:00:00 | 10000 W O'HARE AVE DEMOLITION NOTICE COMMERCIAL/INDUSTRIAL | DEPT. OF PUBLIC HEALTH        | 
| NOI DEMO/RENOVATION | 1010          |                  | W         | DIVERSEY    | AVE         | JASPER LAMBERT                      | 1999-08-26T00:00:00 | 1999-11-29T00:00:00 | DEMO COMPLETED.                                            | HISTORIC DEPT. OF ENVIRONMENT | 
| NOI DEMO/RENOVATION | 1012          |                  | W         | DIVERSEY    | AVE         | 1012 W DIVERSEY L.L.C.              | 1998-11-11T00:00:00 |                     |                                                            | HISTORIC DEPT. OF ENVIRONMENT | 
| NOI DEMO/RENOVATION | 1022          |                  | W         | DIVERSEY    | AVE         | PRO MCPROPERTIES                    | 2011-06-16T00:00:00 |                     |                                                            | HISTORIC DEPT. OF ENVIRONMENT | 
| NOI DEMO/RENOVATION | 1035          |                  | W         | 115TH       | PL          | CITY OF CHICAGO                     | 2009-07-01T00:00:00 |                     |                                                            | HISTORIC DEPT. OF ENVIRONMENT | 
| NOI DEMO/RENOVATION | 1050          |                  | W         | DIVERSEY    | AVE         | CASTLEBEAR ENTERPRISE/STEVE GOLOVAN | 2000-02-20T00:00:00 |                     |                                                            | HISTORIC DEPT. OF ENVIRONMENT | 
| NOI DEMO/RENOVATION | 1057          |                  | E         | 92ND        | PL          | CITY OF CHICAGO                     | 1997-03-21T00:00:00 |                     |                                                            | HISTORIC DEPT. OF ENVIRONMENT | 
```