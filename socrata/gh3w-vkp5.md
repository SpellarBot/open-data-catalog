# Procurement - Intent to Execute Archive

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/procurement-intent-to-execute-archive) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/gh3w-vkp5) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/gh3w-vkp5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/gh3w-vkp5/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | gh3w-vkp5 |
| Name | Procurement - Intent to Execute Archive |
| Attribution | Office of the Chief Procurement Officer |
| Category | Finance & Administration |
| Tags | procurement, purchase, contract, bid, rfp, rfi, award |
| Created | 2016-06-23T03:41:59Z |
| Publication Date | 2016-06-23T03:48:19Z |

## Description

This dataset provides an archive list of vendors and contracts to be executed by the Office of the Chief Procurement Officer. Data starting in June 2016 can be found at https://datacatalog.cookcountyil.gov/Finance-Administration/Procurement-Intent-to-Execute/ag43-fvd7

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type     | Render Type   |
| ======== | =========== | ============ | ============ | ============= | ============= |
| Yes      | time        | posting_date | Posting Date | calendar_date | calendar_date |
| Yes      | series tag  | description  | Description  | text          | text          |
| Yes      | series tag  | notes        | Notes        | text          | text          |
| Yes      | series tag  | link         | Link         | url           | url           |
```

## Time Field

```ls
Value = posting_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:gh3w-vkp5 d:2016-05-27T00:00:00.000Z t:description="Intent to Execute" t:link=http://opendocs.cookcountyil.gov/procurement/intent-execute/Intent-to-Execute-160527.pdf m:row_number.gh3w-vkp5=1

series e:gh3w-vkp5 d:2016-05-20T00:00:00.000Z t:description="Intent to Execute" t:link=http://opendocs.cookcountyil.gov/procurement/intent-execute/Intent-to-Execute-160520.pdf m:row_number.gh3w-vkp5=2

series e:gh3w-vkp5 d:2016-05-18T00:00:00.000Z t:description="Intent to Execute" t:link=http://opendocs.cookcountyil.gov/procurement/intent-execute/Intent-to-Execute-160518.pdf m:row_number.gh3w-vkp5=3
```

## Meta Commands

```ls
metric m:row_number.gh3w-vkp5 p:long l:"Row Number"

entity e:gh3w-vkp5 l:"Procurement - Intent to Execute Archive" t:attribution="Office of the Chief Procurement Officer" t:url=https://datacatalog.cookcountyil.gov/api/views/gh3w-vkp5

property e:gh3w-vkp5 t:meta.view v:id=gh3w-vkp5 v:category="Finance & Administration" v:averageRating=0 v:name="Procurement - Intent to Execute Archive" v:attribution="Office of the Chief Procurement Officer"

property e:gh3w-vkp5 t:meta.view.license v:name="Public Domain"

property e:gh3w-vkp5 t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:gh3w-vkp5 t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| posting_date        | description       | notes | link                                                                                             | 
| =================== | ================= | ===== | ================================================================================================ | 
| 2016-05-27T00:00:00 | Intent to Execute |       | [http://opendocs.cookcountyil.gov/procurement/intent-execute/Intent-to-Execute-160527.pdf, null] | 
| 2016-05-20T00:00:00 | Intent to Execute |       | [http://opendocs.cookcountyil.gov/procurement/intent-execute/Intent-to-Execute-160520.pdf, null] | 
| 2016-05-18T00:00:00 | Intent to Execute |       | [http://opendocs.cookcountyil.gov/procurement/intent-execute/Intent-to-Execute-160518.pdf, null] | 
| 2016-05-13T00:00:00 | Intent to Execute |       | [http://opendocs.cookcountyil.gov/procurement/intent-execute/Intent-to-Execute-160513.pdf, null] | 
| 2016-05-05T00:00:00 | Intent to Execute |       | [http://opendocs.cookcountyil.gov/procurement/intent-execute/Intent-to-Execute-160504.pdf, null] | 
| 2016-04-27T00:00:00 | Intent to Execute |       | [http://opendocs.cookcountyil.gov/procurement/intent-execute/Intent-to-Execute-160427.pdf, null] | 
| 2016-04-22T00:00:00 | Intent to Execute |       | [http://opendocs.cookcountyil.gov/procurement/intent-execute/Intent-to-Execute-160422.pdf, null] | 
| 2016-04-21T00:00:00 | Intent to Execute |       | [http://opendocs.cookcountyil.gov/procurement/intent-execute/Intent-to-Execute-160421.pdf, null] | 
| 2016-04-20T00:00:00 | Intent to Execute |       | [http://opendocs.cookcountyil.gov/procurement/intent-execute/Intent-to-Execute-160420.pdf, null] | 
| 2016-04-15T00:00:00 | Intent to Execute |       | [http://opendocs.cookcountyil.gov/procurement/intent-execute/Intent-to-Execute-160415.pdf, null] | 
```