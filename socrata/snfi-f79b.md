# UCC List of Filings Entered Last Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ucc-list-of-filings-entered-last-month-7c45d) |
| Metadata | [Link](https://data.oregon.gov/api/views/snfi-f79b) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/snfi-f79b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/snfi-f79b/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | snfi-f79b |
| Name | UCC List of Filings Entered Last Month |
| Category | Business |
| Tags | ucc |
| Created | 2011-10-12T21:38:28Z |
| Publication Date | 2017-04-03T16:14:20Z |

## Description

Updated 4/1/2017 List of New UCC filings entered during the previous month. This list will be updated by the 9th of every month.

## Columns

```ls
| Included | Schema Type | Field Name           | Name        | Data Type     | Render Type   |
| ======== | =========== | ==================== | =========== | ============= | ============= |
| Yes      | series tag  | lien_type            | LIEN_TYPE   | text          | text          |
| Yes      | series tag  | original_file_number | LIEN NUMBER | text          | text          |
| Yes      | series tag  | file_number          | FILE_NUMBER | text          | text          |
| Yes      | series tag  | file_type            | FILE_TYPE   | text          | text          |
| Yes      | time        | filing_date          | FILING_DATE | calendar_date | calendar_date |
| No       |             | lapse_date           | LAPSE_DATE  | calendar_date | calendar_date |
| Yes      | series tag  | party_type           | PARTY_TYP   | text          | text          |
| Yes      | series tag  | entity_type          | ENTITY_TYP  | text          | text          |
| Yes      | series tag  | entity               | ENTITY      | text          | text          |
| Yes      | series tag  | mail_addr_1          | MAIL_ADDR_1 | text          | text          |
| Yes      | series tag  | mail_addr_2          | MAIL_ADDR_2 | text          | text          |
| Yes      | series tag  | city_descr           | CITY        | text          | text          |
| Yes      | series tag  | st_cd_txt            | STATE       | text          | text          |
| Yes      | series tag  | zip_code_txt         | ZIP_CODE    | text          | text          |
| Yes      | series tag  | cntry_cd_txt         | COUNTRY     | text          | text          |
```

## Time Field

```ls
Value = filing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = lapse_date
```

## Data Commands

```ls
series e:snfi-f79b d:2017-03-20T00:00:00.000Z t:lien_type=UCC t:city_descr=SPOKANE t:file_number=2091-31 t:party_type=SP t:entity="NORTHWEST FARM CREDIT SERVICES, FLCA, AS AGENT FOR COBANK, ACB" t:st_cd_txt=WA t:zip_code_txt=99220 t:entity_type=ORG t:mail_addr_1="PO BOX 2515" t:cntry_cd_txt=USA t:original_file_number=2091 t:file_type=AMENDMENT m:row_number.snfi-f79b=1

series e:snfi-f79b d:2017-03-21T00:00:00.000Z t:lien_type=UCC t:city_descr=ORANGE t:file_number=2139-17 t:party_type=SP t:entity="WELLS FARGO COMMERCIAL DISTRIBUTION FINANCE, LLC" t:st_cd_txt=CA t:zip_code_txt=92863 t:entity_type=ORG t:mail_addr_1="P.O. BOX 5610" t:cntry_cd_txt=USA t:original_file_number=2139 t:file_type=AMENDMENT m:row_number.snfi-f79b=2

series e:snfi-f79b d:2017-03-09T00:00:00.000Z t:lien_type=UCC t:city_descr=SALEM t:file_number=9230-12 t:party_type=DB t:entity="WHITNELL MOTOR COMPANY" t:st_cd_txt=OR t:zip_code_txt=97302 t:entity_type=ORG t:mail_addr_1="2650 COMMERCIAL ST SE" t:cntry_cd_txt=USA t:original_file_number=9230 t:file_type=AMENDMENT m:row_number.snfi-f79b=3
```

## Meta Commands

```ls
metric m:row_number.snfi-f79b p:long l:"Row Number"

entity e:snfi-f79b l:"UCC List of Filings Entered Last Month" t:url=https://data.oregon.gov/api/views/snfi-f79b

property e:snfi-f79b t:meta.view v:id=snfi-f79b v:category=Business v:averageRating=0 v:name="UCC List of Filings Entered Last Month"

property e:snfi-f79b t:meta.view.license v:name="Public Domain"

property e:snfi-f79b t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:snfi-f79b t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| lien_type | original_file_number | file_number | file_type | filing_date         | lapse_date          | party_type | entity_type | entity                                                         | mail_addr_1                  | mail_addr_2 | city_descr | st_cd_txt | zip_code_txt | cntry_cd_txt | 
| ========= | ==================== | =========== | ========= | =================== | =================== | ========== | =========== | ============================================================== | ============================ | =========== | ========== | ========= | ============ | ============ | 
| UCC       | 2091                 | 2091-31     | AMENDMENT | 2017-03-20T00:00:00 | 2022-06-21T00:00:00 | SP         | ORG         | NORTHWEST FARM CREDIT SERVICES, FLCA, AS AGENT FOR COBANK, ACB | PO BOX 2515                  |             | SPOKANE    | WA        | 99220        | USA          | 
| UCC       | 2139                 | 2139-17     | AMENDMENT | 2017-03-21T00:00:00 | 2022-07-19T00:00:00 | SP         | ORG         | WELLS FARGO COMMERCIAL DISTRIBUTION FINANCE, LLC               | P.O. BOX 5610                |             | ORANGE     | CA        | 92863        | USA          | 
| UCC       | 9230                 | 9230-12     | AMENDMENT | 2017-03-09T00:00:00 | 2020-08-19T00:00:00 | DB         | ORG         | WHITNELL MOTOR COMPANY                                         | 2650 COMMERCIAL ST SE        |             | SALEM      | OR        | 97302        | USA          | 
| UCC       | 17085                | 17085-8     | AMENDMENT | 2017-03-09T00:00:00 | 2022-04-16T00:00:00 | DB         | ORG         | ALAN BROWN TIRE CENTER, INC.                                   | 1155 SW COAST HWY            |             | NEWPORT    | OR        | 97365        | USA          | 
| UCC       | 19197                | 19197-9     | AMENDMENT | 2017-03-20T00:00:00 | 2022-07-29T00:00:00 | DB         | ORG         | THE CRONIN COMPANY                                             | 1205 NW MARSHALL             |             | PORTLAND   | OR        | 97209        | USA          | 
| UCC       | 29405                | 29405-9     | AMENDMENT | 2017-03-09T00:00:00 | 2018-11-02T00:00:00 | DB         | ORG         | WHITNELL MOTOR COMPANY                                         | 555 SW OAK ST CLSC W PL 0285 |             | PORTLAND   | OR        | 97204        | USA          | 
| UCC       | 29406                | 29406-9     | AMENDMENT | 2017-03-09T00:00:00 | 2018-11-02T00:00:00 | DB         | ORG         | WHITNELL MOTOR COMPANY                                         | 555 SW OAK ST CLSC W PL 0285 |             | PORTLAND   | OR        | 97204        | USA          | 
| UCC       | 31773                | 31773-10    | AMENDMENT | 2017-03-31T00:00:00 | 2019-01-27T00:00:00 | DB         | ORG         | RTL-M, INC.                                                    | 1212 NE 122ND                |             | PORTLAND   | OR        | 97230        | USA          | 
| UCC       | 108272               | 108272-7    | AMENDMENT | 2017-03-07T00:00:00 | 2021-08-12T00:00:00 | DB         | IND         | CONANT, THOMAS IVAN                                            | 21977 SE STARK               |             | GRESHAM    | OR        | 97030        | USA          | 
| UCC       | 143502               | 143502-8    | AMENDMENT | 2017-03-07T00:00:00 | 2022-07-09T00:00:00 | DB         | ORG         | POWER AUTO, INC.                                               | 500 W SUBLIMITY BLVD         |             | SUBLIMITY  | OR        | 97383        | USA          | 
```