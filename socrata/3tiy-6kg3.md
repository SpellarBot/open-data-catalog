# Claim Settlements for City of Austin

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/claim-settlements-for-city-of-austin) |
| Metadata | [Link](https://data.austintexas.gov/api/views/3tiy-6kg3) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/3tiy-6kg3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/3tiy-6kg3/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 3tiy-6kg3 |
| Name | Claim Settlements for City of Austin |
| Attribution | COA Law Department |
| Category | Government |
| Tags | claims, law, accident, paid, auto, liability |
| Created | 2015-08-11T21:14:50Z |
| Publication Date | 2015-08-11T21:29:49Z |

## Description

Claims settled between 10/01/14 and 06/30/15

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                 | Data Type     | Render Type   |
| ======== | ============== | ================================== | ==================================== | ============= | ============= |
| Yes      | series tag     | claim_name                         | Claim Name                           | text          | text          |
| Yes      | time           | incident_date                      | Incident Date                        | calendar_date | calendar_date |
| Yes      | series tag     | department                         | Department                           | text          | text          |
| Yes      | series tag     | location_of_incident_if_applicable | Location of Incident (if applicable) | text          | text          |
| Yes      | numeric metric | amount                             | Amount                               | money         | money         |
| Yes      | series tag     | category                           | Category                             | text          | text          |
| Yes      | series tag     | disposition_type                   | Disposition Type                     | text          | text          |
```

## Time Field

```ls
Value = incident_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:3tiy-6kg3 d:2015-02-28T00:00:00.000Z t:category="00 Auto" t:claim_name="Valdez, Michael" t:department="Austin Fire Dept" t:location_of_incident_if_applicable="Bulebell and Marigold" t:disposition_type="Claim Paid" m:amount=700

series e:3tiy-6kg3 d:2014-06-20T00:00:00.000Z t:category="00 Auto" t:claim_name="Caballero, Rosita" t:department="Austin Police Department" t:location_of_incident_if_applicable=Webberville t:disposition_type="Claim Paid" m:amount=7000

series e:3tiy-6kg3 d:2015-04-02T00:00:00.000Z t:category="00 Auto" t:claim_name="Castillo, Angela" t:department="Austin Police Department" t:location_of_incident_if_applicable="8th Street" t:disposition_type="Claim Paid" m:amount=947.17
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:3tiy-6kg3 l:"Claim Settlements for City of Austin" t:attribution="COA Law Department" t:url=https://data.austintexas.gov/api/views/3tiy-6kg3

property e:3tiy-6kg3 t:meta.view v:id=3tiy-6kg3 v:category=Government v:attributionLink=http://austintexas.gov/department/law/faq v:averageRating=0 v:name="Claim Settlements for City of Austin" v:attribution="COA Law Department"

property e:3tiy-6kg3 t:meta.view.license v:name="Public Domain"

property e:3tiy-6kg3 t:meta.view.owner v:id=kz58-z3ur v:screenName=ledelc v:displayName=ledelc

property e:3tiy-6kg3 t:meta.view.tableauthor v:id=kz58-z3ur v:screenName=ledelc v:roleName=editor v:displayName=ledelc
```

## Top Records

```ls
| claim_name                    | incident_date       | department               | location_of_incident_if_applicable | amount   | category | disposition_type | 
| ============================= | =================== | ======================== | ================================== | ======== | ======== | ================ | 
| Valdez, Michael               | 2015-02-28T00:00:00 | Austin Fire Dept         | Bulebell and Marigold              | 700.00   | 00 Auto  | Claim Paid       | 
| Caballero, Rosita             | 2014-06-20T00:00:00 | Austin Police Department | Webberville                        | 7000.00  | 00 Auto  | Claim Paid       | 
| Castillo, Angela              | 2015-04-02T00:00:00 | Austin Police Department | 8th Street                         | 947.17   | 00 Auto  | Claim Paid       | 
| Cutean, Nicki                 | 2015-04-15T00:00:00 | Austin Police Department | 2nd Street & Guadalupe             | 1133.42  | 00 Auto  | Claim Paid       | 
| Ferrovial/ Toyota Lease Trust | 2015-04-08T00:00:00 | Austin Police Department | 400 N. I35 service road            | 13663.31 | 00 Auto  | Claim Paid       | 
| Hardwick, Andrew              | 2014-12-05T00:00:00 | Austin Police Department | IH35 & Riverside                   | 565.88   | 00 Auto  | Claim Paid       | 
| Hardy, Ryan                   | 2015-01-19T00:00:00 | Austin Police Department | 1200 E. 7th Street                 | 4500.00  | 00 Auto  | Claim Paid       | 
| Henna Chevrolet               | 2015-02-28T00:00:00 | Austin Police Department | 3500 W. Parmer Lane                | 2000.00  | 00 Auto  | Claim Paid       | 
| Hertz (Hardy)                 | 2015-01-19T00:00:00 | Austin Police Department | 1200 East 7th                      | 5660.00  | 00 Auto  | Claim Paid       | 
| Kempter, Anne                 | 2015-04-24T00:00:00 | Austin Police Department | 118 El Paso St.                    | 50.00    | 00 Auto  | Claim Paid       | 
```