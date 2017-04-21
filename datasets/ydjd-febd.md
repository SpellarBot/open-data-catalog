# Red Light Cameras

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/red-light-cameras-28127) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/ydjd-febd) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/ydjd-febd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/ydjd-febd/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | ydjd-febd |
| Name | Red Light Cameras |
| Attribution | Department of Transportation |
| Category | Transportation |
| Tags | transportation, red light, citation |
| Created | 2012-03-09T13:06:32Z |
| Publication Date | 2014-04-03T23:38:55Z |

## Description

Motorists who drive aggressively and exceed the posted speed limit by at least 12 miles per hour will receive $40 citations in the mail. These citations are not reported to insurance companies and no license points are assigned. Notification signs will be placed at all speed enforcement locations so that motorists will be aware that they are approaching a speed check zone. The goal of the program is to make the streets of Baltimore safer for everyone by changing aggressive driving behavior. In addition to the eight portable speed enforcement units, the city has retrofitted 50 red light camera locations with the automated speed enforcement technology.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       |             | address          | address          | text      | text        |
| Yes      | series tag  | enforcement      | enforcement      | text      | text        |
| Yes      | time        | installationdate | installationDate | date      | date        |
| Yes      | series tag  | direction        | direction        | text      | text        |
| Yes      | series tag  | street           | street           | text      | text        |
| Yes      | series tag  | block            | block            | text      | text        |
| Yes      | series tag  | crossstreet      | crossStreet      | text      | text        |
| Yes      | series tag  | intersection     | intersection     | text      | text        |
```

## Time Field

```ls
Value = installationdate
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:ydjd-febd d:2009-11-04T08:00:00.000Z t:enforcement="Caton Avenue" t:intersection="Harford Road
 & Christopher Ave" t:crossstreet="Christopher Ave" t:direction=NB t:street="Harford Road" t:block=6100 m:row_number.ydjd-febd=1

series e:ydjd-febd d:2009-10-01T07:00:00.000Z t:enforcement="Caton Avenue" t:intersection="33 rd & The Alameda" t:crossstreet="The Alameda" t:direction=EB t:street=33rd t:block=1300 m:row_number.ydjd-febd=2

series e:ydjd-febd d:2009-10-01T07:00:00.000Z t:enforcement="Charles Street" t:intersection="Almeda & 33rd St" t:crossstreet="33rd St" t:direction=SB t:street=Alameda t:block=3300 m:row_number.ydjd-febd=3
```

## Meta Commands

```ls
metric m:row_number.ydjd-febd p:long l:"Row Number"

entity e:ydjd-febd l:"Red Light Cameras" t:attribution="Department of Transportation" t:url=https://data.baltimorecity.gov/api/views/ydjd-febd

property e:ydjd-febd t:meta.view v:id=ydjd-febd v:category=Transportation v:attributionLink=http://www.baltimorecity.gov/Government/AgenciesDepartments/Transportation/SpeedMonitoringLocations.aspx v:averageRating=0 v:name="Red Light Cameras" v:attribution="Department of Transportation"

property e:ydjd-febd t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:ydjd-febd t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:ydjd-febd t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| address                            | enforcement      | installationdate | direction | street           | block | crossstreet     | intersection                       | 
| ================================== | ================ | ================ | ========= | ================ | ===== | =============== | ================================== | 
| HARFORD RD & CHRISTOPHER AVE       | Caton Avenue     | 1257321600       | NB        | Harford Road     | 6100  | Christopher Ave | Harford Road & Christopher Ave     | 
| E 33RD ST & THE ALAMEDA            | Caton Avenue     | 1254380400       | EB        | 33rd             | 1300  | The Alameda     | 33 rd & The Alameda                | 
| THE ALAMEDA & E 33RD ST            | Charles Street   | 1254380400       | SB        | Alameda          | 3300  | 33rd St         | Almeda & 33rd St                   | 
| S CATON AVE & BENSON AVE           | Cold Spring Lane | 1256886000       | NB        | Caton Ave        | 1100  | Benson Ave      | Caton Ave & Benson Ave             | 
| S CATON AVE & BENSON AVE           | Cold Spring Lane | 1265184000       | SB        | Caton Ave        | 1000  | Benson Ave      | Caton Ave & Benson Ave             | 
| N CHARLES ST & E LAKE AVE          | Cold Spring Lane | 1274338800       | NB        | Charles St.      | 5800  | Lake Ave        | Charles St. & Lake Ave             | 
| E COLD SPRING LN & HILLEN RD       | Cold Spring Lane | 1269241200       | WB        | Cold Spring Lane | 1700  | Hillen Road     | Cold Spring Lane & Hillen Road     | 
| W COLD SPRING LN & TAMARIND RD     | Eastern Avenue   | 1257148800       | EB        | Cold Spring Lane | 2200  | Tamarind        | Cold Spring Lane & Tamarind        | 
| W COLD SPRING LN & ROLAND AVE      | Edmondson Avenue | 1257321600       | EB        | Cold Spring Lane | 500   | Roland Ave      | Cold Spring Lane & Roland Ave      | 
| E COLD SPRING LN & LOCH RAVEN BLVD | Edmondson Avenue | 1267689600       | WB        | Cold Spring Lane | 1500  | Loch Raven Blvd | Cold Spring Lane & Loch Raven Blvd | 
```