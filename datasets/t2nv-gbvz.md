# CWSRF Longer Term Financing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cwsrf-longer-term-financing-9bb87) |
| Metadata | [Link](https://data.oregon.gov/api/views/t2nv-gbvz) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/t2nv-gbvz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/t2nv-gbvz/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | t2nv-gbvz |
| Name | CWSRF Longer Term Financing |
| Created | 2013-10-11T16:13:03Z |
| Publication Date | 2014-03-12T16:11:04Z |

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | first_name          | First Name          | text      | text        |
| Yes      | series tag  | last_name           | Last Name           | text      | text        |
| Yes      | series tag  | email_address       | Email Address       | email     | email       |
| Yes      | series tag  | organization        | Organization        | text      | text        |
| Yes      | series tag  | state               | State               | text      | text        |
| Yes      | series tag  | comment             | Comment             | html      | html        |
| Yes      | series tag  | additional_document | Additional Document | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:t2nv-gbvz d:2013-11-01T16:00:33.000Z t:first_name=Amy t:organization="City of Hermiston" t:state=Oregon t:last_name=Palmer t:comment="This looks like a program we would be interested in, but the income limitations would exclude us.  How many communities in Oregon do you estimate would qualify for the program?" t:email_address=apalmer@hermiston.or.us m:row_number.t2nv-gbvz=1

series e:t2nv-gbvz d:2013-11-01T16:41:30.000Z t:first_name=Diane t:organization="City of Echo" t:state=OR t:last_name=Berry t:comment="On behalf of the City of Echo, I would like to state that allowing the 30 year financing for our upcoming sewer treatment improvments would be very beneficial.  The cost of this project is going to result in very high utility rates. By being able to spread the bond payments over another ten years (our previous loans for water and sewer were through Farm Home and were each for 40 years, which made them affordable). Will result in sewer rates that are affordable to our customers/residents." t:email_address=ecpl@centurytel.net m:row_number.t2nv-gbvz=2

series e:t2nv-gbvz d:2013-11-06T16:35:40.000Z t:first_name=Dave t:organization="City of Ashland" t:state=Oregon t:last_name=Kanner t:comment="The City of Ashland supports the proposed amendment to OAR 340 and we urge the DEQ to adopt it.  We, like many jurisdictions in Oregon, are faced with replacing essential water and sewer infrastructure that has either outlived its useful life or must be upgraded in order to comply with current DEQ and EPA regulations.  The impact on rates is significant.  Longer-term financing allows for decreased annual debt service payments, which translates into lower rates for water and sewer customers.  Again, we support this proposed amendment." t:email_address=dave.kanner@ashland.or.us m:row_number.t2nv-gbvz=3
```

## Meta Commands

```ls
metric m:row_number.t2nv-gbvz p:long l:"Row Number"

entity e:t2nv-gbvz l:"CWSRF Longer Term Financing" t:url=https://data.oregon.gov/api/views/t2nv-gbvz

property e:t2nv-gbvz t:meta.view v:id=t2nv-gbvz v:averageRating=0 v:name="CWSRF Longer Term Financing"

property e:t2nv-gbvz t:meta.view.owner v:id=44u9-wper v:screenName="MT Oregon DEQ" v:displayName="MT Oregon DEQ"

property e:t2nv-gbvz t:meta.view.tableauthor v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"
```

## Top Records

```ls
| :updated_at | first_name                 | last_name                  | email_address             | organization      | state  | comment                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | additional_document      | 
| =========== | ========================== | ========================== | ========================= | ================= | ====== | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ======================== | 
| 1383321633  | Amy                        | Palmer                     | apalmer@hermiston.or.us   | City of Hermiston | Oregon | This looks like a program we would be interested in, but the income limitations would exclude us. How many communities in Oregon do you estimate would qualify for the program?                                                                                                                                                                                                                                                                                                                                                                         | [null, null, null, null] | 
| 1383324090  | Diane                      | Berry                      | ecpl@centurytel.net       | City of Echo      | OR     | On behalf of the City of Echo, I would like to state that allowing the 30 year financing for our upcoming sewer treatment improvments would be very beneficial. The cost of this project is going to result in very high utility rates. By being able to spread the bond payments over another ten years (our previous loans for water and sewer were through Farm Home and were each for 40 years, which made them affordable). Will result in sewer rates that are affordable to our customers/residents.                                             | [null, null, null, null] | 
| 1383755740  | Dave                       | Kanner                     | dave.kanner@ashland.or.us | City of Ashland   | Oregon | The City of Ashland supports the proposed amendment to OAR 340 and we urge the DEQ to adopt it. We, like many jurisdictions in Oregon, are faced with replacing essential water and sewer infrastructure that has either outlived its useful life or must be upgraded in order to comply with current DEQ and EPA regulations. The impact on rates is significant. Longer-term financing allows for decreased annual debt service payments, which translates into lower rates for water and sewer customers. Again, we support this proposed amendment. | [null, null, null, null] | 
| 1385571311  | Christine                  | Pavoni                     | detroit@wvi.com           | City of Detroit   | OR     | The Detroit City Council wishes to express their support for the proposal to allow longer-term financing for Clean Water State Revolving Fund treatment works projects.                                                                                                                                                                                                                                                                                                                                                                                 | [null, null, null, null] | 
| 1414769201  | RCfNvlpvWpqFknUZUwQTgPDwhB | lrNwLtfSNmJjcxPvqneqDQlZHb |                           | ECPfq             |        | more buy valium online no prescription uk - valium effects frank                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | [null, null, null, null] | 
```