# SDOT Road Temperature Stations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-road-temperature-stations-2afd8) |
| Metadata | [Link](https://data.seattle.gov/api/views/wd5q-q35v) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/wd5q-q35v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/wd5q-q35v/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | wd5q-q35v |
| Name | SDOT Road Temperature Stations |
| Tags | storm response |
| Created | 2016-12-08T22:55:45Z |
| Publication Date | 2016-12-14T16:05:31Z |

## Description

Displays the location and data being collected from road temperature stations in the City of Seattle. This data shows the road temperature and the air temperature at the location of the sensor and maintains records of temperature data collected up to 2 hours beforehand.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | objectid          | OBJECTID          | text      | number      |
| Yes      | series tag     | rwis_station_name | RWIS_STATION_NAME | text      | text        |
| Yes      | series tag     | rwis_display_name | RWIS_DISPLAY_NAME | text      | text        |
| Yes      | time           | rwis_datetime     | RWIS_DATETIME     | text      | text        |
| Yes      | numeric metric | rstemp_current    | RSTEMP_CURRENT    | number    | number      |
| Yes      | numeric metric | airtemp_current   | AIRTEMP_CURRENT   | number    | number      |
| Yes      | numeric metric | rstemp_15min      | RSTEMP_15MIN      | number    | number      |
| Yes      | numeric metric | airtemp_15min     | AIRTEMP_15MIN     | number    | number      |
| Yes      | numeric metric | rstemp_30min      | RSTEMP_30MIN      | number    | number      |
| Yes      | numeric metric | airtemp_30min     | AIRTEMP_30MIN     | number    | number      |
| Yes      | numeric metric | rstemp_45min      | RSTEMP_45MIN      | number    | number      |
| Yes      | numeric metric | airtemp_45min     | AIRTEMP_45MIN     | number    | number      |
| Yes      | numeric metric | rstemp_60min      | RSTEMP_60MIN      | number    | number      |
| Yes      | numeric metric | airtemp_60min     | AIRTEMP_60MIN     | number    | number      |
| Yes      | numeric metric | rstemp_75min      | RSTEMP_75MIN      | number    | number      |
| Yes      | numeric metric | airtemp_75min     | AIRTEMP_75MIN     | number    | number      |
| Yes      | numeric metric | rstemp_90min      | RSTEMP_90MIN      | number    | number      |
| Yes      | numeric metric | airtemp_90min     | AIRTEMP_90MIN     | number    | number      |
| Yes      | numeric metric | rstemp_105min     | RSTEMP_105MIN     | number    | number      |
| Yes      | numeric metric | airtemp_105min    | AIRTEMP_105MIN    | number    | number      |
| Yes      | numeric metric | rstemp_120min     | RSTEMP_120MIN     | number    | number      |
| Yes      | numeric metric | airtemp_120min    | AIRTEMP_120MIN    | number    | number      |
```

## Time Field

```ls
Value = rwis_datetime
Format & Zone = yyyy-MM-dd HH:mm:ss
```

## Data Commands

```ls
series e:wd5q-q35v d:2017-09-25T00:20:00.000Z t:rwis_display_name="Alaskan Way Viaduct at King St" t:objectid=1 t:rwis_station_name=AlaskanWayViaduct_KingSt m:rstemp_120min=65.15 m:rstemp_90min=64.39 m:rstemp_current=63.120000000000005 m:rstemp_15min=63.22 m:airtemp_current=61.7 m:airtemp_90min=62.02 m:airtemp_30min=61.75 m:rstemp_60min=63.71 m:airtemp_75min=61.93 m:rstemp_45min=63.480000000000004 m:airtemp_120min=62.14 m:airtemp_15min=61.72 m:rstemp_30min=63.32 m:airtemp_60min=61.84 m:airtemp_105min=62.1 m:rstemp_105min=64.8 m:rstemp_75min=64.01 m:airtemp_45min=61.79

series e:wd5q-q35v d:2017-09-25T00:20:00.000Z t:rwis_display_name="Harbor Ave Upper North Bridge" t:objectid=2 t:rwis_station_name=HarborAveUpperNorthBridge m:rstemp_120min=67.39 m:rstemp_90min=66.61 m:rstemp_current=64.87 m:rstemp_15min=65.04 m:airtemp_current=58.75 m:airtemp_90min=59.28 m:airtemp_30min=58.83 m:rstemp_60min=65.92 m:airtemp_75min=59.31 m:rstemp_45min=65.58 m:airtemp_120min=60.34 m:airtemp_15min=58.74 m:rstemp_30min=65.26 m:airtemp_60min=59.45 m:airtemp_105min=60.13 m:rstemp_105min=67.02 m:rstemp_75min=66.25 m:airtemp_45min=58.94

series e:wd5q-q35v d:2017-09-25T00:20:00.000Z t:rwis_display_name="Spokane Swing Bridge" t:objectid=3 t:rwis_station_name=SpokaneSwingBridge m:rstemp_120min=60.82 m:rstemp_90min=60.64 m:rstemp_current=60.25 m:rstemp_15min=60.28 m:airtemp_current=64.52 m:airtemp_90min=64.75 m:airtemp_30min=64.7 m:rstemp_60min=60.46 m:airtemp_75min=64.76 m:rstemp_45min=60.370000000000005 m:airtemp_120min=65.1 m:airtemp_15min=64.56 m:rstemp_30min=60.29 m:airtemp_60min=64.79 m:airtemp_105min=64.76 m:rstemp_105min=60.730000000000004 m:rstemp_75min=60.56 m:airtemp_45min=64.76
```

## Meta Commands

```ls
metric m:rstemp_current p:float l:RSTEMP_CURRENT d:RSTEMP_CURRENT t:dataTypeName=number

metric m:airtemp_current p:float l:AIRTEMP_CURRENT d:AIRTEMP_CURRENT t:dataTypeName=number

metric m:rstemp_15min p:float l:RSTEMP_15MIN d:RSTEMP_15MIN t:dataTypeName=number

metric m:airtemp_15min p:float l:AIRTEMP_15MIN d:AIRTEMP_15MIN t:dataTypeName=number

metric m:rstemp_30min p:float l:RSTEMP_30MIN d:RSTEMP_30MIN t:dataTypeName=number

metric m:airtemp_30min p:decimal l:AIRTEMP_30MIN d:AIRTEMP_30MIN t:dataTypeName=number

metric m:rstemp_45min p:float l:RSTEMP_45MIN d:RSTEMP_45MIN t:dataTypeName=number

metric m:airtemp_45min p:decimal l:AIRTEMP_45MIN d:AIRTEMP_45MIN t:dataTypeName=number

metric m:rstemp_60min p:float l:RSTEMP_60MIN d:RSTEMP_60MIN t:dataTypeName=number

metric m:airtemp_60min p:decimal l:AIRTEMP_60MIN d:AIRTEMP_60MIN t:dataTypeName=number

metric m:rstemp_75min p:float l:RSTEMP_75MIN d:RSTEMP_75MIN t:dataTypeName=number

metric m:airtemp_75min p:float l:AIRTEMP_75MIN d:AIRTEMP_75MIN t:dataTypeName=number

metric m:rstemp_90min p:float l:RSTEMP_90MIN d:RSTEMP_90MIN t:dataTypeName=number

metric m:airtemp_90min p:float l:AIRTEMP_90MIN d:AIRTEMP_90MIN t:dataTypeName=number

metric m:rstemp_105min p:decimal l:RSTEMP_105MIN d:RSTEMP_105MIN t:dataTypeName=number

metric m:airtemp_105min p:decimal l:AIRTEMP_105MIN d:AIRTEMP_105MIN t:dataTypeName=number

metric m:rstemp_120min p:float l:RSTEMP_120MIN d:RSTEMP_120MIN t:dataTypeName=number

metric m:airtemp_120min p:float l:AIRTEMP_120MIN d:AIRTEMP_120MIN t:dataTypeName=number

entity e:wd5q-q35v l:"SDOT Road Temperature Stations" t:url=https://data.seattle.gov/api/views/wd5q-q35v

property e:wd5q-q35v t:meta.view d:2017-09-25T07:29:41.811Z v:averageRating=0 v:name="SDOT Road Temperature Stations" v:id=wd5q-q35v

property e:wd5q-q35v t:meta.view.owner d:2017-09-25T07:29:41.811Z v:displayName="SDOT GIS" v:lastNotificationSeenAt=1504648993 v:id=geh9-fb2x v:screenName="SDOT GIS"

property e:wd5q-q35v t:meta.view.tableauthor d:2017-09-25T07:29:41.811Z v:displayName="SDOT GIS" v:lastNotificationSeenAt=1504648993 v:roleName=publisher v:id=geh9-fb2x v:screenName="SDOT GIS"
```

## Top Records

```ls
| objectid | rwis_station_name         | rwis_display_name              | rwis_datetime       | rstemp_current                                    | airtemp_current                                    | rstemp_15min                                      | airtemp_15min                                      | rstemp_30min                                       | airtemp_30min                                      | rstemp_45min                                      | airtemp_45min                                      | rstemp_60min                                       | airtemp_60min                                      | rstemp_75min                                      | airtemp_75min                                      | rstemp_90min                                      | airtemp_90min                                      | rstemp_105min                                     | airtemp_105min                                     | rstemp_120min                                      | airtemp_120min                                    | 
| ======== | ========================= | ============================== | =================== | ================================================= | ================================================== | ================================================= | ================================================== | ================================================== | ================================================== | ================================================= | ================================================== | ================================================== | ================================================== | ================================================= | ================================================== | ================================================= | ================================================== | ================================================= | ================================================== | ================================================== | ================================================= | 
| 1        | AlaskanWayViaduct_KingSt  | Alaskan Way Viaduct at King St | 2017-09-25 00:20:00 | 63.1200000000000045474735088646411895751953125    | 61.7000000000000028421709430404007434844970703125  | 63.219999999999998863131622783839702606201171875  | 61.719999999999998863131622783839702606201171875   | 63.32000000000000028421709430404007434844970703125 | 61.75                                              | 63.4800000000000039790393202565610408782958984375 | 61.78999999999999914734871708787977695465087890625 | 63.71000000000000085265128291212022304534912109375 | 61.840000000000003410605131648480892181396484375   | 64.0100000000000051159076974727213382720947265625 | 61.92999999999999971578290569595992565155029296875 | 64.3900000000000005684341886080801486968994140625 | 62.02000000000000312638803734444081783294677734375 | 64.7999999999999971578290569595992565155029296875 | 62.10000000000000142108547152020037174224853515625 | 65.150000000000005684341886080801486968994140625   | 62.1400000000000005684341886080801486968994140625 | 
| 2        | HarborAveUpperNorthBridge | Harbor Ave Upper North Bridge  | 2017-09-25 00:20:00 | 64.8700000000000045474735088646411895751953125    | 58.75                                              | 65.0400000000000062527760746888816356658935546875 | 58.74000000000000198951966012828052043914794921875 | 65.2600000000000051159076974727213382720947265625  | 58.8299999999999982946974341757595539093017578125  | 65.5799999999999982946974341757595539093017578125 | 58.93999999999999772626324556767940521240234375    | 65.9200000000000017053025658242404460906982421875  | 59.4500000000000028421709430404007434844970703125  | 66.25                                             | 59.31000000000000227373675443232059478759765625    | 66.6099999999999994315658113919198513031005859375 | 59.280000000000001136868377216160297393798828125   | 67.0199999999999960209606797434389591217041015625 | 60.13000000000000255795384873636066913604736328125 | 67.3900000000000005684341886080801486968994140625  | 60.340000000000003410605131648480892181396484375  | 
| 3        | SpokaneSwingBridge        | Spokane Swing Bridge           | 2017-09-25 00:20:00 | 60.25                                             | 64.5199999999999960209606797434389591217041015625  | 60.280000000000001136868377216160297393798828125  | 64.56000000000000227373675443232059478759765625    | 60.28999999999999914734871708787977695465087890625 | 64.7000000000000028421709430404007434844970703125  | 60.3700000000000045474735088646411895751953125    | 64.7600000000000051159076974727213382720947265625  | 60.46000000000000085265128291212022304534912109375 | 64.7900000000000062527760746888816356658935546875  | 60.56000000000000227373675443232059478759765625   | 64.7600000000000051159076974727213382720947265625  | 60.6400000000000005684341886080801486968994140625 | 64.75                                              | 60.7300000000000039790393202565610408782958984375 | 64.7600000000000051159076974727213382720947265625  | 60.82000000000000028421709430404007434844970703125 | 65.099999999999994315658113919198513031005859375  | 
| 4        | AlbroPlaceAirportWay      | Albro Place at Airport Way     | 2017-09-24 23:36:00 | -459.69999999999998863131622783839702606201171875 | 60.80000000000000426325641456060111522674560546875 |                                                   |                                                    |                                                    |                                                    | -459.69999999999998863131622783839702606201171875 | 60.80000000000000426325641456060111522674560546875 |                                                    |                                                    |                                                   |                                                    |                                                   |                                                    |                                                   |                                                    |                                                    |                                                   | 
| 5        | JoseRizalBridgeNorth      | Jose Rizal Bridge North        | 2017-09-25 00:20:00 | 67.3299999999999982946974341757595539093017578125 | 60.4800000000000039790393202565610408782958984375  | 67.409999999999996589394868351519107818603515625  | 60.469999999999998863131622783839702606201171875   | 67.5199999999999960209606797434389591217041015625  | 60.31000000000000227373675443232059478759765625    | 67.68000000000000682121026329696178436279296875   | 59.68999999999999772626324556767940521240234375    | 67.8700000000000045474735088646411895751953125     | 59.2300000000000039790393202565610408782958984375  | 68.1400000000000005684341886080801486968994140625 | 59.1700000000000017053025658242404460906982421875  | 68.4500000000000028421709430404007434844970703125 | 60.0799999999999982946974341757595539093017578125  | 68.75                                             | 61.2300000000000039790393202565610408782958984375  | 69                                                 | 61.469999999999998863131622783839702606201171875  | 
| 7        | RooseveltWay_NE80thSt     | Roosevelt Way at NE 80th St    | 2017-09-25 00:20:00 | 64.400000000000005684341886080801486968994140625  | 64.400000000000005684341886080801486968994140625   | 64.4899999999999948840923025272786617279052734375 | 64.4899999999999948840923025272786617279052734375  | 64.5799999999999982946974341757595539093017578125  | 64.5799999999999982946974341757595539093017578125  | 64.7300000000000039790393202565610408782958984375 | 64.7300000000000039790393202565610408782958984375  | 64.9200000000000017053025658242404460906982421875  | 64.9200000000000017053025658242404460906982421875  | 65.06000000000000227373675443232059478759765625   | 65.06000000000000227373675443232059478759765625    | 65.25                                             | 65.25                                              | 65.3799999999999954525264911353588104248046875    | 65.3799999999999954525264911353588104248046875     | 65.4800000000000039790393202565610408782958984375  | 65.4800000000000039790393202565610408782958984375 | 
| 8        | MagnoliaBridge            | Magnolia Bridge                | 2017-09-25 00:20:00 | 65.1299999999999954525264911353588104248046875    | 59.9800000000000039790393202565610408782958984375  | 65.1700000000000017053025658242404460906982421875 | 59.80000000000000426325641456060111522674560546875 | 65.2699999999999960209606797434389591217041015625  | 59.75999999999999801048033987171947956085205078125 | 65.5499999999999971578290569595992565155029296875 | 59.8299999999999982946974341757595539093017578125  | 65.8299999999999982946974341757595539093017578125  | 60.50999999999999801048033987171947956085205078125 | 65.9200000000000017053025658242404460906982421875 | 60.6400000000000005684341886080801486968994140625  | 65.969999999999998863131622783839702606201171875  | 60.60000000000000142108547152020037174224853515625 | 66.150000000000005684341886080801486968994140625  | 60.71000000000000085265128291212022304534912109375 | 66.340000000000003410605131648480892181396484375   | 60.9800000000000039790393202565610408782958984375 | 
| 9        | NE45StViaduct             | NE 45th St Viaduct             |                     |                                                   |                                                    |                                                   |                                                    |                                                    |                                                    |                                                   |                                                    |                                                    |                                                    |                                                   |                                                    |                                                   |                                                    |                                                   |                                                    |                                                    |                                                   | 
| 10       | AuroraBridge              | Aurora Bridge                  | 2017-09-25 00:20:00 | 64.9500000000000028421709430404007434844970703125 | 59.6099999999999994315658113919198513031005859375  | 65.0400000000000062527760746888816356658935546875 | 58.8900000000000005684341886080801486968994140625  | 65.150000000000005684341886080801486968994140625   | 58.090000000000003410605131648480892181396484375   | 65.3299999999999982946974341757595539093017578125 | 58.30000000000000426325641456060111522674560546875 | 65.4800000000000039790393202565610408782958984375  | 58.590000000000003410605131648480892181396484375   | 65.6400000000000005684341886080801486968994140625 | 58.719999999999998863131622783839702606201171875   | 65.81000000000000227373675443232059478759765625   | 59.53999999999999914734871708787977695465087890625 | 66.030000000000001136868377216160297393798828125  | 58.99000000000000198951966012828052043914794921875 | 66.2300000000000039790393202565610408782958984375  | 59.0799999999999982946974341757595539093017578125 | 
| 11       | 35thAveSW_SWMyrtleSt      | 35th Ave SW at SW Myrtle St    | 2017-09-25 00:20:00 | 67.43000000000000682121026329696178436279296875   | 67.43000000000000682121026329696178436279296875    | 67.4800000000000039790393202565610408782958984375 | 67.4800000000000039790393202565610408782958984375  | 67.5799999999999982946974341757595539093017578125  | 67.5799999999999982946974341757595539093017578125  | 67.68000000000000682121026329696178436279296875   | 67.68000000000000682121026329696178436279296875    | 67.7999999999999971578290569595992565155029296875  | 67.7999999999999971578290569595992565155029296875  | 67.93999999999999772626324556767940521240234375   | 67.93999999999999772626324556767940521240234375    | 68.090000000000003410605131648480892181396484375  | 68.090000000000003410605131648480892181396484375   | 68.2600000000000051159076974727213382720947265625 | 68.2600000000000051159076974727213382720947265625  | 68.4899999999999948840923025272786617279052734375  | 68.4899999999999948840923025272786617279052734375 | 
```