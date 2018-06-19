# LAW Published Columns

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/law-published-columns-43e0a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/d84z-5kap) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/d84z-5kap/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/d84z-5kap/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | d84z-5kap |
| Name | LAW Published Columns |
| Attribution | Law Department (LAW) |
| Category | City Government |
| Tags | law, justice, legislation, law journal, law articles, law columns, lawyer |
| Created | 2013-02-14T15:59:53Z |
| Publication Date | 2013-06-21T20:08:49Z |

## Description

First Assistant Corporation Counsel Jeffrey D. Friedlander writes a bi-monthly column, "Municipal Law," for the New York Law Journal on issues of importance relating to public affairs law. Mr. Friedlander is the Law Department's second-in-command and a member of its Executive Staff. The first column appeared in March 2003.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | time        | column_date      | Column Date      | text      | text        |
| Yes      | series tag  | columns_title    | Columns Title    | text      | text        |
| Yes      | series tag  | link_to_pdf_file | Link to PDF File | url       | url         |
```

## Time Field

```ls
Value = column_date
Format & Zone = MM/dd/yy
```

## Data Commands

```ls
series e:d84z-5kap d:2012-11-26T00:00:00.000Z t:columns_title="Municipal Law - Preserving New York City's Finances 11/26/12 (in PDF)" t:link_to_pdf_file=http://www.nyc.gov/html/law/downloads/pdf/Friedlander%20Jeff%20Newspaper%20Article%2011-26-12.pdf m:row_number.d84z-5kap=1

series e:d84z-5kap d:2012-09-18T00:00:00.000Z t:columns_title="Municipal Law - Innovations in City Land-Use Transactions" t:link_to_pdf_file=http://www.nyc.gov/html/law/downloads/pdf/Friedlander%20Jeff%20Newspaper%20Article%209-18-12.pdf m:row_number.d84z-5kap=2

series e:d84z-5kap d:2012-06-18T00:00:00.000Z t:columns_title="Municipal Law - Cleaning Up City Waterways" t:link_to_pdf_file=http://www.nyc.gov/html/law/downloads/pdf/Friedlander%20Jeff%20Newspaper%20Article%206-18-12.pdf m:row_number.d84z-5kap=3
```

## Meta Commands

```ls
metric m:row_number.d84z-5kap p:long l:"Row Number"

entity e:d84z-5kap l:"LAW Published Columns" t:attribution="Law Department (LAW)" t:url=https://data.cityofnewyork.us/api/views/d84z-5kap

property e:d84z-5kap t:meta.view d:2017-09-25T07:30:15.037Z v:averageRating=0 v:name="LAW Published Columns" v:attribution="Law Department (LAW)" v:attributionLink=http://www.nyc.gov/html/law/html/news/articles.shtml#2012 v:id=d84z-5kap v:category="City Government"

property e:d84z-5kap t:meta.view.owner d:2017-09-25T07:30:15.037Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:d84z-5kap t:meta.view.tableauthor d:2017-09-25T07:30:15.037Z v:displayName="Ram S." v:id=8b43-zkvh v:screenName="Ram S."
```

## Top Records

```ls
| column_date | columns_title                                                         | link_to_pdf_file                                                                                          | 
| =========== | ===================================================================== | ========================================================================================================= | 
| 11/26/12    | Municipal Law - Preserving New York City's Finances 11/26/12 (in PDF) | [http://www.nyc.gov/html/law/downloads/pdf/Friedlander%20Jeff%20Newspaper%20Article%2011-26-12.pdf, null] | 
| 9/18/12     | Municipal Law - Innovations in City Land-Use Transactions             | [http://www.nyc.gov/html/law/downloads/pdf/Friedlander%20Jeff%20Newspaper%20Article%209-18-12.pdf, null]  | 
| 6/18/12     | Municipal Law - Cleaning Up City Waterways                            | [http://www.nyc.gov/html/law/downloads/pdf/Friedlander%20Jeff%20Newspaper%20Article%206-18-12.pdf, null]  | 
| 3/21/12     | Municipal Law - Local Legislation: The Year in Review                 | [http://www.nyc.gov/html/law/downloads/pdf/Friedlander%20Jeff%20Newspaper%20Article%203-21-12.pdf, null]  | 
| 12/23/11    | Municipal Law - Improving the City's Air Quality                      | [http://www.nyc.gov/html/law/downloads/pdf/Friedlander%20Jeff%20Newspaper%20Article%2012-23-11.pdf, null] | 
| 9/26/11     | Municipal Law - Increasing Transparency in City Government            | [http://www.nyc.gov/html/law/downloads/pdf/Friedlander%20Jeff%20Newspaper%20Article%209-26-11.pdf, null]  | 
| 6/29/11     | Municipal Law - The City's Appellate Practice: Some Recent Cases      | [http://www.nyc.gov/html/law/downloads/pdf/Friedlander%20Jeff%20Newspaper%20Article%206-29-11.pdf, null]  | 
| 3/28/11     | Municipal Law - Defending the City's RFP Process                      | [http://www.nyc.gov/html/law/downloads/pdf/JF_3.28.11.pdf, null]                                          | 
| 12/23/10    | Municipal Law - Defending Eminent Domain During Economic Development  | [http://www.nyc.gov/html/law/downloads/pdf/Friedlander%20Jeff%20Newspaper%20Article%2012-23-10.pdf, null] | 
| 9/27/10     | Municipal Law - Tax & Bankruptcy Litigation                           | [http://www.nyc.gov/html/law/downloads/pdf/Friedlander%20Jeff%20Newspaper%20Article%209-27-10.pdf, null]  | 
```