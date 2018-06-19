# Imaged Documents and Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/draft-imaged-documents-and-reports-3f560) |
| Metadata | [Link](https://data.wa.gov/api/views/j78t-andi) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/j78t-andi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/j78t-andi/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | j78t-andi |
| Name | Imaged Documents and Reports |
| Attribution | Washington State Public Disclosure Commission |
| Tags | political finance, elections, contributions, campaign, political committee, disclosure |
| Created | 2017-01-10T18:15:46Z |
| Publication Date | 2017-04-09T03:30:49Z |

## Description

This data set an index to all PDC imaged reports and documents. Political disclosure reports are included for the last 10 years. Other document types are included based on the PDC record retention schedule or 10 years. The number of years is determined by looking at both the election year and date submitted and including documents that meet either criteria (favoring the inclusion of documents). Each record contains a link to view the actual imaged document or a link on how to request the document for F1 statements of financial affairs.

The dataset includes both original and amended reports and documents. Data consumers must look at the individual documents to determine if a particular document has been superseded by an amendment. For example, a candidate might file a C4 summary report and file an amendment to the report. There is no indicator on the original C4 that it has been amended. For most documents, amendments have the term "AMENDED" as part of the origin field but the original document will not contain any indicator that it has been superseded by an amendment.

Lobbyist L1, L2 and L3 reports are included through 2015 and partial records for 2016. In mid 2016 the PDC discontinued imaging lobbyist L1, L2 and L3 reports. Please refer to the "Lobbyist Compensation and Expenses" dataset or the PDC online filing system at https://accesshub.pdc.wa.gov for the complete 2016 and later lobbyist information. The statement above does not apply to Public Agency Lobbying (L5) reports.

This dataset is a best-effort by the PDC to provide a complete set of records as described herewith and may contain incomplete or incorrect information. The PDC provides access to the original reports for the purpose of record verification.

Descriptions attached to this dataset do not constitute legal definitions; please consult RCW 42.17A and WAC Title 390 for legal definitions and additional information regarding political finance disclosure requirements.

CONDITION OF RELEASE: This publication constitutes a list of individuals prepared by the Washington State Public Disclosure Commission and may not be used for commercial purposes. This list is provided on the condition and with the understanding that the persons receiving it agree to this statutorily imposed limitation on its use. See RCW 42.56.070(9) and AGO 1975 No. 15.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| No       |                | id                   | id                   | text          | text          |
| Yes      | series tag     | report_number        | report_number        | text          | text          |
| Yes      | series tag     | origin               | origin               | text          | text          |
| Yes      | series tag     | document_description | document_description | text          | text          |
| Yes      | series tag     | filer_id             | filer_id             | text          | text          |
| Yes      | series tag     | type                 | type                 | text          | text          |
| Yes      | series tag     | filer_name           | filer_name           | text          | text          |
| Yes      | series tag     | office               | office               | text          | text          |
| Yes      | series tag     | legislative_district | legislative_district | text          | text          |
| Yes      | series tag     | party                | party                | text          | text          |
| Yes      | numeric metric | election_year        | election_year        | number        | number        |
| Yes      | time           | receipt_date         | receipt_date         | calendar_date | calendar_date |
| No       |                | processed_date       | processed_date       | calendar_date | calendar_date |
| Yes      | series tag     | filing_method        | filing_method        | text          | text          |
| No       |                | report_from          | report_from          | calendar_date | calendar_date |
| No       |                | report_to            | report_to            | calendar_date | calendar_date |
| Yes      | series tag     | url                  | url                  | url           | url           |
```

## Time Field

```ls
Value = receipt_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,processed_date,report_from,report_to
```

## Data Commands

```ls
series e:j78t-andi d:2001-11-27T00:00:00.000Z t:report_number=PDC-000000002972 t:filer_name="XO COMMUNICATIONS" t:document_description="Candidate or committee name change" t:filing_method=Other t:filer_id=INVALID t:origin="NAME CHANGE" t:type=LOBBYISTS t:url="http://web.pdc.wa.gov/rptimg/default.aspx?docid=421285" m:election_year=2011

series e:j78t-andi d:2003-12-12T00:00:00.000Z t:office="COUNTY COUNCIL MEMBER" t:report_number=PDC-000000012363 t:filer_name="PHILLIPS LAWRENCE R" t:document_description="Form C1, candidate registration" t:filing_method=Other t:filer_id="PHILL  199" t:origin=C1 t:type="LOCAL CANDIDATES" t:party=DEMOCRAT t:url="http://web.pdc.wa.gov/rptimg/default.aspx?docid=624499" m:election_year=2007

series e:j78t-andi d:2004-03-01T00:00:00.000Z t:report_number=PDC-000000013337 t:filer_name="KENNEWICK CIT LEVY & BOND COMM" t:document_description="Form C1PC, committee registration" t:filing_method=Other t:filer_id="KENNCL 336" t:origin=C1PC t:type=COMMITTEES t:party="EDUCATION LEVY" t:url="http://web.pdc.wa.gov/rptimg/default.aspx?docid=640760" m:election_year=2008
```

## Meta Commands

```ls
metric m:election_year p:integer l:election_year d:"The election year in the case of candidates and single election committees. The reporting year for all other documents. For documents other than disclosure reports the election year field may be empty." t:dataTypeName=number

entity e:j78t-andi l:"Imaged Documents and Reports" t:attribution="Washington State Public Disclosure Commission" t:url=https://data.wa.gov/api/views/j78t-andi

property e:j78t-andi t:meta.view v:id=j78t-andi v:attributionLink=http://www.pdc.wa.gov v:averageRating=0 v:name="Imaged Documents and Reports" v:attribution="Washington State Public Disclosure Commission"

property e:j78t-andi t:meta.view.license v:name="Public Domain"

property e:j78t-andi t:meta.view.owner v:id=6hhm-htpq v:profileImageUrlMedium=/api/users/6hhm-htpq/profile_images/THUMB v:profileImageUrlLarge=/api/users/6hhm-htpq/profile_images/LARGE v:screenName="Washington Public Disclosure Commission" v:profileImageUrlSmall=/api/users/6hhm-htpq/profile_images/TINY v:displayName="Washington Public Disclosure Commission"

property e:j78t-andi t:meta.view.tableauthor v:id=6hhm-htpq v:profileImageUrlMedium=/api/users/6hhm-htpq/profile_images/THUMB v:profileImageUrlLarge=/api/users/6hhm-htpq/profile_images/LARGE v:screenName="Washington Public Disclosure Commission" v:profileImageUrlSmall=/api/users/6hhm-htpq/profile_images/TINY v:roleName=publisher v:displayName="Washington Public Disclosure Commission"
```

## Top Records

```ls
| id           | report_number    | origin      | document_description                       | filer_id   | type             | filer_name                     | office                | legislative_district | party          | election_year | receipt_date        | processed_date      | filing_method | report_from         | report_to           | url                                                                     | 
| ============ | ================ | =========== | ========================================== | ========== | ================ | ============================== | ===================== | ==================== | ============== | ============= | =================== | =================== | ============= | =================== | =================== | ======================================================================= | 
| 421285.image | PDC-000000002972 | NAME CHANGE | Candidate or committee name change         | INVALID    | LOBBYISTS        | XO COMMUNICATIONS              |                       |                      |                | 2011          | 2001-11-27T00:00:00 | 2001-11-27T00:00:00 | Other         |                     |                     | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=421285, View Document] | 
| 624499.image | PDC-000000012363 | C1          | Form C1, candidate registration            | PHILL 199  | LOCAL CANDIDATES | PHILLIPS LAWRENCE R            | COUNTY COUNCIL MEMBER |                      | DEMOCRAT       | 2007          | 2003-12-12T00:00:00 | 2003-12-12T00:00:00 | Other         |                     |                     | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=624499, View Document] | 
| 640760.image | PDC-000000013337 | C1PC        | Form C1PC, committee registration          | KENNCL 336 | COMMITTEES       | KENNEWICK CIT LEVY & BOND COMM |                       |                      | EDUCATION LEVY | 2008          | 2004-03-01T00:00:00 | 2004-03-01T00:00:00 | Other         |                     |                     | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=640760, View Document] | 
| 641418.image | 100065972        | C4          | Form C4, campaign summary report           | KENNCL 336 | COMMITTEES       | KENNEWICK CIT LEVY & BOND COMM |                       |                      | EDUCATION      | 2008          | 2004-03-03T00:00:00 | 2004-03-03T00:00:00 | Electronic    | 2004-02-19T00:00:00 | 2004-02-29T00:00:00 | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=641418, View Document] | 
| 641419.image | 100065972        | A           | Form C4, schedule A, campaign expenditures | KENNCL 336 | COMMITTEES       | KENNEWICK CIT LEVY & BOND COMM |                       |                      | EDUCATION      | 2008          | 2004-03-03T00:00:00 | 2004-03-03T00:00:00 | Electronic    | 2004-02-19T00:00:00 | 2004-02-29T00:00:00 | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=641419, View Document] | 
| 641420.image | 100065973        | C3          | Form C3, campaign cash receipts            | KENNCL 336 | COMMITTEES       | KENNEWICK CIT LEVY & BOND COMM |                       |                      | EDUCATION      | 2008          | 2004-03-03T00:00:00 | 2004-03-03T00:00:00 | Electronic    | 2004-02-28T00:00:00 | 2004-02-28T00:00:00 | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=641420, View Document] | 
| 648255.image | PDC-000000013693 | C1          | Form C1, candidate registration            | INVALID    | LOCAL CANDIDATES | FERGUSON ROBERT W              | COUNTY COUNCIL MEMBER |                      | DEMOCRAT       | 2007          | 2004-03-29T00:00:00 | 2004-03-29T00:00:00 | Other         |                     |                     | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=648255, View Document] | 
| 649107.image | 100068512        | C4          | Form C4, campaign summary report           | KENNCL 336 | COMMITTEES       | KENNEWICK CIT LEVY & BOND COMM |                       |                      | EDUCATION      | 2008          | 2004-04-02T00:00:00 | 2004-04-02T00:00:00 | Electronic    | 2004-03-01T00:00:00 | 2004-03-31T00:00:00 | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=649107, View Document] | 
| 649108.image | 100068512        | A           | Form C4, schedule A, campaign expenditures | KENNCL 336 | COMMITTEES       | KENNEWICK CIT LEVY & BOND COMM |                       |                      | EDUCATION      | 2008          | 2004-04-02T00:00:00 | 2004-04-02T00:00:00 | Electronic    | 2004-03-01T00:00:00 | 2004-03-31T00:00:00 | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=649108, View Document] | 
| 649110.image | 100068513        | C3          | Form C3, campaign cash receipts            | KENNCL 336 | COMMITTEES       | KENNEWICK CIT LEVY & BOND COMM |                       |                      | EDUCATION      | 2008          | 2004-04-02T00:00:00 | 2004-04-02T00:00:00 | Electronic    | 2004-03-31T00:00:00 | 2004-03-31T00:00:00 | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=649110, View Document] | 
```