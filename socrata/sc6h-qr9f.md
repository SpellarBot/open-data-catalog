# Racial Profiling Dataset 2015- Citations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/racial-profiling-dataset-2015-citations) |
| Metadata | [Link](https://data.austintexas.gov/api/views/sc6h-qr9f) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/sc6h-qr9f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/sc6h-qr9f/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | sc6h-qr9f |
| Name | Racial Profiling Dataset 2015- Citations |
| Category | Public Safety |
| Tags | police, racial profiling, citations |
| Created | 2016-03-10T15:58:56Z |
| Publication Date | 2016-03-10T16:57:26Z |

## Description

In order to protect the privacy of crime victims, addresses are generalized to the block level only and specific locations are not identified.

Due to several factors (offense reclassification, reported versus occurred dates, etc.) comparisons should not be made between numbers generated with this database to any other official police reports. Data provided represents only calls for police service where a report was written. 

Totals in the database may vary considerably from official totals following investigation and final categorization. Therefore, the data should not be used for comparisons with Uniform Crime Report statistics. 

The Austin Police Department does not assume any liability for any decision made or action taken or not taken by the recipient in reliance upon any information or data provided.

This Racial Profiling dataset (citations) provides the raw data needed to identify trends in traffic stops. It is used to help identify potential improvements in department policy, tactics, and training.	
	
	
Corresponding report:	
This data is used to produce the annual Racial Profiling report, posted on APD's website here:	
http://www.austintexas.gov/page/racial-profiling-reports

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | citation_number  | CITATION NUMBER  | text          | number        |
| Yes      | time           | off_from_date    | OFF FROM DATE    | calendar_date | calendar_date |
| No       |                | off_time         | OFF TIME         | text          | text          |
| Yes      | series tag     | race_origin_code | RACE-ORIGIN CODE | text          | text          |
| Yes      | series tag     | case_party_sex   | CASE PARTY SEX   | text          | text          |
| Yes      | numeric metric | reason_for_stop  | REASON FOR STOP  | number        | number        |
| Yes      | series tag     | race_known       | RACE KNOWN       | text          | text          |
| Yes      | series tag     | vl_street_name   | VL STREET NAME   | text          | text          |
| Yes      | series tag     | msearch_y_n      | MSEARCH Y/N      | text          | text          |
| Yes      | series tag     | msearch_type     | MSEARCH TYPE     | text          | number        |
| Yes      | numeric metric | msearch_found    | MSEARCH FOUND    | number        | number        |
```

## Time Field

```ls
Value = off_from_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = off_time
```

## Data Commands

```ls
series e:sc6h-qr9f d:2015-05-25T00:00:00.000Z t:vl_street_name="10000 BLOCK WEST BEN WHITE BOULEVARD" t:citation_number=1111 t:msearch_y_n=N t:case_party_sex=M t:race_origin_code=W t:race_known=N m:reason_for_stop=1

series e:sc6h-qr9f d:2015-12-07T00:00:00.000Z t:vl_street_name="SOUTH PLEASANT VALLEY ROAD" t:citation_number=320540 t:msearch_y_n=N t:case_party_sex=F t:race_origin_code=H t:race_known=N m:reason_for_stop=1

series e:sc6h-qr9f d:2015-09-01T00:00:00.000Z t:vl_street_name="1300 BLOCK SOUTH 1ST STREET" t:citation_number=1394195 t:msearch_y_n=N t:case_party_sex=M t:race_origin_code=W t:race_known=N m:reason_for_stop=1
```

## Meta Commands

```ls
metric m:reason_for_stop p:integer l:"REASON FOR STOP" d:"1 Violation of transportation code/vehicle laws 2 Violation of penal code 3 Consent of interview 4 Suspicious person 5 Call for service 6 Pre-existing knowledge 7 Specific detail 8 Other 9 Violation of city ordinance 10 Outstanding warrant" t:dataTypeName=number

metric m:msearch_found p:integer l:"MSEARCH FOUND" d:"1 Weapons 2 Cash 3 Alcohol 4 Other 5 Nothing 6 Drugs" t:dataTypeName=number

entity e:sc6h-qr9f l:"Racial Profiling Dataset 2015- Citations" t:url=https://data.austintexas.gov/api/views/sc6h-qr9f

property e:sc6h-qr9f t:meta.view v:id=sc6h-qr9f v:category="Public Safety" v:averageRating=0 v:name="Racial Profiling Dataset 2015- Citations"

property e:sc6h-qr9f t:meta.view.owner v:id=q374-e9d9 v:screenName="Ron MacKay" v:displayName="Ron MacKay"

property e:sc6h-qr9f t:meta.view.tableauthor v:id=q374-e9d9 v:screenName="Ron MacKay" v:roleName=publisher_stories v:displayName="Ron MacKay"
```

## Top Records

```ls
| citation_number | off_from_date       | off_time | race_origin_code | case_party_sex | reason_for_stop | race_known | vl_street_name                       | msearch_y_n | msearch_type | msearch_found | 
| =============== | =================== | ======== | ================ | ============== | =============== | ========== | ==================================== | =========== | ============ | ============= | 
| 1111            | 2015-05-25T00:00:00 | 8:00:00  | W                | M              | 1               | N          | 10000 BLOCK WEST BEN WHITE BOULEVARD | N           |              |               | 
| 320540          | 2015-12-07T00:00:00 | 23:46:00 | H                | F              | 1               | N          | SOUTH PLEASANT VALLEY ROAD           | N           |              |               | 
| 1394195         | 2015-09-01T00:00:00 | 21:05:00 | W                | M              | 1               | N          | 1300 BLOCK SOUTH 1ST STREET          | N           |              |               | 
| 1395858         | 2015-02-04T00:00:00 | 20:51:00 | W                | F              | 1               | N          | EAST 7TH STREET                      | N           |              |               | 
| 1409057         | 2015-12-14T00:00:00 | 15:57:00 | W                | M              | 1               | N          | 7200 BLOCK FM 2222 ROAD              | N           |              |               | 
| 1412482         | 2015-04-16T00:00:00 | 23:30:00 | W                | M              | 1               | N          | 1000 BLOCK SOUTH IH 35               | N           |              |               | 
| 1413806         | 2015-03-23T00:00:00 | 23:59:00 | B                | M              | 1               | N          | 500 BLOCK EAST 8TH STREET            | N           |              |               | 
| 1414482         | 2015-06-11T00:00:00 | 12:46:00 | H                | M              | 1               | N          | NORTH IH 35 SERVICE ROAD AND         | N           |              |               | 
| 1417385         | 2015-12-07T00:00:00 | 22:58:00 | B                | M              | 1               | N          | SUNSTRIP                             | N           |              |               | 
| 1417576         | 2015-10-16T00:00:00 | 15:25:00 | W                | M              | 1               | N          | 700 BLOCK NORTH IH 35 SERVICE ROAD   | N           |              |               | 
```