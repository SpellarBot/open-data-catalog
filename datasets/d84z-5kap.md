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
| Rows Updated | 2013-06-21T20:08:47Z |

## Description

First Assistant Corporation Counsel Jeffrey D. Friedlander writes a bi-monthly column, "Municipal Law," for the New York Law Journal on issues of importance relating to public affairs law. Mr. Friedlander is the Law Department's second-in-command and a member of its Executive Staff. The first column appeared in March 2003.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | column_date      | Column Date      | text      | text        |
| Yes      | series tag  | columns_title    | Columns Title    | text      | text        |
| Yes      | series tag  | link_to_pdf_file | Link to PDF File | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:d84z-5kap d:2013-02-14T07:59:56.000Z t:link_to_pdf_file=http://www.nyc.gov/html/law/downloads/pdf/Friedlander%20Jeff%20Newspaper%20Article%2011-26-12.pdf t:columns_title="Municipal Law - Preserving New York City's Finances 11/26/12 (in PDF)" t:column_date=11/26/12 m:row_number.d84z-5kap=1

series e:d84z-5kap d:2013-02-14T07:59:56.000Z t:link_to_pdf_file=http://www.nyc.gov/html/law/downloads/pdf/Friedlander%20Jeff%20Newspaper%20Article%209-18-12.pdf t:columns_title="Municipal Law - Innovations in City Land-Use Transactions" t:column_date=9/18/12 m:row_number.d84z-5kap=2

series e:d84z-5kap d:2013-02-14T07:59:56.000Z t:link_to_pdf_file=http://www.nyc.gov/html/law/downloads/pdf/Friedlander%20Jeff%20Newspaper%20Article%206-18-12.pdf t:columns_title="Municipal Law - Cleaning Up City Waterways" t:column_date=6/18/12 m:row_number.d84z-5kap=3
```

## Meta Commands

```ls
metric m:row_number.d84z-5kap p:long l:"Row Number"

entity e:d84z-5kap l:"LAW Published Columns" t:attribution="Law Department (LAW)" t:url=https://data.cityofnewyork.us/api/views/d84z-5kap

property e:d84z-5kap t:meta.view v:id=d84z-5kap v:category="City Government" v:attributionLink=http://www.nyc.gov/html/law/html/news/articles.shtml#2012 v:averageRating=0 v:name="LAW Published Columns" v:attribution="Law Department (LAW)"

property e:d84z-5kap t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:d84z-5kap t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```