# Government Publications Listing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/government-publications-listing) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pba9-2xiu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pba9-2xiu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pba9-2xiu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pba9-2xiu |
| Name | Government Publications Listing |
| Attribution | Departments of Records and Information Services (DORIS) |
| Category | City Government |
| Created | 2015-08-24T21:30:43Z |
| Publication Date | 2015-08-25T17:07:57Z |

## Description

Documents submitted to the Department of Records and Information Services in compliance with Section 1133 of the New York City Charter

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       |                | id                 | ID                 | text      | number      |
| Yes      | series tag     | title              | Title              | text      | text        |
| Yes      | series tag     | description        | Description        | text      | text        |
| No       |                | date_created       | Date Created       | text      | text        |
| Yes      | series tag     | filename           | Filename           | text      | text        |
| Yes      | series tag     | common_document_id | Common Document ID | text      | text        |
| Yes      | series tag     | document_section   | Document Section   | text      | text        |
| Yes      | numeric metric | number_of_requests | Number of Requests | number    | number      |
| Yes      | series tag     | agency             | Agency             | text      | text        |
| Yes      | series tag     | document_category  | Document Category  | text      | text        |
| Yes      | series tag     | document_type      | Document Type      | text      | text        |
| Yes      | series tag     | document_url       | Document URL       | text      | text        |
| Yes      | series tag     | publication_foil   | Publication/FOIL   | text      | text        |
| Yes      | time           | date_published     | Date Published     | text      | text        |
```

## Time Field

```ls
Value = date_published
Format & Zone = yyyy-MM-dd HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,date_created
```

## Data Commands

```ls
series e:pba9-2xiu d:2015-03-10T10:07:31.000Z t:document_category=Technology t:title="City Council Testimony" t:description="re: Intro. 771 / QR Codes. Agency submitted date as Feb-12." t:common_document_id=N t:publication_foil=Publication t:filename="Hearing Testimony 22712.pdf" t:agency=DOITT t:document_url=/static/data/gppPdfs/DOITT/Hearing_Testimony_22712.pdf t:document_type="Legislative Document" t:document_section=N m:number_of_requests=0

series e:pba9-2xiu d:0002-11-30T00:00:00.000Z t:document_category="Government Policy" t:title="March 31st, 2014 - City Record" t:description="March 31st, 2014 - City Record" t:common_document_id=N t:publication_foil=Publication t:filename="7806_March 31st, 2014 - City Record" t:agency="Citywide Admin Svcs" t:document_url="/static/data/gppPdfs/7806_March 31st, 2014   City Record.pdf" t:document_type="Serial Publication" t:document_section=N m:number_of_requests=0

series e:pba9-2xiu d:2015-03-04T00:20:47.000Z t:document_category="Public Safety" t:title="Annual Report 2006" t:description="Annual Report for the Fire Department on fire and EMS operations as well as major accomplishments.  Agency submitted date as 2007." t:common_document_id=N t:publication_foil=Publication t:filename=2006_annual_report.pdf t:agency=Fire t:document_url=/static/data/gppPdfs/NYFD/2006_annual_report.pdf t:document_type=Report t:document_section=N m:number_of_requests=0
```

## Meta Commands

```ls
metric m:number_of_requests p:integer l:"Number of Requests" d:"Number of accesses to each document" t:dataTypeName=number

entity e:pba9-2xiu l:"Government Publications Listing" t:attribution="Departments of Records and Information Services (DORIS)" t:url=https://data.cityofnewyork.us/api/views/pba9-2xiu

property e:pba9-2xiu t:meta.view v:id=pba9-2xiu v:category="City Government" v:averageRating=0 v:name="Government Publications Listing" v:attribution="Departments of Records and Information Services (DORIS)"

property e:pba9-2xiu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pba9-2xiu t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| id    | title                                                                                                                                               | description                                                                                                                                                                                                                                                            | date_created | filename                                                                                                                                                 | common_document_id | document_section | number_of_requests | agency                | document_category      | document_type        | document_url                                                                                                                                                                      | publication_foil | date_published      | 
| ===== | =================================================================================================================================================== | ====================================================================================================================================================================================================================================================================== | ============ | ======================================================================================================================================================== | ================== | ================ | ================== | ===================== | ====================== | ==================== | ================================================================================================================================================================================= | ================ | =================== | 
| 20268 | City Council Testimony                                                                                                                              | re: Intro. 771 / QR Codes. Agency submitted date as Feb-12.                                                                                                                                                                                                            | 2012-02-01   | Hearing Testimony 22712.pdf                                                                                                                              | N                  | N                | 0                  | DOITT                 | Technology             | Legislative Document | /static/data/gppPdfs/DOITT/Hearing_Testimony_22712.pdf                                                                                                                            | Publication      | 2015-03-10 10:07:31 | 
| 7806  | March 31st, 2014 - City Record                                                                                                                      | March 31st, 2014 - City Record                                                                                                                                                                                                                                         | 2014-03-31   | 7806_March 31st, 2014 - City Record                                                                                                                      | N                  | N                | 0                  | Citywide Admin Svcs   | Government Policy      | Serial Publication   | /static/data/gppPdfs/7806_March 31st, 2014 City Record.pdf                                                                                                                        | Publication      | 0000-00-00 00:00:00 | 
| 17149 | Annual Report 2006                                                                                                                                  | Annual Report for the Fire Department on fire and EMS operations as well as major accomplishments. Agency submitted date as 2007.                                                                                                                                      | 2007-01-01   | 2006_annual_report.pdf                                                                                                                                   | N                  | N                | 0                  | Fire                  | Public Safety          | Report               | /static/data/gppPdfs/NYFD/2006_annual_report.pdf                                                                                                                                  | Publication      | 2015-03-04 00:20:47 | 
| 1466  | Landmarks Preservation Commission - John De Groot House                                                                                             | The Landmarks Preservation Commission held a public hearing on the proposed designation as a landmark of the John De Groot House, located at 1674 Richmond Terrace, Staten Island. It was initially built in 1870 and retains most of its historic form and detailing. | 2005-06-28   | 1466_John De Groot House Designation Report                                                                                                              | N                  | N                | 0                  | Landmarks             | Housing and Buildings  | Report               | /static/data/gppPdfs/1466_John De Groot House Designation Report.pdf                                                                                                              | Publication      | 0000-00-00 00:00:00 | 
| 16442 | DHS_CriticalActivitiesReport_toptenfy07                                                                                                             | Top Ten: FY07. Agency submitted date as Jun-07.                                                                                                                                                                                                                        | 2007-06-01   | DHS_CriticalActivitiesReport_toptenfy07.pdf                                                                                                              | N                  | N                | 0                  | Homeless Services     | Human Services         | Report               | /static/data/gppPdfs/DHS/DHS_CriticalActivitiesReport_toptenfy07.pdf                                                                                                              | Publication      | 2015-03-04 00:20:40 | 
| 232   | How to Stop Junk Mail Postcard                                                                                                                      | An advertisement dealing with stopping junk mail from reaching the mailbox. It encourages recycling paper by giving out tips on how no to get junk mail.                                                                                                               | 2003-06-01   | 232_Stop Junk Mail Postcard                                                                                                                              | N                  | N                | 0                  | Sanitation            | Sanitation             | Guide - Manual       | /static/data/gppPdfs/232_Stop Junk Mail Postcard.pdf                                                                                                                              | Publication      | 0000-00-00 00:00:00 | 
| 16581 | DOB Loft Board Minutes                                                                                                                              | Includes the minutes of the monthly meeting of the Loft Board.                                                                                                                                                                                                         | 2011-05-19   | DOB Loft Board Minutes-5-19-11.pdf                                                                                                                       | N                  | N                | 0                  | Loft Board            | Housing and Buildings  | Hearing - Minutes    | /static/data/gppPdfs/DOB_LB/DOB_Loft_Board_Minutes-5-19-11.pdf                                                                                                                    | Publication      | 2015-03-04 00:20:41 | 
| 1547  | AUDIT REPORT ON OTHER THAN PERSONAL SERVICES EXPENDITURES OF SCHOOLS WITHIN THE DEPARTMENT EDUCATION REGIONAL OPERATIONS CENTER FOR REGIONS 1 AND 2 | An audit report on the Department of Education's procurement policies and to see if they were followed for the goods and services by schools in Regions 1 and 2.                                                                                                       | 2005-06-30   | 1547_AUDIT REPORT ON OTHER THAN PERSONAL SERVICES EXPENDITURES OF SCHOOLS WITHIN THE DEPARTMENT EDUCATION REGIONAL OPERATIONS CENTER FOR REGIONS 1 AND 2 | N                  | N                | 0                  | Comptroller           | Finance and Budget     | Audit Report         | /static/data/gppPdfs/1547_AUDIT REPORT ON OTHER THAN PERSONAL SERVICES EXPENDITURES OF SCHOOLS WITHIN THE DEPARTMENT EDUCATION REGIONAL OPERATIONS CENTER FOR REGIONS 1 AND 2.pdf | Publication      | 0000-00-00 00:00:00 | 
| 14979 | DCA Commissioner Mintz Reminds Last Minute Tax Filers and those with Extensions to use Free Online Services                                         | OFE                                                                                                                                                                                                                                                                    | 2010-04-15   | FreeOnlineTaxSrvc_2010-04.pdf                                                                                                                            | N                  | N                | 0                  | Consumer Affairs      | Business and Consumers | Press Release        | /static/data/gppPdfs/DCA/FreeOnlineTaxSrvc_2010-04.pdf                                                                                                                            | Publication      | 2015-03-04 00:20:35 | 
| 14080 | Ask the City Ethicist, Double-Dipping                                                                                                               | Article                                                                                                                                                                                                                                                                | 2009-09-01   | ace_1_10_supsub_kas.pdf                                                                                                                                  | N                  | N                | 0                  | Conflicts of Interest | Government Policy      | Serial Publication   | /static/data/gppPdfs/COIB/ace_1_10_supsub_kas.pdf                                                                                                                                 | Publication      | 2015-03-04 00:20:32 | 
```