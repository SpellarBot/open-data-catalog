# Number of Austin Energy Customers 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/number-of-austin-energy-customers-2015) |
| Metadata | [Link](https://data.austintexas.gov/api/views/qmdk-sha4) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/qmdk-sha4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/qmdk-sha4/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | qmdk-sha4 |
| Name | Number of Austin Energy Customers 2015 |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | austin energy |
| Created | 2016-12-02T19:41:07Z |
| Publication Date | 2016-12-12T21:10:07Z |

## Description

As part of the FY 2013 rate case, Austin Energy restructured its customer classes. 

Austin Energy?s four customer classes include: 

Residential ? customers living in single-family dwellings, mobile homes, townhouses or individually metered apartment units. 

Secondary ? commercial customers including small to large businesses. This means Austin Energy owns, operates and maintains the equipment supplying power to those facilities . 
Secondary 1 ? commercial customers served at less than 10 kW. 
Secondary 2 ? commercial customers served between 10 and 50 kW. Secondary 3 ? commercial customers served at more than 50 kW. 

Primary ? customers that take service at high voltage and own, operate and maintain their own equipment. Consequently, Austin Energy experiences lower overall system losses and expense in serving these customers. Large commercial and industrial customers such as semiconductors, hightech facilities and data centers typically fall under this level of service. These customers have very high usage and load factors because they tend to operate 24/7. 
Primary 1 ? commercial customers served at less than 3 MW. 
Primary 2 ? commercial customers served between 3 and 20 MW. 
Primary 3 ? commercial customers served at more than 20 MW.

Contract/Transmission ? customers owning and maintaining all equipment on the customer side for electric delivery and receiving service at 69 kV or above. Contract applies to a small number of large commercial customers operating under legacy contracts. 

Lighting ? typically refers to street lighting and facilities including ballparks.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | customer_class      | Customer Class      | text          | text          |
| Yes      | time           | fiscal_year         | Fiscal Year         | calendar_date | calendar_date |
| Yes      | numeric metric | number_of_customers | Number of Customers | number        | number        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:qmdk-sha4 d:2015-01-01T00:00:00.000Z t:customer_class=Residential m:number_of_customers=401556

series e:qmdk-sha4 d:2015-01-01T00:00:00.000Z t:customer_class="Secondary 1" m:number_of_customers=29511

series e:qmdk-sha4 d:2015-01-01T00:00:00.000Z t:customer_class="Secondary 2" m:number_of_customers=13926
```

## Meta Commands

```ls
metric m:number_of_customers p:integer l:"Number of Customers" t:dataTypeName=number

entity e:qmdk-sha4 l:"Number of Austin Energy Customers 2015" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/qmdk-sha4

property e:qmdk-sha4 t:meta.view v:id=qmdk-sha4 v:category=Utility v:averageRating=0 v:name="Number of Austin Energy Customers 2015" v:attribution="Austin Energy"

property e:qmdk-sha4 t:meta.view.license v:name="Public Domain"

property e:qmdk-sha4 t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:qmdk-sha4 t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| customer_class     | fiscal_year         | number_of_customers | 
| ================== | =================== | =================== | 
| Residential        | 2015-01-01T00:00:00 | 401556              | 
| Secondary 1        | 2015-01-01T00:00:00 | 29511               | 
| Secondary 2        | 2015-01-01T00:00:00 | 13926               | 
| Secondary 3        | 2015-01-01T00:00:00 | 5184                | 
| Primary 1          | 2015-01-01T00:00:00 | 69                  | 
| Primary 2          | 2015-01-01T00:00:00 | 7                   | 
| Primary 3          | 2015-01-01T00:00:00 | 0                   | 
| Contract/TES/Trans | 2015-01-01T00:00:00 | 144                 | 
| Lighting           | 2015-01-01T00:00:00 | 82                  | 
```