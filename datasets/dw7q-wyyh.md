# All Tweets And Stats 2011 To 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/all-tweets-and-stats-2011-to-2013-7531d) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/dw7q-wyyh) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/dw7q-wyyh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/dw7q-wyyh/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | dw7q-wyyh |
| Name | All Tweets And Stats 2011 To 2013 |
| Attribution | Cook County Bureau of Technology |
| Category | Finance & Administration |
| Created | 2014-01-23T17:23:55Z |
| Publication Date | 2014-10-09T22:51:25Z |

## Description

All Cook County Tweets, starting in 2011 to 12/31/2013. As measured by Crowdbooster.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | time           | date                  | Date                  | calendar_date | calendar_date |
| Yes      | series tag     | time                  | Time                  | text          | text          |
| Yes      | series tag     | text                  | Text                  | text          | text          |
| Yes      | numeric metric | retweets              | Retweets              | number        | number        |
| Yes      | numeric metric | replies               | Replies               | number        | number        |
| Yes      | numeric metric | potential_impressions | Potential Impressions | number        | number        |
| Yes      | series tag     | link                  | Link                  | url           | url           |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:dw7q-wyyh d:2011-03-01T00:00:00.000Z t:text="The new Cook County Government homepage makes its debut. Easier to use, Twitter, Facebook and more. http://ping.fm/cbGAL" t:time="7:09 AM" t:link=http://twitter.com/ToniPreckwinkle/status/42602271674085376 m:potential_impressions=3112 m:replies=0 m:retweets=0

series e:dw7q-wyyh d:2011-03-01T00:00:00.000Z t:text="Announcing a brand new look for the Forest Preserve of Cook County. Check it out: http://ping.fm/qVGib" t:time="7:09 AM" t:link=http://twitter.com/ToniPreckwinkle/status/42602325537333248 m:potential_impressions=3112 m:replies=0 m:retweets=0

series e:dw7q-wyyh d:2011-03-01T00:00:00.000Z t:text="Today is the last day to register online for the Cook County General Business License. Click here to apply:http://cot.ag/eRd2H7" t:time="7:10 AM" t:link=http://twitter.com/ToniPreckwinkle/status/42602607491039232 m:potential_impressions=3112 m:replies=0 m:retweets=0
```

## Meta Commands

```ls
metric m:retweets p:integer l:Retweets t:dataTypeName=number

metric m:replies p:integer l:Replies t:dataTypeName=number

metric m:potential_impressions p:integer l:"Potential Impressions" t:dataTypeName=number

entity e:dw7q-wyyh l:"All Tweets And Stats 2011 To 2013" t:attribution="Cook County Bureau of Technology" t:url=https://datacatalog.cookcountyil.gov/api/views/dw7q-wyyh

property e:dw7q-wyyh t:meta.view v:id=dw7q-wyyh v:category="Finance & Administration" v:attributionLink=http://www.cookcountyil.gov/technology v:averageRating=0 v:name="All Tweets And Stats 2011 To 2013" v:attribution="Cook County Bureau of Technology"

property e:dw7q-wyyh t:meta.view.license v:name="Public Domain"

property e:dw7q-wyyh t:meta.view.owner v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:displayName="Cook County Webmaster"

property e:dw7q-wyyh t:meta.view.tableauthor v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:roleName=administrator v:displayName="Cook County Webmaster"
```

## Top Records

```ls
| date                | time     | text                                                                                                                                       | retweets | replies | potential_impressions | link                                                                | 
| =================== | ======== | ========================================================================================================================================== | ======== | ======= | ===================== | =================================================================== | 
| 2011-03-01T00:00:00 | 7:09 AM  | The new Cook County Government homepage makes its debut. Easier to use, Twitter, Facebook and more. http://ping.fm/cbGAL                   | 0        | 0       | 3112                  | [http://twitter.com/ToniPreckwinkle/status/42602271674085376, null] | 
| 2011-03-01T00:00:00 | 7:09 AM  | Announcing a brand new look for the Forest Preserve of Cook County. Check it out: http://ping.fm/qVGib                                     | 0        | 0       | 3112                  | [http://twitter.com/ToniPreckwinkle/status/42602325537333248, null] | 
| 2011-03-01T00:00:00 | 7:10 AM  | Today is the last day to register online for the Cook County General Business License. Click here to apply:http://cot.ag/eRd2H7            | 0        | 0       | 3112                  | [http://twitter.com/ToniPreckwinkle/status/42602607491039232, null] | 
| 2011-03-01T00:00:00 | 7:10 AM  | Board of Review Opens Five Townships for Appeal http://bit.ly/eLWCgi                                                                       | 0        | 0       | 3112                  | [http://twitter.com/ToniPreckwinkle/status/42602674251759616, null] | 
| 2011-03-01T00:00:00 | 7:19 AM  | Follow the Cook County Blog on Twitter: http://bit.ly/h6XNMt                                                                               | 0        | 0       | 3112                  | [http://twitter.com/ToniPreckwinkle/status/42604756581089281, null] | 
| 2011-03-01T00:00:00 | 7:19 AM  | Like the Cook County Blog on Facebook: http://ping.fm/IYXSV                                                                                | 0        | 0       | 3112                  | [http://twitter.com/ToniPreckwinkle/status/42604941587656704, null] | 
| 2011-03-01T00:00:00 | 7:21 AM  | Toni Preckwinkle talks 2011 budget on WTTW's "Chicago Tonight" http://bit.ly/glo5Cs                                                        | 0        | 0       | 3112                  | [http://twitter.com/ToniPreckwinkle/status/42605311474929664, null] | 
| 2011-03-02T00:00:00 | 10:06 AM | You have until March 8th to register to vote in the April 5th Cook County Consolidated Election. Click here for info: http://ping.fm/a3Pbk | 0        | 0       | 3112                  | [http://twitter.com/ToniPreckwinkle/status/43009251488182272, null] | 
| 2011-03-02T00:00:00 | 10:07 AM | Everything you need to know about the April 5th Cook County Consolidated Election: http://ping.fm/RLnKk                                    | 0        | 0       | 3112                  | [http://twitter.com/ToniPreckwinkle/status/43009633375358976, null] | 
| 2011-03-02T00:00:00 | 10:08 AM | Everything you need to know about the April 5th Cook County Consolidated Election: http://bit.ly/fG0pj0                                    | 0        | 0       | 3112                  | [http://twitter.com/ToniPreckwinkle/status/43009923088515072, null] | 
```