# State Of Connecticut Online Transaction Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-connecticut-online-transaction-inventory) |
| Metadata | [Link](https://data.ct.gov/api/views/uxdv-m92a) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/uxdv-m92a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/uxdv-m92a/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | uxdv-m92a |
| Name | State Of Connecticut Online Transaction Inventory |
| Attribution | Department of Administrative Services |
| Category | Government |
| Tags | ct, online, tansactions, egov |
| Created | 2014-06-25T15:00:17Z |
| Publication Date | 2016-06-15T14:43:53Z |

## Description

A listing of various online transactions available from the Connecticut State Agencies and Offices

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | state_agency_or_office | State Agency or Office | text      | text        |
| Yes      | series tag  | online_transaction     | Online Transaction     | text      | text        |
| Yes      | series tag  | website                | Website                | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uxdv-m92a d:2016-06-15T07:43:16.000Z t:online_transaction="Request a Constituent Service" t:website="http://www.governor.ct.gov/malloy/cwp/view.asp?a=3998&q=479084" t:state_agency_or_office="Governor's Office" m:row_number.uxdv-m92a=1

series e:uxdv-m92a d:2016-06-15T07:43:16.000Z t:online_transaction="Sign up for News Alerts" t:website="http://portal.ct.gov/governor/alerts/subscribe/?subscriptionid=6" t:state_agency_or_office="Governor's Office" m:row_number.uxdv-m92a=2

series e:uxdv-m92a d:2016-06-15T07:43:16.000Z t:online_transaction="Share an Opinion with the Governor" t:website=http://portal.ct.gov/Share_Your_Opinion.aspx t:state_agency_or_office="Governor's Office" m:row_number.uxdv-m92a=3
```

## Meta Commands

```ls
metric m:row_number.uxdv-m92a p:long l:"Row Number"

entity e:uxdv-m92a l:"State Of Connecticut Online Transaction Inventory" t:attribution="Department of Administrative Services" t:url=https://data.ct.gov/api/views/uxdv-m92a

property e:uxdv-m92a t:meta.view v:id=uxdv-m92a v:category=Government v:attributionLink=http://www.ct.gov/das v:averageRating=0 v:name="State Of Connecticut Online Transaction Inventory" v:attribution="Department of Administrative Services"

property e:uxdv-m92a t:meta.view.license v:name="Public Domain"

property e:uxdv-m92a t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:uxdv-m92a t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | state_agency_or_office | online_transaction                 | website                                                                  | 
| =========== | ====================== | ================================== | ======================================================================== | 
| 1465976596  | Governor's Office      | Request a Constituent Service      | [http://www.governor.ct.gov/malloy/cwp/view.asp?a=3998&q=479084, null]   | 
| 1465976596  | Governor's Office      | Sign up for News Alerts            | [http://portal.ct.gov/governor/alerts/subscribe/?subscriptionid=6, null] | 
| 1465976596  | Governor's Office      | Share an Opinion with the Governor | [http://portal.ct.gov/Share_Your_Opinion.aspx, null]                     | 
| 1465976596  | Governor's Office      | Contact Constituent Services       | [http://portal.ct.gov/Constituent_Services.aspx, null]                   | 
| 1465976596  | Governor's Office      | Request a Proclamation             | [http://portal.ct.gov/Request_Proclamation.aspx, null]                   | 
| 1465976596  | Governor's Office      | Invite Governor Malloy to an Event | [http://portal.ct.gov/OnlineInvitation.aspx, null]                       | 
| 1465976596  | Governor's Office      | Intern at the Governor's Office    | [http://portal.ct.gov/Internships.aspx, null]                            | 
| 1465976596  | Governor's Office      | Sign up for Governor's Office News | [http://www.governor.ct.gov/malloy/guestaccount/login.asp, null]         | 
| 1465976596  | Governor's Office      | Contact Us / Help                  | [http://portal.ct.gov/contact-us/, null]                                 | 
| 1465976596  | LT. Governor's Office  | Register Online to Vote            | [https://voterregistration.ct.gov/OLVR/welcome.do, null]                 | 
```