# City Streetlights Retrofitted with LED Technology (2012 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-streetlights-retrofitted-with-led-technology-2012-present) |
| Metadata | [Link](https://data.nola.gov/api/views/thvj-m69y) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/thvj-m69y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/thvj-m69y/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | thvj-m69y |
| Name | City Streetlights Retrofitted with LED Technology (2012 - Present) |
| Attribution | City of New Orleans |
| Category | Transportation and Infrastructure |
| Tags | resultsnola |
| Created | 2016-02-05T19:30:29Z |
| Publication Date | 2016-02-05T20:40:30Z |

## Description

This data includes city streetlights that have been retrofitted with LED technology.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | zone            | Zone            | text          | text          |
| Yes      | series tag     | workordernumber | WorkOrderNumber | text          | number        |
| Yes      | time           | completiondate  | CompletionDate  | calendar_date | calendar_date |
| No       |                | year            | Year            | number        | number        |
| No       |                | addressnumber   | AddressNumber   | text          | number        |
| Yes      | series tag     | street          | Street          | text          | text          |
| Yes      | series tag     | atorbetween     | AtOrBetween     | text          | text          |
| Yes      | series tag     | intersection    | Intersection    | text          | text          |
| Yes      | series tag     | assetid         | AssetID         | text          | text          |
| Yes      | numeric metric | numberoflights  | NumberOfLights  | number        | number        |
| Yes      | series tag     | fixturetype     | FixtureType     | text          | text          |
| Yes      | series tag     | ledtype         | LEDType         | text          | text          |
| Yes      | numeric metric | watts           | Watts           | number        | number        |
```

## Time Field

```ls
Value = completiondate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = addressnumber,year
```

## Data Commands

```ls
series e:thvj-m69y d:2013-04-16T00:00:00.000Z t:street="Elysian Fields" t:ledtype=MJ t:workordernumber=5750 t:assetid="AH152 -1" t:zone=3C t:fixturetype="LED Cooper Navion" m:numberoflights=1 m:watts=154

series e:thvj-m69y d:2013-04-16T00:00:00.000Z t:street="Elysian Fields" t:ledtype=MJ t:workordernumber=5749 t:assetid="AH153 -1" t:zone=3C t:fixturetype="LED Cooper Navion" m:numberoflights=1 m:watts=154

series e:thvj-m69y d:2013-04-16T00:00:00.000Z t:street="Elysian Fields" t:ledtype=MJ t:workordernumber=5748 t:assetid="AH155 -1" t:zone=3C t:fixturetype="LED Cooper Navion" m:numberoflights=1 m:watts=154
```

## Meta Commands

```ls
metric m:numberoflights p:integer l:NumberOfLights t:dataTypeName=number

metric m:watts p:integer l:Watts t:dataTypeName=number

entity e:thvj-m69y l:"City Streetlights Retrofitted with LED Technology (2012 - Present)" t:attribution="City of New Orleans" t:url=https://data.nola.gov/api/views/thvj-m69y

property e:thvj-m69y t:meta.view v:id=thvj-m69y v:category="Transportation and Infrastructure" v:attributionLink=http://www.nola.gov/dpw/ v:averageRating=0 v:name="City Streetlights Retrofitted with LED Technology (2012 - Present)" v:attribution="City of New Orleans"

property e:thvj-m69y t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:thvj-m69y t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:thvj-m69y t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| zone | workordernumber | completiondate      | year | addressnumber | street         | atorbetween | intersection      | assetid  | numberoflights | fixturetype       | ledtype | watts | 
| ==== | =============== | =================== | ==== | ============= | ============== | =========== | ================= | ======== | ============== | ================= | ======= | ===== | 
| 3C   | 5750            | 2013-04-16T00:00:00 | 2013 | 5411          | Elysian Fields |             |                   | AH152 -1 | 1              | LED Cooper Navion | MJ      | 154   | 
| 3C   | 5749            | 2013-04-16T00:00:00 | 2013 | 5427          | Elysian Fields |             |                   | AH153 -1 | 1              | LED Cooper Navion | MJ      | 154   | 
| 3C   | 5748            | 2013-04-16T00:00:00 | 2013 | 5530          | Elysian Fields |             |                   | AH155 -1 | 1              | LED Cooper Navion | MJ      | 154   | 
| 3C   | 5747            | 2013-04-16T00:00:00 | 2013 | 5530          | Elysian Fields |             |                   | AH156 -1 | 1              | LED Cooper Navion | MJ      | 154   | 
| 3C   | 1604            | 2012-12-28T00:00:00 | 2012 |               | Elysian Fields | @           | Rapides           | AH157-1  | 1              | LED Cooper Navion | MJ      | 154   | 
| 3C   | 1586            | 2012-12-31T00:00:00 | 2012 |               | Elysian Fields | btw         | Prentiss & Mendez | AH158 -1 | 1              | LED Cooper Navion | MJ      | 154   | 
| 3C   | 1589            | 2012-12-31T00:00:00 | 2012 |               | Elysian Fields | @           | Prentiss          | AH161 -1 | 1              | LED Cooper Navion | MJ      | 154   | 
| 3C   | 1588            | 2012-12-31T00:00:00 | 2012 | 5713          | Elysian Fields |             |                   | AH162 -1 | 1              | LED Cooper Navion | MJ      | 154   | 
| 3C   | 1587            | 2012-12-31T00:00:00 | 2012 | 5721          | Elysian Fields |             |                   | AH163 -1 | 1              | LED Cooper Navion | MJ      | 154   | 
| 3C   | 5954            | 2013-04-18T00:00:00 | 2013 |               | Elysian Fields | @           | Athis             | AH164 -1 | 1              | LED Cooper Navion | MJ      | 154   | 
```