# Recycled Commodities and Waste Streams: Beginning 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recycled-commodities-and-waste-streams-beginning-2008) |
| Metadata | [Link](https://data.ny.gov/api/views/cqfk-4aw6) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cqfk-4aw6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cqfk-4aw6/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cqfk-4aw6 |
| Name | Recycled Commodities and Waste Streams: Beginning 2008 |
| Attribution | NYS Office of General Services |
| Category | Energy & Environment |
| Tags | recycle; recycling; 3r?s; solid waste management program; rpm&f; real property management and facilities; waste stream reduction |
| Created | 2015-12-18T19:06:26Z |
| Publication Date | 2016-01-25T20:48:44Z |

## Description

Tonnage of recycled commodities by commodity and fiscal year for Office of General Services (OGS) operated facilities; tonnage of recycled commodities by Region; percentage of waste stream reduction.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | fiscal_year | Fiscal Year | text      | text        |
| Yes      | series tag     | region      | Region      | text      | text        |
| Yes      | series tag     | type        | Type        | text      | text        |
| Yes      | numeric metric | amount      | Amount      | number    | number      |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cqfk-4aw6 d:2008-01-01T00:00:00.000Z t:region=Statewide t:fiscal_year=2008-2009 t:type="Batteries Recycled, Tons" m:amount=2

series e:cqfk-4aw6 d:2008-01-01T00:00:00.000Z t:region=Statewide t:fiscal_year=2009-2010 t:type="Batteries Recycled, Tons" m:amount=3

series e:cqfk-4aw6 d:2008-01-01T00:00:00.000Z t:region=Statewide t:fiscal_year=2010-2011 t:type="Batteries Recycled, Tons" m:amount=4
```

## Meta Commands

```ls
metric m:amount p:double l:Amount d:"Quantity of the type specified; units given as part of ?Type? name" t:dataTypeName=number

entity e:cqfk-4aw6 l:"Recycled Commodities and Waste Streams: Beginning 2008" t:attribution="NYS Office of General Services" t:url=https://data.ny.gov/api/views/cqfk-4aw6

property e:cqfk-4aw6 t:meta.view v:id=cqfk-4aw6 v:category="Energy & Environment" v:attributionLink=http://ogs.ny.gov v:averageRating=0 v:name="Recycled Commodities and Waste Streams: Beginning 2008" v:attribution="NYS Office of General Services"

property e:cqfk-4aw6 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cqfk-4aw6 t:meta.view.tableauthor v:id=28jg-4c4u v:screenName="Diane L. Boyd" v:roleName=administrator v:displayName="Diane L. Boyd"
```

## Top Records

```ls
| fiscal_year | region    | type                               | amount | 
| =========== | ========= | ================================== | ====== | 
| 2008-2009   | Statewide | Batteries Recycled, Tons           | 2      | 
| 2009-2010   | Statewide | Batteries Recycled, Tons           | 3      | 
| 2010-2011   | Statewide | Batteries Recycled, Tons           | 4      | 
| 2011-2012   | Statewide | Batteries Recycled, Tons           | 8      | 
| 2012-2013   | Statewide | Batteries Recycled, Tons           | 1      | 
| 2013-2014   | Statewide | Batteries Recycled, Tons           | 4      | 
| 2014-2015   | Statewide | Batteries Recycled, Tons           | 2      | 
| 2008-2009   | Statewide | Carpet Recycling, Tons             | 9      | 
| 2008-2009   | Statewide | Comingled Materials Recycled, Tons | 21     | 
| 2009-2010   | Statewide | Comingled Materials Recycled, Tons | 14     | 
```