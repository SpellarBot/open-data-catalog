# Lobbyist Employment Registrations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/draft-lobbyist-employment-registration) |
| Metadata | [Link](https://data.wa.gov/api/views/xhn7-64im) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/xhn7-64im/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/xhn7-64im/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | xhn7-64im |
| Name | Lobbyist Employment Registrations |
| Attribution | Public Disclosure Commission |
| Tags | political finance, elections, expenditures, campaign, political committee, lobbying |
| Created | 2017-01-12T22:37:50Z |
| Publication Date | 2017-02-10T17:13:15Z |

## Description

This dataset contains records indicating the employment of lobbyist firms by entities that employ lobbyists. Each record represents a registration by the lobbyist firm and employer (client) for one year. 

In some cases, the lobbyist firm may have been hired as a subcontractor by another firm to lobby on behalf of their clients. In these cases, refer to the contractor fields to determine the lobbyist firm that has hired the subcontractor.

This data set contains only records for 2016 and later. For records prior to 2016, please see the data set, "Pre-2016 Lobbyist Employment Registrations"

Each record provides links to document providing detailed information about the lobbyist firm, employer and nature of the employment.

This dataset is a best-effort by the PDC to provide a complete set of records as described herewith and may contain incomplete or incorrect information. The PDC provides access to the original reports for the purpose of record verification.

Descriptions attached to this dataset do not constitute legal definitions; please consult RCW 42.17A and WAC Title 390 for legal definitions and additional information regarding political finance disclosure requirements.

CONDITION OF RELEASE: This publication and or referenced documents constitutes a list of individuals prepared by the Washington State Public Disclosure Commission and may not be used for commercial purposes. This list is provided on the condition and with the understanding that the persons receiving it agree to this statutorily imposed limitation on its use. See RCW 42.56.070(9) and AGO 1975 No. 15.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       |             | id              | id              | text      | text        |
| Yes      | series tag  | report_number   | report_number   | text      | text        |
| Yes      | series tag  | lobbyist_id     | lobbyist_id     | text      | text        |
| Yes      | series tag  | lobbyist_name   | lobbyist_name   | text      | text        |
| Yes      | series tag  | lobbyist_url    | lobbyist_url    | url       | url         |
| Yes      | series tag  | employer_id     | employer_id     | text      | text        |
| Yes      | series tag  | employer_name   | employer_name   | text      | text        |
| Yes      | series tag  | employer_url    | employer_url    | url       | url         |
| Yes      | time        | employment_year | employment_year | number    | number      |
| Yes      | series tag  | contractor_id   | contractor_id   | text      | text        |
| Yes      | series tag  | contractor_name | contractor_name | text      | text        |
| Yes      | series tag  | contractor_url  | contractor_url  | url       | url         |
| Yes      | series tag  | employment_url  | employment_url  | url       | url         |
```

## Time Field

```ls
Value = employment_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:xhn7-64im l:"Lobbyist Employment Registrations" t:attribution="Public Disclosure Commission" t:url=https://data.wa.gov/api/views/xhn7-64im

property e:xhn7-64im t:meta.view v:id=xhn7-64im v:attributionLink=http://www.pdc.wa.gov v:averageRating=0 v:name="Lobbyist Employment Registrations" v:attribution="Public Disclosure Commission"

property e:xhn7-64im t:meta.view.license v:name="Public Domain"

property e:xhn7-64im t:meta.view.owner v:id=6hhm-htpq v:profileImageUrlMedium=/api/users/6hhm-htpq/profile_images/THUMB v:profileImageUrlLarge=/api/users/6hhm-htpq/profile_images/LARGE v:screenName="Washington Public Disclosure Commission" v:profileImageUrlSmall=/api/users/6hhm-htpq/profile_images/TINY v:displayName="Washington Public Disclosure Commission"

property e:xhn7-64im t:meta.view.tableauthor v:id=6hhm-htpq v:profileImageUrlMedium=/api/users/6hhm-htpq/profile_images/THUMB v:profileImageUrlLarge=/api/users/6hhm-htpq/profile_images/LARGE v:screenName="Washington Public Disclosure Commission" v:profileImageUrlSmall=/api/users/6hhm-htpq/profile_images/TINY v:roleName=publisher v:displayName="Washington Public Disclosure Commission"
```

## Top Records

```ls
| id         | report_number | lobbyist_id | lobbyist_name  | lobbyist_url                                                  | employer_id | employer_name                     | employer_url                                                  | employment_year | contractor_id | contractor_name | contractor_url | employment_url                                                                 | 
| ========== | ============= | =========== | ============== | ============================================================= | =========== | ================================= | ============================================================= | =============== | ============= | =============== | ============== | ============================================================================== | 
| 18113-2017 | 18113         | 17329       | ADVOCATES INC* | [https://accesshub.pdc.wa.gov/node/17329, View lobbyist info] | 16068       | ADVANCE AMERICA (THRU MULTISTATE) | [https://accesshub.pdc.wa.gov/node/16068, View employer info] | 2017            |               |                 | [null, null]   | [https://accesshub.pdc.wa.gov/node/18113, View employment_registration report] | 
| 18113-2016 | 18113         | 17329       | ADVOCATES INC* | [https://accesshub.pdc.wa.gov/node/17329, View lobbyist info] | 16068       | ADVANCE AMERICA (THRU MULTISTATE) | [https://accesshub.pdc.wa.gov/node/16068, View employer info] | 2016            |               |                 | [null, null]   | [https://accesshub.pdc.wa.gov/node/18113, View employment_registration report] | 
| 18114-2017 | 18114         | 17329       | ADVOCATES INC* | [https://accesshub.pdc.wa.gov/node/17329, View lobbyist info] | 16252       | CHECK INTO CASH (THRU MULTISTATE) | [https://accesshub.pdc.wa.gov/node/16252, View employer info] | 2017            |               |                 | [null, null]   | [https://accesshub.pdc.wa.gov/node/18114, View employment_registration report] | 
| 18114-2016 | 18114         | 17329       | ADVOCATES INC* | [https://accesshub.pdc.wa.gov/node/17329, View lobbyist info] | 16252       | CHECK INTO CASH (THRU MULTISTATE) | [https://accesshub.pdc.wa.gov/node/16252, View employer info] | 2016            |               |                 | [null, null]   | [https://accesshub.pdc.wa.gov/node/18114, View employment_registration report] | 
| 18116-2017 | 18116         | 17329       | ADVOCATES INC* | [https://accesshub.pdc.wa.gov/node/17329, View lobbyist info] | 16666       | NATIONAL GUARD ASSOC OF WA        | [https://accesshub.pdc.wa.gov/node/16666, View employer info] | 2017            |               |                 | [null, null]   | [https://accesshub.pdc.wa.gov/node/18116, View employment_registration report] | 
| 18116-2016 | 18116         | 17329       | ADVOCATES INC* | [https://accesshub.pdc.wa.gov/node/17329, View lobbyist info] | 16666       | NATIONAL GUARD ASSOC OF WA        | [https://accesshub.pdc.wa.gov/node/16666, View employer info] | 2016            |               |                 | [null, null]   | [https://accesshub.pdc.wa.gov/node/18116, View employment_registration report] | 
| 18117-2017 | 18117         | 17329       | ADVOCATES INC* | [https://accesshub.pdc.wa.gov/node/17329, View lobbyist info] | 16824       | PUBLIC SCHOOL EMPLOYEES OF WA     | [https://accesshub.pdc.wa.gov/node/16824, View employer info] | 2017            |               |                 | [null, null]   | [https://accesshub.pdc.wa.gov/node/18117, View employment_registration report] | 
| 18117-2016 | 18117         | 17329       | ADVOCATES INC* | [https://accesshub.pdc.wa.gov/node/17329, View lobbyist info] | 16824       | PUBLIC SCHOOL EMPLOYEES OF WA     | [https://accesshub.pdc.wa.gov/node/16824, View employer info] | 2016            |               |                 | [null, null]   | [https://accesshub.pdc.wa.gov/node/18117, View employment_registration report] | 
| 18118-2017 | 18118         | 17329       | ADVOCATES INC* | [https://accesshub.pdc.wa.gov/node/17329, View lobbyist info] | 16835       | PUYALLUP TRIBE OF INDIANS         | [https://accesshub.pdc.wa.gov/node/16835, View employer info] | 2017            |               |                 | [null, null]   | [https://accesshub.pdc.wa.gov/node/18118, View employment_registration report] | 
| 18118-2016 | 18118         | 17329       | ADVOCATES INC* | [https://accesshub.pdc.wa.gov/node/17329, View lobbyist info] | 16835       | PUYALLUP TRIBE OF INDIANS         | [https://accesshub.pdc.wa.gov/node/16835, View employer info] | 2016            |               |                 | [null, null]   | [https://accesshub.pdc.wa.gov/node/18118, View employment_registration report] | 
```