# DTS/DFM Sign Inventory - Fort St. to River St. as of: 2014-08-07

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dts-dfm-sign-inventory-fort-st-to-river-st-as-of-2014-08-07-392e0) |
| Metadata | [Link](https://data.honolulu.gov/api/views/8hqv-tn8i) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/8hqv-tn8i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/8hqv-tn8i/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | 8hqv-tn8i |
| Name | DTS/DFM Sign Inventory - Fort St. to River St. as of: 2014-08-07 |
| Category | Transportation |
| Created | 2015-05-15T21:30:51Z |
| Publication Date | 2015-05-15T21:44:53Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | series tag     | point_id   | POINT_ID   | text          | number        |
| Yes      | series tag     | pole_type  | POLE_TYPE  | text          | text          |
| Yes      | numeric metric | numplates  | NUMPLATES  | number        | number        |
| Yes      | series tag     | signmsg1   | SIGNMSG1   | text          | text          |
| Yes      | series tag     | signmsg2   | SIGNMSG2   | text          | text          |
| Yes      | series tag     | signmsg3   | SIGNMSG3   | text          | text          |
| Yes      | series tag     | signmsg4   | SIGNMSG4   | text          | text          |
| Yes      | series tag     | signmsg5   | SIGNMSG5   | text          | text          |
| Yes      | series tag     | signmsg6   | SIGNMSG6   | text          | text          |
| Yes      | numeric metric | offset     | OFFSET     | number        | number        |
| Yes      | series tag     | pic        | PIC        | text          | text          |
| Yes      | time           | dateinven  | DATEINVEN  | calendar_date | calendar_date |
| Yes      | series tag     | material1  | MATERIAL1  | text          | text          |
| Yes      | series tag     | material2  | MATERIAL2  | text          | text          |
| Yes      | series tag     | material3  | MATERIAL3  | text          | text          |
| Yes      | series tag     | material4  | MATERIAL4  | text          | text          |
| Yes      | series tag     | material5  | MATERIAL5  | text          | text          |
| Yes      | series tag     | material6  | MATERIAL6  | text          | text          |
| Yes      | series tag     | inventory  | INVENTORY  | text          | text          |
| No       |                | xcoord     | XCOORD     | number        | number        |
| No       |                | ycoord     | YCOORD     | number        | number        |
| Yes      | series tag     | daterepl1  | DATEREPL1  | text          | text          |
| Yes      | series tag     | daterepl2  | DATEREPL2  | text          | text          |
| Yes      | series tag     | daterepl3  | DATEREPL3  | text          | text          |
| Yes      | series tag     | daterepl4  | DATEREPL4  | text          | text          |
| Yes      | series tag     | daterepl5  | DATEREPL5  | text          | text          |
| Yes      | series tag     | daterepl6  | DATEREPL6  | text          | text          |
| Yes      | numeric metric | dateinstl1 | DATEINSTL1 | number        | number        |
| Yes      | numeric metric | dateinstl2 | DATEINSTL2 | number        | number        |
| Yes      | numeric metric | dateinstl3 | DATEINSTL3 | number        | number        |
| Yes      | numeric metric | dateinstl4 | DATEINSTL4 | number        | number        |
| Yes      | numeric metric | dateinstl5 | DATEINSTL5 | number        | number        |
| Yes      | numeric metric | dateinstl6 | DATEINSTL6 | number        | number        |
| Yes      | numeric metric | height_ft  | Height_ft  | number        | number        |
| Yes      | numeric metric | height_in  | Height_In  | number        | number        |
| Yes      | series tag     | pic2       | PIC2       | text          | text          |
| Yes      | series tag     | signclr1   | SIGNCLR1   | text          | text          |
| Yes      | series tag     | signclr2   | SIGNCLR2   | text          | text          |
| Yes      | series tag     | signclr3   | SIGNCLR3   | text          | text          |
| Yes      | series tag     | signclr4   | SIGNCLR4   | text          | text          |
| Yes      | series tag     | signclr5   | SIGNCLR5   | text          | text          |
| Yes      | series tag     | signclr6   | SIGNCLR6   | text          | text          |
| Yes      | numeric metric | horiz_gap  | Horiz_Gap  | number        | number        |
| Yes      | series tag     | comments   | Comments   | text          | text          |
```

## Time Field

```ls
Value = dateinven
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = xcoord,ycoord
```

## Data Commands

```ls
series e:8hqv-tn8i d:2011-12-15T00:00:00.000Z t:inventory=RTD_GPS t:pic=.\CCH_Signs\Images\2.jpg t:pole_type="Traffic Signals w/Pedestrian Signals" t:signmsg1="SPEED LIMIT [25] (R2-1)" t:point_id=2 t:signclr1="Black on White" m:numplates=1 m:horiz_gap=0 m:height_in=8 m:offset=0 m:height_ft=6

series e:8hqv-tn8i d:2011-12-15T00:00:00.000Z t:inventory=Adjusted t:pic=.\CCH_Signs\Images\3.jpg t:pole_type="Street Light Standard" t:signmsg1="1 HR PARKING [7 AM TO 3:30 PM MON THRU FRI, 7 AM TO 6PM SATURDAYS EXCEPT SUNDAYS STATE HOLIDAYS] (R7-108)" t:signclr2="Red on White" t:comments="GPS point visually adjusted to aerial image" t:point_id=3 t:signmsg2="TOW-AWAY ZONE [3:30 PM TO 5:30 PM EXCEPT SATURDAYS SUNDAYS AND STATE HOLIDAYS] (R9)" t:signclr1="Green on White" m:numplates=2 m:horiz_gap=0 m:height_in=2 m:offset=0 m:height_ft=7

series e:8hqv-tn8i d:2011-12-15T00:00:00.000Z t:inventory=Adjusted t:material2="Diamond Grade" t:pic=.\CCH_Signs\Images\4.jpg t:pole_type=Round t:signmsg1="FREIGHT LOADING ZONE - [7:00 AM TO 3:30 PM MON THRU FRI, 7:00 AM TO 4:00 PM SATURDAYS EXCEPT SUNDAYS AND STATE HOLIDAYS] (R9)" t:signclr2="Red on White" t:comments="GPS point visually adjusted to aerial image" t:point_id=4 t:signmsg2="TOW-AWAY ZONE [3:30 PM TO 5:30 PM EXCEPT SATURDAYS SUNDAYS AND STATE HOLIDAYS] (R9)" t:signclr1="Red on White" m:numplates=2 m:horiz_gap=0 m:dateinstl2=7012008 m:height_in=2.5 m:offset=0 m:height_ft=7
```

## Meta Commands

```ls
metric m:numplates p:integer l:NUMPLATES t:dataTypeName=number

metric m:offset p:integer l:OFFSET t:dataTypeName=number

metric m:dateinstl1 p:integer l:DATEINSTL1 t:dataTypeName=number

metric m:dateinstl2 p:integer l:DATEINSTL2 t:dataTypeName=number

metric m:dateinstl3 p:integer l:DATEINSTL3 t:dataTypeName=number

metric m:dateinstl4 p:integer l:DATEINSTL4 t:dataTypeName=number

metric m:dateinstl5 p:integer l:DATEINSTL5 t:dataTypeName=number

metric m:dateinstl6 p:integer l:DATEINSTL6 t:dataTypeName=number

metric m:height_ft p:integer l:Height_ft t:dataTypeName=number

metric m:height_in p:float l:Height_In t:dataTypeName=number

metric m:horiz_gap p:integer l:Horiz_Gap t:dataTypeName=number

entity e:8hqv-tn8i l:"DTS/DFM Sign Inventory - Fort St. to River St.  as of: 2014-08-07" t:url=https://data.honolulu.gov/api/views/8hqv-tn8i

property e:8hqv-tn8i t:meta.view v:id=8hqv-tn8i v:category=Transportation v:averageRating=0 v:name="DTS/DFM Sign Inventory - Fort St. to River St.  as of: 2014-08-07"

property e:8hqv-tn8i t:meta.view.owner v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:displayName="Karl Sueyoshi"

property e:8hqv-tn8i t:meta.view.tableauthor v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"
```