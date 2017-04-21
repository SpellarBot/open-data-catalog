# DHS Grant Extract FY14 - Origin CSA Tracking

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dhs-grant-extract-fy14-origin-csa-tracking-10970) |
| Metadata | [Link](https://data.illinois.gov/api/views/vq6s-ze7w) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/vq6s-ze7w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/vq6s-ze7w/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | vq6s-ze7w |
| Name | DHS Grant Extract FY14 - Origin CSA Tracking |
| Attribution | Department of Human Services - Doug Kasamis |
| Category | Social/Healthcare |
| Tags | dhs, department of human services, grants |
| Created | 2014-01-24T18:42:35Z |
| Publication Date | 2014-01-24T18:45:59Z |

## Description

Department of Human Services FY14 Grants Extract. Source of Extract is CSA Tracking for Grants values greater than $0

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | agency              | AGENCY              | text          | text          |
| Yes      | series tag     | division            | DIVISION            | text          | text          |
| Yes      | series tag     | provider            | PROVIDER            | text          | text          |
| Yes      | series tag     | provider_zip        | PROVIDER_ZIP        | text          | number        |
| Yes      | series tag     | program_name        | PROGRAM_NAME        | text          | text          |
| Yes      | series tag     | program_description | PROGRAM_DESCRIPTION | text          | text          |
| Yes      | time           | funding_begin_date  | FUNDING_BEGIN_DATE  | calendar_date | calendar_date |
| No       |                | funding_end_date    | FUNDING_END_DATE    | calendar_date | calendar_date |
| Yes      | numeric metric | funding_amount      | FUNDING_AMOUNT      | money         | money         |
```

## Time Field

```ls
Value = funding_begin_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = funding_end_date
```

## Data Commands

```ls
series e:vq6s-ze7w d:2013-07-01T00:00:00.000Z t:provider_zip=60607 t:division=ASO t:program_description="WELCOMING CENTER FAMILY FOCUS ONE-STOP PROJECT" t:program_name="WELCOMING CENTER FAMILY FOCUS ONE-STOP PROJECT" t:agency=DHS t:provider="FAMILY FOCUS, INC." m:funding_amount=140000

series e:vq6s-ze7w d:2013-10-25T00:00:00.000Z t:provider_zip=60607 t:division=ASO t:program_description="WELCOMING CENTER FAMILY FOCUS ONE-STOP PROJECT" t:program_name="WELCOMING CENTER FAMILY FOCUS ONE-STOP PROJECT" t:agency=DHS t:provider="FAMILY FOCUS, INC." m:funding_amount=-10000

series e:vq6s-ze7w d:2013-12-02T00:00:00.000Z t:provider_zip=60607 t:division=ASO t:program_description="FRAMEWORK STAKEHOLDER ENGAGEMENT" t:program_name="FRAMEWORK STAKEHOLDER ENGAGEMENT" t:agency=DHS t:provider="ILLINOIS PUBLIC HEALTH INSTITUTE" m:funding_amount=233334
```

## Meta Commands

```ls
metric m:funding_amount p:double l:FUNDING_AMOUNT t:dataTypeName=money

entity e:vq6s-ze7w l:"DHS Grant Extract FY14 - Origin CSA Tracking" t:attribution="Department of Human Services - Doug Kasamis" t:url=https://data.illinois.gov/api/views/vq6s-ze7w

property e:vq6s-ze7w t:meta.view v:id=vq6s-ze7w v:category=Social/Healthcare v:averageRating=0 v:name="DHS Grant Extract FY14 - Origin CSA Tracking" v:attribution="Department of Human Services - Doug Kasamis"

property e:vq6s-ze7w t:meta.view.owner v:id=n8hi-8t7f v:screenName="Doug Kasamis" v:displayName="Doug Kasamis"

property e:vq6s-ze7w t:meta.view.tableauthor v:id=n8hi-8t7f v:screenName="Doug Kasamis" v:displayName="Doug Kasamis"
```

## Top Records

```ls
| agency | division | provider                             | provider_zip | program_name                                   | program_description                            | funding_begin_date  | funding_end_date    | funding_amount | 
| ====== | ======== | ==================================== | ============ | ============================================== | ============================================== | =================== | =================== | ============== | 
| DHS    | ASO      | FAMILY FOCUS, INC.                   | 60607        | WELCOMING CENTER FAMILY FOCUS ONE-STOP PROJECT | WELCOMING CENTER FAMILY FOCUS ONE-STOP PROJECT | 2013-07-01T00:00:00 | 2014-06-30T00:00:00 | 140000         | 
| DHS    | ASO      | FAMILY FOCUS, INC.                   | 60607        | WELCOMING CENTER FAMILY FOCUS ONE-STOP PROJECT | WELCOMING CENTER FAMILY FOCUS ONE-STOP PROJECT | 2013-10-25T00:00:00 | 2014-06-30T00:00:00 | -10000         | 
| DHS    | ASO      | ILLINOIS PUBLIC HEALTH INSTITUTE     | 60607        | FRAMEWORK STAKEHOLDER ENGAGEMENT               | FRAMEWORK STAKEHOLDER ENGAGEMENT               | 2013-12-02T00:00:00 | 2014-06-30T00:00:00 | 233334         | 
| DHS    | ASO      | LATINO ORGANIZATION OF THE SOUTHWEST | 60629        | IMMIGRATION INTEGRATION                        | SPECIAL PROJECT-ADMIN                          | 2013-07-01T00:00:00 | 2014-06-30T00:00:00 | 115000         | 
| DHS    | ASO      | LATINO RESOURCE INSTITUTE            | 60617        | WELCOMING CENTER FAMILY FOCUS ONE-STOP PROJECT | WELCOMING CENTER FAMILY FOCUS ONE-STOP PROJECT | 2013-12-01T00:00:00 | 2014-06-30T00:00:00 | 25000          | 
| DHS    | ASO      | Mt. Vernon Baptist Church            | 60624        | WELCOMING CENTER FAMILY FOCUS ONE-STOP PROJECT | WELCOMING CENTER FAMILY FOCUS ONE-STOP PROJECT | 2013-07-01T00:00:00 | 2014-06-30T00:00:00 | 13000          | 
| DHS    | ASO      | Mt. Vernon Baptist Church            | 60624        | WELCOMING CENTER FAMILY FOCUS ONE-STOP PROJECT | WELCOMING CENTER FAMILY FOCUS ONE-STOP PROJECT | 2013-10-25T00:00:00 | 2014-06-30T00:00:00 | -10000         | 
| DHS    | ASO      | OUR LADY OF MT CARMEL                | 60160        | IMMIGRATION INTEGRATION                        | SPECIAL PROJECT-ADMIN                          | 2013-07-01T00:00:00 | 2014-06-30T00:00:00 | 115000         | 
| DHS    | DASA     | A Safe Haven                         | 60608        | GLOBAL                                         | GLOBAL                                         | 2013-07-01T00:00:00 | 2014-06-30T00:00:00 | 1399576        | 
| DHS    | DASA     | A Safe Haven                         | 60608        | GLOBAL - DCFS                                  | GLOBAL FUNDING FOR DCFS INVOLVED CLIENTS       | 2013-07-01T00:00:00 | 2014-06-30T00:00:00 | 143000         | 
```