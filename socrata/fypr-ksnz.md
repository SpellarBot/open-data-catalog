# CDPH Environmental Complaints

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdph-environmental-complaints-3f9e3) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/fypr-ksnz) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/fypr-ksnz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/fypr-ksnz/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | fypr-ksnz |
| Name | CDPH Environmental Complaints |
| Attribution | Chicago Department of Public Health |
| Category | Environment & Sustainable Development |
| Tags | environmental complaints |
| Created | 2012-09-24T14:11:26Z |
| Publication Date | 2017-04-19T16:28:32Z |

## Description

Environmental complaints received by the Department of Environment (DOE) from January 1993 to December 31, 2011 and by the Department of Public Health (CDPH) since January 1, 2012. On January 1, 2012, the DOE was disbanded and all its inspection, permitting, and enforcement authorities were transferred to the CDPH.   
Data fields requiring description are detailed below. 
COMPLAINT ID:  This is the unique identifier of the complaint incident. 
COMPLAINT TYPE: Specifies the type of complaint. CDPH complaint types are  ?Abandoned Site?, ?Air Pollution Work Order?, ?Asbestos Work Order?, ?Construction and Demolition?, ?Toxics Hazardous Materials Work Order?, ?Illegal Dumping Work Order?, ?Noise Complaint?, ?Permits Issued by DOE Work Order?, ?Recycling Work Order?, ?Service Stations/Storage Tanks Work Order?, ?Vehicle Idling Work Order?, and ?Water Pollution.? For consistency, historic DOE complaint types were renamed to match the most appropriate CDPH complaint type. DOE complaint types that had no matches are designated as ?Other.?  
MAPPED LOCATION: Contains latitude/longitude coordinates of the site as determined through the Chicago Open Data Portal?s geocoding engine. In instances where the facility address is a range, the lower number (the value in the ?Street Number From? column) is used for geocoding. For example, for the range address 1000-1005 S Wabash Ave, the Mapped Location would be the coordinates for 1000 S Wabash Ave. 
 INSPECTOR: Contains the badge or ID number of the inspector or engineer who conducted the compliant inspection. 
COMPLAINT DATE: Date complaint was received by the department. 
COMPLAINT DETAIL: Brief description of the nature of the complaint.  
INSPECTION LOG: This is the inspector?s narrative log of the complaint inspection.
DATA SOURCE: The city department that collected the data.

## Columns

```ls
| Included | Schema Type | Field Name       | Name               | Data Type     | Render Type   |
| ======== | =========== | ================ | ================== | ============= | ============= |
| Yes      | series tag  | complaint_id     | COMPLAINT ID       | text          | text          |
| Yes      | series tag  | complaint_type   | COMPLAINT TYPE     | text          | text          |
| Yes      | series tag  | street_number    | STREET NUMBER FROM | text          | number        |
| Yes      | series tag  | street_number_to | STREET NUMBER TO   | text          | number        |
| Yes      | series tag  | direction        | DIRECTION          | text          | text          |
| Yes      | series tag  | street_name      | STREET NAME        | text          | text          |
| Yes      | series tag  | street_type      | STREET TYPE        | text          | text          |
| Yes      | series tag  | inspector        | INSPECTOR          | text          | text          |
| No       |             | complaint_date   | COMPLAINT DATE     | calendar_date | calendar_date |
| Yes      | series tag  | complaint_detail | COMPLAINT DETAIL   | text          | text          |
| Yes      | series tag  | inspection_log   | INSPECTION LOG     | text          | text          |
| Yes      | series tag  | data_source      | DATA SOURCE        | text          | text          |
| Yes      | time        | modified_date    | Modified Date      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = modified_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = complaint_date
```

## Data Commands

```ls
series e:fypr-ksnz d:2017-04-19T15:52:51.000Z t:inspector=INSPECTOR t:complaint_type="COMPLAINT TYPE" t:direction=DIRECTION t:complaint_id="COMPLAINT ID" t:street_name="STREET NAME" t:data_source="DATA SOURCE" t:inspection_log="INSPECTION LOG" t:street_type="STREET TYPE" t:complaint_detail="COMPLAINT DETAIL" m:row_number.fypr-ksnz=1

series e:fypr-ksnz d:2012-01-01T00:00:00.000Z t:inspector=9 t:complaint_type="Toxics Hazardous Materials Work Order" t:direction=S t:complaint_id=DOECOMP138 t:street_name="COTTAGE GROVE" t:data_source="HISTORIC DEPT. OF ENVIRONMENT" t:inspection_log="MORE INFORMATION MAY BE AVAILABLE IN THE CDPH ENVIRONMENTAL INSPECTIONS DATASET" t:street_number=100 t:street_type=AVE t:complaint_detail="TANKER LEAKING FUEL AT COTTAGE GROVE AND I-94. DRIVER DIDN'T KNOW THAT HE WAS LEAKING DIESEL FUEL UNTIL HE OBSERVED WHAT HE THOUGH WAS SMOKE EMANATING FROM THE REAR OF THE TRACTOR." m:row_number.fypr-ksnz=2

series e:fypr-ksnz d:2012-01-01T00:00:00.000Z t:inspector=9 t:complaint_type="Air Pollution Work Order" t:direction=W t:complaint_id=DOECOMP215 t:street_name=DIVERSEY t:data_source="HISTORIC DEPT. OF ENVIRONMENT" t:inspection_log="MORE INFORMATION MAY BE AVAILABLE IN THE CDPH ENVIRONMENTAL INSPECTIONS DATASET" t:street_number=1000 t:street_type=AVE t:complaint_detail="RESIDENTIAL AREA                    STRONG CHEMICAL ODORS COMING AFTER CLOUD PASSED THROUGH AREA. I CANVASSED IMMEDIATE AREA & DIS- COVERED NO CLOUDS OF CHEMICAL ODORS IN THE VICINIT" m:row_number.fypr-ksnz=3
```

## Meta Commands

```ls
metric m:row_number.fypr-ksnz p:long l:"Row Number"

entity e:fypr-ksnz l:"CDPH Environmental Complaints" t:attribution="Chicago Department of Public Health" t:url=https://data.cityofchicago.org/api/views/fypr-ksnz

property e:fypr-ksnz t:meta.view v:id=fypr-ksnz v:category="Environment & Sustainable Development" v:attributionLink=http://www.cityofchicago.org/city/en/depts/cdph.html v:averageRating=0 v:name="CDPH Environmental Complaints" v:attribution="Chicago Department of Public Health"

property e:fypr-ksnz t:meta.view.owner v:id=e3v2-km8a v:screenName=Renante v:displayName=Renante

property e:fypr-ksnz t:meta.view.tableauthor v:id=e3v2-km8a v:screenName=Renante v:roleName=publisher v:displayName=Renante
```

## Top Records

```ls
| complaint_id | complaint_type                        | street_number | street_number_to | direction | street_name   | street_type | inspector | complaint_date      | complaint_detail                                                                                                                                                                                                                                                                            | inspection_log                                                                  | data_source                   | modified_date       | 
| ============ | ===================================== | ============= | ================ | ========= | ============= | =========== | ========= | =================== | =========================================================================================================================================================================================================================================================================================== | =============================================================================== | ============================= | =================== | 
| COMPLAINT ID | COMPLAINT TYPE                        |               |                  | DIRECTION | STREET NAME   | STREET TYPE | INSPECTOR |                     | COMPLAINT DETAIL                                                                                                                                                                                                                                                                            | INSPECTION LOG                                                                  | DATA SOURCE                   |                     | 
| DOECOMP138   | Toxics Hazardous Materials Work Order | 100           |                  | S         | COTTAGE GROVE | AVE         | 9         | 2011-06-13T00:00:00 | TANKER LEAKING FUEL AT COTTAGE GROVE AND I-94. DRIVER DIDN'T KNOW THAT HE WAS LEAKING DIESEL FUEL UNTIL HE OBSERVED WHAT HE THOUGH WAS SMOKE EMANATING FROM THE REAR OF THE TRACTOR.                                                                                                        | MORE INFORMATION MAY BE AVAILABLE IN THE CDPH ENVIRONMENTAL INSPECTIONS DATASET | HISTORIC DEPT. OF ENVIRONMENT | 2012-01-01T00:00:00 | 
| DOECOMP215   | Air Pollution Work Order              | 1000          |                  | W         | DIVERSEY      | AVE         | 9         | 1996-12-17T00:00:00 | RESIDENTIAL AREA STRONG CHEMICAL ODORS COMING AFTER CLOUD PASSED THROUGH AREA. I CANVASSED IMMEDIATE AREA & DIS- COVERED NO CLOUDS OF CHEMICAL ODORS IN THE VICINIT                                                                                                                         | MORE INFORMATION MAY BE AVAILABLE IN THE CDPH ENVIRONMENTAL INSPECTIONS DATASET | HISTORIC DEPT. OF ENVIRONMENT | 2012-01-01T00:00:00 | 
| DOECOMP236   | Illegal Dumping Work Order            | 10000         |                  | S         | STONY ISLAND  | AVE         | 10        | 1995-10-26T00:00:00 | RESIDENTIAL AREA FLY DUMPING DEBRIS AND CONCRETE.                                                                                                                                                                                                                                           | MORE INFORMATION MAY BE AVAILABLE IN THE CDPH ENVIRONMENTAL INSPECTIONS DATASET | HISTORIC DEPT. OF ENVIRONMENT | 2012-01-01T00:00:00 | 
| DOECOMP237   | Illegal Dumping Work Order            | 10000         |                  | S         | STONY ISLAND  | AVE         | 11        | 1995-10-27T00:00:00 | RESIDENTIAL AREA SITE MONITORED FOR A PERIOD AFTER CITING AN OFFENDER 10/26/95 FOR FLY DUMPING ENTRANCE GATE TO LOACTION WERE CLOSED COURT PENDING 1/3/96.                                                                                                                                  | MORE INFORMATION MAY BE AVAILABLE IN THE CDPH ENVIRONMENTAL INSPECTIONS DATASET | HISTORIC DEPT. OF ENVIRONMENT | 2012-01-01T00:00:00 | 
| DOECOMP238   | Other                                 | 10000         |                  | S         | STONY ISLAND  | AVE         | 62        | 1998-04-07T00:00:00 | N & S SWITCH YARD VERY LOUD EXPLOSION FROM NORFOLK & SOUTHERN TRACK & SWITCH YARD.                                                                                                                                                                                                          | MORE INFORMATION MAY BE AVAILABLE IN THE CDPH ENVIRONMENTAL INSPECTIONS DATASET | HISTORIC DEPT. OF ENVIRONMENT | 2012-01-01T00:00:00 | 
| DOECOMP239   | Air Pollution Work Order              | 10000         |                  | S         | STONY ISLAND  | AVE         | 57        | 1998-07-13T00:00:00 | RESIDENTIAL AREA                                                                                                                                                                                                                                                                            | MORE INFORMATION MAY BE AVAILABLE IN THE CDPH ENVIRONMENTAL INSPECTIONS DATASET | HISTORIC DEPT. OF ENVIRONMENT | 2012-01-01T00:00:00 | 
| DOECOMP282   | Air Pollution Work Order              | 1000          |                  | N         | MICHIGAN      | AVE         | 10        | 2000-06-29T00:00:00 | OAK STREET BEACH HEADING SOUTH ON LAKE SHORE DR.(CTA BUS#7125) WAS EMITTING EMISSION/FUMES.NOTIFIED CTA SPOKE WITH TRAN.MANG.WHO REFERRED TO MAINTANCE MANGER.                                                                                                                              | MORE INFORMATION MAY BE AVAILABLE IN THE CDPH ENVIRONMENTAL INSPECTIONS DATASET | HISTORIC DEPT. OF ENVIRONMENT | 2012-01-01T00:00:00 | 
| DOECOMP308   | Toxics Hazardous Materials Work Order | 10014         |                  | S         | YATES         | AVE         | 55        | 2002-01-17T00:00:00 | GAS CYLINDER LEFT IN THE ALLEY. DISCOVERED GAS GRILL PROPANE CYLINDER IN THE RESIDENTIAL ALLEY. THERE WAS NO ANSWER AT THE HOUSE, SO INSPECTOR PICKED UP THE CYLINDER AND TRANSFERRED IT TO HOME DEPOT AT 210 W. 87TH ST., AND GAVE IT TO ONE OF THE EMPLOYEE FOR THE GAS EXCHANGE PROGRAM. | MORE INFORMATION MAY BE AVAILABLE IN THE CDPH ENVIRONMENTAL INSPECTIONS DATASET | HISTORIC DEPT. OF ENVIRONMENT | 2012-01-01T00:00:00 | 
| DOECOMP311   | Air Pollution Work Order              | 10015         |                  | S         | YATES         | AVE         | 17        | 1993-06-07T00:00:00 | FLOODED BASEMENT                                                                                                                                                                                                                                                                            | MORE INFORMATION MAY BE AVAILABLE IN THE CDPH ENVIRONMENTAL INSPECTIONS DATASET | HISTORIC DEPT. OF ENVIRONMENT | 2012-01-01T00:00:00 | 
```