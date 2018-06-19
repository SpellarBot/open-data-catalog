# One Day Liquor Licenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/one-day-liquor-licenses-a2018) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/bcxw-m234) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/bcxw-m234/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/bcxw-m234/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | bcxw-m234 |
| Name | One Day Liquor Licenses |
| Attribution | Baltimore City Liquor License Board |
| Category | City Services |
| Tags | liquor, event, festival, license, permit |
| Created | 2011-09-30T18:30:12Z |
| Publication Date | 2017-01-11T08:14:58Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | time           | issuedate         | IssueDate         | calendar_date | calendar_date |
| No       |                | startdate         | StartDate         | calendar_date | calendar_date |
| No       |                | enddate           | EndDate           | calendar_date | calendar_date |
| Yes      | series tag     | certificatenumber | certificateNumber | text          | text          |
| Yes      | numeric metric | fee               | fee               | money         | money         |
| Yes      | series tag     | nponame           | NPOName           | text          | text          |
| Yes      | series tag     | locname           | LocName           | text          | text          |
| Yes      | series tag     | licenseclass      | LicenseClass      | text          | text          |
| Yes      | series tag     | subclass          | SubClass          | text          | text          |
| Yes      | series tag     | description       | Description       | text          | text          |
| Yes      | series tag     | addrstreet        | AddrStreet        | text          | text          |
| Yes      | series tag     | addrzip           | AddrZip           | text          | text          |
```

## Time Field

```ls
Value = issuedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = startdate,enddate
```

## Data Commands

```ls
series e:bcxw-m234 d:2013-01-25T00:00:00.000Z t:nponame="The Bong County, Liberia/Maryland, U.S.A Educational Culture Foundation, Inc." t:addrzip=21212 t:description="Beer, Wine, & Liquor" t:subclass=BWL t:locname=Fundraiser t:certificatenumber=61916 t:licenseclass=LS t:addrstreet="4339 YORK ROAD" m:fee=50

series e:bcxw-m234 d:2013-01-25T00:00:00.000Z t:nponame="The Bong County, Liberia/Maryland, U.S.A Educational Culture Foundation, Inc." t:addrzip=21212 t:description="Beer, Wine, & Liquor" t:subclass=BWL t:locname=Fundraiser t:certificatenumber=61915 t:licenseclass=LS t:addrstreet="4339 YORK ROAD" m:fee=50

series e:bcxw-m234 d:2013-01-25T00:00:00.000Z t:nponame="Glenn L Martin Aviation Museum Inc" t:addrzip=21224 t:description="Beer & Wines" t:subclass=BW t:locname="Sporting Event" t:certificatenumber=61917 t:licenseclass=WS t:addrstreet="1301 S. Ellwood Ave" m:fee=25
```

## Meta Commands

```ls
metric m:fee p:double l:fee t:dataTypeName=money

entity e:bcxw-m234 l:"One Day Liquor Licenses" t:attribution="Baltimore City Liquor License Board" t:url=https://data.baltimorecity.gov/api/views/bcxw-m234

property e:bcxw-m234 t:meta.view v:id=bcxw-m234 v:category="City Services" v:attributionLink=http://www.baltimorecity.gov/Government/BoardsandCommissions/LiquorBoard.aspx v:averageRating=0 v:name="One Day Liquor Licenses" v:attribution="Baltimore City Liquor License Board"

property e:bcxw-m234 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:bcxw-m234 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:bcxw-m234 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| issuedate | startdate | enddate | certificatenumber | fee | nponame | locname | licenseclass | subclass | description | addrstreet | addrzip | 
| ========= | ========= | ======= | ================= | === | ======= | ======= | ============ | ======== | =========== | ========== | ======= | 
|           |           |         |                   |     |         |         |              |          |             |            |         | 
|           |           |         |                   |     |         |         |              |          |             |            |         | 
|           |           |         |                   |     |         |         |              |          |             |            |         | 
|           |           |         |                   |     |         |         |              |          |             |            |         | 
|           |           |         |                   |     |         |         |              |          |             |            |         | 
|           |           |         |                   |     |         |         |              |          |             |            |         | 
|           |           |         |                   |     |         |         |              |          |             |            |         | 
|           |           |         |                   |     |         |         |              |          |             |            |         | 
|           |           |         |                   |     |         |         |              |          |             |            |         | 
|           |           |         |                   |     |         |         |              |          |             |            |         | 
```