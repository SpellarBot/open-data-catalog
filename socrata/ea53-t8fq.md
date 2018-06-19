# Salaries: Agencies: As of June 30, 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-agencies-as-of-june-30-2010-d18db) |
| Metadata | [Link](https://data.oregon.gov/api/views/ea53-t8fq) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ea53-t8fq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ea53-t8fq/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ea53-t8fq |
| Name | Salaries: Agencies: As of June 30, 2010 |
| Attribution | State of Oregon - Department of Administrative Services |
| Tags | workforce, salary, oregon, transparency, state, agency, data, data.oregon.gov |
| Created | 2011-02-08T01:05:25Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Each annual salary listed in this report is 12 times that particular employee's monthly adjusted salary rate as of June 30, 2010 (between July 1, 2009 and June 30, 2010). "Annual Salary" includes most differential payments (such as work-out-of-classification and bilingual differential), but excludes payments for overtime, shift differential, benefits, and vacation payout. The report does not account for unpaid furlough leave that management employees began taking in fiscal year 2009-2010; neither does it reflect step decreases and unpaid furlough leave that some classified employees began taking after June 2009.

This report does not include annual salaries for employees of the Oregon University System, semi-independent agencies, temporary employees, or records protected by court order.

For more State of Oregon Workforce/salary information please visit the Oregon Transparency Website: http://oregon.gov/transparency/state_workforce.page

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | classification | CLASSIFICATION | text      | text        |
| Yes      | series tag     | service_type   | SERVICE TYPE   | text      | text        |
| Yes      | numeric metric | annual_salary  | ANNUAL SALARY  | money     | money       |
| Yes      | series tag     | agency         | AGENCY #       | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ea53-t8fq d:2010-01-01T00:00:00.000Z t:service_type=UNREPRESENTED t:classification="ADMINISTRATIVE SPECIALIST 2" t:agency=12000 m:annual_salary=38820

series e:ea53-t8fq d:2010-01-01T00:00:00.000Z t:service_type=UNREPRESENTED t:classification="EXECUTIVE SUPPORT SPECIALIST 2" t:agency=12000 m:annual_salary=44064

series e:ea53-t8fq d:2010-01-01T00:00:00.000Z t:service_type="MANAGEMENT SERVICE" t:classification="FINANCIAL INVESTIGATOR 1" t:agency=12000 m:annual_salary=64872
```

## Meta Commands

```ls
metric m:annual_salary p:decimal l:"ANNUAL SALARY" t:dataTypeName=money

entity e:ea53-t8fq l:"Salaries: Agencies: As of June 30, 2010" t:attribution="State of Oregon - Department of Administrative Services" t:url=https://data.oregon.gov/api/views/ea53-t8fq

property e:ea53-t8fq t:meta.view v:id=ea53-t8fq v:attributionLink=http://oregon.gov/transparency/state_workforce.page v:averageRating=100 v:name="Salaries: Agencies: As of June 30, 2010" v:attribution="State of Oregon - Department of Administrative Services"

property e:ea53-t8fq t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ea53-t8fq t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| classification                 | service_type       | annual_salary      | agency | 
| ============================== | ================== | ================== | ====== | 
| ADMINISTRATIVE SPECIALIST 2    | UNREPRESENTED      | 38820              | 12000  | 
| EXECUTIVE SUPPORT SPECIALIST 2 | UNREPRESENTED      | 44064              | 12000  | 
| FINANCIAL INVESTIGATOR 1       | MANAGEMENT SERVICE | 64872              | 12000  | 
| OFFICE SPECIALIST 2            | UNREPRESENTED      | 35340              | 12000  | 
| OFFICE SPECIALIST 2            | UNREPRESENTED      | 33768              | 12000  | 
| PRINCIPAL EXECUTIVE/MANAGER D  | AGENCY HEAD        | 83964              | 12000  | 
| ACCOUNTANT 1                   | MANAGEMENT SERVICE | 41920.199999999997 | 10700  | 
| ACCOUNTANT 1                   | REPRESENTED        | 46836              | 10700  | 
| ACCOUNTANT 2                   | MANAGEMENT SERVICE | 41844              | 10700  | 
| ACCOUNTANT 2                   | MANAGEMENT SERVICE | 53376              | 10700  | 
```