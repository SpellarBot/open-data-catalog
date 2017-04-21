# CDPH Environmental Hold on City-Issued Permits and LUST NFR

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdph-environmental-hold-on-city-issued-permits-and-lust-nfr-b445d) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/6gqn-e2ij) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/6gqn-e2ij/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/6gqn-e2ij/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 6gqn-e2ij |
| Name | CDPH Environmental Hold on City-Issued Permits and LUST NFR |
| Category | Environment & Sustainable Development |
| Tags | lust, nfr, thorium, radiation, highway authority agreement |
| Created | 2012-11-13T22:38:39Z |
| Publication Date | 2017-04-19T17:37:43Z |

## Description

This dataset contains environmental holds placed by the Department of Environment (DOE) up to December 31, 2011 and by the Department of Public Health (CDPH) post December 31, 2011 on construction-related permits issued by the City of Chicago. On January 1, 2012, the DOE was disbanded and all its inspection, permitting, and enforcement authorities were transferred to the CDPH.  This dataset also contains No Further Remediation Letters (NFRs) received by the DOE or the CDPH for properties that have been cleaned up under the Illinois Environmental Protections Agency?s (IEPA) Leaking Underground Storage Tank (LUST) program. Throrium holds in this dataset ends November 15, 2016.
Data fields requiring description are detailed below. 
APPLICATION ID:  Unique identifier of record.
MAPPED LOCATION: Contains latitude/longitude coordinates of the site as determined through the Chicago Open Data Portal?s geocoding engine. In instances where the facility address is a range, the lower number (the value in the ?Street Number From? column) is used for geocoding. For example, for the range address 1000-1005 S Wabash Ave, the Mapped Location would be the coordinates for 1000 S Wabash Ave. 
TYPE: Specifies the type of permit hold placed on a property or the hold released on an individual permit.  HIGHWAY AUTHORITY AGREEMENT is a permit hold placed on construction projects in the public right-of-way at certain locations in the City of Chicago. Refer to http://tinyurl.com/bn3grwt for more information. A THORIUM PERMIT HOLD is a permit hold placed on select properties in the Streeterville area for thorium contamination. Refer to http://tinyurl.com/d6wth39 . A THORIUM PERMIT HOLD RELEASE indicates that an applicant has complied with the necessary requirements and the Thorium Permit Hold has been lifted on the permit application. An NFR LUST is not a permit hold but the property may have certain land use restrictions or requirements (i.e. institutional or engineering controls) to prevent or minimize exposure of contaminants that may still be present at the property.
DATE: Date the record was entered into the database. 
COMMENT: Comments relating to the hold or release. 
DATA SOURCE: The city department that placed or released the hold.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | application_id     | APPLICATION ID     | text          | text          |
| Yes      | series tag  | street_number_from | STREET NUMBER FROM | text          | number        |
| Yes      | series tag  | street_number_to   | STREET NUMBER TO   | text          | number        |
| Yes      | series tag  | street_direction   | STREET DIRECTION   | text          | text          |
| Yes      | series tag  | street_name        | STREET NAME        | text          | text          |
| Yes      | series tag  | street_type        | STREET TYPE        | text          | text          |
| Yes      | series tag  | data_type          | MORATORIUM TYPE    | text          | text          |
| Yes      | time        | date               | DATE               | calendar_date | calendar_date |
| Yes      | series tag  | comment            | COMMENT            | text          | text          |
| Yes      | series tag  | data_source        | DATA SOURCE        | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:6gqn-e2ij d:2017-04-19T17:36:31.000Z t:data_type="DATA TYPE" t:data_source="DATA SOURCE" t:street_name="STREET NAME" t:street_direction="STREET DIRECTION" t:comment=COMMENT t:application_id="Application ID" t:street_type="STREET TYPE" m:row_number.6gqn-e2ij=1

series e:6gqn-e2ij d:2017-04-19T17:36:31.000Z t:data_type="HIGHWAY AUTHORITY AGREEMENT" t:data_source="HISTORIC DEPT. OF ENVIRONMENT" t:street_name=MONTROSE t:street_number_from=301 t:street_direction=W t:comment=MGP t:application_id=049 t:street_type=AVE m:row_number.6gqn-e2ij=2

series e:6gqn-e2ij d:2017-04-19T17:36:31.000Z t:data_type="HIGHWAY AUTHORITY AGREEMENT" t:data_source="HISTORIC DEPT. OF ENVIRONMENT" t:street_name=STEWART t:street_number_from=4551 t:street_direction=S t:comment=MGP t:application_id=063 t:street_type=AVE m:row_number.6gqn-e2ij=3
```

## Meta Commands

```ls
metric m:row_number.6gqn-e2ij p:long l:"Row Number"

entity e:6gqn-e2ij l:"CDPH Environmental Hold on City-Issued Permits and LUST NFR" t:url=https://data.cityofchicago.org/api/views/6gqn-e2ij

property e:6gqn-e2ij t:meta.view v:id=6gqn-e2ij v:category="Environment & Sustainable Development" v:averageRating=0 v:name="CDPH Environmental Hold on City-Issued Permits and LUST NFR"

property e:6gqn-e2ij t:meta.view.owner v:id=e3v2-km8a v:screenName=Renante v:displayName=Renante

property e:6gqn-e2ij t:meta.view.tableauthor v:id=e3v2-km8a v:screenName=Renante v:roleName=publisher v:displayName=Renante
```

## Top Records

```ls
| application_id | street_number_from | street_number_to | street_direction | street_name         | street_type | data_type                   | date                | comment                                                                | data_source                   | 
| ============== | ================== | ================ | ================ | =================== | =========== | =========================== | =================== | ====================================================================== | ============================= | 
| Application ID |                    |                  | STREET DIRECTION | STREET NAME         | STREET TYPE | DATA TYPE                   |                     | COMMENT                                                                | DATA SOURCE                   | 
| 049            | 301                |                  | W                | MONTROSE            | AVE         | HIGHWAY AUTHORITY AGREEMENT |                     | MGP                                                                    | HISTORIC DEPT. OF ENVIRONMENT | 
| 063            | 4551               |                  | S                | STEWART             | AVE         | HIGHWAY AUTHORITY AGREEMENT |                     | MGP                                                                    | HISTORIC DEPT. OF ENVIRONMENT | 
| 109            | 5150               |                  | W                | CHICAGO             |             | HIGHWAY AUTHORITY AGREEMENT | 2000-08-11T00:00:00 | LUST                                                                   | HISTORIC DEPT. OF ENVIRONMENT | 
| 115            | 6341               |                  | S                | DR MARTIN L KING JR | DR          | HIGHWAY AUTHORITY AGREEMENT | 2001-01-26T00:00:00 | LUST                                                                   | HISTORIC DEPT. OF ENVIRONMENT | 
| 159            | 4957               |                  | S                | CALIFORNIA          | BLVD        | HIGHWAY AUTHORITY AGREEMENT | 2002-07-11T00:00:00 | LUST                                                                   | HISTORIC DEPT. OF ENVIRONMENT | 
| 196            | 8300               |                  | S                | STONEY ISLAND       |             | HIGHWAY AUTHORITY AGREEMENT | 2003-08-01T00:00:00 | LUST                                                                   | HISTORIC DEPT. OF ENVIRONMENT | 
| 199            | 5048               |                  | N                | CORNELL             |             | HIGHWAY AUTHORITY AGREEMENT | 2003-08-08T00:00:00 | LUST                                                                   | HISTORIC DEPT. OF ENVIRONMENT | 
| 203            | 9500               |                  | S                | DR MARTIN L KING JR | DR          | HIGHWAY AUTHORITY AGREEMENT | 2003-08-26T00:00:00 | RECIVED RECORDER DEEDS DATED 10/14/2004 1:23 P.M DOC # 0428834013 LUST | HISTORIC DEPT. OF ENVIRONMENT | 
| 227            | 6000               |                  | W                | ROOSEVELT           | RD          | HIGHWAY AUTHORITY AGREEMENT | 2004-10-26T00:00:00 | LUST                                                                   | HISTORIC DEPT. OF ENVIRONMENT | 
```