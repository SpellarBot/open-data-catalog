# Procurement - Buying Plan - Fiscal Year 2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/procurement-buying-plan-fiscal-year-2017) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/pads-xcm2) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/pads-xcm2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/pads-xcm2/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | pads-xcm2 |
| Name | Procurement - Buying Plan - Fiscal Year 2017 |
| Attribution | Office of the Chief Procurement Officer |
| Category | Finance & Administration |
| Created | 2016-11-22T16:10:10Z |
| Publication Date | 2016-12-09T19:43:16Z |

## Description

As a public agency, the Office of the Chief Procurement Officer welcomes all vendors to participate in the open and competitive process. The buying plan contains hundreds of great opportunities for vendors to do business with Cook County. The buying plan includes information on numerous County projects and needs. You will find useful information on the department requesting proposals, project descriptions, value of contract, advertising date, and various Minority, Women and Veteran Business Enterprise subcontracting opportunities. OCPO encourages all potential vendors to use the information provided in the plan to assist them in future procurement efforts. Please contact Procurement staff or visit our website at https://www.cookcountyil.gov/procurement with any questions regarding procurement and contracting.

## Columns

```ls
| Included | Schema Type | Field Name                                   | Name                                           | Data Type | Render Type |
| ======== | =========== | ============================================ | ============================================== | ========= | =========== |
| Yes      | series tag  | department                                   | Department                                     | text      | text        |
| Yes      | series tag  | estimated_amount                             | Estimated Amount                               | text      | text        |
| Yes      | series tag  | description                                  | Description                                    | text      | text        |
| No       |             | anticipated_advertising_date_quarterly       | Anticipated Advertising Date (Quarterly)       | text      | text        |
| Yes      | series tag  | m_wbe_subcontracting_opportunities_by_trades | M/WBE Subcontracting Opportunities (By Trades) | text      | text        |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = anticipated_advertising_date_quarterly
```

## Data Commands

```ls
series e:pads-xcm2 d:2017-01-01T00:00:00.000Z t:description="ADOPTION CASE MANAGEMENT SYSTEM" t:department="Adoption and Family Supportive Services" t:estimated_amount="$500,001 - $1,000,000" t:m_wbe_subcontracting_opportunities_by_trades="Professional Services, Project Management" m:row_number.pads-xcm2=1

series e:pads-xcm2 d:2017-01-01T00:00:00.000Z t:description="RABIES VACCINATION TAGS" t:department="Animal Control Department" t:estimated_amount="$25,001 - $100,000" t:m_wbe_subcontracting_opportunities_by_trades=TBD m:row_number.pads-xcm2=2

series e:pads-xcm2 d:2017-01-01T00:00:00.000Z t:description="AFTER HOURS ANSWERING SERVICE" t:department="Animal Control Department" t:estimated_amount=<$25,000 t:m_wbe_subcontracting_opportunities_by_trades=TBD m:row_number.pads-xcm2=3
```

## Meta Commands

```ls
metric m:row_number.pads-xcm2 p:long l:"Row Number"

entity e:pads-xcm2 l:"Procurement - Buying Plan - Fiscal Year 2017" t:attribution="Office of the Chief Procurement Officer" t:url=https://datacatalog.cookcountyil.gov/api/views/pads-xcm2

property e:pads-xcm2 t:meta.view v:id=pads-xcm2 v:category="Finance & Administration" v:attributionLink=https://www.cookcountyil.gov/procurement v:averageRating=0 v:name="Procurement - Buying Plan - Fiscal Year 2017" v:attribution="Office of the Chief Procurement Officer"

property e:pads-xcm2 t:meta.view.license v:name="Public Domain"

property e:pads-xcm2 t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:pads-xcm2 t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| department                              | estimated_amount        | description                            | anticipated_advertising_date_quarterly | m_wbe_subcontracting_opportunities_by_trades | 
| ======================================= | ======================= | ====================================== | ====================================== | ============================================ | 
| Adoption and Family Supportive Services | $500,001 - $1,000,000   | ADOPTION CASE MANAGEMENT SYSTEM        | FY17 1st Quarter (Dec-Feb)             | Professional Services, Project Management    | 
| Animal Control Department               | $25,001 - $100,000      | RABIES VACCINATION TAGS                | FY17 1st Quarter (Dec-Feb)             | TBD                                          | 
| Animal Control Department               | <$25,000                | AFTER HOURS ANSWERING SERVICE          | FY17 2nd Quarter (Mar-May)             | TBD                                          | 
| Animal Control Department               | <$25,000                | RABIES CERTIFICATE BOOKLETS            | FY17 3rd Quarter (Jun-Aug)             | TBD                                          | 
| Building and Zoning                     | $100,001 - $500,000     | CASE MANAGEMENT ENHANCEMENTS           | FY17 1st Quarter (Dec-Feb)             | Professional Services, Project Management    | 
| Capital Planning                        | >$5,000,000             | COUNTYWIDE ROOF REPLACEMENTS           | FY17 2nd Quarter (Mar-May)             | TBD                                          | 
| Capital Planning                        | >$5,000,000             | BUILDING RENOVATION; RECORDER OF DEEDS | FY17 2nd Quarter (Mar-May)             | TBD                                          | 
| Capital Planning                        | >$5,000,000             | CCB MAIN HOLDING AREA ADA IMPROVEMENTS | FY17 2nd Quarter (Mar-May)             | TBD                                          | 
| Capital Planning                        | $1,000,001 - $5,000,000 | BUILDING RENOVATION; MEDICAL EXAMINER  | FY17 2nd Quarter (Mar-May)             | TBD                                          | 
| Capital Planning                        | >$5,000,000             | DIVISION I & IA DEMOLITION             | FY17 3rd Quarter (Jun-Aug)             | TBD                                          | 
```