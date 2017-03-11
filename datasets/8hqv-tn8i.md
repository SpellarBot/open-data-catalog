# DTS/DFM Sign Inventory - Fort St. to River St. as of: 2014-08-07

## Dataset

* [Dataset URL](https://data.honolulu.gov/api/views/8hqv-tn8i/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/dts-dfm-sign-inventory-fort-st-to-river-st-as-of-2014-08-07-392e0)
* Id = 8hqv-tn8i
* Name = DTS/DFM Sign Inventory - Fort St. to River St. as of: 2014-08-07
* Category = Transportation
* Created = 2015-05-15T21:30:51Z
* Publication Date = 2015-05-15T21:44:53Z
* Rows Updated = 2015-05-15T21:34:33Z

## Description



## Columns

```ls
| Name       | Field Name | Data Type     | Render Type   | Schema Type    | Included | 
| ========== | ========== | ============= | ============= | ============== | ======== | 
| POINT_ID   | point_id   | text          | number        | series tag     | Yes      | 
| POLE_TYPE  | pole_type  | text          | text          | series tag     | Yes      | 
| NUMPLATES  | numplates  | number        | number        | numeric metric | Yes      | 
| SIGNMSG1   | signmsg1   | text          | text          | series tag     | Yes      | 
| SIGNMSG2   | signmsg2   | text          | text          | series tag     | Yes      | 
| SIGNMSG3   | signmsg3   | text          | text          | series tag     | Yes      | 
| SIGNMSG4   | signmsg4   | text          | text          | series tag     | Yes      | 
| SIGNMSG5   | signmsg5   | text          | text          | series tag     | Yes      | 
| SIGNMSG6   | signmsg6   | text          | text          | series tag     | Yes      | 
| OFFSET     | offset     | number        | number        | numeric metric | Yes      | 
| PIC        | pic        | text          | text          | series tag     | Yes      | 
| DATEINVEN  | dateinven  | calendar_date | calendar_date | time           | Yes      | 
| MATERIAL1  | material1  | text          | text          | series tag     | Yes      | 
| MATERIAL2  | material2  | text          | text          | series tag     | Yes      | 
| MATERIAL3  | material3  | text          | text          | series tag     | Yes      | 
| MATERIAL4  | material4  | text          | text          | series tag     | Yes      | 
| MATERIAL5  | material5  | text          | text          | series tag     | Yes      | 
| MATERIAL6  | material6  | text          | text          | series tag     | Yes      | 
| INVENTORY  | inventory  | text          | text          | series tag     | Yes      | 
| XCOORD     | xcoord     | number        | number        | numeric metric | Yes      | 
| YCOORD     | ycoord     | number        | number        | numeric metric | Yes      | 
| DATEREPL1  | daterepl1  | text          | text          | series tag     | Yes      | 
| DATEREPL2  | daterepl2  | text          | text          | series tag     | Yes      | 
| DATEREPL3  | daterepl3  | text          | text          | series tag     | Yes      | 
| DATEREPL4  | daterepl4  | text          | text          | series tag     | Yes      | 
| DATEREPL5  | daterepl5  | text          | text          | series tag     | Yes      | 
| DATEREPL6  | daterepl6  | text          | text          | series tag     | Yes      | 
| DATEINSTL1 | dateinstl1 | number        | number        | numeric metric | Yes      | 
| DATEINSTL2 | dateinstl2 | number        | number        | numeric metric | Yes      | 
| DATEINSTL3 | dateinstl3 | number        | number        | numeric metric | Yes      | 
| DATEINSTL4 | dateinstl4 | number        | number        | numeric metric | Yes      | 
| DATEINSTL5 | dateinstl5 | number        | number        | numeric metric | Yes      | 
| DATEINSTL6 | dateinstl6 | number        | number        | numeric metric | Yes      | 
| Height_ft  | height_ft  | number        | number        | numeric metric | Yes      | 
| Height_In  | height_in  | number        | number        | numeric metric | Yes      | 
| PIC2       | pic2       | text          | text          | series tag     | Yes      | 
| SIGNCLR1   | signclr1   | text          | text          | series tag     | Yes      | 
| SIGNCLR2   | signclr2   | text          | text          | series tag     | Yes      | 
| SIGNCLR3   | signclr3   | text          | text          | series tag     | Yes      | 
| SIGNCLR4   | signclr4   | text          | text          | series tag     | Yes      | 
| SIGNCLR5   | signclr5   | text          | text          | series tag     | Yes      | 
| SIGNCLR6   | signclr6   | text          | text          | series tag     | Yes      | 
| Horiz_Gap  | horiz_gap  | number        | number        | numeric metric | Yes      | 
| Comments   | comments   | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = dateinven
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:8hqv-tn8i d:2011-12-15T00:00:00.000Z t:inventory=RTD_GPS t:pic=.\CCH_Signs\Images\2.jpg t:pole_type="Traffic Signals w/Pedestrian Signals" t:signmsg1="SPEED LIMIT [25] (R2-1)" t:point_id=2 t:signclr1="Black on White" m:ycoord=21.30965 m:xcoord=21.30965 m:numplates=1 m:horiz_gap=0 m:height_in=8 m:offset=0 m:height_ft=6

series e:8hqv-tn8i d:2011-12-15T00:00:00.000Z t:inventory=Adjusted t:pic=.\CCH_Signs\Images\3.jpg t:pole_type="Street Light Standard" t:signmsg1="1 HR PARKING [7 AM TO 3:30 PM MON THRU FRI, 7 AM TO 6PM SATURDAYS EXCEPT SUNDAYS STATE HOLIDAYS] (R7-108)" t:signclr2="Red on White" t:comments="GPS point visually adjusted to aerial image" t:point_id=3 t:signmsg2="TOW-AWAY ZONE [3:30 PM TO 5:30 PM EXCEPT SATURDAYS SUNDAYS AND STATE HOLIDAYS] (R9)" t:signclr1="Green on White" m:ycoord=21.30974 m:xcoord=21.30974 m:numplates=2 m:horiz_gap=0 m:height_in=2 m:offset=0 m:height_ft=7

series e:8hqv-tn8i d:2011-12-15T00:00:00.000Z t:inventory=Adjusted t:material2="Diamond Grade" t:pic=.\CCH_Signs\Images\4.jpg t:pole_type=Round t:signmsg1="FREIGHT LOADING ZONE - [7:00 AM TO 3:30 PM MON THRU FRI, 7:00 AM TO 4:00 PM SATURDAYS EXCEPT SUNDAYS AND STATE HOLIDAYS] (R9)" t:signclr2="Red on White" t:comments="GPS point visually adjusted to aerial image" t:point_id=4 t:signmsg2="TOW-AWAY ZONE [3:30 PM TO 5:30 PM EXCEPT SATURDAYS SUNDAYS AND STATE HOLIDAYS] (R9)" t:signclr1="Red on White" m:ycoord=21.30982 m:xcoord=21.30982 m:numplates=2 m:horiz_gap=0 m:dateinstl2=7012008 m:height_in=2.5 m:offset=0 m:height_ft=7
```

## Meta Commands

```ls
Red on White

Red on Whit*" m:ycoord=21.31087 m:xcoord=21.31087 m:numplates=1 m:horiz_gap=0 m:height_in=1 m:offset=0 m:height_ft=7

on White" m:ycoord=21.31094 m:xcoord=21.31094 m:numplates=2 m:horiz_gap=0 m:height_in=4 m:offset=0 m:height_ft=7

Black and Red

Black on White

Bl*" t:point_id=98 t:signmsg2="EXCEPT CITY BUSES AND BIKES (R5-3)" t:signclr1="Black on White

Black and Red

Black on White

Bl*" m:ycoord=21.31105 m:xcoord=21.31105 m:numplates=2 m:horiz_gap=0 m:height_in=11 m:offset=0 m:height_ft=6

metric m:numplates p:integer l:NUMPLATES t:dataTypeName=number

metric m:offset p:integer l:OFFSET t:dataTypeName=number

metric m:xcoord l:XCOORD t:dataTypeName=number

metric m:ycoord l:YCOORD t:dataTypeName=number

metric m:dateinstl1 p:integer l:DATEINSTL1 t:dataTypeName=number

metric m:dateinstl2 p:integer l:DATEINSTL2 t:dataTypeName=number

metric m:dateinstl3 p:integer l:DATEINSTL3 t:dataTypeName=number

metric m:dateinstl4 p:integer l:DATEINSTL4 t:dataTypeName=number

metric m:dateinstl5 p:integer l:DATEINSTL5 t:dataTypeName=number

metric m:dateinstl6 p:integer l:DATEINSTL6 t:dataTypeName=number

metric m:height_ft p:integer l:Height_ft t:dataTypeName=number

metric m:height_in l:Height_In t:dataTypeName=number

metric m:horiz_gap p:integer l:Horiz_Gap t:dataTypeName=number

entity e:8hqv-tn8i l:"DTS/DFM Sign Inventory - Fort St. to River St.  as of: 2014-08-07" t:url=https://data.honolulu.gov/api/views/8hqv-tn8i

property e:8hqv-tn8i t:meta.view d:2017-03-03T13:48:06.433Z v:id=8hqv-tn8i v:category=Transportation v:averageRating=0 v:name="DTS/DFM Sign Inventory - Fort St. to River St.  as of: 2014-08-07"

property e:8hqv-tn8i t:meta.view.owner d:2017-03-03T13:48:06.433Z v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"

property e:8hqv-tn8i t:meta.view.tableauthor d:2017-03-03T13:48:06.433Z v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"
```