# Historic Tax Credit Applicants Given Preliminary Approval in 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historic-tax-credit-applicants-given-preliminary-approval-in-2010-f5f6b) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/iub8-xy78) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/iub8-xy78/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/iub8-xy78/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | iub8-xy78 |
| Name | Historic Tax Credit Applicants Given Preliminary Approval in 2010 |
| Attribution | Baltimore City Planning Department |
| Category | Financial |
| Tags | tax credits, historic, planning |
| Created | 2011-10-19T20:23:06Z |
| Publication Date | 2014-04-03T23:45:34Z |

## Description

A list of properties given preliminary approval for the Historic Tax Credit during the 2010 calendar year.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | =========== | ==================== | ==================== | ============= | ============= |
| No       |             | property_address     | Property Address     | text          | text          |
| Yes      | series tag  | zip_code             | Zip Code             | text          | text          |
| Yes      | series tag  | historic_district    | Historic District    | text          | text          |
| Yes      | series tag  | district_type        | District Type        | text          | text          |
| Yes      | time        | application_date     | Application Date     | calendar_date | calendar_date |
| No       |             | preliminary_approval | Preliminary Approval | calendar_date | calendar_date |
| No       |             | final_certification  | Final Certification  | calendar_date | calendar_date |
```

## Time Field

```ls
Value = application_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = property_address,preliminary_approval,final_certification
```

## Data Commands

```ls
series e:iub8-xy78 d:2010-01-12T00:00:00.000Z t:historic_district="Broadway East / S. Clifton Park" t:zip_code=0 t:district_type="National District" m:row_number.iub8-xy78=1

series e:iub8-xy78 d:2010-01-15T00:00:00.000Z t:historic_district="Bolton Hill" t:zip_code=21217 t:district_type="Local & National District" m:row_number.iub8-xy78=2

series e:iub8-xy78 d:2009-12-21T00:00:00.000Z t:historic_district="Old West Baltimore" t:zip_code=0 t:district_type="National District" m:row_number.iub8-xy78=3
```

## Meta Commands

```ls
metric m:row_number.iub8-xy78 p:long l:"Row Number"

entity e:iub8-xy78 l:"Historic Tax Credit Applicants Given Preliminary Approval in 2010" t:attribution="Baltimore City Planning Department" t:url=https://data.baltimorecity.gov/api/views/iub8-xy78

property e:iub8-xy78 t:meta.view v:id=iub8-xy78 v:category=Financial v:attributionLink=http://www.baltimorecity.gov/Government/AgenciesDepartments/Planning.aspx v:averageRating=0 v:name="Historic Tax Credit Applicants Given Preliminary Approval in 2010" v:attribution="Baltimore City Planning Department"

property e:iub8-xy78 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:iub8-xy78 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:iub8-xy78 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| property_address          | zip_code | historic_district               | district_type             | application_date    | preliminary_approval | final_certification | 
| ========================= | ======== | =============================== | ========================= | =================== | ==================== | =================== | 
| 1740 E. Chase St          | 0        | Broadway East / S. Clifton Park | National District         | 2010-01-12T00:00:00 | 2010-01-26T00:00:00  |                     | 
| 142 W. Lanvale Street     | 21217    | Bolton Hill                     | Local & National District | 2010-01-15T00:00:00 | 2010-01-26T00:00:00  | 2011-01-14T00:00:00 | 
| 2125 McCulloh St          | 0        | Old West Baltimore              | National District         | 2009-12-21T00:00:00 | 2010-01-06T00:00:00  |                     | 
| 813 S. Bouldin St         | 21224    | Canton                          | National District         | 2010-01-05T00:00:00 | 2010-01-26T00:00:00  | 2010-05-14T00:00:00 | 
| 1117 McDonough St         | 0        | Broadway East / S. Clifton Park | National District         | 2010-01-14T00:00:00 | 2010-01-26T00:00:00  |                     | 
| 1012 Hollins St           | 21223    | Union Square                    | Local & National District | 2010-01-21T00:00:00 | 2010-02-19T00:00:00  | 2010-03-18T00:00:00 | 
| 1311 Druid Hill Ave       | 0        | Old West Baltimore              | National District         | 2009-12-07T00:00:00 | 2010-01-06T00:00:00  |                     | 
| 2528 Fleet St             | 21224    | Canton                          | National District         | 2010-01-14T00:00:00 | 2010-01-26T00:00:00  | 2010-06-15T00:00:00 | 
| 1711 Guilford Ave         | 0        | North Central                   | National District         | 2009-12-21T00:00:00 | 2010-01-06T00:00:00  |                     | 
| 513 S. Patterson Park Ave | 21231    | Canton                          | National District         | 2009-12-21T00:00:00 | 2010-01-06T00:00:00  | 2010-09-16T00:00:00 | 
```