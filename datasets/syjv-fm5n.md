# Freedom of Information Requests

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/freedom-of-information-requests) |
| Metadata | [Link](https://data.hartford.gov/api/views/syjv-fm5n) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/syjv-fm5n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/syjv-fm5n/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | syjv-fm5n |
| Name | Freedom of Information Requests |
| Attribution | City of Hartford |
| Category | Community |
| Tags | hartford, foi, freedom of information |
| Created | 2014-11-09T15:25:02Z |
| Publication Date | 2014-11-09T15:38:05Z |

## Description

Updated on a nightly basis. The data comes from a database that was created in April 2014 to track the City's FOI requests. The requestor's address and phone number has been removed.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | ticket_num       | Ticket_Num       | text      | number      |
| Yes      | series tag     | request          | Request          | text      | text        |
| Yes      | series tag     | first_name       | First_Name       | text      | text        |
| Yes      | series tag     | last_name        | Last_Name        | text      | text        |
| Yes      | series tag     | company          | Company          | text      | text        |
| Yes      | series tag     | email            | Email            | text      | text        |
| Yes      | time           | date_request     | Date_Request     | date      | date        |
| No       |                | date_received    | Date_Received    | date      | date        |
| Yes      | series tag     | file_request     | File_Request     | text      | text        |
| No       |                | date_acknowledge | Date_Acknowledge | date      | date        |
| Yes      | series tag     | file_acknowledge | File_Acknowledge | text      | text        |
| Yes      | series tag     | status           | Status           | text      | text        |
| No       |                | date1_response   | Date1_Response   | date      | date        |
| Yes      | series tag     | file1_response   | File1_Response   | text      | text        |
| Yes      | series tag     | note1_response   | Note1_Response   | text      | text        |
| No       |                | date2_response   | Date2_Response   | date      | date        |
| Yes      | series tag     | file2_response   | File2_Response   | text      | text        |
| Yes      | series tag     | note2_response   | Note2_response   | text      | text        |
| No       |                | date3_response   | Date3_response   | date      | date        |
| Yes      | series tag     | file3_response   | File3_Response   | text      | text        |
| Yes      | series tag     | note3_response   | Note3_Response   | text      | text        |
| No       |                | date4_response   | Date4_Response   | date      | date        |
| Yes      | series tag     | file4_response   | File4_Response   | text      | text        |
| Yes      | series tag     | note4_response   | Note4_Response   | text      | text        |
| No       |                | date5_response   | Date5_Response   | date      | date        |
| Yes      | series tag     | file5_response   | File5_Response   | text      | text        |
| Yes      | series tag     | note5_response   | Note5_Response   | text      | text        |
| No       |                | date6_response   | Date6_Response   | date      | date        |
| Yes      | series tag     | file6_response   | File6_Response   | text      | text        |
| Yes      | series tag     | note6_response   | Note6_Response   | text      | text        |
| No       |                | date7_response   | Date7_Response   | date      | date        |
| Yes      | series tag     | file7_response   | File7_Response   | text      | text        |
| Yes      | series tag     | note7_response   | Note7_Response   | text      | text        |
| Yes      | series tag     | file8_response   | File8_Response   | text      | text        |
| Yes      | series tag     | note8_response   | Note8_Response   | text      | text        |
| No       |                | date9_response   | Date9_Response   | date      | date        |
| Yes      | series tag     | file9_response   | File9_Response   | text      | text        |
| Yes      | series tag     | note9_response   | Note9_Response   | text      | text        |
| No       |                | date10_response  | Date10_Response  | date      | date        |
| Yes      | series tag     | file10_response  | File10_Response  | text      | text        |
| Yes      | series tag     | note10_response  | Note10_Response  | text      | text        |
| Yes      | series tag     | fees_paid        | Fees_Paid        | text      | text        |
| Yes      | numeric metric | fees_amount      | Fees_Amount      | money     | money       |
| Yes      | series tag     | fees_source      | Fees_Source      | text      | text        |
| Yes      | series tag     | fees_comment     | Fees_Comment     | text      | text        |
| Yes      | series tag     | general_comment  | General_Comment  | text      | text        |
```

## Time Field

```ls
Value = date_request
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date_received,date_acknowledge,date1_response,date2_response,date3_response,date4_response,date5_response,date6_response,date7_response,date9_response,date10_response
```

## Data Commands

```ls
series e:syjv-fm5n d:2016-11-01T00:00:00.000Z t:first_name="Howard E. Kantrovitz" t:file_acknowledge="20161104152438_FOIA Acknowledgeement Letter - Dunkin Donuts Park.pdf" t:ticket_num=1010 t:status=Open t:file_request="20161104152433_FOIA request - dunkin donuts park.pdf" t:company="Gesmonde, Pietrosimone & Sgrignari, LLC" t:request="Copy of Performance and Payment Bonds issued for the Dunkin Donuts Park Project" t:last_name=Kantrovitz t:note1_response="Forward to Mike Looney to search for the info requested." m:fees_amount=0

series e:syjv-fm5n d:2016-11-09T00:00:00.000Z t:first_name=Robert t:file_acknowledge="20161110142335_initial acknowledgment letter.pdf" t:ticket_num=1019 t:status=Complete t:file_request="20161109151736_Initial request.pdf" t:fees_paid=No t:request="request for incident reports for Henry Depaneas" t:last_name=Ludgin t:file1_response=20161114095723_documents.pdf m:fees_amount=0

series e:syjv-fm5n d:2016-11-09T00:00:00.000Z t:first_name=Eric t:file_acknowledge="20161115110952_RE FOI Response 112-114 webster.msg" t:ticket_num=1025 t:email=ethomas@thekyricgroup.com t:status=Complete t:file_request="20161115110936_FOI Request 112-114 Webster.msg" t:company="The Kyric Group" t:request="112-114 Webster Street - legal 4 or 5 family house" t:last_name=Thomas t:file1_response="20161117114411_112-114 Webster Street.zip" m:fees_amount=0
```

## Meta Commands

```ls
metric m:fees_amount p:integer l:Fees_Amount t:dataTypeName=money

entity e:syjv-fm5n l:"Freedom of Information Requests" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/syjv-fm5n

property e:syjv-fm5n t:meta.view v:id=syjv-fm5n v:category=Community v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Freedom of Information Requests" v:attribution="City of Hartford"

property e:syjv-fm5n t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:syjv-fm5n t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:syjv-fm5n t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| ticket_num | request                                                                                                               | first_name           | last_name   | company                                 | email                     | date_request | date_received | file_request                                         | date_acknowledge | file_acknowledge                                                      | status   | date1_response | file1_response                              | note1_response                                           | date2_response | file2_response | note2_response | date3_response | file3_response | note3_response | date4_response | file4_response | note4_response | date5_response | file5_response | note5_response | date6_response | file6_response | note6_response | date7_response | file7_response | note7_response | file8_response | note8_response | date9_response | file9_response | note9_response | date10_response | file10_response | note10_response | fees_paid | fees_amount | fees_source | fees_comment | general_comment | 
| ========== | ===================================================================================================================== | ==================== | =========== | ======================================= | ========================= | ============ | ============= | ==================================================== | ================ | ===================================================================== | ======== | ============== | =========================================== | ======================================================== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | =============== | =============== | =============== | ========= | =========== | =========== | ============ | =============== | 
| 1010       | Copy of Performance and Payment Bonds issued for the Dunkin Donuts Park Project                                       | Howard E. Kantrovitz | Kantrovitz  | Gesmonde, Pietrosimone & Sgrignari, LLC |                           | 1477958400   |               | 20161104152433_FOIA request - dunkin donuts park.pdf | 1478217600       | 20161104152438_FOIA Acknowledgeement Letter - Dunkin Donuts Park.pdf  | Open     |                |                                             | Forward to Mike Looney to search for the info requested. |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                 |                 |                 |           | 0           |             |              |                 | 
| 1019       | request for incident reports for Henry Depaneas                                                                       | Robert               | Ludgin      |                                         |                           | 1478649600   | 1478649600    | 20161109151736_Initial request.pdf                   | 1478649600       | 20161110142335_initial acknowledgment letter.pdf                      | Complete | 1479081600     | 20161114095723_documents.pdf                |                                                          |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                 |                 |                 | No        | 0           |             |              |                 | 
| 1025       | 112-114 Webster Street - legal 4 or 5 family house                                                                    | Eric                 | Thomas      | The Kyric Group                         | ethomas@thekyricgroup.com | 1478649600   |               | 20161115110936_FOI Request 112-114 Webster.msg       | 1478736000       | 20161115110952_RE FOI Response 112-114 webster.msg                    | Complete |                | 20161117114411_112-114 Webster Street.zip   |                                                          |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                 |                 |                 |           | 0           |             |              |                 | 
| 1027       | All certified payroll records for Centerplan for work performed on the consturction of Ballpark                       | Brendan              | Hughes      | Robert M. Cheverie & Associates         | bhughes@cheverielaw.com   | 1478736000   |               | 20161115124039_FOI request - ballpark.pdf            |                  | 20161115124111_FOI Letter Response- Ballpark -Cheverie Associates.pdf | Open     |                |                                             | Forward request to Mike Looney                           |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                 |                 |                 |           | 0           |             |              |                 | 
| 1071       | 240 Cleveland - building permits, building violations, zoning permits and violations, health violations after 5-27-16 | Terrie               | Allen       |                                         | terrie@sound-title.com    | 1480377600   |               |                                                      |                  |                                                                       | Complete | 1480464000     | 20161130162255_FOI - letter of response.pdf |                                                          |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                 |                 |                 |           | 0           |             |              |                 | 
| 1143       | 16-18 McKinley Street                                                                                                 | Scott                | Golochowicz |                                         | smGolochowicz@gmail.com   | 1483488000   |               |                                                      |                  |                                                                       | Complete | 1484092800     |                                             | No responsive documents                                  |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                 |                 |                 |           | 0           |             |              |                 | 
| 1144       | 159 russ st - open permits                                                                                            | Scott                | Golochowicz |                                         | smgolochowicz@gmail.com   |              |               |                                                      |                  |                                                                       | Complete |                | 20170124114010_159 Russ Street.zip          |                                                          |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                 |                 |                 |           | 0           |             |              |                 | 
| 1145       | 103-105 lincoln street - open permits                                                                                 | Scott                | Golochowicz |                                         | Smgolochowicz@gmail.com   | 1483488000   |               |                                                      |                  |                                                                       | Complete | 1484092800     |                                             | No responsive documents                                  |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                 |                 |                 |           | 0           |             |              |                 | 
| 1146       | 107 lincoln street - open permits                                                                                     | Scott                | Golochowicz |                                         | smgolochowicz@gmail.com   | 1483488000   |               |                                                      |                  |                                                                       | Complete | 1484092800     | 20170111160436_107-109 Lincoln Street.zip   |                                                          |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                 |                 |                 |           | 0           |             |              |                 | 
| 1147       | 111 Lincoln Street - Open/active permits                                                                              | Scott                | Golochowicz |                                         | smgolochowicz@gmail.com   | 1483488000   |               |                                                      |                  |                                                                       | Complete | 1484092800     |                                             | No responsive documents                                  |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                |                 |                 |                 |           | 0           |             |              |                 | 
```