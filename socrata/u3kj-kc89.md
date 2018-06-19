# Local Capital Improvement Program Municipal Entitlement Amounts (2014)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-capital-improvement-program-municipal-entitlement-amounts-2014) |
| Metadata | [Link](https://data.ct.gov/api/views/u3kj-kc89) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/u3kj-kc89/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/u3kj-kc89/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | u3kj-kc89 |
| Name | Local Capital Improvement Program Municipal Entitlement Amounts (2014) |
| Attribution | Office of Policy and Management |
| Category | Government |
| Tags | ct, opm, locip, municipal |
| Created | 2014-03-13T16:37:56Z |
| Publication Date | 2014-03-13T16:46:25Z |

## Description

The Local Capital Improvement Program (LoCIP) distributes funds to municipalities to reimburse the cost of eligible local capital improvement projects such as road, bridge or public building construction activities. A municipality can request LoCIP funds by completing a simple application form for project approval and project reimbursement that gives a general description of the project, its work location, and the actual cost of the project. Each year, the State Office of Policy and Management provides a formula based entitlement to each municipality's available LoCIP balance. These funds can accumulate from year to year

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | municipality     | Municipality     | text      | text        |
| Yes      | numeric metric | 2005             | 2005             | money     | money       |
| Yes      | numeric metric | 2006             | 2006             | money     | money       |
| Yes      | numeric metric | 2007             | 2007             | money     | money       |
| Yes      | numeric metric | 2008             | 2008             | money     | money       |
| Yes      | numeric metric | 2009             | 2009             | money     | money       |
| Yes      | numeric metric | 2010             | 2010             | money     | money       |
| Yes      | numeric metric | 2011             | 2011             | money     | money       |
| Yes      | numeric metric | 2012             | 2012             | money     | money       |
| Yes      | numeric metric | 2013             | 2013             | money     | money       |
| Yes      | numeric metric | 2014             | 2014             | money     | money       |
| Yes      | numeric metric | available_3_1_14 | Available 3/1/14 | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:u3kj-kc89 d:2014-01-01T00:00:00.000Z t:municipality=Andover m:2008=27913 m:2009=28270 m:2006=28955 m:2007=28444 m:2013=28196 m:2005=28947 m:2014=27906 m:available_3_1_14=118213 m:2012=28735 m:2011=28465 m:2010=28129

series e:u3kj-kc89 d:2014-01-01T00:00:00.000Z t:municipality=Willington m:2008=61430 m:2009=61375 m:2006=60202 m:2007=60836 m:2013=61562 m:2005=60445 m:2014=60224 m:available_3_1_14=134245.43 m:2012=59907 m:2011=60591 m:2010=59376

series e:u3kj-kc89 d:2014-01-01T00:00:00.000Z t:municipality=Wilton m:2008=112569 m:2009=111703 m:2006=112780 m:2007=113035 m:2013=111666 m:2005=113100 m:2014=112983 m:available_3_1_14=112983 m:2012=111140 m:2011=111998 m:2010=111159
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=money

metric m:2006 p:integer l:2006 t:dataTypeName=money

metric m:2007 p:integer l:2007 t:dataTypeName=money

metric m:2008 p:integer l:2008 t:dataTypeName=money

metric m:2009 p:integer l:2009 t:dataTypeName=money

metric m:2010 p:integer l:2010 t:dataTypeName=money

metric m:2011 p:integer l:2011 t:dataTypeName=money

metric m:2012 p:integer l:2012 t:dataTypeName=money

metric m:2013 p:integer l:2013 t:dataTypeName=money

metric m:2014 p:integer l:2014 t:dataTypeName=money

metric m:available_3_1_14 p:double l:"Available 3/1/14" t:dataTypeName=money

entity e:u3kj-kc89 l:"Local Capital Improvement Program Municipal Entitlement Amounts (2014)" t:attribution="Office of Policy and Management" t:url=https://data.ct.gov/api/views/u3kj-kc89

property e:u3kj-kc89 t:meta.view v:id=u3kj-kc89 v:category=Government v:attributionLink="http://www.ct.gov/opm/cwp/view.asp?a=2985&q=383108" v:averageRating=0 v:name="Local Capital Improvement Program Municipal Entitlement Amounts (2014)" v:attribution="Office of Policy and Management"

property e:u3kj-kc89 t:meta.view.license v:name="Public Domain"

property e:u3kj-kc89 t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:u3kj-kc89 t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| municipality | 2005   | 2006   | 2007   | 2008   | 2009   | 2010   | 2011   | 2012   | 2013   | 2014   | available_3_1_14 | 
| ============ | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ================ | 
| Andover      | 28947  | 28955  | 28444  | 27913  | 28270  | 28129  | 28465  | 28735  | 28196  | 27906  | 118213.00        | 
| Willington   | 60445  | 60202  | 60836  | 61430  | 61375  | 59376  | 60591  | 59907  | 61562  | 60224  | 134245.43        | 
| Wilton       | 113100 | 112780 | 113035 | 112569 | 111703 | 111159 | 111998 | 111140 | 111666 | 112983 | 112983.00        | 
| Winchester   | 91589  | 91443  | 92116  | 92680  | 91966  | 87457  | 88890  | 89318  | 89217  | 89720  | 375872.03        | 
| Windham      | 236451 | 236838 | 230598 | 239359 | 261928 | 220269 | 226613 | 247091 | 259909 | 246882 | 293906.09        | 
|              |        |        |        |        |        |        |        |        |        |        |                  | 
| Beacon Falls | 37087  | 36995  | 36279  | 36665  | 37937  | 37538  | 38309  | 38903  | 38500  | 38044  | 160415.57        | 
| Berlin       | 124221 | 124578 | 127412 | 129881 | 132310 | 128158 | 133059 | 127659 | 124390 | 125634 | 338990.88        | 
| Bethany      | 47502  | 47419  | 47661  | 48577  | 48581  | 47882  | 48193  | 48050  | 47474  | 47173  | 143008.00        | 
| Bethel       | 115168 | 115270 | 120169 | 118327 | 118520 | 114416 | 117193 | 115982 | 115858 | 119373 | 253956.11        | 
```