# Austin Energy GreenChoice? Sales

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-energy-green-choice-sales) |
| Metadata | [Link](https://data.austintexas.gov/api/views/wr7f-jdtu) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/wr7f-jdtu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/wr7f-jdtu/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | wr7f-jdtu |
| Name | Austin Energy GreenChoice? Sales |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | greenchoice, green choice, wind, texas wind, wind energy, renewable, renewable energy |
| Created | 2011-12-16T13:43:41Z |
| Publication Date | 2017-04-07T16:13:22Z |

## Description

Austin Energy?s GreenChoice? program is among the nation?s most successful utility-sponsored, voluntary green-pricing energy programs. View Austin Energy's GreenChoice? sales by kWh starting fiscal year 2004.Go to austinenergy.com/go/greenchoice and austinenergy.com/go/corporatereports to learn more about GreenChoice?.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name                     | Data Type     | Render Type   |
| ======== | ============== | ============= | ======================== | ============= | ============= |
| Yes      | time           | fiscal_year_1 | Fiscal Year              | calendar_date | calendar_date |
| Yes      | numeric metric | sales_by_kwh  | GreenChoice Sales by kWh | number        | number        |
```

## Time Field

```ls
Value = fiscal_year_1
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:wr7f-jdtu d:2012-01-01T00:00:00.000Z m:sales_by_kwh=744442709

series e:wr7f-jdtu d:2015-01-01T00:00:00.000Z m:sales_by_kwh=637575158

series e:wr7f-jdtu d:2014-01-01T00:00:00.000Z m:sales_by_kwh=683986607
```

## Meta Commands

```ls
metric m:sales_by_kwh p:integer l:"GreenChoice Sales by kWh" t:dataTypeName=number

entity e:wr7f-jdtu l:"Austin Energy GreenChoice? Sales" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/wr7f-jdtu

property e:wr7f-jdtu t:meta.view v:id=wr7f-jdtu v:category=Utility v:averageRating=0 v:name="Austin Energy GreenChoice? Sales" v:attribution="Austin Energy"

property e:wr7f-jdtu t:meta.view.license v:name="Public Domain"

property e:wr7f-jdtu t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:wr7f-jdtu t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| fiscal_year_1       | sales_by_kwh | 
| =================== | ============ | 
| 2012-01-01T00:00:00 | 744442709    | 
| 2015-01-01T00:00:00 | 637575158    | 
| 2014-01-01T00:00:00 | 683986607    | 
| 2013-01-01T00:00:00 | 863956193    | 
| 2004-01-01T00:00:00 | 344446101    | 
| 2005-01-01T00:00:00 | 434040739    | 
| 2006-01-01T00:00:00 | 580580401    | 
| 2007-01-01T00:00:00 | 577636840    | 
| 2008-01-01T00:00:00 | 723824901    | 
| 2009-01-01T00:00:00 | 764895830    | 
```