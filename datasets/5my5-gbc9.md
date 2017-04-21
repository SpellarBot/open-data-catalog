# DEL Office Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/del-office-locations) |
| Metadata | [Link](https://data.wa.gov/api/views/5my5-gbc9) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/5my5-gbc9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/5my5-gbc9/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 5my5-gbc9 |
| Name | DEL Office Locations |
| Category | Education |
| Tags | del, early learning |
| Created | 2013-05-15T18:27:45Z |
| Publication Date | 2017-04-14T07:57:22Z |

## Description

The DEL Office Locations data set is comprised of the DEL office locations at the point in time the data is extracted. Below is a description of the data elements for the data set.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | officeid             | OfficeId             | text      | number      |
| Yes      | series tag     | officename           | OfficeName           | text      | text        |
| Yes      | series tag     | officenumber         | OfficeNumber         | text      | number      |
| Yes      | series tag     | mainofficeid         | MainOfficeId         | text      | text        |
| No       |                | physicaladdressline1 | PhysicalAddressLine1 | text      | text        |
| No       |                | physicaladdressline2 | PhysicalAddressLine2 | text      | text        |
| Yes      | series tag     | physicalcity         | PhysicalCity         | text      | text        |
| Yes      | series tag     | physicalstate        | PhysicalState        | text      | text        |
| Yes      | series tag     | physicalzip          | PhysicalZip          | text      | text        |
| No       |                | mailaddressline1     | MailAddressLine1     | text      | text        |
| No       |                | mailaddressline2     | MailAddressLine2     | text      | text        |
| Yes      | series tag     | mailcity             | MailCity             | text      | text        |
| Yes      | series tag     | mailstate            | MailState            | text      | text        |
| Yes      | series tag     | mailzip              | MailZip              | text      | text        |
| Yes      | series tag     | mailstop             | MailStop             | text      | text        |
| Yes      | numeric metric | phone                | Phone                | number    | text        |
| Yes      | numeric metric | fax                  | Fax                  | number    | text        |
| Yes      | numeric metric | tollfree             | TollFree             | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = physicaladdressline1,physicaladdressline2,mailaddressline1,mailaddressline2
```

## Data Commands

```ls
series e:5my5-gbc9 d:2017-04-13T17:22:20.000Z t:mailstop=N/A t:officename=Silverdale t:officenumber=986 t:physicalcity=Silverdale t:officeid=4 t:physicalstate=WA t:physicalzip=98383 m:phone=360.698 m:fax=360.698

series e:5my5-gbc9 d:2017-04-14T07:57:15.000Z t:mailstop=40970 t:mailcity=Olympia t:officename="State Office" t:mailstate=WA t:officenumber=990 t:mailzip=98504-0970 t:physicalcity=Olympia t:officeid=13 t:physicalstate=WA t:physicalzip=98501 m:phone=360.725 m:fax=360.413 m:tollfree=1.866

series e:5my5-gbc9 d:2017-04-14T07:57:15.000Z t:mainofficeid=21 t:mailstop=S8-6 t:officename=Kelso t:mailstate=WA t:officenumber=988 t:physicalcity=Kelso t:officeid=8 t:physicalstate=WA t:physicalzip=98626 m:phone=360.501 m:fax=360.577
```

## Meta Commands

```ls
metric m:phone p:double l:Phone d:"The primary phone number for the office location." t:dataTypeName=number

metric m:fax p:double l:Fax d:"The primary fax number for the office location." t:dataTypeName=number

metric m:tollfree p:double l:TollFree d:"The toll-free phone number for the office location." t:dataTypeName=number

entity e:5my5-gbc9 l:"DEL Office Locations" t:url=https://data.wa.gov/api/views/5my5-gbc9

property e:5my5-gbc9 t:meta.view v:id=5my5-gbc9 v:category=Education v:averageRating=0 v:name="DEL Office Locations"

property e:5my5-gbc9 t:meta.view.owner v:id=2rzx-gdqv v:screenName="Department of Early Learning" v:displayName="Department of Early Learning"

property e:5my5-gbc9 t:meta.view.tableauthor v:id=2rzx-gdqv v:screenName="Department of Early Learning" v:roleName=editor v:displayName="Department of Early Learning"
```

## Top Records

```ls
| :updated_at | officeid | officename   | officenumber | mainofficeid | physicaladdressline1           | physicaladdressline2 | physicalcity | physicalstate | physicalzip | mailaddressline1       | mailaddressline2 | mailcity | mailstate | mailzip    | mailstop | phone        | fax          | tollfree       | 
| =========== | ======== | ============ | ============ | ============ | ============================== | ==================== | ============ | ============= | =========== | ====================== | ================ | ======== | ========= | ========== | ======== | ============ | ============ | ============== | 
| 1492104140  | 4        | Silverdale   | 986          |              | 388 NW Randall Way             | Suite 201            | Silverdale   | WA            | 98383       |                        |                  |          |           |            | N/A      | 360.698.4388 | 360.698.4398 |                | 
| 1492156635  | 13       | State Office | 990          |              | 1110 Jefferson Street Southeas |                      | Olympia      | WA            | 98501       | PO Box 40970           |                  | Olympia  | WA        | 98504-0970 | 40970    | 360.725.4665 | 360.413.3482 | 1.866.482.4325 | 
| 1492156635  | 8        | Kelso        | 988          | 21           | 711 Vine Street                |                      | Kelso        | WA            | 98626       |                        |                  |          | WA        |            | S8-6     | 360.501.2645 | 360.577.2382 |                | 
| 1492156635  | 20       | Tri-Cities   | 993          |              | 3918 West Court Street         |                      | Pasco        | WA            | 99301       |                        |                  |          | WA        |            | N/A      | 509.544.5705 | 509.544.5792 | 1.800.731.3536 | 
| 1492156635  | 10       | Everett      | 996          |              | 1000 SE Everett Mall Way       | Suite 204            | Everett      | WA            | 98208       |                        |                  |          | WA        |            | TB-98    | 425.740.6871 | 425.514.5465 |                | 
| 1492156635  | 1        | Tacoma       | 985          |              | 1949 South State Street        |                      | Tacoma       | WA            | 98405       |                        |                  |          | WA        |            | WT-14    | 253.983.6400 | 253.597.3640 |                | 
| 1492156635  | 2        | Port Angeles | 986          | 4            | 201 West First Street, Suite 2 |                      | Port Angeles | WA            | 98362       |                        |                  |          | WA        |            | N/A      | 360.565.2272 | 360.417.1440 |                | 
| 1492156635  | 6        | Aberdeen     | 987          | 7            | 415 West Wishkah, Suite 2C     |                      | Aberdeen     | WA            | 98520       |                        |                  |          | WA        |            | W14-4    | 360.537.4312 | 360.533.9236 |                | 
| 1492156635  | 12       | Yakima       | 994          |              | 111 South Second Avenue        |                      | Yakima       | WA            | 98902       | 33 South Second Avenue |                  | Yakima   | WA        | 98902      | N/A      | 509.834.6839 | 509.834.6850 |                | 
| 1492156635  | 7        | Olympia      | 987          |              | 505 Union Avenue, Suite 200    |                      | Olympia      | WA            | 98501       | PO Box 40972           |                  | Olympia  | WA        | 98504-0972 | 40972    | 360.407.1992 | 360.407.1990 |                | 
```