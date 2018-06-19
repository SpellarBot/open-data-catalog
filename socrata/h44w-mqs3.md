# CT Department of Labor, Office of Research - Current Employment Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ct-department-of-labor-office-of-research-current-employment-statistics) |
| Metadata | [Link](https://data.ct.gov/api/views/h44w-mqs3) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/h44w-mqs3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/h44w-mqs3/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | h44w-mqs3 |
| Name | CT Department of Labor, Office of Research - Current Employment Statistics |
| Attribution | Department of Labor, Office of Research |
| Category | Government |
| Tags | current employment statistics, ces, estimates |
| Created | 2016-05-19T18:11:23Z |
| Publication Date | 2017-03-24T15:21:11Z |

## Description

Current Employment Statistics - February 2017

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       |                | year                   | YEAR                   | number    | text        |
| No       |                | month                  | MONTH                  | text      | text        |
| No       |                | st                     | ST                     | number    | text        |
| Yes      | numeric metric | area                   | AREA                   | number    | text        |
| Yes      | series tag     | publish_industry_title | PUBLISH INDUSTRY TITLE | text      | text        |
| Yes      | numeric metric | series                 | SERIES                 | number    | text        |
| Yes      | series tag     | data_type              | DATA TYPE              | text      | text        |
| Yes      | numeric metric | current_mo             | CURRENT MO             | number    | text        |
| Yes      | numeric metric | previous_mo            | PREVIOUS MO            | number    | text        |
| Yes      | numeric metric | 1yr_ago_mo             | 1YR AGO MO             | number    | text        |
| Yes      | series tag     | diff_cur_prv           | DIFF CUR - PRV         | text      | text        |
| Yes      | numeric metric | cur_prv                | % CUR/PRV              | number    | text        |
| Yes      | series tag     | diff_cur_1yr_ago       | DIFF CUR - 1YR AGO     | text      | text        |
| Yes      | numeric metric | cur_1yr_ago            | % CUR/1YR AGO          | number    | text        |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = st,year,month
```

## Data Commands

```ls
series e:h44w-mqs3 d:2017-02-01T00:00:00.000Z t:diff_cur_prv=-300 t:diff_cur_1yr_ago=1,400 t:data_type=1 t:publish_industry_title="Total Nonfarm" m:series=0 m:current_mo=1654300 m:area=0 m:cur_prv=-0.019999999552965164 m:previous_mo=1654600 m:cur_1yr_ago=0.07999999821186066 m:1yr_ago_mo=1652900

series e:h44w-mqs3 d:2017-02-01T00:00:00.000Z t:diff_cur_prv=-2,600 t:diff_cur_1yr_ago=5,700 t:data_type=1 t:publish_industry_title="Total Private" m:series=5000000 m:current_mo=1417900 m:area=0 m:cur_prv=-0.18000000715255737 m:previous_mo=1420500 m:cur_1yr_ago=0.4000000059604645 m:1yr_ago_mo=1412200

series e:h44w-mqs3 d:2017-02-01T00:00:00.000Z t:diff_cur_prv=-600 t:diff_cur_1yr_ago=-2,300 t:data_type=1 t:publish_industry_title="Goods Producing" m:series=6000000 m:current_mo=207200 m:area=0 m:cur_prv=-0.28999999165534973 m:previous_mo=207800 m:cur_1yr_ago=-1.100000023841858 m:1yr_ago_mo=209500
```

## Meta Commands

```ls
metric m:area p:integer l:AREA t:dataTypeName=number

metric m:series p:integer l:SERIES t:dataTypeName=number

metric m:current_mo p:integer l:"CURRENT MO" t:dataTypeName=number

metric m:previous_mo p:integer l:"PREVIOUS MO" t:dataTypeName=number

metric m:1yr_ago_mo p:integer l:"1YR AGO MO" t:dataTypeName=number

metric m:cur_prv p:float l:"% CUR/PRV" t:dataTypeName=number

metric m:cur_1yr_ago p:float l:"% CUR/1YR AGO" t:dataTypeName=number

entity e:h44w-mqs3 l:"CT Department of Labor, Office of Research - Current Employment Statistics" t:attribution="Department of Labor, Office of Research" t:url=https://data.ct.gov/api/views/h44w-mqs3

property e:h44w-mqs3 t:meta.view v:id=h44w-mqs3 v:category=Government v:attributionLink=http://www1.ctdol.state.ct.us/lmi/index.asp v:averageRating=0 v:name="CT Department of Labor, Office of Research - Current Employment Statistics" v:attribution="Department of Labor, Office of Research"

property e:h44w-mqs3 t:meta.view.license v:name="Public Domain"

property e:h44w-mqs3 t:meta.view.owner v:id=dm7v-mmvk v:screenName="Andrew Condon" v:displayName="Andrew Condon"

property e:h44w-mqs3 t:meta.view.tableauthor v:id=dm7v-mmvk v:screenName="Andrew Condon" v:roleName=editor v:displayName="Andrew Condon"
```

## Top Records

```ls
| year | month    | st | area | publish_industry_title           | series   | data_type | current_mo | previous_mo | 1yr_ago_mo | diff_cur_prv | cur_prv | diff_cur_1yr_ago | cur_1yr_ago | 
| ==== | ======== | == | ==== | ================================ | ======== | ========= | ========== | =========== | ========== | ============ | ======= | ================ | =========== | 
| 2017 | February | 9  | 0    | Total Nonfarm                    | 0        | 1         | 1654300    | 1654600     | 1652900    | -300         | -0.02%  | 1,400            | 0.08%       | 
| 2017 | February | 9  | 0    | Total Private                    | 5000000  | 1         | 1417900    | 1420500     | 1412200    | -2,600       | -0.18%  | 5,700            | 0.40%       | 
| 2017 | February | 9  | 0    | Goods Producing                  | 6000000  | 1         | 207200     | 207800      | 209500     | -600         | -0.29%  | -2,300           | -1.10%      | 
| 2017 | February | 9  | 0    | Service-Providing                | 7000000  | 1         | 1447100    | 1446800     | 1443400    | 300          | 0.02%   | 3,700            | 0.26%       | 
| 2017 | February | 9  | 0    | Private Service Providing        | 8000000  | 1         | 1210700    | 1212700     | 1202700    | -2,000       | -0.16%  | 8,000            | 0.67%       | 
| 2017 | February | 9  | 0    | Mining and Logging               | 10000000 | 1         | 500        | 500         | 500        | 0            | 0.00%   | 0                | 0.00%       | 
| 2017 | February | 9  | 0    | Mining, Logging and Construction | 15000000 | 1         | 52500      | 52600       | 53800      | -100         | -0.19%  | -1,300           | -2.42%      | 
| 2017 | February | 9  | 0    | Construction                     | 20000000 | 1         | 52000      | 52100       | 53300      | -100         | -0.19%  | -1,300           | -2.44%      | 
| 2017 | February | 9  | 0    | Construction of Buildings        | 20236000 | 1         | 10200      | 10400       | 10800      | -200         | -1.92%  | -600             | -5.56%      | 
| 2017 | February | 9  | 0    | Specialty Trade Contractors      | 20238000 | 1         | 35700      | 35800       | 37600      | -100         | -0.28%  | -1,900           | -5.05%      | 
```