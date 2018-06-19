# Administrative Hearings - Ticket Summary Report - September 2011 to March 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/administrative-hearings-ticket-summary-report-september-2011-to-march-2012-32b3d) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/kyty-9fmm) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/kyty-9fmm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/kyty-9fmm/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | kyty-9fmm |
| Name | Administrative Hearings - Ticket Summary Report - September 2011 to March 2012 |
| Attribution | Cook County Department of Administrative Hearings |
| Category | Courts |
| Created | 2012-05-21T17:33:17Z |
| Publication Date | 2014-10-09T22:22:28Z |

## Description

Data covers September 2011 through March 2012.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                | Data Type | Render Type |
| ======== | ============== | ================== | =================== | ========= | =========== |
| Yes      | series tag     | department         | Department          | text      | text        |
| Yes      | numeric metric | of_tickets_issued  | # of Tickets Issued | number    | text        |
| Yes      | numeric metric | total_original_amt | Total Original Amt  | money     | money       |
| Yes      | numeric metric | total_ajd_fines    | Total Ajd Fines     | money     | money       |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kyty-9fmm d:2011-01-01T00:00:00.000Z t:department="Animal Control" m:total_original_amt=0 m:total_ajd_fines=58250 m:of_tickets_issued=142

series e:kyty-9fmm d:2011-01-01T00:00:00.000Z t:department="Building and Zoning" m:total_original_amt=0 m:total_ajd_fines=7250 m:of_tickets_issued=361

series e:kyty-9fmm d:2011-01-01T00:00:00.000Z t:department="Department of Revenue" m:total_original_amt=75 m:total_ajd_fines=1540094 m:of_tickets_issued=970
```

## Meta Commands

```ls
metric m:of_tickets_issued p:integer l:"# of Tickets Issued" t:dataTypeName=number

metric m:total_original_amt p:double l:"Total Original Amt" t:dataTypeName=money

metric m:total_ajd_fines p:double l:"Total Ajd Fines" t:dataTypeName=money

entity e:kyty-9fmm l:"Administrative Hearings - Ticket Summary Report - September 2011 to March 2012" t:attribution="Cook County Department of Administrative Hearings" t:url=https://datacatalog.cookcountyil.gov/api/views/kyty-9fmm

property e:kyty-9fmm t:meta.view v:id=kyty-9fmm v:category=Courts v:attributionLink=http://www.cookcountyildoah.org/ v:averageRating=0 v:name="Administrative Hearings - Ticket Summary Report - September 2011 to March 2012" v:attribution="Cook County Department of Administrative Hearings"

property e:kyty-9fmm t:meta.view.license v:name="Public Domain"

property e:kyty-9fmm t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:kyty-9fmm t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| department              | of_tickets_issued | total_original_amt | total_ajd_fines | 
| ======================= | ================= | ================== | =============== | 
| Animal Control          | 142               | 0.00               | 58250.00        | 
| Building and Zoning     | 361               | 0.00               | 7250.00         | 
| Department of Revenue   | 970               | 75.00              | 1540094.00      | 
| Environmental Control   | 221               | 0.00               | 79297.00        | 
| Forest Preserve         | 1032              | 0.00               | 95170.00        | 
| Impound Forest Preserve | 87                | 0.00               | 22700.00        | 
| Parking Forest Preserve | 213               | 0.00               | 9120.00         | 
| Public Health           | 2                 | 0.00               | 0.00            | 
| Revenue Collection      | 1144              | 376619.18          | 902234.41       | 
| Revenue Parking         | 1                 | 25.00              | 25.00           | 
```