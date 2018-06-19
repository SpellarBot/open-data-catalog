# Unemployment Insurance Initial Claims Statewide By Month: Beginning 1971

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-insurance-initial-claims-statewide-by-month-beginning-1971) |
| Metadata | [Link](https://data.ny.gov/api/views/ns8z-xewg) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ns8z-xewg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ns8z-xewg/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ns8z-xewg |
| Name | Unemployment Insurance Initial Claims Statewide By Month: Beginning 1971 |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | unemployment, insurance, claims, initial claims |
| Created | 2015-11-24T19:49:06Z |
| Publication Date | 2017-04-17T22:01:29Z |

## Description

Dataset contains monthly counts, from 1971 to present, of initial claims for regular unemployment insurance benefits.
Initial Claims include new claims as well as subsequent additional claims filed. New claims are filed in person, by mail, telephone or other means to request a determination of entitlement to and eligibility for compensation which results in an agency generated document of an appealable monetary determination provided to the potential claimant. Additional claims are filed during an existing benefit year due to new unemployment when a break of one week or more has occurred in the claim series due to intervening employment.
Data are provided for New York State. Counts include only state residents who file a claim (excluding out-of-state residents).

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | time           | period_ending  | Period Ending  | calendar_date | calendar_date |
| Yes      | numeric metric | initial_claims | Initial Claims | number        | number        |
```

## Time Field

```ls
Value = period_ending
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ns8z-xewg d:1971-01-31T00:00:00.000Z m:initial_claims=172620

series e:ns8z-xewg d:1971-02-28T00:00:00.000Z m:initial_claims=140364

series e:ns8z-xewg d:1971-03-31T00:00:00.000Z m:initial_claims=142435
```

## Meta Commands

```ls
metric m:initial_claims p:integer l:"Initial Claims" t:dataTypeName=number

entity e:ns8z-xewg l:"Unemployment Insurance Initial Claims Statewide By Month: Beginning 1971" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/ns8z-xewg

property e:ns8z-xewg t:meta.view v:id=ns8z-xewg v:category="Economic Development" v:attributionLink=http://www.labor.ny.gov/stats/UI/Unemployment-Insurance-Data.shtm v:averageRating=0 v:name="Unemployment Insurance Initial Claims Statewide By Month: Beginning 1971" v:attribution="New York State Department of Labor"

property e:ns8z-xewg t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ns8z-xewg t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| period_ending       | initial_claims | 
| =================== | ============== | 
| 1971-01-31T00:00:00 | 172620         | 
| 1971-02-28T00:00:00 | 140364         | 
| 1971-03-31T00:00:00 | 142435         | 
| 1971-04-30T00:00:00 | 134342         | 
| 1971-05-31T00:00:00 | 127409         | 
| 1971-06-30T00:00:00 | 157526         | 
| 1971-07-31T00:00:00 | 168579         | 
| 1971-08-31T00:00:00 | 150285         | 
| 1971-09-30T00:00:00 | 157330         | 
| 1971-10-31T00:00:00 | 123278         | 
```