# CIP Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cip-expenditures-8c090) |
| Metadata | [Link](https://data.hawaii.gov/api/views/54sf-nz6w) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/54sf-nz6w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/54sf-nz6w/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 54sf-nz6w |
| Name | CIP Expenditures |
| Attribution | Accounting Divisions of the Department of Accounting and General Services |
| Category | Government-Wide Support |
| Tags | famis, dags |
| Created | 2012-08-20T20:58:44Z |
| Publication Date | 2012-09-06T17:16:02Z |

## Description

CIP Expenditures. Monthly Data Extract from FAMIS - Financial Accounting Management Information System. Coded fields may require further analysis to interpret

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | document_type             | Document type             | text      | text        |
| Yes      | series tag     | encumbrance_type          | Encumbrance Type          | text      | text        |
| Yes      | series tag     | reporting_program         | Reporting Program         | text      | text        |
| Yes      | series tag     | appropriation_type        | Appropriation Type        | text      | text        |
| Yes      | series tag     | mode_of_funding           | Mode of Funding           | text      | text        |
| Yes      | series tag     | transaction_code          | Transaction code          | text      | text        |
| Yes      | series tag     | division                  | Division                  | text      | text        |
| Yes      | series tag     | fund                      | Fund                      | text      | text        |
| Yes      | time           | fiscal_year               | Fiscal Year               | number    | number      |
| Yes      | numeric metric | appropriation_account     | Appropriation Account     | number    | text        |
| Yes      | series tag     | department                | Department                | text      | text        |
| Yes      | numeric metric | source_object             | Source object             | number    | text        |
| Yes      | series tag     | cost_center               | Cost Center               | text      | text        |
| Yes      | series tag     | project                   | Project                   | text      | text        |
| Yes      | series tag     | active                    | Active                    | text      | text        |
| Yes      | numeric metric | amount                    | Amount                    | money     | money       |
| Yes      | series tag     | encumbrance_number        | Encumbrance Number        | text      | text        |
| Yes      | series tag     | encumbrance_number_suffix | Encumbrance Number Suffix | text      | text        |
| Yes      | series tag     | vendor_number             | Vendor Number             | text      | text        |
| Yes      | series tag     | vendor_name               | Vendor Name               | text      | text        |
| Yes      | series tag     | invoice_number            | Invoice number            | text      | text        |
| Yes      | series tag     | check_number              | Check Number              | text      | number      |
| No       |                | check_date                | Check Date                | text      | number      |
| Yes      | series tag     | cvn                       | CVN                       | text      | text        |
| Yes      | series tag     | department_vn             | Department VN             | text      | text        |
| Yes      | series tag     | document_number           | Document Number           | text      | text        |
| No       |                | fm                        | FM                        | number    | number      |
| Yes      | series tag     | enc_fm                    | ENC FM                    | text      | text        |
| No       |                | transaction_fiscal_year   | Transaction Fiscal Year   | number    | number      |
| No       |                | processing_year           | Processing Year           | number    | number      |
| Yes      | numeric metric | process_month             | Process Month             | number    | number      |
| No       |                | process_date              | Process Date              | text      | number      |
| Yes      | series tag     | transaction_id            | Transaction ID            | text      | text        |
| No       |                | aging_start_date          | Aging Start Date          | text      | number      |
| Yes      | series tag     | optional_department_data  | Optional Department Data  | text      | text        |
| No       |                | invoice_date              | Invoice Date              | text      | number      |
| Yes      | series tag     | d11_vf_1099_ind           | D11-VF-1099-IND           | text      | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = check_date,fm,transaction_fiscal_year,processing_year,process_date,aging_start_date,invoice_date
```

## Data Commands

```ls
series e:54sf-nz6w d:2007-01-01T00:00:00.000Z t:encumbrance_type=C t:encumbrance_number=60195 t:d11_vf_1099_ind=Y t:vendor_number=74324 t:cvn=3659 t:enc_fm=12 t:department=A t:invoice_number=9 t:transaction_id="A J120625930000010" t:reporting_program=AGR141 t:document_type=VP t:appropriation_type=4 t:mode_of_funding=C t:project=5 t:cost_center=11 t:department_vn=946 t:document_number=946 t:encumbrance_number_suffix=1 t:active=0 t:fund=B t:transaction_code=231 t:vendor_name="ROYAL CONTRACTING CO., LTD." m:amount=1394098 m:process_month=6 m:appropriation_account=411 m:source_object=7107

series e:54sf-nz6w d:2007-01-01T00:00:00.000Z t:encumbrance_type=C t:encumbrance_number=60195 t:d11_vf_1099_ind=Y t:vendor_number=74324 t:cvn=3659 t:enc_fm=12 t:department=A t:invoice_number=9 t:transaction_id="A J120625930000020" t:reporting_program=AGR141 t:document_type=VP t:appropriation_type=4 t:mode_of_funding=C t:project=5 t:cost_center=11 t:department_vn=946 t:document_number=946 t:encumbrance_number_suffix=1 t:active=0 t:fund=B t:transaction_code=203 t:vendor_name="ROYAL CONTRACTING CO., LTD." m:amount=-69705 m:process_month=6 m:appropriation_account=411 m:source_object=7107

series e:54sf-nz6w d:2009-01-01T00:00:00.000Z t:encumbrance_type=C t:encumbrance_number=60636 t:d11_vf_1099_ind=Y t:vendor_number=311499 t:cvn=3664 t:enc_fm=5 t:department=A t:invoice_number=37239318 t:transaction_id="A J120625940000010" t:reporting_program=AGR141 t:document_type=VP t:appropriation_type=4 t:mode_of_funding=C t:project=1 t:cost_center=11 t:department_vn=943 t:document_number=943 t:encumbrance_number_suffix=1 t:active=303 t:fund=B t:transaction_code=231 t:vendor_name="AECOM TECHNICAL SERVICES, INC." m:amount=6253600 m:process_month=6 m:appropriation_account=400 m:source_object=7107
```

## Meta Commands

```ls
metric m:appropriation_account p:integer l:"Appropriation Account" t:dataTypeName=number

metric m:source_object p:integer l:"Source object" t:dataTypeName=number

metric m:amount p:long l:Amount t:dataTypeName=money

metric m:process_month p:integer l:"Process Month" t:dataTypeName=number

entity e:54sf-nz6w l:"CIP Expenditures" t:attribution="Accounting Divisions of the Department of Accounting and General Services" t:url=https://data.hawaii.gov/api/views/54sf-nz6w

property e:54sf-nz6w t:meta.view v:id=54sf-nz6w v:category="Government-Wide Support" v:attributionLink=http://hawaii.gov/dags/accounting-division v:averageRating=0 v:name="CIP Expenditures" v:attribution="Accounting Divisions of the Department of Accounting and General Services"

property e:54sf-nz6w t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:54sf-nz6w t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:54sf-nz6w t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| document_type | encumbrance_type | reporting_program | appropriation_type | mode_of_funding | transaction_code | division | fund | fiscal_year | appropriation_account | department | source_object | cost_center | project | active | amount   | encumbrance_number | encumbrance_number_suffix | vendor_number | vendor_name                    | invoice_number | check_number | check_date | cvn  | department_vn | document_number | fm | enc_fm | transaction_fiscal_year | processing_year | process_month | process_date | transaction_id     | aging_start_date | optional_department_data | invoice_date | d11_vf_1099_ind | 
| ============= | ================ | ================= | ================== | =============== | ================ | ======== | ==== | =========== | ===================== | ========== | ============= | =========== | ======= | ====== | ======== | ================== | ========================= | ============= | ============================== | ============== | ============ | ========== | ==== | ============= | =============== | == | ====== | ======================= | =============== | ============= | ============ | ================== | ================ | ======================== | ============ | =============== | 
| VP            | C                | AGR141            | 4                  | C               | 231              |          | B    | 2007        | 411                   | A          | 7107          | 11          | 5       | 0      | 1394098  | 60195              | 1                         | 74324         | ROYAL CONTRACTING CO., LTD.    | 9              |              |            | 3659 | 946           | 946             | 12 | 12     | 2012                    | 2012            | 6             | 25           | A J120625930000010 | 20120607         |                          | 20120531     | Y               | 
| VP            | C                | AGR141            | 4                  | C               | 203              |          | B    | 2007        | 411                   | A          | 7107          | 11          | 5       | 0      | -69705   | 60195              | 1                         | 74324         | ROYAL CONTRACTING CO., LTD.    | 9              |              |            | 3659 | 946           | 946             | 12 | 12     | 2012                    | 2012            | 6             | 25           | A J120625930000020 | 20120607         |                          | 20120531     | Y               | 
| VP            | C                | AGR141            | 4                  | C               | 231              |          | B    | 2009        | 400                   | A          | 7107          | 11          | 1       | 303    | 6253600  | 60636              | 1                         | 311499        | AECOM TECHNICAL SERVICES, INC. | 37239318       |              |            | 3664 | 943           | 943             | 12 | 5      | 2012                    | 2012            | 6             | 25           | A J120625940000010 | 20120605         |                          | 20120522     | Y               | 
| VP            | C                | AGR141            | 4                  | C               | 231              |          | B    | 2009        | 407                   | A          | 7107          | 11          | 5       | 302    | 17403280 | 60636              | 3                         | 311499        | AECOM TECHNICAL SERVICES, INC. | 37239318       |              |            | 3664 | 943           | 943             | 12 | 5      | 2012                    | 2012            | 6             | 25           | A J120625940000020 | 20120605         |                          | 20120522     | Y               | 
| VP            | C                | AGR141            | 4                  | C               | 231              |          | B    | 2009        | 404                   | A          | 7107          | 11          | 2       | 304    | 1760665  | 60626              | 1                         | 83529         | AKINAKA & ASSOCIATES, LTD.     | 4              |              |            | 3664 | 943           | 943             | 12 | 5      | 2012                    | 2012            | 6             | 25           | A J120625940000030 | 20120605         |                          | 20120522     | Y               | 
| VP            | C                | AGR141            | 4                  | C               | 231              |          | B    | 2006        | 400                   | A          | 7107          | 10          | 1       | 0      | 1829958  | 57279              | 1                         | 308434        | ALLOY HARDFACING & ENGINEERING | 1              |              |            | 3664 | 943           | 943             | 12 | 12     | 2012                    | 2012            | 6             | 25           | A J120625940000040 | 20120614         |                          | 20120529     | Y               | 
| VP            | C                | AGR141            | 4                  | C               | 231              |          | B    | 2004        | 410                   | A          | 7107          | 10          | 1       | 108    | 1029215  | 54479              | 2                         | 280114        | EXCEL DESIGNS, INC.            | E-12-019       |              |            | 3664 | 943           | 943             | 12 | 10     | 2012                    | 2012            | 6             | 25           | A J120625940000050 | 20120605         |                          | 20120514     | Y               | 
| VP            | C                | AGR141            | 4                  | C               | 231              |          | B    | 2006        | 400                   | A          | 7107          | 10          | 1       | 108    | 944685   | 54479              | 3                         | 280114        | EXCEL DESIGNS, INC.            | E-12-019       |              |            | 3664 | 943           | 943             | 12 | 12     | 2012                    | 2012            | 6             | 25           | A J120625940000060 | 20120605         |                          | 20120514     | Y               | 
| VP            | C                | AGR141            | 4                  | C               | 231              |          | B    | 2009        | 408                   | A          | 7107          | 11          | 5       | 302    | 6815517  | 60205              | 1                         | 296127        | FOPCO, INC.                    | 8              |              |            | 3664 | 943           | 943             | 12 | 12     | 2012                    | 2012            | 6             | 25           | A J120625940000070 | 20120614         |                          | 20120430     | Y               | 
| VP            | C                | AGR141            | 4                  | C               | 203              |          | B    | 2009        | 408                   | A          | 7107          | 11          | 5       | 302    | -340776  | 60205              | 1                         | 296127        | FOPCO, INC.                    | 8              |              |            | 3664 | 943           | 943             | 12 | 12     | 2012                    | 2012            | 6             | 25           | A J120625940000080 | 20120614         |                          | 20120430     | Y               | 
```