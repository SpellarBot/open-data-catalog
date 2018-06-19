# Utlity Contact Center Call Distribution For FY2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/utlity-contact-center-call-distribution-for-fy2011) |
| Metadata | [Link](https://data.austintexas.gov/api/views/8uvp-rwpt) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/8uvp-rwpt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/8uvp-rwpt/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 8uvp-rwpt |
| Name | Utlity Contact Center Call Distribution For FY2011 |
| Attribution | City of Austin |
| Created | 2011-12-16T13:38:51Z |
| Publication Date | 2011-12-16T13:39:47Z |

## Description

The City of Austin Utility Contact Center is managed by Austin Energy. This is the place customers call to start, stop, or transfer utility services. The center receives about 6,000 calls per day on average and Online Customer Care handles about 12,000 requests per month.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | type       | Type       | text      | text        |
| Yes      | numeric metric | percentage | Percentage | number    | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8uvp-rwpt d:2011-01-01T00:00:00.000Z t:type="General Residential" m:percentage=88.4000015258789

series e:8uvp-rwpt d:2011-01-01T00:00:00.000Z t:type="General Commercial" m:percentage=7.099999904632568

series e:8uvp-rwpt d:2011-01-01T00:00:00.000Z t:type=Outages m:percentage=4.5
```

## Meta Commands

```ls
metric m:percentage p:float l:Percentage t:dataTypeName=number

entity e:8uvp-rwpt l:"Utlity Contact Center Call Distribution For FY2011" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/8uvp-rwpt

property e:8uvp-rwpt t:meta.view v:id=8uvp-rwpt v:averageRating=0 v:name="Utlity Contact Center Call Distribution For FY2011" v:attribution="City of Austin"

property e:8uvp-rwpt t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:8uvp-rwpt t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| type                | percentage | 
| =================== | ========== | 
| General Residential | 88.40%     | 
| General Commercial  | 7.10%      | 
| Outages             | 4.50%      | 
```