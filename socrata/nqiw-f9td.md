# Food Assistance Program Households Recipients and Allotments by Month and County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/food-assistance-program-recipients-and-grants-by-month-and-county) |
| Metadata | [Link](https://data.iowa.gov/api/views/nqiw-f9td) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/nqiw-f9td/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/nqiw-f9td/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | nqiw-f9td |
| Name | Food Assistance Program Households Recipients and Allotments by Month and County |
| Attribution | Iowa Department of Human Services, Food Assistance Program |
| Category | Economy |
| Tags | public assistance, food assistance |
| Created | 2014-11-10T14:17:09Z |
| Publication Date | 2017-02-21T15:41:04Z |

## Description

The Food Assistance Program provides Electronic Benefit Transfer (EBT) cards that can be used to buy groceries at supermarkets, grocery stores and some Farmers Markets. This dataset provides data on the number of households, recipients and cash assistance provided through the Food Assistance Program participation by month and county starting in January 2011 and updated monthly.

Beginning January 2017, the method used to identify households is based on the following:
1.  If one or more individuals receiving Food Assistance also receives  FIP, the household is categorized as FA/FIP.
2.  If no one receives FIP, but at least one individual also receives Medical Assistance, the household is categorized as FA/Medical Assistance.
3.  If no one receives FIP or Medical Assistance, but at least one individual receives Healthy and Well Kids in Iowa or hawk-i benefits, the household is categorized as FA/hawk-i.
4.  If no one receives FIP, Medical Assistance or  hawk-i , the household is categorized as FA Only.

Changes have also been made to reflect more accurate identification of individuals.  The same categories from above are used in identifying an individual's circumstances.  Previously, the household category was assigned to all individuals of the Food Assistance household, regardless of individual status.  This change in how individuals are categorized provides a more accurate count of individual categories.

Timing of when the report is run also changed starting January 2017.  Reports were previously ran on the 1st, but changed to the 17th to better capture Food Assistance households that received benefits for the prior month.  This may give the impression that caseloads have increased when in reality, under the previous approach, cases were missed.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| No       |                | cy                  | CY                  | number        | number        |
| Yes      | time           | month               | Month               | calendar_date | calendar_date |
| Yes      | series tag     | county_name         | County Name         | text          | text          |
| Yes      | series tag     | service_area        | Service Area        | text          | text          |
| Yes      | numeric metric | households          | Households          | number        | number        |
| Yes      | numeric metric | recipients          | Recipients          | number        | number        |
| Yes      | numeric metric | allotments          | Allotments          | money         | money         |
| No       |                | primary_county_lat  | Primary County Lat  | number        | number        |
| No       |                | primary_county_long | Primary County Long | number        | number        |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = cy,primary_county_lat,primary_county_long
```

## Data Commands

```ls
series e:nqiw-f9td d:2011-01-31T00:00:00.000Z t:service_area="Des Moines" t:county_name=Adair m:households=343 m:allotments=88162 m:recipients=731

series e:nqiw-f9td d:2011-01-31T00:00:00.000Z t:service_area="Des Moines" t:county_name=Adams m:households=176 m:allotments=50417 m:recipients=428

series e:nqiw-f9td d:2011-01-31T00:00:00.000Z t:service_area=Northern t:county_name=Allamakee m:households=684 m:allotments=188687 m:recipients=1505
```

## Meta Commands

```ls
metric m:households p:integer l:Households d:"Number of households participating in the program. Please note that changes have been made to reflect more accurate information about the households who receive Food Assistance in Iowa. New methods started in month ending 1/31/2017." t:dataTypeName=number

metric m:recipients p:integer l:Recipients d:"Number of recipients participating in the program. Please note that changes have been made to reflect more accurate information about the individuals who receive Food Assistance in Iowa. New methods started in month ending 1/31/2017." t:dataTypeName=number

metric m:allotments p:integer l:Allotments d:"Amount of food assistance payments made to recipients" t:dataTypeName=money

entity e:nqiw-f9td l:"Food Assistance Program Households Recipients and Allotments by Month and County" t:attribution="Iowa Department of Human Services, Food Assistance Program" t:url=https://data.iowa.gov/api/views/nqiw-f9td

property e:nqiw-f9td t:meta.view v:id=nqiw-f9td v:category=Economy v:averageRating=0 v:name="Food Assistance Program Households Recipients and Allotments by Month and County" v:attribution="Iowa Department of Human Services, Food Assistance Program"

property e:nqiw-f9td t:meta.view.license v:name="Public Domain"

property e:nqiw-f9td t:meta.view.owner v:id=grmb-3z9d v:profileImageUrlMedium=/api/users/grmb-3z9d/profile_images/THUMB v:profileImageUrlLarge=/api/users/grmb-3z9d/profile_images/LARGE v:screenName="Iowa Department of Human Services" v:profileImageUrlSmall=/api/users/grmb-3z9d/profile_images/TINY v:displayName="Iowa Department of Human Services"

property e:nqiw-f9td t:meta.view.tableauthor v:id=grmb-3z9d v:profileImageUrlMedium=/api/users/grmb-3z9d/profile_images/THUMB v:profileImageUrlLarge=/api/users/grmb-3z9d/profile_images/LARGE v:screenName="Iowa Department of Human Services" v:profileImageUrlSmall=/api/users/grmb-3z9d/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Human Services"
```

## Top Records

```ls
| cy   | month               | county_name | service_area | households | recipients | allotments | primary_county_lat | primary_county_long | 
| ==== | =================== | =========== | ============ | ========== | ========== | ========== | ================== | =================== | 
| 2011 | 2011-01-31T00:00:00 | Adair       | Des Moines   | 343        | 731        | 88162      | 41.3307464         | -94.4709413         | 
| 2011 | 2011-01-31T00:00:00 | Adams       | Des Moines   | 176        | 428        | 50417      | 41.0289839         | -94.6991849         | 
| 2011 | 2011-01-31T00:00:00 | Allamakee   | Northern     | 684        | 1505       | 188687     | 43.2842838         | -91.3780923         | 
| 2011 | 2011-01-31T00:00:00 | Appanoose   | Cedar Rapids | 1072       | 2186       | 263632     | 40.7431635         | -92.8686104         | 
| 2011 | 2011-01-31T00:00:00 | Audubon     | Western      | 188        | 453        | 48987      | 41.6845893         | -94.9058222         | 
| 2011 | 2011-01-31T00:00:00 | Benton      | Cedar Rapids | 1000       | 2278       | 280766     | 42.0801864         | -92.0656912         | 
| 2011 | 2011-01-31T00:00:00 | Black Hawk  | Northern     | 8757       | 17827      | 2297770    | 42.4700957         | -92.3088197         | 
| 2011 | 2011-01-31T00:00:00 | Boone       | Des Moines   | 1172       | 2518       | 328866     | 42.0365493         | -93.931671          | 
| 2011 | 2011-01-31T00:00:00 | Bremer      | Northern     | 492        | 1127       | 131610     | 42.7745873         | -92.3180548         | 
| 2011 | 2011-01-31T00:00:00 | Buchanan    | Northern     | 784        | 1798       | 205762     | 42.4707777         | -91.8378392         | 
```