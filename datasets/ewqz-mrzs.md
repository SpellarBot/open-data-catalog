# Bond Ratings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bond-ratings) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ewqz-mrzs) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ewqz-mrzs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ewqz-mrzs/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ewqz-mrzs |
| Name | Bond Ratings |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | "bond ratings", "credit quality", debt |
| Created | 2015-08-17T15:08:29Z |
| Publication Date | 2016-12-15T19:48:31Z |

## Description

Austin Energy has consistently maintained high bond ratings. A bond rating is a measure of a company?s credit quality, which includes the ability to repay its debt in a timely fashion. In 2016, two bond rating agencies upgraded their assessments of Austin Energy's creditworthiness, allowing the City of Austin-owned utility to reach a key financial goal of a AA credit rating. Standard & Poor's rated the $1.3 billion utility's bonds at AA Stable, up from AA- Stable. The rating service cited "the electric system's very strong financial performance trend as evidenced by its ability to maintain stronger fixed-charge coverage and total available liquidity levels.

## Columns

```ls
| Included | Schema Type | Field Name                    | Name                            | Data Type | Render Type |
| ======== | =========== | ============================= | =============================== | ========= | =========== |
| Yes      | series tag  | description_of_debt           | Description of Debt             | text      | text        |
| Yes      | time        | fiscal_year_ended             | Fiscal Year Ended               | number    | number      |
| Yes      | series tag  | fitch_inc                     | Fitch, Inc.                     | text      | text        |
| Yes      | series tag  | moody_s_investors_service_inc | Moody's Investors Service, Inc. | text      | text        |
| Yes      | series tag  | standard_and_poor_s           | Standard and Poor's             | text      | text        |
```

## Time Field

```ls
Value = fiscal_year_ended
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:ewqz-mrzs l:"Bond Ratings" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/ewqz-mrzs

property e:ewqz-mrzs t:meta.view v:id=ewqz-mrzs v:category=Utility v:averageRating=0 v:name="Bond Ratings" v:attribution="Austin Energy"

property e:ewqz-mrzs t:meta.view.license v:name="Public Domain"

property e:ewqz-mrzs t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:ewqz-mrzs t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| description_of_debt                               | fiscal_year_ended | fitch_inc | moody_s_investors_service_inc | standard_and_poor_s | 
| ================================================= | ================= | ========= | ============================= | =================== | 
| Combined utility revenue bonds - prior lien       | 2013              | AA        | Aa1                           | AA                  | 
| Combined utility revenue bonds - prior lien       | 2012              | AA-       | Aa1                           | AA                  | 
| Combined utility revenue bonds - prior lien       | 2011              | AA-       | A1                            | AA                  | 
| Combined utility revenue bonds - prior lien       | 2010              | AA-       | A1                            | AA                  | 
| Combined utility revenue bonds - prior lien       | 2009              | AA-       | A1                            | AA                  | 
| Combined utility revenue bonds - prior lien       | 2008              | AA-       | A1                            | AA                  | 
| Combined utility revenue bonds - prior lien       | 2007              | AA-       | A1                            | AA-                 | 
| Combined utility revenue bonds - prior lien       | 2006              | AA-       | A1                            | AA-                 | 
| Combined utility revenue bonds - subordinate lien | 2013              | AA-       | Aa2                           | AA                  | 
| Combined utility revenue bonds - subordinate lien | 2012              | AA-       | Aa2                           | AA                  | 
```