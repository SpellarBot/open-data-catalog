# Unemployment Insurance Initial Claims By Region By Month: Beginning 2003

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-insurance-initial-claims-by-region-by-month-beginning-2003) |
| Metadata | [Link](https://data.ny.gov/api/views/w34r-gwfk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/w34r-gwfk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/w34r-gwfk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | w34r-gwfk |
| Name | Unemployment Insurance Initial Claims By Region By Month: Beginning 2003 |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | unemployment, insurance, claims, initial claims |
| Created | 2015-11-24T15:42:07Z |
| Publication Date | 2017-04-17T22:02:14Z |

## Description

Dataset contains monthly counts, from July 2003 to present, of initial claims for regular unemployment insurance benefits. 

Initial Claims include new claims as well as subsequent additional claims filed. New claims are filed in person, by mail, telephone or other means to request a determination of entitlement to and eligibility for compensation which results in an agency generated document of an appealable monetary determination provided to the potential claimant. Additional claims are filed during an existing benefit year due to new unemployment when a break of one week or more has occurred in the claim series due to intervening employment. 

Data are provided for New York State regions.  Region counts include only state residents who file a claim (excluding out-of-state residents).

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | time           | period_ending  | Period Ending  | calendar_date | calendar_date |
| Yes      | series tag     | region         | Region         | text          | text          |
| Yes      | numeric metric | initial_claims | Initial Claims | number        | number        |
```

## Time Field

```ls
Value = period_ending
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:w34r-gwfk d:2003-07-31T00:00:00.000Z t:region=Capital m:initial_claims=4326

series e:w34r-gwfk d:2003-07-31T00:00:00.000Z t:region="Central New York" m:initial_claims=4366

series e:w34r-gwfk d:2003-07-31T00:00:00.000Z t:region="Finger Lakes" m:initial_claims=7095
```

## Meta Commands

```ls
metric m:initial_claims p:integer l:"Initial Claims" d:"Number of initial claims for regular unemployment insurance." t:dataTypeName=number

entity e:w34r-gwfk l:"Unemployment Insurance Initial Claims By Region By Month: Beginning 2003" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/w34r-gwfk

property e:w34r-gwfk t:meta.view v:id=w34r-gwfk v:category="Economic Development" v:attributionLink=http://www.labor.ny.gov/stats/UI/Unemployment-Insurance-Data.shtm v:averageRating=0 v:name="Unemployment Insurance Initial Claims By Region By Month: Beginning 2003" v:attribution="New York State Department of Labor"

property e:w34r-gwfk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:w34r-gwfk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| period_ending       | region           | initial_claims | 
| =================== | ================ | ============== | 
| 2003-07-31T00:00:00 | Capital          | 4326           | 
| 2003-07-31T00:00:00 | Central New York | 4366           | 
| 2003-07-31T00:00:00 | Finger Lakes     | 7095           | 
| 2003-07-31T00:00:00 | Hudson Valley    | 8454           | 
| 2003-07-31T00:00:00 | Long Island      | 13575          | 
| 2003-07-31T00:00:00 | Mohawk Valley    | 3210           | 
| 2003-07-31T00:00:00 | New York City    | 45703          | 
| 2003-07-31T00:00:00 | North Country    | 2529           | 
| 2003-07-31T00:00:00 | Southern Tier    | 3335           | 
| 2003-07-31T00:00:00 | Western New York | 11484          | 
```