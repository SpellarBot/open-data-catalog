# WQFeeRule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wqfeerule-cf1cd) |
| Metadata | [Link](https://data.oregon.gov/api/views/yrxz-a6ea) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/yrxz-a6ea/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/yrxz-a6ea/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | yrxz-a6ea |
| Name | WQFeeRule |
| Created | 2013-07-12T21:01:11Z |
| Publication Date | 2013-08-05T18:45:36Z |

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | first_name           | First Name           | text      | text        |
| Yes      | series tag  | last_name            | Last Name            | text      | text        |
| Yes      | series tag  | email                | Email                | email     | email       |
| Yes      | series tag  | organization         | Organization         | text      | text        |
| Yes      | series tag  | state                | State                | text      | text        |
| Yes      | series tag  | comment              | Comment              | html      | html        |
| Yes      | series tag  | additional_documents | Additional Documents | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yrxz-a6ea d:2013-07-29T10:23:31.000Z t:first_name=Arnold t:organization=CPA t:email=arnmaryjo@aol.com t:last_name=Meier t:comment="Makes sense to me!     Lets increase fees so we can increase our government bureaucracy.  If you did your jobs properly you wouldn't need more money." m:row_number.yrxz-a6ea=1

series e:yrxz-a6ea d:2013-07-29T13:52:24.000Z t:first_name=robert t:organization="Edgewater NW" t:email=robert@edgewaternw.com t:state=oregon t:last_name="van creveld" t:comment="I object to yet another fee increase. Current fees are very high. 

I do not understand the logic of saying that this is to cover the increased cost of providing service. How has that cost increased? Is it because state employees got a raise?Or is PERS pinching the budget? Nobody else got a raise in the last several years. Pushing PERS expenses onto the permitted population is unfair as well. This is inflationary policy. There is simply no justification. The workload does not seem to have increased over the workload five years ago.

While I respect the work of DEQ water quality staff. I do not believe that another fee increase is justified." m:row_number.yrxz-a6ea=2

series e:yrxz-a6ea d:2013-07-29T13:53:47.000Z t:first_name=Carl t:organization="City of Drain" t:email=city.admin@cityofdrain.org t:state=OR t:last_name=Patenode t:comment="Douglas County still has one of the most depressed economies in the state. Almost 70% of Drain citizens are without jobs or living on a fixed income.The city cannot absorb higher DEQ fees and must pass these fee increases onto the customers." m:row_number.yrxz-a6ea=3
```

## Meta Commands

```ls
metric m:row_number.yrxz-a6ea p:long l:"Row Number"

entity e:yrxz-a6ea l:WQFeeRule t:url=https://data.oregon.gov/api/views/yrxz-a6ea

property e:yrxz-a6ea t:meta.view v:id=yrxz-a6ea v:averageRating=0 v:name=WQFeeRule

property e:yrxz-a6ea t:meta.view.owner v:id=7f2t-e4kt v:screenName="Mary-Frances Makichen" v:displayName="Mary-Frances Makichen"

property e:yrxz-a6ea t:meta.view.tableauthor v:id=7f2t-e4kt v:screenName="Mary-Frances Makichen" v:displayName="Mary-Frances Makichen"
```

## Top Records

```ls
| :updated_at | first_name | last_name   | email                      | organization              | state  | comment                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | additional_documents     | 
| =========== | ========== | =========== | ========================== | ========================= | ====== | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ======================== | 
| 1375093411  | Arnold     | Meier       | arnmaryjo@aol.com          | CPA                       |        | Makes sense to me! Lets increase fees so we can increase our government bureaucracy. If you did your jobs properly you wouldn't need more money.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | [null, null, null, null] | 
| 1375105944  | robert     | van creveld | robert@edgewaternw.com     | Edgewater NW              | oregon | I object to yet another fee increase. Current fees are very high. I do not understand the logic of saying that this is to cover the increased cost of providing service. How has that cost increased? Is it because state employees got a raise?Or is PERS pinching the budget? Nobody else got a raise in the last several years. Pushing PERS expenses onto the permitted population is unfair as well. This is inflationary policy. There is simply no justification. The workload does not seem to have increased over the workload five years ago. While I respect the work of DEQ water quality staff. I do not believe that another fee increase is justified.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | [null, null, null, null] | 
| 1375106027  | Carl       | Patenode    | city.admin@cityofdrain.org | City of Drain             | OR     | Douglas County still has one of the most depressed economies in the state. Almost 70% of Drain citizens are without jobs or living on a fixed income.The city cannot absorb higher DEQ fees and must pass these fee increases onto the customers.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | [null, null, null, null] | 
| 1375349649  | Thomas     | Harmon      | tharmon@harmoncc.com       |                           | Oregon | I see no justification for the proposed fees. DEQ doesn't really provide a service unless requiring a permit and collecting fees is a service. I believe that DEQ should look at reducing expense to land owners and businesses and find ways to reduce cost to citizens and not increase the burden on them. I would like to see an itemization of the proposed cost, I am assuming that the bulk of the increase is in increased salaries. This is not a time to be increasing cost. Please reconsider your request for a fee increase and find ways to function within the revenue you currently have.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | [null, null, null, null] | 
| 1375367695  | John       | Orueta      | jjo84594@gmail.com         | Ana Reservoir RV Park LLC | OR     | On approximately 7-17-13 I contacted your office in regards to the proposed rate increase. I am submitting this for consideration. Ana Reservoir RV Park is located in Summer Lake Oregon in a very remote part of Lake County. We provide an extremely clean and safe environment for travelers and sportsmen alike. Ana Reservoir RV Park provides basic amenities to campers, water, power and a limited number of sewer connections. Because of the remoteness of our location our business is minimal, except for hunting season. Business expenses are always at a break-even point. With insurance, electricity, propane and DEQ being our major providers. The one last thing I need is to have an ad hoc rate increase by anyone. We currently pay $350.00 per year to DEQ for our ACD fee. I would like to see DEQ more responsive to their customers and review locations and utilization, which can be found by reviewing the Oregon State Lodging Tax we pay quarterly, as a means of determining fees for our business. This,to me, would be a farer way, instead of imposing an across the board rate hike, especially on the marginal businesses. Thank You. John Orueta | [null, null, null, null] | 
| 1377165685  | Michael    | Maas        | facilitymgr@thesfi.org     | Siskiyou Field Institute  | Oregon | I am Facility Manager for Siskiyou Field Institute, a 501(c)(3) non-profit educational institution. I oversee the functioning of a Quasi-Municipal water treatment system. Our organization struggles to pay our expenses, as education of the public is not a money-making proposition. Every dollar we have to pay in fees and permits subtracts from the resources we can use to fulfill our mission of education. I urge those responsible for overseeing the rule-making process to exempt small 501(c)(3) organizations from further fee increases. Michael Maas Facility Manager Siskiyou Field Institute Deer Creek Center 1241 Illinois River Road Selma, Or 97538 541-597-8530 PWS id 4195360                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | [null, null, null, null] | 
```