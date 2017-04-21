# Regent Institution Revenue By Fiscal Year Class And Unit

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/regent-institution-revenue-by-fiscal-year-class-and-unit) |
| Metadata | [Link](https://data.iowa.gov/api/views/j5dj-2hfj) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/j5dj-2hfj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/j5dj-2hfj/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | j5dj-2hfj |
| Name | Regent Institution Revenue By Fiscal Year Class And Unit |
| Attribution | Iowa Board of Regents |
| Category | Education |
| Tags | revenue, financials |
| Created | 2014-12-23T17:33:18Z |
| Publication Date | 2016-08-30T19:55:59Z |

## Description

Provides aggregate revenue data for Board of Regent's universities and special schools by fiscal year, class and unit starting with Fiscal Year 2012.  Fiscal years run from July 1 to the following June 30, and are numbered for the calendar year in which they end.  All receipts are deposited to the appropriate fiscal year in which the revenues were received.  If revenue is received after the end of the fiscal year but within 60 days, they may be adjusted back to previous fiscal year.  If received after 60 days, they are recorded in the fiscal year received.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | time           | fiscal_year   | Fiscal Year   | number    | number      |
| Yes      | series tag     | institution   | Institution   | text      | text        |
| Yes      | series tag     | unit          | Unit          | text      | text        |
| Yes      | series tag     | revenue_class | Revenue Class | text      | text        |
| Yes      | numeric metric | revenues      | Revenues      | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:j5dj-2hfj d:2012-01-01T00:00:00.000Z t:unit="General University" t:revenue_class="State Appropriations" t:institution="University of Iowa" m:revenues=209737311

series e:j5dj-2hfj d:2012-01-01T00:00:00.000Z t:unit="General University" t:revenue_class="Interest Income" t:institution="University of Iowa" m:revenues=1631727

series e:j5dj-2hfj d:2012-01-01T00:00:00.000Z t:unit="General University" t:revenue_class=Tuition t:institution="University of Iowa" m:revenues=366397221
```

## Meta Commands

```ls
metric m:revenues p:integer l:Revenues d:"Aggregate revenue by fiscal year, institution, unit and revenue class" t:dataTypeName=money

entity e:j5dj-2hfj l:"Regent Institution Revenue By Fiscal Year Class And Unit" t:attribution="Iowa Board of Regents" t:url=https://data.iowa.gov/api/views/j5dj-2hfj

property e:j5dj-2hfj t:meta.view v:id=j5dj-2hfj v:category=Education v:averageRating=0 v:name="Regent Institution Revenue By Fiscal Year Class And Unit" v:attribution="Iowa Board of Regents"

property e:j5dj-2hfj t:meta.view.license v:name="Public Domain"

property e:j5dj-2hfj t:meta.view.owner v:id=ym7w-2hjx v:profileImageUrlMedium=/api/users/ym7w-2hjx/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym7w-2hjx/profile_images/LARGE v:screenName="Iowa Board of Regents" v:profileImageUrlSmall=/api/users/ym7w-2hjx/profile_images/TINY v:displayName="Iowa Board of Regents"

property e:j5dj-2hfj t:meta.view.tableauthor v:id=ym7w-2hjx v:profileImageUrlMedium=/api/users/ym7w-2hjx/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym7w-2hjx/profile_images/LARGE v:screenName="Iowa Board of Regents" v:profileImageUrlSmall=/api/users/ym7w-2hjx/profile_images/TINY v:roleName=editor v:displayName="Iowa Board of Regents"
```

## Top Records

```ls
| fiscal_year | institution        | unit                      | revenue_class                | revenues  | 
| =========== | ================== | ========================= | ============================ | ========= | 
| 2012        | University of Iowa | General University        | State Appropriations         | 209737311 | 
| 2012        | University of Iowa | General University        | Interest Income              | 1631727   | 
| 2012        | University of Iowa | General University        | Tuition                      | 366397221 | 
| 2012        | University of Iowa | General University        | Indirect Cost Reimbursements | 46575653  | 
| 2012        | University of Iowa | General University        | Other Income                 | 51146     | 
| 2012        | University of Iowa | State Hygienic Laboratory | State Appropriations         | 3536716   | 
| 2012        | University of Iowa | State Hygienic Laboratory | Indirect Cost Reimbursements | 260825    | 
| 2012        | University of Iowa | State Hygienic Laboratory | Sales & Services             | 2514087   | 
| 2012        | University of Iowa | Oakdale Campus            | State Appropriations         | 2186558   | 
| 2012        | University of Iowa | Oakdale Campus            | Indirect Cost Reimbursements | 1137171   | 
```