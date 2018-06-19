# Vacant and Abandoned Buildings - Violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vacant-and-abandoned-buildings-violations-f0288) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/kc9i-wq85) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/kc9i-wq85/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/kc9i-wq85/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | kc9i-wq85 |
| Name | Vacant and Abandoned Buildings - Violations |
| Attribution | City of Chicago |
| Category | Buildings |
| Tags | violations |
| Created | 2011-12-22T20:59:19Z |
| Publication Date | 2017-04-20T12:44:50Z |

## Description

Vacant and abandoned building violations issued on properties owned by financial institutions since January 1, 2011. Each violation is tied to a Docket Number. A Docket may have more than one violation associated with it. Fees are assessed based on all violations associated with a particular Docket. This dataset displays the most recent action (disposition description) for each violation, the fees and fines associated with the docket and the amount paid or outstanding for the docket. If the docket is a City Non-Suit or the owner is found to be Not Liable, then no payment is required. Note that multiple addresses may be associated with a violation; in these cases, multiple records will be included in this dataset for a single violation. / Data Owners: Administrative Hearings / Finance / Time Period: January 1, 2011 to present  / Update Frequency: Data is updated daily

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | ============== | ================================= | ================================= | ============= | ============= |
| Yes      | series tag     | docket_number                     | Docket Number                     | text          | text          |
| Yes      | series tag     | violation_number                  | Violation Number                  | text          | text          |
| Yes      | time           | issued_date                       | Issued Date                       | calendar_date | calendar_date |
| Yes      | series tag     | issuing_department                | Issuing Department                | text          | text          |
| No       |                | last_hearing_date                 | Last Hearing Date                 | calendar_date | calendar_date |
| No       |                | property_address                  | Property Address                  | text          | text          |
| Yes      | series tag     | violation_type                    | Violation Type                    | text          | text          |
| Yes      | series tag     | entity_or_person_s_               | Entity or Person(s)               | text          | text          |
| Yes      | series tag     | disposition_description           | Disposition Description           | text          | text          |
| Yes      | numeric metric | total_fines                       | Total Fines                       | money         | money         |
| Yes      | numeric metric | total_administrative_costs        | Total Administrative Costs        | money         | money         |
| Yes      | numeric metric | interest_amount                   | Interest Amount                   | money         | money         |
| Yes      | numeric metric | collection_costs_or_attorney_fees | Collection Costs or Attorney Fees | money         | money         |
| Yes      | numeric metric | court_cost                        | Court Cost                        | money         | money         |
| Yes      | numeric metric | original_total_amount_due         | Original Total Amount Due         | money         | money         |
| Yes      | numeric metric | total_paid                        | Total Paid                        | money         | money         |
| Yes      | numeric metric | current_amount_due                | Current Amount Due                | money         | money         |
```

## Time Field

```ls
Value = issued_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = last_hearing_date,property_address
```

## Data Commands

```ls
series e:kc9i-wq85 d:2011-01-24T00:00:00.000Z t:violation_type="193110 Insure and secure vacant building. (13-12-125 (a)." t:disposition_description="Not liable - Respondent came into compliance with building code prior to hearing" t:docket_number=11BS01063A t:violation_number=11DR279704 t:issuing_department=BLDINGS t:entity_or_person_s_=CITIBANK, m:collection_costs_or_attorney_fees=0 m:total_administrative_costs=0 m:total_fines=0 m:court_cost=0 m:interest_amount=0

series e:kc9i-wq85 d:2011-03-31T00:00:00.000Z t:violation_type="193110 Insure and secure vacant building. (13-12-125 (a)." t:disposition_description="Not liable - Respondent came into compliance with building code prior to hearing" t:docket_number=11BS02904A t:violation_number=11DR286648 t:issuing_department=BLDINGS t:entity_or_person_s_="FEDERAL NATIONAL MORTGAGE ASSN NATIONAL PROPERTY DISPOSITION CENTER," m:collection_costs_or_attorney_fees=0 m:total_administrative_costs=0 m:total_fines=0 m:court_cost=0 m:interest_amount=0

series e:kc9i-wq85 d:2011-05-28T00:00:00.000Z t:violation_type="193105 Register and secure vacant building. (13-12-125 (a)(1), 13-12-125 (b)(1) )." t:disposition_description="Not liable - City failed to establish prima facie case" t:docket_number=11BS04331A t:violation_number=11N0295731 t:issuing_department=BLDINGS t:entity_or_person_s_="US BANK, NA C/O JEANNE ESCOBEDO, TRUST LEGAL DEPARTMENT," m:collection_costs_or_attorney_fees=0 m:total_administrative_costs=0 m:total_fines=2000 m:total_paid=0 m:interest_amount=0 m:current_amount_due=2053.17 m:original_total_amount_due=0
```

## Meta Commands

```ls
metric m:total_fines p:double l:"Total Fines" t:dataTypeName=money

metric m:total_administrative_costs p:double l:"Total Administrative Costs" t:dataTypeName=money

metric m:interest_amount p:double l:"Interest Amount" t:dataTypeName=money

metric m:collection_costs_or_attorney_fees p:double l:"Collection Costs or Attorney Fees" t:dataTypeName=money

metric m:court_cost p:double l:"Court Cost" t:dataTypeName=money

metric m:original_total_amount_due p:double l:"Original Total Amount Due" t:dataTypeName=money

metric m:total_paid p:double l:"Total Paid" t:dataTypeName=money

metric m:current_amount_due p:double l:"Current Amount Due" t:dataTypeName=money

entity e:kc9i-wq85 l:"Vacant and Abandoned Buildings - Violations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/kc9i-wq85

property e:kc9i-wq85 t:meta.view v:id=kc9i-wq85 v:category=Buildings v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Vacant and Abandoned Buildings - Violations" v:attribution="City of Chicago"

property e:kc9i-wq85 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:kc9i-wq85 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| docket_number | violation_number | issued_date         | issuing_department | last_hearing_date   | property_address  | violation_type                                                                     | entity_or_person_s_                                                                                      | disposition_description                                                          | total_fines | total_administrative_costs | interest_amount | collection_costs_or_attorney_fees | court_cost | original_total_amount_due | total_paid | current_amount_due | 
| ============= | ================ | =================== | ================== | =================== | ================= | ================================================================================== | ======================================================================================================== | ================================================================================ | =========== | ========================== | =============== | ================================= | ========== | ========================= | ========== | ================== | 
| 11BS01063A    | 11DR279704       | 2011-01-24T00:00:00 | BLDINGS            | 2011-08-11T10:30:00 | 2955 N AVERS      | 193110 Insure and secure vacant building. (13-12-125 (a).                          | CITIBANK,                                                                                                | Not liable - Respondent came into compliance with building code prior to hearing | 0           | 0                          | 0               | 0                                 | 0          |                           |            |                    | 
| 11BS02904A    | 11DR286648       | 2011-03-31T00:00:00 | BLDINGS            | 2011-05-12T12:00:00 | 6738 S KOLIN      | 193110 Insure and secure vacant building. (13-12-125 (a).                          | FEDERAL NATIONAL MORTGAGE ASSN NATIONAL PROPERTY DISPOSITION CENTER,                                     | Not liable - Respondent came into compliance with building code prior to hearing | 0           | 0                          | 0               | 0                                 | 0          |                           |            |                    | 
| 11BS04331A    | 11N0295731       | 2011-05-28T00:00:00 | BLDINGS            | 2011-07-12T12:00:00 | 3563 W MC LEAN    | 193105 Register and secure vacant building. (13-12-125 (a)(1), 13-12-125 (b)(1) ). | US BANK, NA C/O JEANNE ESCOBEDO, TRUST LEGAL DEPARTMENT,                                                 | Not liable - City failed to establish prima facie case                           | 2000        | 0                          | 0               | 0                                 |            | 0                         | 0          | 2053.17            | 
| 11BS04331A    | 11N0295731       | 2011-05-28T00:00:00 | BLDINGS            | 2011-07-12T12:00:00 | 3563 W MC LEAN    | 193110 Insure and secure vacant building. (13-12-125 (a).                          | US BANK, NA C/O JEANNE ESCOBEDO, TRUST LEGAL DEPARTMENT,                                                 | Not liable - City failed to establish prima facie case                           | 2000        | 0                          | 0               | 0                                 |            | 0                         | 0          | 2053.17            | 
| 11BS04362A    | 11WO295906       | 2011-06-01T00:00:00 | BLDINGS            | 2011-09-08T09:00:00 | 3330 W 58TH       | 193105 Register and secure vacant building. (13-12-125 (a)(1), 13-12-125 (b)(1) ). | DEUTSCHE BK NAT'L TR CO TRUSTEE OF ARGENT MTG SECURITIES INC ASSET-BACKED PASS THRU CERT SERIES 2006-W4, | City non-suit                                                                    | 1000        | 0                          | 0               | 0                                 |            | 0                         | 0          | 1083.22            | 
| 11BS04362A    | 11WO295906       | 2011-06-01T00:00:00 | BLDINGS            | 2011-09-08T09:00:00 | 3330 W 58TH       | 193110 Insure and secure vacant building. (13-12-125 (a).                          | DEUTSCHE BK NAT'L TR CO TRUSTEE OF ARGENT MTG SECURITIES INC ASSET-BACKED PASS THRU CERT SERIES 2006-W4, | City non-suit                                                                    | 1000        | 0                          | 0               | 0                                 |            | 0                         | 0          | 1083.22            | 
| 11BS04362A    | 11WO295906       | 2011-06-01T00:00:00 | BLDINGS            | 2011-09-08T09:00:00 | 5758 S CHRISTIANA | 193105 Register and secure vacant building. (13-12-125 (a)(1), 13-12-125 (b)(1) ). | DEUTSCHE BK NAT'L TR CO TRUSTEE OF ARGENT MTG SECURITIES INC ASSET-BACKED PASS THRU CERT SERIES 2006-W4, | City non-suit                                                                    | 1000        | 0                          | 0               | 0                                 |            | 0                         | 0          | 1083.22            | 
| 11BS04362A    | 11WO295906       | 2011-06-01T00:00:00 | BLDINGS            | 2011-09-08T09:00:00 | 5758 S CHRISTIANA | 193110 Insure and secure vacant building. (13-12-125 (a).                          | DEUTSCHE BK NAT'L TR CO TRUSTEE OF ARGENT MTG SECURITIES INC ASSET-BACKED PASS THRU CERT SERIES 2006-W4, | City non-suit                                                                    | 1000        | 0                          | 0               | 0                                 |            | 0                         | 0          | 1083.22            | 
| 11BS04511A    | 11DR293344       | 2011-06-09T00:00:00 | BLDINGS            | 2011-07-21T09:00:00 | 444 E 89TH        | 193110 Insure and secure vacant building. (13-12-125 (a).                          | DEUTSCHE BANK NAT'L TRUST CO TRUSTEE FOR HSI ASSET SECURITIZATION CORP,                                  | Not liable - Respondent came into compliance with building code prior to hearing | 0           | 0                          | 0               | 0                                 | 0          |                           |            |                    | 
| 11BS04514A    | 11DR296244       | 2011-06-09T00:00:00 | BLDINGS            | 2011-09-15T09:00:00 | 12928 S ESCANABA  | 193110 Insure and secure vacant building. (13-12-125 (a).                          | GREEN TREE SERVICING, LLC C/O C T CORPORATION SYSTEM,                                                    | City non-suit                                                                    | 0           | 0                          | 0               | 0                                 | 0          |                           |            |                    | 
```