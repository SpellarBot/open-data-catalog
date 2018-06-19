# Baltimore City Farmers Markets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baltimore-city-farmers-markets-29ddf) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/atzp-3tnt) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/atzp-3tnt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/atzp-3tnt/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | atzp-3tnt |
| Name | Baltimore City Farmers Markets |
| Attribution | Baltimore City Planning Department |
| Category | Health |
| Tags | farmers markets, community, food |
| Created | 2011-10-18T15:15:00Z |
| Publication Date | 2014-04-03T23:28:16Z |

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | name            | name            | text      | text        |
| Yes      | series tag  | day_            | day             | text      | text        |
| Yes      | series tag  | monthsopen      | monthsOpen      | text      | text        |
| Yes      | series tag  | monthsclose     | monthsClose     | text      | text        |
| Yes      | series tag  | openingtime     | openingTime     | text      | text        |
| Yes      | series tag  | closingtime     | closingTime     | text      | text        |
| Yes      | series tag  | ebtmachine      | EBTMachine      | text      | text        |
| Yes      | series tag  | wicfmnp         | WICFMNP         | text      | text        |
| Yes      | series tag  | seniorfmnp      | seniorFMNP      | text      | text        |
| Yes      | series tag  | fvc             | FVC             | text      | text        |
| Yes      | series tag  | fooddesert      | foodDesert      | text      | text        |
| Yes      | series tag  | numberofvendors | numberOfVendors | text      | text        |
| Yes      | series tag  | avgfoo_traffic  | avgFootTraffic  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:atzp-3tnt d:2011-10-18T08:15:12.000Z t:ebtmachine=N t:day_=Sunday t:monthsopen=3-Apr t:numberofvendors=68 t:avgfoo_traffic=n/a t:name="Baltimore City/JFX" t:wicfmnp=Y t:fvc=Y t:seniorfmnp=Y t:openingtime="7:00 a.m." t:fooddesert=Bordering t:monthsclose=18-Dec t:closingtime="12:00 p.m." m:row_number.atzp-3tnt=1

series e:atzp-3tnt d:2011-10-18T08:15:12.000Z t:ebtmachine=N t:day_=Thursday t:monthsopen=19-May t:numberofvendors=9 t:avgfoo_traffic=n/a t:name="Johns Hopkins Hospital" t:wicfmnp=N t:fvc=N t:seniorfmnp=N t:openingtime="10:00 a.m." t:fooddesert=Yes t:monthsclose=17-Nov t:closingtime="2:00 p.m." m:row_number.atzp-3tnt=2

series e:atzp-3tnt d:2011-10-18T08:15:12.000Z t:ebtmachine=Y t:day_=Saturday t:monthsopen="All year" t:numberofvendors=40 t:avgfoo_traffic=1000 t:name="32nd Street/Waverly" t:wicfmnp=Y t:fvc=Y t:seniorfmnp=Y t:openingtime="7:00 a.m." t:fooddesert=Bordering t:monthsclose="All year" t:closingtime="12:00 p.m." m:row_number.atzp-3tnt=3
```

## Meta Commands

```ls
metric m:row_number.atzp-3tnt p:long l:"Row Number"

entity e:atzp-3tnt l:"Baltimore City Farmers Markets" t:attribution="Baltimore City Planning Department" t:url=https://data.baltimorecity.gov/api/views/atzp-3tnt

property e:atzp-3tnt t:meta.view v:id=atzp-3tnt v:category=Health v:attributionLink=http://www.baltimorecity.gov/Government/AgenciesDepartments/Planning.aspx v:averageRating=0 v:name="Baltimore City Farmers Markets" v:attribution="Baltimore City Planning Department"

property e:atzp-3tnt t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:atzp-3tnt t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:atzp-3tnt t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                         | day_      | monthsopen | monthsclose | openingtime | closingtime | ebtmachine | wicfmnp | seniorfmnp | fvc | fooddesert | numberofvendors | avgfoo_traffic | 
| =========== | ============================ | ========= | ========== | =========== | =========== | =========== | ========== | ======= | ========== | === | ========== | =============== | ============== | 
| 1318925712  | Baltimore City/JFX           | Sunday    | 3-Apr      | 18-Dec      | 7:00 a.m.   | 12:00 p.m.  | N          | Y       | Y          | Y   | Bordering  | 68              | n/a            | 
| 1318925712  | Johns Hopkins Hospital       | Thursday  | 19-May     | 17-Nov      | 10:00 a.m.  | 2:00 p.m.   | N          | N       | N          | N   | Yes        | 9               | n/a            | 
| 1318925712  | 32nd Street/Waverly          | Saturday  | All year   | All year    | 7:00 a.m.   | 12:00 p.m.  | Y          | Y       | Y          | Y   | Bordering  | 40              | 1000           | 
| 1318925717  | Druid Hill                   | Wednesday | 1-Jun      | 5-Oct       | 3:30 p.m.   | 7:30 p.m.   | Y          | Y       | Y          | Y   | Bordering  | 6               | n/a            | 
| 1318925716  | Park Heights Community       | Wednesday | 15-Jun     | 23-Nov      | 9:30 a.m.   | 2:00 p.m.   | Y          | Y       | Y          | Y   | Bordering  | 7               | n/a            | 
| 1318925717  | University of Maryland       | Tuesday   | 10-May     | 22-Nov      | 10:30 a.m.  | 2:30 p.m.   | N          | Y       | Y          | Y   | Bordering  | 15              | n/a            | 
| 1318925717  | Highlandtown                 | Thursday  | 9-Jun      | 13-Oct      | 4:00 p.m.   | 8:00 p.m.   | Y          | Y       | Y          | Y   | Bordering  | 5               | 200            | 
| 1318925717  | Mt. Washington Whole Foods   | Wednesday | 8-Jun      | 26-Oct      | 3:30 p.m.   | 6:30 p.m.   | N          | N       | N          | N   | No         | n/a             | n/a            | 
| 1318925717  | Tuesday Market in Lauraville | Tuesday   | 7-Jun      | 25-Oct      | 4:00 p.m.   | 8:00 p.m.   | N          | N       | N          | N   | No         | 20              | 400            | 
| 1318925717  | Govanstowne (Loyola)         | Wednesday | 20-Jul     | 10-Aug      | 3:00 p.m.   | 7:00 p.m.   | Y          | N       | N          | N   | No         | n/a             | n/a            | 
```