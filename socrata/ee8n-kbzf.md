# WQFee14

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wqfee14-31421) |
| Metadata | [Link](https://data.oregon.gov/api/views/ee8n-kbzf) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ee8n-kbzf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ee8n-kbzf/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ee8n-kbzf |
| Name | WQFee14 |
| Created | 2014-05-14T18:10:04Z |
| Publication Date | 2014-05-14T20:01:29Z |

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
series e:ee8n-kbzf d:2014-05-15T09:51:30.000Z t:first_name=David t:state=OR t:last_name=Hoffman t:comment="I approve" t:email_address=fixit@efn.org m:row_number.ee8n-kbzf=1

series e:ee8n-kbzf d:2014-05-26T06:16:48.000Z t:first_name=George t:organization="Lake of the Woods Resort" t:state=OR t:last_name=Gregory t:comment="I am opposed to fee increases that will cost our business more money to do business. As business we are subject to many fees from many agencies and do not believe that fee increases are necessary for government agencies to do their job or to do a  better job. When is the last time the agency had an efficiency study? As a government agency are they doing everything they can to operate within their budget and as an agency do they regularly look at ways to do things better and at the best cost for the customers they serve. As a business we are constantly looking at the efficiency of our operation and making adjustments to ensure that we are offering the best services to our customers. It would be helpful to know more about why the agency thinks it needs to raise fees and how the fee increase will be used effectively. Will the fee increase result in better service to me as a customer of the DEQ? I would like to know how my service from the DEQ would be improved by the fee increase?
Thank you" t:email_address=lowoffice@aol.com m:row_number.ee8n-kbzf=2

series e:ee8n-kbzf d:2014-10-02T11:39:57.000Z t:first_name=William t:organization="Oregon DEQ" t:state=Oregon t:last_name=Knight t:comment="Testing the system. I think it might be still accepting comments." t:email_address=knight.william@deq.state.or.us m:row_number.ee8n-kbzf=3
```

## Meta Commands

```ls
metric m:row_number.ee8n-kbzf p:long l:"Row Number"

entity e:ee8n-kbzf l:WQFee14 t:url=https://data.oregon.gov/api/views/ee8n-kbzf

property e:ee8n-kbzf t:meta.view v:id=ee8n-kbzf v:averageRating=0 v:name=WQFee14

property e:ee8n-kbzf t:meta.view.owner v:id=44u9-wper v:screenName="MT Oregon DEQ" v:displayName="MT Oregon DEQ"

property e:ee8n-kbzf t:meta.view.tableauthor v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"
```

## Top Records

```ls
| :updated_at | first_name | last_name | email_address                  | organization             | state  | comment                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | additional_document      | 
| =========== | ========== | ========= | ============================== | ======================== | ====== | ========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ======================== | 
| 1400147490  | David      | Hoffman   | fixit@efn.org                  |                          | OR     | I approve                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | [null, null, null, null] | 
| 1401085008  | George     | Gregory   | lowoffice@aol.com              | Lake of the Woods Resort | OR     | I am opposed to fee increases that will cost our business more money to do business. As business we are subject to many fees from many agencies and do not believe that fee increases are necessary for government agencies to do their job or to do a better job. When is the last time the agency had an efficiency study? As a government agency are they doing everything they can to operate within their budget and as an agency do they regularly look at ways to do things better and at the best cost for the customers they serve. As a business we are constantly looking at the efficiency of our operation and making adjustments to ensure that we are offering the best services to our customers. It would be helpful to know more about why the agency thinks it needs to raise fees and how the fee increase will be used effectively. Will the fee increase result in better service to me as a customer of the DEQ? I would like to know how my service from the DEQ would be improved by the fee increase? Thank you | [null, null, null, null] | 
| 1412249997  | William    | Knight    | knight.william@deq.state.or.us | Oregon DEQ               | Oregon | Testing the system. I think it might be still accepting comments.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | [null, null, null, null] | 
```