# Public Assistance Case Denials by Reason for Denial: Beginning 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-assistance-case-denials-by-reason-for-denial-beginning-2006) |
| Metadata | [Link](https://data.ny.gov/api/views/tyyj-jgv5) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/tyyj-jgv5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/tyyj-jgv5/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | tyyj-jgv5 |
| Name | Public Assistance Case Denials by Reason for Denial: Beginning 2006 |
| Attribution | New York State Office of Temporary and Disability Assistance (OTDA) |
| Category | Human Services |
| Tags | ta, sna, public assistance, welfare, case denials |
| Created | 2016-05-10T16:50:36Z |
| Publication Date | 2017-01-09T23:01:53Z |
| Rows Updated | 2017-01-09T23:01:47Z |

## Description

This dataset, from New York State Office of Temporary and Disability Assistance, provides the number of Public Assistance case denials in each month by reason for case denial, for each Local Social Services District (SSD).  It is similar to data published on an annual basis in the "Statistical Report on the Operations of New York State Public Assistance Programs."

## Columns

```ls
| Included | Schema Type    | Field Name      | Name                                                       | Data Type | Render Type |
| ======== | ============== | =============== | ========================================================== | ========= | =========== |
| No       |                | year            | Year                                                       | number    | number      |
| No       |                | month           | Month                                                      | text      | text        |
| Yes      | series tag     | month_code      | Month Code                                                 | text      | number      |
| Yes      | series tag     | district_code   | District Code                                              | text      | text        |
| Yes      | series tag     | district        | District                                                   | text      | text        |
| Yes      | numeric metric | ta_client_req   | Total Public Assistance (PA) Case Denials - Client Request | number    | number      |
| Yes      | numeric metric | ta_finance      | Total PA Case Denials - Financial Issues                   | number    | number      |
| Yes      | numeric metric | ta_residence    | Total PA Case Denials - Residence Issues                   | number    | number      |
| Yes      | numeric metric | ta_comp_employ  | Total PA Case Denials - Compliance Issues / Employment     | number    | number      |
| Yes      | numeric metric | ta_comp_other   | Total PA Case Denials - Compliance Issues / Other          | number    | number      |
| Yes      | numeric metric | ta_other        | Total PA Case Denials - Other                              | number    | number      |
| Yes      | numeric metric | fa_client_req   | Family Assistance (FA) Case Denials - Client Request       | number    | number      |
| Yes      | numeric metric | fa_finance      | FA Denials Case - Financial Issues                         | number    | number      |
| Yes      | numeric metric | fa_residence    | FA Case Denials - Residence Issues                         | number    | number      |
| Yes      | numeric metric | fa_comp_employ  | FA Case Denials - Compliance Issues / Employment           | number    | number      |
| Yes      | numeric metric | fa_comp_other   | FA Case Denials - Compliance Issues / Other                | number    | number      |
| Yes      | numeric metric | fa_other        | FA Case Denials - Other                                    | number    | number      |
| Yes      | numeric metric | sna_client_req  | Safety Net Assistance (SNA) Case Denials - Client Request  | number    | number      |
| Yes      | numeric metric | sna_finance     | SNA Case Denials - Financial Issues                        | number    | number      |
| Yes      | numeric metric | sna_residence   | SNA Case Denials - Residence Issues                        | number    | number      |
| Yes      | numeric metric | sna_comp_employ | SNA Case Denials - Compliance Issues / Employment          | number    | number      |
| Yes      | numeric metric | sna_comp_other  | SNA Case Denials - Compliance Issues / Other               | number    | number      |
| Yes      | numeric metric | sna_other       | SNA Case Denials - Other                                   | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = month,year
```

## Data Commands

```ls
series e:tyyj-jgv5 d:2006-01-01T00:00:00.000Z t:district_code=01 t:month_code=1 t:district=Albany m:fa_finance=10 m:fa_comp_other=79 m:sna_comp_employ=20 m:ta_comp_employ=25 m:fa_comp_employ=5 m:fa_client_req=2 m:ta_finance=16 m:sna_client_req=0 m:fa_residence=9 m:sna_finance=6 m:ta_residence=28 m:ta_client_req=2 m:fa_other=5 m:sna_residence=19 m:sna_other=30 m:ta_other=35 m:sna_comp_other=176 m:ta_comp_other=255

series e:tyyj-jgv5 d:2006-01-01T00:00:00.000Z t:district_code=02 t:month_code=1 t:district=Allegany m:fa_finance=4 m:fa_comp_other=4 m:sna_comp_employ=3 m:ta_comp_employ=5 m:fa_comp_employ=2 m:fa_client_req=2 m:ta_finance=6 m:sna_client_req=4 m:fa_residence=1 m:sna_finance=2 m:ta_residence=2 m:ta_client_req=6 m:fa_other=0 m:sna_residence=1 m:sna_other=0 m:ta_other=0 m:sna_comp_other=10 m:ta_comp_other=14

series e:tyyj-jgv5 d:2006-01-01T00:00:00.000Z t:district_code=03 t:month_code=1 t:district=Broome m:fa_finance=28 m:fa_comp_other=67 m:sna_comp_employ=17 m:ta_comp_employ=19 m:fa_comp_employ=2 m:fa_client_req=8 m:ta_finance=81 m:sna_client_req=4 m:fa_residence=3 m:sna_finance=53 m:ta_residence=14 m:ta_client_req=12 m:fa_other=3 m:sna_residence=11 m:sna_other=17 m:ta_other=20 m:sna_comp_other=97 m:ta_comp_other=164
```

## Meta Commands

```ls
metric m:ta_client_req l:"Total Public Assistance (PA) Case Denials - Client Request" d:"Total Public Assistance case denials at the request of the client. Sum of Family Assistance and Safety Net Assistance case denials." t:dataTypeName=number

metric m:ta_finance l:"Total PA Case Denials - Financial Issues" d:"Total Public Assistance case denials due to financial issues; these include increased earned or unearned income, exceeding resource limits, or other household circumstance changes that make the case financially ineligible. Sum of Family Assistance and Safety Net Assistance case denials." t:dataTypeName=number

metric m:ta_residence l:"Total PA Case Denials - Residence Issues" d:"Total Public Assistance case denials due to residence issues; these include cases not residing in the jurisdiction of application or where the client cannot be located. Sum of Family Assistance and Safety Net Assistance case denials." t:dataTypeName=number

metric m:ta_comp_employ l:"Total PA Case Denials - Compliance Issues / Employment" d:"Total Public Assistance case denials due to compliance issues related to employment; these include failure to participate as required in Public Assistance work participation requirements, such as failure to cooperate with establishing employability, failure to attend work program assignments and voluntarily leaving or failing to accept employment without good cause. Sum of Family Assistance and Safety Net Assistance case denials." t:dataTypeName=number

metric m:ta_comp_other l:"Total PA Case Denials - Compliance Issues / Other" d:"Total Public Assistance case denials due to compliance issues other than employment; these include failure to comply with rules other than those related to employment, such as failure to show for eligibility interviews, provide required documentation to verify eligibility or comply with household composition requirements. Sum of Family Assistance and Safety Net Assistance case denials." t:dataTypeName=number

metric m:ta_other l:"Total PA Case Denials - Other" d:"Total Public Assistance case denials due to issues not included in the previous categories. Sum of Family Assistance and Safety Net Assistance case denials." t:dataTypeName=number

metric m:fa_client_req l:"Family Assistance (FA) Case Denials - Client Request" d:"Family Assistance case denials at the request of the client." t:dataTypeName=number

metric m:fa_finance l:"FA Denials Case - Financial Issues" d:"Family Assistance case denials due to financial issues; these include increased earned or unearned income, exceeding resource limits, or other household circumstance changes that make the case financially ineligible." t:dataTypeName=number

metric m:fa_residence l:"FA Case Denials - Residence Issues" d:"Family Assistance case denials due to residence issues; these include cases not residing in the jurisdiction of application or where the client cannot be located." t:dataTypeName=number

metric m:fa_comp_employ l:"FA Case Denials - Compliance Issues / Employment" d:"Family Assistance case denials due to compliance issues related to employment; these include failure to participate as required in Public Assistance work participation requirements, such as failure to cooperate with establishing employability, failure to attend work program assignments and voluntarily leaving or failing to accept employment without good cause." t:dataTypeName=number

metric m:fa_comp_other l:"FA Case Denials - Compliance Issues / Other" d:"Family Assistance case denials due to compliance issues other than employment; these include failure to comply with rules other than those related to employment, such as failure to show for eligibility interviews, provide required documentation to verify eligibility or comply with household composition requirements." t:dataTypeName=number

metric m:fa_other l:"FA Case Denials - Other" d:"Family Assistance case denials due to issues not included in the previous categories." t:dataTypeName=number

metric m:sna_client_req l:"Safety Net Assistance (SNA) Case Denials - Client Request" d:"Safety Net Assistance case denials at the request of the client." t:dataTypeName=number

metric m:sna_finance l:"SNA Case Denials - Financial Issues" d:"Safety Net Assistance case denials due to financial issues; these include increased earned or unearned income, exceeding resource limits, or other household circumstance changes that make the case financially ineligible." t:dataTypeName=number

metric m:sna_residence l:"SNA Case Denials - Residence Issues" d:"Safety Net Assistance case denials due to residence issues; these include cases not residing in the jurisdiction of application or where the client cannot be located." t:dataTypeName=number

metric m:sna_comp_employ l:"SNA Case Denials - Compliance Issues / Employment" d:"Safety Net Assistance case denials due to compliance issues related to employment; these include failure to participate as required in Public Assistance work participation requirements, such as failure to cooperate with establishing employability, failure to attend work program assignments and voluntarily leaving or failing to accept employment without good cause." t:dataTypeName=number

metric m:sna_comp_other l:"SNA Case Denials - Compliance Issues / Other" d:"Safety Net Assistance case denials due to compliance issues other than employment; these include failure to comply with rules other than those related to employment, such as failure to show for eligibility interviews, provide required documentation to verify eligibility or comply with household composition requirements." t:dataTypeName=number

metric m:sna_other l:"SNA Case Denials - Other" d:"Safety Net Assistance case denials due to issues not included in the previous categories." t:dataTypeName=number

entity e:tyyj-jgv5 l:"Public Assistance Case Denials by Reason for Denial: Beginning 2006" t:attribution="New York State Office of Temporary and Disability Assistance (OTDA)" t:url=https://data.ny.gov/api/views/tyyj-jgv5

property e:tyyj-jgv5 t:meta.view v:id=tyyj-jgv5 v:category="Human Services" v:attributionLink=https://otda.ny.gov/resources/legislative-report/ v:averageRating=0 v:name="Public Assistance Case Denials by Reason for Denial: Beginning 2006" v:attribution="New York State Office of Temporary and Disability Assistance (OTDA)"

property e:tyyj-jgv5 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:tyyj-jgv5 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```