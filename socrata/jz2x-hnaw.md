# Administrative Hearings - Ticket Summary Without Payments Report - FY2011 through September 27th, 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/administrative-hearings-ticket-summary-without-payments-report-fy2011-through-september-20-eac30) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/jz2x-hnaw) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/jz2x-hnaw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/jz2x-hnaw/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | jz2x-hnaw |
| Name | Administrative Hearings - Ticket Summary Without Payments Report - FY2011 through September 27th, 2011 |
| Attribution | Cook County Department of Administrative Hearings |
| Category | Courts |
| Created | 2011-09-27T21:14:54Z |
| Publication Date | 2014-10-09T22:59:45Z |

## Description

Data last updated September 27th, 2011.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | department_description   | Department Description   | text      | text        |
| Yes      | numeric metric | number_of_tickets_issued | Number of Tickets Issued | number    | number      |
| Yes      | numeric metric | original_amt_due         | Original Amt Due         | money     | money       |
| Yes      | numeric metric | total_fines              | Total Fines              | money     | money       |
| Yes      | numeric metric | total_paid               | Total Paid               | money     | money       |
| Yes      | numeric metric | balance_due              | Balance Due              | money     | money       |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jz2x-hnaw d:2011-01-01T00:00:00.000Z t:department_description=Amusement m:number_of_tickets_issued=65 m:total_fines=574361.48 m:original_amt_due=0

series e:jz2x-hnaw d:2011-01-01T00:00:00.000Z t:department_description="Animal Control" m:number_of_tickets_issued=164 m:total_fines=70365 m:original_amt_due=0

series e:jz2x-hnaw d:2011-01-01T00:00:00.000Z t:department_description="Building and Zoning" m:number_of_tickets_issued=522 m:total_fines=30115 m:original_amt_due=0
```

## Meta Commands

```ls
metric m:number_of_tickets_issued p:integer l:"Number of Tickets Issued" t:dataTypeName=number

metric m:original_amt_due p:double l:"Original Amt Due" t:dataTypeName=money

metric m:total_fines p:double l:"Total Fines" t:dataTypeName=money

metric m:total_paid p:double l:"Total Paid" t:dataTypeName=money

metric m:balance_due p:double l:"Balance Due" t:dataTypeName=money

entity e:jz2x-hnaw l:"Administrative Hearings - Ticket Summary Without Payments Report - FY2011 through September 27th, 2011" t:attribution="Cook County Department of Administrative Hearings" t:url=https://datacatalog.cookcountyil.gov/api/views/jz2x-hnaw

property e:jz2x-hnaw t:meta.view v:id=jz2x-hnaw v:category=Courts v:attributionLink=http://www.cookcountyildoah.org/ v:averageRating=0 v:name="Administrative Hearings - Ticket Summary Without Payments Report - FY2011 through September 27th, 2011" v:attribution="Cook County Department of Administrative Hearings"

property e:jz2x-hnaw t:meta.view.license v:name="Public Domain"

property e:jz2x-hnaw t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:jz2x-hnaw t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| department_description  | number_of_tickets_issued | original_amt_due | total_fines | total_paid | balance_due | 
| ======================= | ======================== | ================ | =========== | ========== | =========== | 
| Amusement               | 65                       | 0.00             | 574361.48   |            |             | 
| Animal Control          | 164                      | 0.00             | 70365.00    |            |             | 
| Building and Zoning     | 522                      | 0.00             | 30115.00    |            |             | 
| Department of Revenue   | 838                      | 0.00             | 1215819.55  |            |             | 
| Diesel Tax              | 16                       | 0.00             | 54694.24    |            |             | 
| Environmental Control   | 95                       | 0.00             | 63359.00    |            |             | 
| Forest Preserve         | 2823                     | 0.00             | 377138.00   |            |             | 
| Gas Tax                 | 11                       | 0.00             | 29292.11    |            |             | 
| Highway Department      | 3                        | 0.00             | 175.00      |            |             | 
| Impound Forest Preserve | 167                      | 0.00             | 45600.00    |            |             | 
```