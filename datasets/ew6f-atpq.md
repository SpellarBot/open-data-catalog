# Long Term Care and Individual and Small Group Major Medical/Hospital Rate Increases

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/long-term-care-and-major-medical-hospital-rate-increases) |
| Metadata | [Link](https://data.iowa.gov/api/views/ew6f-atpq) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/ew6f-atpq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/ew6f-atpq/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | ew6f-atpq |
| Name | Long Term Care and Individual and Small Group Major Medical/Hospital Rate Increases |
| Category | Health |
| Tags | long term care, major medical, hospital, individual, small group |
| Created | 2016-11-09T22:07:40Z |
| Publication Date | 2017-04-17T20:00:42Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | company_name    | Company Name    | text          | text          |
| Yes      | time           | closed_on       | Closed On       | calendar_date | calendar_date |
| Yes      | series tag     | form_numbers    | Form Numbers    | text          | text          |
| No       |                | effective_date  | Effective Date  | calendar_date | calendar_date |
| Yes      | numeric metric | increase        | Increase        | percent       | percent       |
| Yes      | series tag     | approved        | Approved        | text          | text          |
| Yes      | numeric metric | negotiated_1    | Negotiated %    | percent       | percent       |
| Yes      | series tag     | negotiated_2    | Negotiated?     | text          | text          |
| Yes      | series tag     | type_of_product | Type of Product | text          | text          |
| Yes      | numeric metric | proposed        | Proposed %      | percent       | percent       |
```

## Time Field

```ls
Value = closed_on
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = effective_date
```

## Data Commands

```ls
series e:ew6f-atpq d:2017-04-11T00:00:00.000Z t:approved=Yes t:company_name="Metropolitan Life Insurance Company" t:negotiated_2=Yes t:type_of_product=SUCCESSFUL t:form_numbers="Form LTC-FAC-IA (VIP1), LTC-VAL-IA, LTC-IDEAL-IA, LTC-PREM-I A --
Original proposal = 21.21%, however, the IID was able to modify this proposal down to  15%" m:negotiated_1=15 m:increase=15 m:proposed=21.2

series e:ew6f-atpq d:2017-04-11T00:00:00.000Z t:approved=Yes t:company_name="Metropolitan Life Insurance Company" t:negotiated_2=Yes t:type_of_product=SUCCESSFUL t:form_numbers="Form LTC2-FAC-IA (VIP2_New), LTC2-VAL-IA, LTC2-IDEAL-IA, LTC2-PREM-IA -- Original proposal = 35.4% (over 2-years), however, the IID was able to modify this proposal down to 15%" m:negotiated_1=15 m:increase=15 m:proposed=35.4

series e:ew6f-atpq d:2017-04-11T00:00:00.000Z t:approved=Yes t:company_name="Metropolitan Life Insurance Company" t:negotiated_2=Yes t:type_of_product=SUCCESSFUL t:form_numbers="Form LTC2-FAC-IA (VIP2_Old), LTC2-VAL-IA, LTC2-IDEAL-IA, LTC2-PREM-IA -- Original proposal = 18.98%, however, the IID was able to modify this proposal down to 15%" m:negotiated_1=15 m:increase=15 m:proposed=19
```

## Meta Commands

```ls
metric m:increase p:float l:Increase t:dataTypeName=percent

metric m:negotiated_1 p:float l:"Negotiated %" t:dataTypeName=percent

metric m:proposed p:float l:"Proposed %" t:dataTypeName=percent

entity e:ew6f-atpq l:"Long Term Care and Individual and Small Group Major Medical/Hospital Rate Increases" t:url=https://data.iowa.gov/api/views/ew6f-atpq

property e:ew6f-atpq t:meta.view v:id=ew6f-atpq v:category=Health v:averageRating=0 v:name="Long Term Care and Individual and Small Group Major Medical/Hospital Rate Increases"

property e:ew6f-atpq t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:ew6f-atpq t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| company_name                                      | closed_on           | form_numbers                                                                                                                                                                                                    | effective_date      | increase | approved | negotiated_1 | negotiated_2 | type_of_product | proposed | 
| ================================================= | =================== | =============================================================================================================================================================================================================== | =================== | ======== | ======== | ============ | ============ | =============== | ======== | 
| Metropolitan Life Insurance Company               | 2017-04-11T00:00:00 | Form LTC-FAC-IA (VIP1), LTC-VAL-IA, LTC-IDEAL-IA, LTC-PREM-I A -- Original proposal = 21.21%, however, the IID was able to modify this proposal down to 15%                                                     | 2017-07-01T00:00:00 | 15.0     | Yes      | 15.0         | Yes          | SUCCESSFUL      | 21.2     | 
| Metropolitan Life Insurance Company               | 2017-04-11T00:00:00 | Form LTC2-FAC-IA (VIP2_New), LTC2-VAL-IA, LTC2-IDEAL-IA, LTC2-PREM-IA -- Original proposal = 35.4% (over 2-years), however, the IID was able to modify this proposal down to 15%                                | 2017-07-01T00:00:00 | 15.0     | Yes      | 15.0         | Yes          | SUCCESSFUL      | 35.4     | 
| Metropolitan Life Insurance Company               | 2017-04-11T00:00:00 | Form LTC2-FAC-IA (VIP2_Old), LTC2-VAL-IA, LTC2-IDEAL-IA, LTC2-PREM-IA -- Original proposal = 18.98%, however, the IID was able to modify this proposal down to 15%                                              | 2017-07-01T00:00:00 | 15.0     | Yes      | 15.0         | Yes          | SUCCESSFUL      | 19.0     | 
| Prudential Insurance Company of America           | 2017-04-10T00:00:00 | Form 83500 BFW 5005 -- this is a true-up rate increase to bring Iowa's rate schedule to the U.S. level. Iowa modified the previous proposal from 40% down to 18%. Carrier included MAE certification language.  | 2017-07-01T00:00:00 | 18.6     | Yes      | 18.6         | No           | NOT SUCCESSFUL  | 18.6     | 
| Bankers Life & Casualty Company                   | 2017-03-30T00:00:00 | Forms GR-N050, GR-N100, GR-N105, GR-N160, GR-N165, GR-240, GR-N250, GR-N270, GR-N280                                                                                                                            | 2017-05-01T00:00:00 | 15.0     | Yes      | 15.0         | No           | NOT SUCCESSFUL  | 15.0     | 
| Genworth Life Insurance Company                   | 2017-03-20T00:00:00 | Form series - 7042, 7044, 7042REV and 7044REV -- this is not a rate increase, but rather an updated projection involving a prior rate filing                                                                    | 2017-03-20T00:00:00 | 0.0      | Yes      | 0.0          | No           | NOT SUCCESSFUL  | 0.0      | 
| United Security Assurance Company of Pennsylvania | 2017-03-17T00:00:00 | Forms PAL-1, PAL-1(02)R, QLT-1, QLT-1(02)R et al --- Original proposal was 20%, however, the IID was able to modify this proposal to 17.5% for the remaining Iowa policies inforce.                             | 2017-05-01T00:00:00 | 17.5     | Yes      | 17.5         | Yes          | SUCCESSFUL      | 20.0     | 
| Wellmark Health Plan of Iowa                      | 2017-03-08T00:00:00 | Rate filing proposal applies to all pre-ACA compliant SG grandfathered and transitional business with effective/renewal dates of 7/1, 8/1, and 9/1 of 2017. The 12% only applies to the grandfathered business. | 2017-07-01T00:00:00 | 12.0     | Yes      | 12.0         | No           | NOT SUCCESSFUL  | 12.0     | 
| Wellmark Blue Cross Blue Shield of Iowa           | 2017-03-08T00:00:00 | Rate filing proposal applies to all pre-ACA compliant SG grandfathered and transitional business with effective/renewal dates of 7/1, 8/1, and 9/1 of 2017. The 7% only applies to the grandfathered business.  | 2017-07-01T00:00:00 | 7.0      | Yes      | 7.0          | No           | NOT SUCCESSFUL  | 7.0      | 
| Pennsylvania Life Insurance Company               | 2017-02-23T00:00:00 | Forms 1460, 1490, P30, P35, P39, PLNHO, PLNHOQ -- Original proposal was 30%, however, the IID was able to negotiate it to 17% due to various factors.                                                           | 2017-07-01T00:00:00 | 17.0     | Yes      | 17.0         | Yes          | SUCCESSFUL      | 30.0     | 
```