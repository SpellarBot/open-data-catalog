# Plus 1 Funding Source

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/plus-1-funding-source) |
| Metadata | [Link](https://data.austintexas.gov/api/views/9e5g-zqyt) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/9e5g-zqyt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/9e5g-zqyt/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 9e5g-zqyt |
| Name | Plus 1 Funding Source |
| Category | Utility |
| Tags | "austin energy" "plus 1" |
| Created | 2015-07-30T16:58:28Z |
| Publication Date | 2016-07-06T14:11:03Z |

## Description

The City of Austin's Plus 1 Fund provides emergency utility bill financial assistance to customers experiencing extreme hardships such as medical illness or sudden job loss. In 2009 the City of Austin doubled to $300,000 the amount of funding made available annually for this program. Beginning in fiscal year 2009, City of Austin employees were given the option to donate to the Plus 1 Fund through the City's annual Combined Charities Campaign which raises money for local and regional charitable groups. Additionally, utility customers have the option to donate to the Plus 1 Fund when they make their monthly utility bill payments. Plus 1 funding is distributed to customers by more than a dozen social service agencies including Travis County Family Services and Meals on Wheels.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | funding_source | Funding Source | text          | text          |
| Yes      | time           | fiscal_year    | Fiscal Year    | calendar_date | calendar_date |
| Yes      | numeric metric | amount_funded  | Amount Funded  | money         | money         |
| Yes      | series tag     | notes          | Notes          | text          | text          |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:9e5g-zqyt d:2007-10-01T00:00:00.000Z t:funding_source="Austin Energy" m:amount_funded=125000

series e:9e5g-zqyt d:2008-10-01T00:00:00.000Z t:funding_source="Austin Energy" m:amount_funded=150000

series e:9e5g-zqyt d:2009-10-01T00:00:00.000Z t:funding_source="Austin Energy" m:amount_funded=300000
```

## Meta Commands

```ls
metric m:amount_funded p:double l:"Amount Funded" t:dataTypeName=money

entity e:9e5g-zqyt l:"Plus 1 Funding Source" t:url=https://data.austintexas.gov/api/views/9e5g-zqyt

property e:9e5g-zqyt t:meta.view v:id=9e5g-zqyt v:category=Utility v:averageRating=0 v:name="Plus 1 Funding Source"

property e:9e5g-zqyt t:meta.view.license v:name="Public Domain"

property e:9e5g-zqyt t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:9e5g-zqyt t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| funding_source                                  | fiscal_year         | amount_funded | notes | 
| =============================================== | =================== | ============= | ===== | 
| Austin Energy                                   | 2007-10-01T00:00:00 | 125000        |       | 
| Austin Energy                                   | 2008-10-01T00:00:00 | 150000        |       | 
| Austin Energy                                   | 2009-10-01T00:00:00 | 300000        |       | 
| Austin Energy                                   | 2010-10-01T00:00:00 | 300000        |       | 
| Austin Energy                                   | 2011-10-01T00:00:00 | 300000        |       | 
| Austin Energy                                   | 2012-10-01T00:00:00 | 300000        |       | 
| Austin Energy                                   | 2013-10-01T00:00:00 | 300000        |       | 
| Austin Energy                                   | 2014-10-01T00:00:00 | 300000        |       | 
| COA Combined Charities Campaign (COA employees) | 2006-10-01T00:00:00 | 0             |       | 
| COA Combined Charities Campaign (COA employees) | 2007-10-01T00:00:00 | 0             |       | 
```