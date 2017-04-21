# Debt Reported by Candidates and Political Committees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/draft-debts) |
| Metadata | [Link](https://data.wa.gov/api/views/3r6b-hsaa) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/3r6b-hsaa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/3r6b-hsaa/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 3r6b-hsaa |
| Name | Debt Reported by Candidates and Political Committees |
| Attribution | Public Disclosure Commission |
| Tags | political finance, elections, debts, campaign, political committee |
| Created | 2017-01-12T22:35:03Z |
| Publication Date | 2017-04-18T06:09:57Z |

## Description

This dataset contains debts, obligations, and orders placed by Washington State Candidates and Political committees for the last 10 years as reported to the PDC on Schedule B to the C4 Summary Report.

Loans are not included in this dataset. Loans, however, are a debt but are contained in the Loan dataset.

For candidates, the number of years is determined by the year of the election, not necessarily the year the expenditure was reported. For political committees, the number of years is determined by the calendar year of the reporting period.

Candidates and political committees choosing to file under "mini reporting" are not included in this dataset. See WAC 390-16-105 for information regarding eligibility.

This dataset is a best-effort by the PDC to provide a complete set of records as described herewith and may contain incomplete or incorrect information. The PDC provides access to the original reports for the purpose of record verification.

Descriptions attached to this dataset do not constitute legal definitions; please consult RCW 42.17A and WAC Title 390 for legal definitions and additional information regarding political finance disclosure requirements.

CONDITION OF RELEASE: This publication constitutes a list of individuals prepared by the Washington State Public Disclosure Commission and may not be used for commercial purposes. This list is provided on the condition and with the understanding that the persons receiving it agree to this statutorily imposed limitation on its use. See
RCW 42.56.070(9) and AGO 1975 No. 15.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| No       |                | id                   | id                   | text          | text          |
| Yes      | series tag     | report_number        | report_number        | text          | text          |
| Yes      | series tag     | origin               | origin               | text          | text          |
| Yes      | series tag     | filer_id             | filer_id             | text          | text          |
| Yes      | series tag     | filer_type           | filer_type           | text          | text          |
| Yes      | series tag     | filer_name           | filer_name           | text          | text          |
| Yes      | series tag     | first_name           | first_name           | text          | text          |
| Yes      | series tag     | middle_initial       | middle_initial       | text          | text          |
| Yes      | series tag     | last_name            | last_name            | text          | text          |
| Yes      | series tag     | office               | office               | text          | text          |
| Yes      | series tag     | legislative_district | legislative_district | text          | text          |
| Yes      | series tag     | position             | position             | text          | text          |
| Yes      | series tag     | party                | party                | text          | text          |
| Yes      | series tag     | jurisdiction         | jurisdiction         | text          | text          |
| Yes      | series tag     | jurisdiction_county  | jurisdiction_county  | text          | text          |
| Yes      | series tag     | jurisdiction_type    | jurisdiction_type    | text          | text          |
| No       |                | election_year        | election_year        | number        | number        |
| Yes      | numeric metric | amount               | amount               | money         | money         |
| Yes      | series tag     | record_type          | record_type          | text          | text          |
| Yes      | time           | debt_date            | debt_date            | calendar_date | calendar_date |
| Yes      | series tag     | code                 | code                 | text          | text          |
| Yes      | series tag     | description          | description          | text          | text          |
| Yes      | series tag     | vendor_name          | vendor_name          | text          | text          |
| No       |                | vendor_address       | vendor_address       | text          | text          |
| Yes      | series tag     | vendor_city          | vendor_city          | text          | text          |
| Yes      | series tag     | vendor_state         | vendor_state         | text          | text          |
| Yes      | series tag     | vendor_zip           | vendor_zip           | text          | text          |
| Yes      | series tag     | url                  | url                  | url           | url           |
```

## Time Field

```ls
Value = debt_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,vendor_address,election_year
```

## Data Commands

```ls
series e:3r6b-hsaa d:2005-09-12T00:00:00.000Z t:office="COUNTY COUNCIL MEMBER" t:position=09 t:vendor_state=WA t:report_number=100159853 t:filer_name="DUNN REAGAN B" t:jurisdiction_county=KING t:middle_initial=B t:origin=B.3 t:filer_type=Candidate t:jurisdiction="KING CO" t:party="NON PARTISAN" t:url="http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100159853" t:vendor_city=SEATTLE t:jurisdiction_type=Local t:first_name=REAGAN t:vendor_zip=98101 t:record_type=DEBT t:description=CATERING/PHONE/POSTAGE t:filer_id="DUNNR  059" t:last_name=DUNN t:vendor_name="FUNDRAISING PARTNERS NORTHWEST" m:amount=411.57

series e:3r6b-hsaa d:2005-09-12T00:00:00.000Z t:office="COUNTY COUNCIL MEMBER" t:position=09 t:vendor_state=WA t:report_number=100159853 t:filer_name="DUNN REAGAN B" t:jurisdiction_county=KING t:middle_initial=B t:origin=B.3 t:filer_type=Candidate t:jurisdiction="KING CO" t:party="NON PARTISAN" t:url="http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100159853" t:vendor_city=SEATTLE t:jurisdiction_type=Local t:first_name=REAGAN t:vendor_zip=98101 t:record_type=DEBT t:description=CONSULTING t:filer_id="DUNNR  059" t:last_name=DUNN t:vendor_name="FUNDRAISING PARTNERS NORTHWEST" m:amount=3000

series e:3r6b-hsaa d:2005-10-11T00:00:00.000Z t:office="COUNTY COUNCIL MEMBER" t:position=09 t:vendor_state=WA t:report_number=100159853 t:filer_name="DUNN REAGAN B" t:jurisdiction_county=KING t:middle_initial=B t:origin=B.3 t:filer_type=Candidate t:jurisdiction="KING CO" t:party="NON PARTISAN" t:url="http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100159853" t:vendor_city=SEATTLE t:jurisdiction_type=Local t:first_name=REAGAN t:vendor_zip=98101 t:record_type=DEBT t:description=CATERING/PHONE/POSTAGE t:filer_id="DUNNR  059" t:last_name=DUNN t:vendor_name="FUNDRAISING PARTNERS NORTHWEST" m:amount=274.71
```

## Meta Commands

```ls
metric m:amount p:double l:amount d:"The amount of the debt incurred or order placed. This field could be an estimate while the campaign is awaiting the final invoice. This column may contain a few negative amounts. These are caused by inaccurate reporting by the filer." t:dataTypeName=money

entity e:3r6b-hsaa l:"Debt Reported by Candidates and Political Committees" t:attribution="Public Disclosure Commission" t:url=https://data.wa.gov/api/views/3r6b-hsaa

property e:3r6b-hsaa t:meta.view v:id=3r6b-hsaa v:attributionLink=http://www.pdc.wa.gov v:averageRating=0 v:name="Debt Reported by Candidates and Political Committees" v:attribution="Public Disclosure Commission"

property e:3r6b-hsaa t:meta.view.license v:name="Public Domain"

property e:3r6b-hsaa t:meta.view.owner v:id=6hhm-htpq v:profileImageUrlMedium=/api/users/6hhm-htpq/profile_images/THUMB v:profileImageUrlLarge=/api/users/6hhm-htpq/profile_images/LARGE v:screenName="Washington Public Disclosure Commission" v:profileImageUrlSmall=/api/users/6hhm-htpq/profile_images/TINY v:displayName="Washington Public Disclosure Commission"

property e:3r6b-hsaa t:meta.view.tableauthor v:id=6hhm-htpq v:profileImageUrlMedium=/api/users/6hhm-htpq/profile_images/THUMB v:profileImageUrlLarge=/api/users/6hhm-htpq/profile_images/LARGE v:screenName="Washington Public Disclosure Commission" v:profileImageUrlSmall=/api/users/6hhm-htpq/profile_images/TINY v:roleName=publisher v:displayName="Washington Public Disclosure Commission"
```

## Top Records

```ls
| id         | report_number | origin | filer_id  | filer_type | filer_name    | first_name | middle_initial | last_name | office                | legislative_district | position | party        | jurisdiction | jurisdiction_county | jurisdiction_type | election_year | amount  | record_type | debt_date           | code | description                | vendor_name                    | vendor_address        | vendor_city | vendor_state | vendor_zip | url                                                                            | 
| ========== | ============= | ====== | ========= | ========== | ============= | ========== | ============== | ========= | ===================== | ==================== | ======== | ============ | ============ | =================== | ================= | ============= | ======= | =========== | =================== | ==== | ========================== | ============================== | ===================== | =========== | ============ | ========== | ============================================================================== | 
| 11285.debt | 100159853     | B.3    | DUNNR 059 | Candidate  | DUNN REAGAN B | REAGAN     | B              | DUNN      | COUNTY COUNCIL MEMBER |                      | 09       | NON PARTISAN | KING CO      | KING                | Local             | 2009          | 411.57  | DEBT        | 2005-09-12T00:00:00 |      | CATERING/PHONE/POSTAGE     | FUNDRAISING PARTNERS NORTHWEST | 1411 4TH AVE STE 1210 | SEATTLE     | WA           | 98101      | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100159853, View report] | 
| 11286.debt | 100159853     | B.3    | DUNNR 059 | Candidate  | DUNN REAGAN B | REAGAN     | B              | DUNN      | COUNTY COUNCIL MEMBER |                      | 09       | NON PARTISAN | KING CO      | KING                | Local             | 2009          | 3000.00 | DEBT        | 2005-09-12T00:00:00 |      | CONSULTING                 | FUNDRAISING PARTNERS NORTHWEST | 1411 4TH AVE STE 1210 | SEATTLE     | WA           | 98101      | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100159853, View report] | 
| 11287.debt | 100159853     | B.3    | DUNNR 059 | Candidate  | DUNN REAGAN B | REAGAN     | B              | DUNN      | COUNTY COUNCIL MEMBER |                      | 09       | NON PARTISAN | KING CO      | KING                | Local             | 2009          | 274.71  | DEBT        | 2005-10-11T00:00:00 |      | CATERING/PHONE/POSTAGE     | FUNDRAISING PARTNERS NORTHWEST | 1411 4TH AVE STE 1210 | SEATTLE     | WA           | 98101      | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100159853, View report] | 
| 11288.debt | 100159853     | B.3    | DUNNR 059 | Candidate  | DUNN REAGAN B | REAGAN     | B              | DUNN      | COUNTY COUNCIL MEMBER |                      | 09       | NON PARTISAN | KING CO      | KING                | Local             | 2009          | 3000.00 | DEBT        | 2005-10-11T00:00:00 |      | CONSULTING                 | FUNDRAISING PARTNERS NORTHWEST | 1411 4TH AVE STE 1210 | SEATTLE     | WA           | 98101      | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100159853, View report] | 
| 11289.debt | 100159853     | B.3    | DUNNR 059 | Candidate  | DUNN REAGAN B | REAGAN     | B              | DUNN      | COUNTY COUNCIL MEMBER |                      | 09       | NON PARTISAN | KING CO      | KING                | Local             | 2009          | 8000.00 | DEBT        | 2005-10-30T00:00:00 |      | FUNDRAISING BONUS          | FUNDRAISING PARTNERS NORTHWEST | 1411 4TH AVE STE 1210 | SEATTLE     | WA           | 98101      | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100159853, View report] | 
| 11290.debt | 100159853     | B.3    | DUNNR 059 | Candidate  | DUNN REAGAN B | REAGAN     | B              | DUNN      | COUNTY COUNCIL MEMBER |                      | 09       | NON PARTISAN | KING CO      | KING                | Local             | 2009          | 5000.00 | DEBT        | 2005-10-29T00:00:00 |      | RETAINER FEE               | POLIS POLITICAL SERVICES       | 2014 CLAIRMONT CIR SW | OLYMPIA     | WA           | 98512      | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100159853, View report] | 
| 11291.debt | 100159853     | B.3    | DUNNR 059 | Candidate  | DUNN REAGAN B | REAGAN     | B              | DUNN      | COUNTY COUNCIL MEMBER |                      | 09       | NON PARTISAN | KING CO      | KING                | Local             | 2009          | 5000.00 | DEBT        | 2005-10-30T00:00:00 |      | POLITICAL CONSULTING BONUS | POLIS POLITICAL SERVICES       | 2014 CLAIRMONT CIR SW | OLYMPIA     | WA           | 98512      | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100159853, View report] | 
| 12178.debt | 100177142     | B.3    | DUNNR 059 | Candidate  | DUNN REAGAN B | REAGAN     | B              | DUNN      | COUNTY COUNCIL MEMBER |                      | 09       | NON PARTISAN | KING CO      | KING                | Local             | 2009          | 6686.28 | DEBT        | 2005-10-30T00:00:00 |      | FUNDRAISING BONUS          | FUNDRAISING PARTNERS NORTHWEST | 1411 4TH AVE STE 1210 | SEATTLE     | WA           | 98101      | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100177142, View report] | 
| 12179.debt | 100177142     | B.3    | DUNNR 059 | Candidate  | DUNN REAGAN B | REAGAN     | B              | DUNN      | COUNTY COUNCIL MEMBER |                      | 09       | NON PARTISAN | KING CO      | KING                | Local             | 2009          | 5000.00 | DEBT        | 2005-10-29T00:00:00 |      | RETAINER FEE               | POLIS POLITICAL SERVICES       | 2014 CLAIRMONT CIR SW | OLYMPIA     | WA           | 98512      | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100177142, View report] | 
| 12180.debt | 100177142     | B.3    | DUNNR 059 | Candidate  | DUNN REAGAN B | REAGAN     | B              | DUNN      | COUNTY COUNCIL MEMBER |                      | 09       | NON PARTISAN | KING CO      | KING                | Local             | 2009          | 5000.00 | DEBT        | 2005-10-30T00:00:00 |      | POLITICAL CONSULTING BONUS | POLIS POLITICAL SERVICES       | 2014 CLAIRMONT CIR SW | OLYMPIA     | WA           | 98512      | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100177142, View report] | 
```