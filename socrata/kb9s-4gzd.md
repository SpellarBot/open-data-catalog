# City of Albany Building Permits Issued: Beginning January, 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-albany-building-permits-issued-beginning-january-2009) |
| Metadata | [Link](https://data.ny.gov/api/views/kb9s-4gzd) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/kb9s-4gzd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/kb9s-4gzd/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | kb9s-4gzd |
| Name | City of Albany Building Permits Issued: Beginning January, 2009 |
| Attribution | City of Albany |
| Category | Government & Finance |
| Tags | albany, building, permits |
| Created | 2013-03-05T19:05:25Z |
| Publication Date | 2014-03-27T19:19:21Z |

## Description

This data summarizes the Building Permits issued since 2009 in the City of Albany. This process is governed by the Division of Buildings and Regulatory Compliance.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | time           | date                | Date                | calendar_date | calendar_date |
| Yes      | series tag     | application_number  | Application Number  | text          | number        |
| Yes      | series tag     | permit_number       | Permit Number       | text          | number        |
| No       |                | address             | Address             | text          | text          |
| Yes      | series tag     | owner               | Owner               | text          | text          |
| Yes      | series tag     | contractor          | Contractor          | text          | text          |
| Yes      | numeric metric | estimated_cost      | Estimated Cost      | money         | money         |
| Yes      | numeric metric | fee                 | Fee                 | money         | money         |
| Yes      | series tag     | description_of_work | Description of Work | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:kb9s-4gzd d:2012-12-27T00:00:00.000Z t:description_of_work="REPLACE WINDOWS" t:permit_number=53916 t:contractor="Window World     489-0889" t:owner="William Dawson   229-0688" t:application_number=66194 m:fee=0 m:estimated_cost=1481

series e:kb9s-4gzd d:2012-12-26T00:00:00.000Z t:description_of_work="REPLACE PORCH WINDOWS & REPAIR STEPS" t:permit_number=53913 t:contractor="Brent Stephens" t:owner="Brent Stephens   374-9508" t:application_number=66185 m:fee=0 m:estimated_cost=3500

series e:kb9s-4gzd d:2012-12-19T00:00:00.000Z t:description_of_work="REPLACE ROOF ATENNAS" t:permit_number=53902 t:contractor="Crown Castle" t:owner="Crown Castle   201-236-9224" t:application_number=66161 m:fee=0 m:estimated_cost=14500
```

## Meta Commands

```ls
metric m:estimated_cost p:double l:"Estimated Cost" t:dataTypeName=money

metric m:fee p:double l:Fee t:dataTypeName=money

entity e:kb9s-4gzd l:"City of Albany Building Permits Issued:  Beginning January, 2009" t:attribution="City of Albany" t:url=https://data.ny.gov/api/views/kb9s-4gzd

property e:kb9s-4gzd t:meta.view v:id=kb9s-4gzd v:category="Government & Finance" v:attributionLink=http://albanyny.gov/Government/Departments/Codes.aspx v:averageRating=0 v:name="City of Albany Building Permits Issued:  Beginning January, 2009" v:attribution="City of Albany"

property e:kb9s-4gzd t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:kb9s-4gzd t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:kb9s-4gzd t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| date                | application_number | permit_number | address                 | owner                               | contractor                               | estimated_cost | fee | description_of_work                  | 
| =================== | ================== | ============= | ======================= | =================================== | ======================================== | ============== | === | ==================================== | 
| 2012-12-27T00:00:00 | 66194              | 53916         | 39 Orchard Avenue       | William Dawson 229-0688             | Window World 489-0889                    | 1481           | 0   | REPLACE WINDOWS                      | 
| 2012-12-26T00:00:00 | 66185              | 53913         | 94 Hazelhurst Avenue    | Brent Stephens 374-9508             | Brent Stephens                           | 3500           | 0   | REPLACE PORCH WINDOWS & REPAIR STEPS | 
| 2012-12-19T00:00:00 | 66161              | 53902         | 3 Terminal Street       | Crown Castle 201-236-9224           | Crown Castle                             | 14500          | 0   | REPLACE ROOF ATENNAS                 | 
| 2012-12-24T00:00:00 | 66118              | 53910         | 45 Russell Road         | Ezra & Muriel Cook 489-6687         | The Home Depot 436-1586                  | 1511           | 0   | REPLACE SHED                         | 
| 2012-12-31T00:00:00 | 66160              | 53919         | 900 Central Avenue      | Century II Mall Associates 459-0688 | Nick's Signs 785-2295                    | 400            | 0   | INSTALL SIGN                         | 
| 2012-12-19T00:00:00 | 66143              | 53888         | 27-29 North Swan Street | Albany Housing Authority 641-7500   | Fence Masters 265-1874                   | 9600           | 0   | INSINSTALL FENCE                     | 
| 2012-12-19T00:00:00 | 66159              | 53901         | 426 Second Street       | Andrew King                         | The Home Depot at Home Services 383-6614 | 3000           | 0   | REPLACE WINDOWS                      | 
| 2012-12-19T00:00:00 | 66132              | 53890         | 539 Warren Street       | Judy Janco 573-9906                 | Contract Management Co 505-7203          | 1000           | 0   | REPAIRS TO DECK & HANDRAILS          | 
| 2012-12-18T00:00:00 | 66158              | 53879         | 30 South Pearl St       | P.S. Associates L.P. 432-4500       | Omni Management Group 432-4500           | 30000          | 0   | GUTTING                              | 
| 2012-12-19T00:00:00 | 66177              | 53899         | 42 West Street          | Mohamed Abdalla - 427-9750          | Mohamed Abdalla                          | 3000           | 0   | REPLACING ROOF                       | 
```