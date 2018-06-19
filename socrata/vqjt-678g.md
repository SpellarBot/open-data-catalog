# Disconnects For Non-pay

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disconnects-for-non-pay) |
| Metadata | [Link](https://data.austintexas.gov/api/views/vqjt-678g) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/vqjt-678g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/vqjt-678g/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | vqjt-678g |
| Name | Disconnects For Non-pay |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | disconnect, utilities, delinquent, payment, energy |
| Created | 2016-09-30T13:31:25Z |
| Publication Date | 2016-11-14T15:09:17Z |

## Description

The City of Austin gives customers 17 days to pay their utility bills from the date of issuance. If the account remains unpaid customers can be subject to having their utilities disconnected for non-payment. If services are disconnected, the following reconnection fees apply: 
$25.00 reconnection fee. Disconnects are suspended during certain periods of extreme heat or cold. View the number of disconnects for non-pay per year, starting in fiscal year 2002.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | ============== | ================================= | ================================= | ============= | ============= |
| Yes      | time           | fiscal_year                       | Fiscal Year                       | calendar_date | calendar_date |
| Yes      | numeric metric | number_of_disconnects_for_non_pay | Number of Disconnects for Non-Pay | number        | number        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:vqjt-678g d:2016-01-01T00:00:00.000Z m:number_of_disconnects_for_non_pay=9056

series e:vqjt-678g d:2015-01-01T00:00:00.000Z m:number_of_disconnects_for_non_pay=9590

series e:vqjt-678g d:2014-01-01T00:00:00.000Z m:number_of_disconnects_for_non_pay=23044
```

## Meta Commands

```ls
metric m:number_of_disconnects_for_non_pay p:integer l:"Number of Disconnects for Non-Pay" d:"*Austin Energy suspended the issuance of disconnects for non-pay in FY 2012 due to the implementation of the new customer billing system. This allowed the utility to spend time quality assuring the system prior to the commencement of collections activities. *For FY 2011, utility bills delinquent by 30 days or more averaged $16.2 million per month. The total number of disconnects in fiscal year 2011 was down from previous years due to a suspension of disconnects resulting from hotter than normal temperatures." t:dataTypeName=number

entity e:vqjt-678g l:"Disconnects For Non-pay" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/vqjt-678g

property e:vqjt-678g t:meta.view v:id=vqjt-678g v:category=Utility v:averageRating=0 v:name="Disconnects For Non-pay" v:attribution="Austin Energy"

property e:vqjt-678g t:meta.view.license v:name="Public Domain"

property e:vqjt-678g t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:vqjt-678g t:meta.view.tableauthor v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"
```

## Top Records

```ls
| fiscal_year         | number_of_disconnects_for_non_pay | 
| =================== | ================================= | 
| 2016-01-01T00:00:00 | 9056                              | 
| 2015-01-01T00:00:00 | 9590                              | 
| 2014-01-01T00:00:00 | 23044                             | 
| 2013-01-01T00:00:00 | 3111                              | 
| 2012-01-01T00:00:00 | 0                                 | 
| 2011-01-01T00:00:00 | 26280                             | 
| 2010-01-01T00:00:00 | 43175                             | 
| 2009-01-01T00:00:00 | 43195                             | 
| 2008-01-01T00:00:00 | 43531                             | 
| 2007-01-01T00:00:00 | 41507                             | 
```