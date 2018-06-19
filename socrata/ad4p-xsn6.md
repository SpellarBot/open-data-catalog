# Plus 1 Fund

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/plus-1-fund) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ad4p-xsn6) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ad4p-xsn6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ad4p-xsn6/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ad4p-xsn6 |
| Name | Plus 1 Fund |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | plus 1, utility bill donation, utility bill, plus 1 fund |
| Created | 2015-08-04T21:52:25Z |
| Publication Date | 2015-12-18T21:38:00Z |

## Description

The City of Austin's Plus 1 Fund provides emergency utility bill financial assistance to customers experiencing extreme hardships such as medical illness or sudden job loss. In 2009 the City of Austin doubled to $300,000 the amount of funding made available annually for this program. Beginning in fiscal year 2009, City of Austin employees were given the option to donate to the Plus 1 Fund through the City's annual Combined Charities Campaign, which raises money for local and regional charitable groups. Additionally, utility customers have the option to donate to the Plus 1 Fund when they make their monthly utility bill payments. Plus 1 funding is distributed to customers by more than a dozen social service agencies including Travis County Family Services and Meals on Wheels.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | fiscal_year       | Fiscal Year       | text          | text          |
| No       |                | calendar_year     | calendar_year     | number        | number        |
| Yes      | series tag     | calendar_month    | calendar_month    | text          | text          |
| Yes      | time           | calendar_date_utc | calendar_date_utc | calendar_date | calendar_date |
| Yes      | numeric metric | dollars_dispersed | Dollars Dispersed | money         | money         |
| Yes      | numeric metric | households_served | Households Served | number        | number        |
```

## Time Field

```ls
Value = calendar_date_utc
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = calendar_year
```

## Data Commands

```ls
series e:ad4p-xsn6 d:2013-10-01T00:00:00.000Z t:fiscal_year="FY 2014" t:calendar_month=Oct m:households_served=6 m:dollars_dispersed=5000

series e:ad4p-xsn6 d:2013-11-01T00:00:00.000Z t:fiscal_year="FY 2014" t:calendar_month=Nov m:households_served=282 m:dollars_dispersed=83775.68

series e:ad4p-xsn6 d:2013-12-01T00:00:00.000Z t:fiscal_year="FY 2014" t:calendar_month=Dec m:households_served=184 m:dollars_dispersed=41437.52
```

## Meta Commands

```ls
metric m:dollars_dispersed p:double l:"Dollars Dispersed" t:dataTypeName=money

metric m:households_served p:integer l:"Households Served" t:dataTypeName=number

entity e:ad4p-xsn6 l:"Plus 1 Fund" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/ad4p-xsn6

property e:ad4p-xsn6 t:meta.view v:id=ad4p-xsn6 v:category=Utility v:averageRating=0 v:name="Plus 1 Fund" v:attribution="Austin Energy"

property e:ad4p-xsn6 t:meta.view.license v:name="Public Domain"

property e:ad4p-xsn6 t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:ad4p-xsn6 t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| fiscal_year | calendar_year | calendar_month | calendar_date_utc   | dollars_dispersed | households_served | 
| =========== | ============= | ============== | =================== | ================= | ================= | 
| FY 2014     | 2013          | Oct            | 2013-10-01T00:00:00 | 5000.00           | 6                 | 
| FY 2014     | 2013          | Nov            | 2013-11-01T00:00:00 | 83775.68          | 282               | 
| FY 2014     | 2013          | Dec            | 2013-12-01T00:00:00 | 41437.52          | 184               | 
| FY 2014     | 2014          | Jan            | 2014-01-01T00:00:00 | 41681.75          | 189               | 
| FY 2014     | 2014          | Feb            | 2014-02-01T00:00:00 | 59145.90          | 220               | 
| FY 2014     | 2014          | Mar            | 2014-03-01T00:00:00 | 78400.34          | 231               | 
| FY 2014     | 2014          | Apr            | 2014-04-01T00:00:00 | 91241.15          | 295               | 
| FY 2014     | 2014          | May            | 2014-05-01T00:00:00 | 63459.66          | 266               | 
| FY 2014     | 2014          | Jun            | 2014-06-01T00:00:00 | 55755.58          | 239               | 
| FY 2014     | 2014          | Jul            | 2014-07-01T00:00:00 | 104869.26         | 342               | 
```