# Multi-Family Housing FY 2011-2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/multi-family-housing-fy-2011-2015) |
| Metadata | [Link](https://data.maryland.gov/api/views/cadm-spqd) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/cadm-spqd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/cadm-spqd/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | cadm-spqd |
| Name | Multi-Family Housing FY 2011-2017 |
| Attribution | Department of Housing and Community Development |
| Category | Housing |
| Tags | dhcd, department of housing & community development, multifamily, multifamily housing, multi-family, multi-family housing, cda, community development administration, affordable housing, rental hou... |
| Created | 2016-07-01T15:26:31Z |
| Publication Date | 2017-09-01T13:57:46Z |

## Description

The Maryland Department of Housing and Community Development offers multifamily finance programs for the construction and rehabilitation of affordable rental housing units for low to moderate income families, senior citizens and individuals with disabilities.

Our multifamily bond programs issues tax-exempt and taxable revenue mortgage bonds to finance the acquisition, preservation and creation of affordable multifamily rental housing units in priority funding areas.

By advocating for increased production of rental housing units, we help create much-needed jobs and leverage opportunities to live, work and prosper for hardworking Maryland families, senior citizens, and individuals with disabilities throughout the state.​

DISCLAIMER: Some of the information may be tied to the Department’s bond funded loan programs and should not be relied upon in making an investment decision. The Department provides comprehensive quarterly and annual financial information and operating data regarding its bonds and bond funded loan programs, all of which is posted on the publicly-accessible Electronic Municipal Market Access system website (commonly known as EMMA) that is maintained by the Municipal Securities Rulemaking Board, and on the Department’s website under Investor Information. 

More information accessible here: http://dhcd.maryland.gov/Investors/Pages/default.aspx

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       |                | fy              | FY              | number    | text        |
| Yes      | series tag     | project_name    | Project Name    | text      | text        |
| No       |                | project_address | Project Address | text      | text        |
| Yes      | series tag     | project_city    | Project City    | text      | text        |
| Yes      | series tag     | project_zip     | Project Zip     | text      | text        |
| Yes      | series tag     | project_county  | Project County  | text      | text        |
| Yes      | numeric metric | units           | Units           | number    | number      |
| Yes      | series tag     | projecttype     | ProjectType     | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = fy,project_address
```

## Data Commands

```ls
series e:cadm-spqd d:2011-01-01T00:00:00.000Z t:project_county=Howard t:project_city=Elkridge t:projecttype=Acq./Rehab. t:project_zip=21075 t:project_name="Park View at Colonial Landing" m:units=100

series e:cadm-spqd d:2011-01-01T00:00:00.000Z t:project_county="Prince George's" t:project_city=Bladensburg t:projecttype=Acq./Rehab. t:project_zip=20710 t:project_name="Park View at Bladensburg" m:units=101

series e:cadm-spqd d:2011-01-01T00:00:00.000Z t:project_county="Anne Arundel" t:project_city="Glen Burnie" t:projecttype=New t:project_zip=21061 t:project_name="Burwood Gardens Phase I" m:units=100
```

## Meta Commands

```ls
metric m:units p:integer l:Units t:dataTypeName=number

entity e:cadm-spqd l:"Multi-Family Housing FY 2011-2017" t:attribution="Department of Housing and Community Development" t:url=https://data.maryland.gov/api/views/cadm-spqd

property e:cadm-spqd t:meta.view d:2017-09-25T07:26:30.223Z v:averageRating=0 v:name="Multi-Family Housing FY 2011-2017" v:attribution="Department of Housing and Community Development" v:attributionLink=http://dhcd.maryland.gov/Pages/default.aspx v:id=cadm-spqd v:category=Housing

property e:cadm-spqd t:meta.view.license d:2017-09-25T07:26:30.223Z v:name="Public Domain"

property e:cadm-spqd t:meta.view.owner d:2017-09-25T07:26:30.223Z v:displayName="Jessica Handy" v:lastNotificationSeenAt=1504032914 v:id=pugw-9r35 v:screenName="Jessica Handy"

property e:cadm-spqd t:meta.view.tableauthor d:2017-09-25T07:26:30.223Z v:displayName="Jessica Handy" v:lastNotificationSeenAt=1504032914 v:roleName=editor v:id=pugw-9r35 v:screenName="Jessica Handy"
```

## Top Records

```ls
| fy   | project_name                      | project_address                                   | project_city  | project_zip | project_county  | units | projecttype | 
| ==== | ================================= | ================================================= | ============= | =========== | =============== | ===== | =========== | 
| 2013 | Park View at Colonial Landing     | 6391 Rowanberry Drive                             | Elkridge      | 21075       | Howard          | 100   | Acq./Rehab. | 
| 2013 | Park View at Bladensburg          | 4202 58th Avenue                                  | Bladensburg   | 20710       | Prince George's | 101   | Acq./Rehab. | 
| 2013 | Burwood Gardens Phase I           | 6652 Shelly Avenue                                | Glen Burnie   | 21061       | Anne Arundel    | 100   | New         | 
| 2013 | Oakwood Family Homes              | 8219 and 8221 Oakwood Road                        | Glen Burnie   | 21061       | Anne Arundel    | 22    | New         | 
| 2013 | Belle Hill Manor                  | Belle Hill Road                                   | Elkton        | 21921       | Cecil           | 84    | New         | 
| 2013 | Tanglewood Sligo Hills Apartments | 8900 Manchester Road 8902 8904 9000 Manchester Rd | Silver Spring | 20901       | Montgomery      | 132   | Rehab.      | 
| 2013 | Barclay Square Phase II           | 341 E. 20th Street                                | Baltimore     | 21218       | Baltimore City  | 69    | New/Rehab.  | 
| 2013 | O'Donnell Townhomes 1             | 6349 Boston Street                                | Baltimore     | 21224       | Baltimore City  | 75    | New         | 
| 2013 | Parkview Towers Apartments        | 7667 N Maple Avenue                               | Silver Spring | 20912       | Montgomery      | 125   | Acq./Rehab. | 
| 2013 | The Greens at Logan Field         | 3455 Dundalk Avenue                               | Dundalk       | 21222       | Baltimore       | 102   | New         | 
```