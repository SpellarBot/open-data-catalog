# LAW Speeches

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/law-speeches-6537d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/g7ir-4pf8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/g7ir-4pf8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/g7ir-4pf8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | g7ir-4pf8 |
| Name | LAW Speeches |
| Attribution | Law Department (LAW) |
| Category | City Government |
| Tags | law, justice, legislation, law journal, law speeches, lawyer |
| Created | 2013-02-14T16:03:27Z |
| Publication Date | 2013-06-21T20:08:56Z |

## Description

The Corporation Counsel is often invited to address bar associations, law students, and other organizations. Below are links to the text of speeches given by Corporation Counsel

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | time        | date_of_speech   | Date of Speech   | text      | text        |
| Yes      | series tag  | speaker          | Speaker          | text      | text        |
| Yes      | series tag  | law_speech_title | Law Speech Title | text      | text        |
| Yes      | series tag  | link_to_pdf_file | Link to PDF File | url       | url         |
```

## Time Field

```ls
Value = date_of_speech
Format & Zone = MM/dd/yy
```

## Data Commands

```ls
series e:g7ir-4pf8 d:2012-11-27T00:00:00.000Z t:law_speech_title="Corporation Counsel Michael A. Cardozo's Remarks at the Bloomberg Administration's Legal Legacy Symposium, Fordham Law School" t:speaker="Michael A. Cardozo" t:link_to_pdf_file=http://www.nyc.gov/html/law/downloads/pdf/Mayor%27s_Legal_Legacy_Symposium_Remarks.pdf m:row_number.g7ir-4pf8=1

series e:g7ir-4pf8 d:2012-10-11T00:00:00.000Z t:law_speech_title="Corporation Counsel's Michael A. Cardozo's Remarks at the Law Department's Bi-Annual Alumni Dinner" t:speaker="Michael A. Cardozo" t:link_to_pdf_file=http://www.nyc.gov/html/law/downloads/pdf/Remarks_Victor_Kovner.pdf m:row_number.g7ir-4pf8=2

series e:g7ir-4pf8 d:2012-03-24T00:00:00.000Z t:law_speech_title="Remarks of Corporation Counsel Michael A. Cardozo on a Government's Role in the Pursuit of Justice for the Sam and Anna Jacobs Foundation Lecture on Law and the Legal Profession at John Jay College Law Day" t:speaker="Michael A. Cardozo" t:link_to_pdf_file=http://www.nyc.gov/html/law/downloads/pdf/John_Jay_Speech_March_24.pdf m:row_number.g7ir-4pf8=3
```

## Meta Commands

```ls
metric m:row_number.g7ir-4pf8 p:long l:"Row Number"

entity e:g7ir-4pf8 l:"LAW Speeches" t:attribution="Law Department (LAW)" t:url=https://data.cityofnewyork.us/api/views/g7ir-4pf8

property e:g7ir-4pf8 t:meta.view v:id=g7ir-4pf8 v:category="City Government" v:attributionLink=http://www.nyc.gov/html/law/html/news/speeches.shtml v:averageRating=0 v:name="LAW Speeches" v:attribution="Law Department (LAW)"

property e:g7ir-4pf8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:g7ir-4pf8 t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| date_of_speech | speaker            | law_speech_title                                                                                                                                                                                                                                                        | link_to_pdf_file                                                                               | 
| ============== | ================== | ======================================================================================================================================================================================================================================================================= | ============================================================================================== | 
| 11/27/12       | Michael A. Cardozo | Corporation Counsel Michael A. Cardozo's Remarks at the Bloomberg Administration's Legal Legacy Symposium, Fordham Law School                                                                                                                                           | [http://www.nyc.gov/html/law/downloads/pdf/Mayor%27s_Legal_Legacy_Symposium_Remarks.pdf, null] | 
| 10/11/12       | Michael A. Cardozo | Corporation Counsel's Michael A. Cardozo's Remarks at the Law Department's Bi-Annual Alumni Dinner                                                                                                                                                                      | [http://www.nyc.gov/html/law/downloads/pdf/Remarks_Victor_Kovner.pdf, null]                    | 
| 3/24/12        | Michael A. Cardozo | Remarks of Corporation Counsel Michael A. Cardozo on a Government's Role in the Pursuit of Justice for the Sam and Anna Jacobs Foundation Lecture on Law and the Legal Profession at John Jay College Law Day                                                           | [http://www.nyc.gov/html/law/downloads/pdf/John_Jay_Speech_March_24.pdf, null]                 | 
| 11/23/11       | Michael A. Cardozo | Address of Corporation Counsel Michael A. Cardozo to the Federal Bar Council in Accepting the Emory Buckner Medal, Focusing on the Legal Profession Today and How to Improve the Training of Junior Lawyers and Support Government and Legal Services Offices, New York | [http://www.nyc.gov/html/law/downloads/pdf/FBC_Emory_Buckner_Award.pdf, null]                  | 
| 9/22/11        | Michael A. Cardozo | Remarks of Corporation Counsel Michael A. Cardozo to the Citizens Budget Commission on the City's Legal & Financial "Catch-22's," New York                                                                                                                              | [http://www.nyc.gov/html/law/downloads/pdf/CBC.pdf, null]                                      | 
| 7/20/11        | Michael A. Cardozo | Testimony of Michael A. Cardozo Before the Special Commission on Judicial Compensation, Albany, New York                                                                                                                                                                | [http://www.nyc.gov/html/law/downloads/pdf/Statement%20on%20judicial%20compensation.pdf, null] | 
| 1/24/11        | Michael A. Cardozo | Remarks of Corporation Counsel Michael A. Cardozo on the Future of the Legal Profession, Hofstra Law School Distinguished Practitioners Series                                                                                                                          | [http://www.nyc.gov/html/law/downloads/pdf/2897763_1.pdf, null]                                | 
| 3/29/10        | Michael A. Cardozo | Remarks of Corporation Counsel Michael A. Cardozo on New York City's Initiative to Provide Free Legal Representation for Homeowners Facing Foreclosure                                                                                                                  | [http://www.nyc.gov/html/law/downloads/pdf/Speech_Cyrus_Vance_Tribute_Award.pdf, null]         | 
| 12/4/09        | Michael A. Cardozo | Remarks of Corporation Counsel Michael A. Cardozo Upon Accepting the Cyrus Vance Tribute Award from the Fund for Modern Courts, Discussing Judicial Efficiency in Times of Economic Crisis                                                                              | [http://www.nyc.gov/html/law/downloads/pdf/Speech_Cyrus_Vance_Tribute_Award.pdf, null]         | 
| 3/12/09        | Michael A. Cardozo | Corporation Counsel Michael A. Cardozo Speaks at Brown Class of 1963 Mini-Reunion, Discussing Career Challenges and Highlights                                                                                                                                          | [http://www.nyc.gov/html/law/downloads/pdf/2289203_1.pdf, null]                                | 
```