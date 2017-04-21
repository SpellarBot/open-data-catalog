# Department of Labor, Office of Research (Current Employment Statistics NSA 1990 - Current)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-labor-office-of-research-current-employment-statistics-nsa-1990-current-a9420) |
| Metadata | [Link](https://data.ct.gov/api/views/8zbs-9atu) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/8zbs-9atu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/8zbs-9atu/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 8zbs-9atu |
| Name | Department of Labor, Office of Research (Current Employment Statistics NSA 1990 - Current) |
| Attribution | Department of Labor, Office of Research |
| Category | Government |
| Tags | ces, emplyment, jobs, earnings, historical |
| Created | 2016-04-14T13:34:39Z |
| Publication Date | 2017-03-24T15:29:57Z |

## Description

Historical Employment Statistics 1990 - current.
The Current Employment Statistics (CES) more information program provides the most current estimates of nonfarm employment, hours, and earnings data by industry (place of work) for the nation as a whole, all states, and most major metropolitan areas. The CES survey is a federal-state cooperative endeavor in which states develop state and sub-state data using concepts, definitions, and technical procedures prescribed by the Bureau of Labor Statistics (BLS). Estimates produced by the CES program include both full- and part-time jobs. Excluded are self-employment, as well as agricultural and domestic positions. In Connecticut, more than 4,000 employers are surveyed each month to determine the number of the jobs in the State. For more information please visit us at http://www1.ctdol.state.ct.us/lmi/ces/default.asp.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | bmrk_yr        | BMRK YR        | text      | text        |
| No       |                | st             | ST             | number    | text        |
| Yes      | numeric metric | area           | AREA           | number    | text        |
| Yes      | series tag     | industry_title | INDUSTRY TITLE | text      | text        |
| Yes      | numeric metric | series         | SERIES         | number    | text        |
| Yes      | series tag     | data_type_code | DATA TYPE CODE | text      | text        |
| Yes      | series tag     | data_type      | DATA TYPE      | text      | text        |
| Yes      | time           | year           | YEAR           | number    | text        |
| Yes      | numeric metric | jan            | JAN            | number    | text        |
| Yes      | numeric metric | feb            | FEB            | number    | text        |
| Yes      | numeric metric | mar            | MAR            | number    | text        |
| Yes      | numeric metric | apr            | APR            | number    | text        |
| Yes      | numeric metric | may            | MAY            | number    | text        |
| Yes      | numeric metric | jun            | JUN            | number    | text        |
| Yes      | numeric metric | jul            | JUL            | number    | text        |
| Yes      | numeric metric | aug            | AUG            | number    | text        |
| Yes      | numeric metric | sep            | SEP            | number    | text        |
| Yes      | numeric metric | oct            | OCT            | number    | text        |
| Yes      | numeric metric | nov            | NOV            | number    | text        |
| Yes      | numeric metric | dec            | DEC            | number    | text        |
| Yes      | numeric metric | average        | AVERAGE        | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = st
```

## Data Commands

```ls
series e:8zbs-9atu d:1990-01-01T00:00:00.000Z t:data_type_code=1 t:data_type=AE t:bmrk_yr=2016-1 t:industry_title="Total Nonfarm" m:series=0 m:may=1634 m:apr=1622.3 m:jul=1612.7 m:jun=1646.1 m:area=0 m:oct=1610.5 m:dec=1612.3 m:feb=1613.7 m:nov=1611.8 m:sep=1621 m:mar=1624.9 m:jan=1621.7 m:aug=1604.3 m:average=1619.6

series e:8zbs-9atu d:1991-01-01T00:00:00.000Z t:data_type_code=1 t:data_type=AE t:bmrk_yr=2016-1 t:industry_title="Total Nonfarm" m:series=0 m:may=1568.8 m:apr=1562.8 m:jul=1542.1 m:jun=1578.2 m:area=0 m:oct=1553.9 m:dec=1561 m:feb=1550 m:nov=1557.6 m:sep=1553.5 m:mar=1559.4 m:jan=1563.8 m:aug=1535 m:average=1557.2

series e:8zbs-9atu d:1992-01-01T00:00:00.000Z t:data_type_code=1 t:data_type=AE t:bmrk_yr=2016-1 t:industry_title="Total Nonfarm" m:series=0 m:may=1531.5 m:apr=1521.3 m:jul=1522 m:jun=1540.4 m:area=0 m:oct=1535.9 m:dec=1545 m:feb=1507.4 m:nov=1541 m:sep=1531.7 m:mar=1515.4 m:jan=1511.4 m:aug=1513.3 m:average=1526.4
```

## Meta Commands

```ls
metric m:area p:integer l:AREA t:dataTypeName=number

metric m:series p:integer l:SERIES t:dataTypeName=number

metric m:jan p:float l:JAN t:dataTypeName=number

metric m:feb p:float l:FEB t:dataTypeName=number

metric m:mar p:float l:MAR t:dataTypeName=number

metric m:apr p:float l:APR t:dataTypeName=number

metric m:may p:float l:MAY t:dataTypeName=number

metric m:jun p:float l:JUN t:dataTypeName=number

metric m:jul p:float l:JUL t:dataTypeName=number

metric m:aug p:float l:AUG t:dataTypeName=number

metric m:sep p:integer l:SEP t:dataTypeName=number

metric m:oct p:float l:OCT t:dataTypeName=number

metric m:nov p:float l:NOV t:dataTypeName=number

metric m:dec p:float l:DEC t:dataTypeName=number

metric m:average p:float l:AVERAGE t:dataTypeName=number

entity e:8zbs-9atu l:"Department of Labor, Office of Research (Current Employment Statistics NSA 1990 - Current)" t:attribution="Department of Labor, Office of Research" t:url=https://data.ct.gov/api/views/8zbs-9atu

property e:8zbs-9atu t:meta.view v:id=8zbs-9atu v:category=Government v:attributionLink=http://www1.ctdol.state.ct.us/lmi/ces/default.asp v:averageRating=0 v:name="Department of Labor, Office of Research (Current Employment Statistics NSA 1990 - Current)" v:attribution="Department of Labor, Office of Research"

property e:8zbs-9atu t:meta.view.license v:name="Public Domain"

property e:8zbs-9atu t:meta.view.owner v:id=dm7v-mmvk v:screenName="Andrew Condon" v:displayName="Andrew Condon"

property e:8zbs-9atu t:meta.view.tableauthor v:id=dm7v-mmvk v:screenName="Andrew Condon" v:roleName=editor v:displayName="Andrew Condon"
```

## Top Records

```ls
| bmrk_yr | st | area | industry_title | series | data_type_code | data_type | year | jan    | feb    | mar    | apr    | may    | jun    | jul    | aug    | sep    | oct    | nov    | dec    | average | 
| ======= | == | ==== | ============== | ====== | ============== | ========= | ==== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======= | 
| 2016-1  | 9  | 0    | Total Nonfarm  | 0      | 1              | AE        | 1990 | 1621.7 | 1613.7 | 1624.9 | 1622.3 | 1634   | 1646.1 | 1612.7 | 1604.3 | 1621   | 1610.5 | 1611.8 | 1612.3 | 1619.6  | 
| 2016-1  | 9  | 0    | Total Nonfarm  | 0      | 1              | AE        | 1991 | 1563.8 | 1550   | 1559.4 | 1562.8 | 1568.8 | 1578.2 | 1542.1 | 1535   | 1553.5 | 1553.9 | 1557.6 | 1561   | 1557.2  | 
| 2016-1  | 9  | 0    | Total Nonfarm  | 0      | 1              | AE        | 1992 | 1511.4 | 1507.4 | 1515.4 | 1521.3 | 1531.5 | 1540.4 | 1522   | 1513.3 | 1531.7 | 1535.9 | 1541   | 1545   | 1526.4  | 
| 2016-1  | 9  | 0    | Total Nonfarm  | 0      | 1              | AE        | 1993 | 1511.9 | 1515.1 | 1518.8 | 1522.2 | 1534.6 | 1541.8 | 1520   | 1513   | 1537.3 | 1546.6 | 1553.8 | 1560.3 | 1531.3  | 
| 2016-1  | 9  | 0    | Total Nonfarm  | 0      | 1              | AE        | 1994 | 1502.9 | 1503.4 | 1516   | 1537.1 | 1548.8 | 1560.4 | 1539.2 | 1535.7 | 1559.6 | 1568.2 | 1575.7 | 1579.3 | 1543.9  | 
| 2016-1  | 9  | 0    | Total Nonfarm  | 0      | 1              | AE        | 1995 | 1532.9 | 1539.4 | 1552.4 | 1554   | 1563.6 | 1571.9 | 1550.4 | 1549.1 | 1571.2 | 1574.4 | 1586.8 | 1593.5 | 1561.6  | 
| 2016-1  | 9  | 0    | Total Nonfarm  | 0      | 1              | AE        | 1996 | 1533.1 | 1547.2 | 1558.1 | 1572.1 | 1587.4 | 1600.2 | 1570.8 | 1575.4 | 1593.5 | 1607.3 | 1619.5 | 1626.1 | 1582.6  | 
| 2016-1  | 9  | 0    | Total Nonfarm  | 0      | 1              | AE        | 1997 | 1567.2 | 1575.4 | 1587.5 | 1599.2 | 1610.1 | 1621.9 | 1595.8 | 1593.8 | 1621.9 | 1629.7 | 1638.7 | 1651.9 | 1607.8  | 
| 2016-1  | 9  | 0    | Total Nonfarm  | 0      | 1              | AE        | 1998 | 1601.7 | 1612.7 | 1624.6 | 1630.5 | 1643.2 | 1658.4 | 1641.8 | 1634.9 | 1653.4 | 1662.2 | 1673.7 | 1685.4 | 1643.5  | 
| 2016-1  | 9  | 0    | Total Nonfarm  | 0      | 1              | AE        | 1999 | 1632.6 | 1639.2 | 1651.1 | 1663.2 | 1668.5 | 1683.4 | 1667.6 | 1663.4 | 1679.6 | 1682.8 | 1692.7 | 1706.5 | 1669.2  | 
```