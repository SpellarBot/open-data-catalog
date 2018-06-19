# BAVN Open Bid Opportunities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bavn-open-bid-opportunities-e5ed5) |
| Metadata | [Link](https://data.lacity.org/api/views/qtax-byj7) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/qtax-byj7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/qtax-byj7/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | qtax-byj7 |
| Name | BAVN Open Bid Opportunities |
| Category | A Well Run City |
| Tags | rfp, rfq, rfi, rfb, bids, proposals, labavn, bavn, jobs, construction, personal services, commodity, request for proposal, request for bid, request for quote, request for qualification, request fo... |
| Created | 2014-05-27T21:54:19Z |
| Publication Date | 2014-05-27T22:37:50Z |

## Description

A listing of open bid opportunities provided by the City of Los Angeles and available on the Los Angeles Business Assistance Virtual Network (BAVN) at http://www.labavn.org

## Columns

```ls
| Included | Schema Type | Field Name | Name       | Data Type     | Render Type   |
| ======== | =========== | ========== | ========== | ============= | ============= |
| Yes      | series tag  | bavn_id    | BAVN ID    | text          | number        |
| Yes      | series tag  | department | Department | text          | text          |
| Yes      | series tag  | status     | Status     | text          | text          |
| Yes      | series tag  | category   | Category   | text          | text          |
| Yes      | series tag  | type       | Type       | text          | text          |
| Yes      | time        | open_date  | Open Date  | calendar_date | calendar_date |
| No       |             | due_date   | Due Date   | calendar_date | calendar_date |
| Yes      | series tag  | title      | Title      | text          | text          |
| Yes      | series tag  | bavn_link  | BAVN Link  | text          | text          |
```

## Time Field

```ls
Value = open_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = due_date
```

## Data Commands

```ls
series e:qtax-byj7 d:2017-03-23T05:05:00.000Z t:title="LADDER UPS  STAINLESS STEEL LADDERS  LARUV DP" t:category=Commodity t:bavn_id=29792 t:bavn_link=https://www.labavn.org/bid.cfm?29792 t:status=Amended t:department="Water & Power" t:type="Request For Bid" m:row_number.qtax-byj7=1

series e:qtax-byj7 d:2017-03-20T04:00:00.000Z t:title="Construction of Various Types of Masonry" t:category=Construction t:bavn_id=29751 t:bavn_link=https://www.labavn.org/bid.cfm?29751 t:status=Open t:department="General Services Non-Commodity" t:type="Request For Bid" m:row_number.qtax-byj7=2

series e:qtax-byj7 d:2017-02-08T01:57:00.000Z t:title="PLUGIN HYBRID ELECTRIC SEDANS" t:category=Commodity t:bavn_id=29409 t:bavn_link=https://www.labavn.org/bid.cfm?29409 t:status=Amended t:department="Water & Power" t:type="Request For Bid" m:row_number.qtax-byj7=3
```

## Meta Commands

```ls
metric m:row_number.qtax-byj7 p:long l:"Row Number"

entity e:qtax-byj7 l:"BAVN Open Bid Opportunities" t:url=https://data.lacity.org/api/views/qtax-byj7

property e:qtax-byj7 t:meta.view v:id=qtax-byj7 v:category="A Well Run City" v:averageRating=0 v:name="BAVN Open Bid Opportunities"

property e:qtax-byj7 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:qtax-byj7 t:meta.view.owner v:id=yb4r-dcys v:profileImageUrlMedium=/api/users/yb4r-dcys/profile_images/THUMB v:profileImageUrlLarge=/api/users/yb4r-dcys/profile_images/LARGE v:screenName="ITA OpenData" v:profileImageUrlSmall=/api/users/yb4r-dcys/profile_images/TINY v:displayName="ITA OpenData"

property e:qtax-byj7 t:meta.view.tableauthor v:id=yb4r-dcys v:profileImageUrlMedium=/api/users/yb4r-dcys/profile_images/THUMB v:profileImageUrlLarge=/api/users/yb4r-dcys/profile_images/LARGE v:screenName="ITA OpenData" v:profileImageUrlSmall=/api/users/yb4r-dcys/profile_images/TINY v:roleName=publisher v:displayName="ITA OpenData"
```

## Top Records

```ls
| bavn_id | department                                                           | status  | category          | type                      | open_date           | due_date            | title                                                                                                 | bavn_link                            | 
| ======= | ==================================================================== | ======= | ================= | ========================= | =================== | =================== | ===================================================================================================== | ==================================== | 
| 29792   | Water & Power                                                        | Amended | Commodity         | Request For Bid           | 2017-03-23T05:05:00 | 2017-04-24T05:05:00 | LADDER UPS STAINLESS STEEL LADDERS LARUV DP                                                           | https://www.labavn.org/bid.cfm?29792 | 
| 29751   | General Services Non-Commodity                                       | Open    | Construction      | Request For Bid           | 2017-03-20T04:00:00 | 2017-04-27T04:00:00 | Construction of Various Types of Masonry                                                              | https://www.labavn.org/bid.cfm?29751 | 
| 29409   | Water & Power                                                        | Amended | Commodity         | Request For Bid           | 2017-02-08T01:57:00 | 2017-06-01T01:57:00 | PLUGIN HYBRID ELECTRIC SEDANS                                                                         | https://www.labavn.org/bid.cfm?29409 | 
| 29916   | Office of Wage Standards Contract Administration Bureau Public Works | Open    | Personal Services | Task Order Solicitation   | 2017-04-07T03:00:00 | 2017-04-21T03:00:00 | Various Wage Standards Enforcement and Implementation Projects TOS No OWS17008                        | https://www.labavn.org/bid.cfm?29916 | 
| 29492   | Public Works Board Offices of                                        | Amended | Personal Services | Request For Proposal      | 2017-02-17T06:00:00 | 2017-04-21T06:00:00 | Public Works Trust Fund Nexus Study and Policy Development                                            | https://www.labavn.org/bid.cfm?29492 | 
| 29696   | Harbor Department Port of Los Angeles                                | Open    | Personal Services | Request For Qualification | 2017-03-14T11:00:00 | 2017-04-25T11:00:00 | OnCall Transportation EngineeringPlanning Consulting Services                                         | https://www.labavn.org/bid.cfm?29696 | 
| 29902   | Neighborhood Initiative Los Angeles                                  | Open    | Personal Services | Request For Quote         | 2017-04-07T04:00:00 | 2017-05-05T04:00:00 | CD6 Sidewalk Reconstruction Project                                                                   | https://www.labavn.org/bid.cfm?29902 | 
| 29886   | Airports Los Angeles World                                           | Open    | Commodity         | Request For Bid           | 2017-04-05T05:00:00 | 2017-05-04T05:00:00 | 117024 Supply and Delivery of a Self Propelled Paint Striper at the Los Angeles International Airport | https://www.labavn.org/bid.cfm?29886 | 
| 29708   | Library Los Angeles Public                                           | Open    | Personal Services | Request For Qualification | 2017-03-15T07:00:00 | 2017-06-13T07:00:00 | Immigration Assistance Contractor RFQ                                                                 | https://www.labavn.org/bid.cfm?29708 | 
| 29726   | Chief Legislative Analyst                                            | Open    | Construction      | Request For Proposal      | 2017-03-16T05:00:00 | 2017-06-09T05:00:00 | Lincoln Heights Jail Adaptive Reuse                                                                   | https://www.labavn.org/bid.cfm?29726 | 
```