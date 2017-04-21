# Title V Emissions Inventory: Beginning 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/title-v-emissions-inventory-beginning-2010) |
| Metadata | [Link](https://data.ny.gov/api/views/4ry5-tfin) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/4ry5-tfin/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/4ry5-tfin/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 4ry5-tfin |
| Name | Title V Emissions Inventory: Beginning 2010 |
| Attribution | Environmental Conservation, Department of |
| Category | Energy & Environment |
| Tags | title v, emissions, voc, nox, co, co2, haps, pm, pm10, pm2.5, so2 |
| Created | 2016-05-17T16:41:25Z |
| Publication Date | 2016-06-23T19:40:27Z |

## Description

A list by county of New York State Title V facilities and the air pollutants emitted from those facilities.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name                | Data Type | Render Type |
| ======== | ============== | ============= | =================== | ========= | =========== |
| Yes      | time           | year          | Year                | number    | number      |
| Yes      | series tag     | county        | County              | text      | text        |
| Yes      | series tag     | municipality  | Municipality        | text      | text        |
| Yes      | series tag     | dec_id        | DEC ID              | text      | number      |
| Yes      | series tag     | facility_name | Facility Name       | text      | text        |
| Yes      | series tag     | sic_code      | SIC Code            | text      | number      |
| Yes      | numeric metric | voc           | VOC (tons)          | number    | number      |
| Yes      | numeric metric | nox           | NOx (tons)          | number    | number      |
| No       |                | co            | CO (tons)           | number    | number      |
| Yes      | numeric metric | co2           | CO2 (tons)          | number    | number      |
| Yes      | numeric metric | particulates  | Particulates (tons) | number    | number      |
| Yes      | numeric metric | pm10          | PM10 (tons)         | number    | number      |
| Yes      | numeric metric | pm2_5         | PM2.5 (tons)        | number    | number      |
| Yes      | numeric metric | haps          | HAPS (tons)         | number    | number      |
| Yes      | numeric metric | so2           | SO2 (tons)          | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = co
```

## Data Commands

```ls
series e:4ry5-tfin d:2010-01-01T00:00:00.000Z t:facility_name="CARBO INDUSTRIES PROPERTY" t:county=Nassau t:sic_code=5171 t:dec_id=1282001085 t:municipality=Hempstead m:so2=0 m:nox=0 m:pm10=0 m:voc=22.81 m:pm2_5=0 m:particulates=0 m:haps=0

series e:4ry5-tfin d:2010-01-01T00:00:00.000Z t:facility_name="AVA LANDFILL" t:county=Oneida t:sic_code=4953 t:dec_id=6302400009 t:municipality=Ava m:so2=6.06 m:nox=1.96 m:pm10=5.78 m:voc=4.21 m:pm2_5=0 m:particulates=5.78 m:haps=0.23

series e:4ry5-tfin d:2010-01-01T00:00:00.000Z t:facility_name="TAM CERAMICS LLC" t:county=Niagara t:sic_code=3295 t:dec_id=9293000032 t:municipality=Niagara m:so2=0 m:nox=0 m:pm10=0 m:voc=0 m:pm2_5=0 m:particulates=0 m:haps=0
```

## Meta Commands

```ls
metric m:voc p:float l:"VOC (tons)" d:"Volatile organic compounds (VOC) means any compound of carbon, excluding carbon monoxide, carbon dioxide, carbonic acid, metallic carbides or carbonates and ammonium carbonate, which participates in atmospheric photochemical reactions, except those designated by EPA as having negligible photochemical reactivity. Annual volatile organic compound emissions at the facility measured in tons." t:dataTypeName=number

metric m:nox p:float l:"NOx (tons)" d:"Nitrogen oxides (NOx) is the term used to describe the sum of nitric oxide (NO), nitrogen dioxide (NO2), and other oxides of nitrogen. Most airborne NOX comes from combustion-related emissions sources of human origin, primarily fossil fuel combustion in electric utilities, high-temperature operations at other industrial sources, and operation of motor vehicles. Annual nitrogen oxide emissions at the facility measured in tons." t:dataTypeName=number

metric m:co2 p:double l:"CO2 (tons)" d:"Carbon dioxide is a naturally occurring gas, and also a by-product of burning fossil fuels and biomass, as well as land-use changes and other industrial processes. It is the principal human caused greenhouse gas that affects the Earth's radiative balance. Annual carbon dioxide emissions at the facility measured in tons." t:dataTypeName=number

metric m:particulates p:float l:"Particulates (tons)" d:"Particulates are tiny particles or liquid droplets suspended in the air that can contain a variety of chemical components. Larger particles are visible as smoke or dust and settle out relatively rapidly. The tiniest particles can be suspended in the air for long periods of time and are the most harmful to human health because they can penetrate deep into the lungs. Some particles are directly emitted into the air. They come from a variety of sources such as cars, trucks, buses, factories, construction sites, tilled fields, unpaved roads, stone crushing, and wood burning. Other particles are formed in the atmosphere by chemical reactions. Annual particulate matter (total) emissions at the facility measured in tons." t:dataTypeName=number

metric m:pm10 p:float l:"PM10 (tons)" d:"Particles that are less than 10 microns in diameter. Most particulate matter is PM10. Annual particulate matter (less than 10 microns in diameter) emissions at the facility measured in tons." t:dataTypeName=number

metric m:pm2_5 p:float l:"PM2.5 (tons)" d:"Particles that are less than 2.5 microns in diameter. These particles are often referred to as ""PM fine."" PM fine particles are so small that they are not typically visible to the naked eye. In the atmosphere, however, they are significant contributors to haze. Smaller particles are generally more harmful to human health because they can penetrate more deeply into the lungs than larger particles. Annual particulate matter (less than 2.5 microns in diameter) emissions at the facility measured in tons." t:dataTypeName=number

metric m:haps p:float l:"HAPS (tons)" d:"Hazardous air pollutants, also known as toxic air pollutants or air toxics, are those pollutants that are known or suspected to cause cancer or other serious health effects, such as reproductive effects or birth defects, or adverse environmental effects. EPA is working with state, local, and tribal governments to reduce air emissions of 187 toxic air pollutants to the environment. Examples of toxic air pollutants include benzene, which is found in gasoline; perchloroethylene, which is emitted from some dry cleaning facilities; and methylene chloride, which is used as a solvent and paint stripper by a number of industries. Examples of other listed air toxics include dioxin, asbestos, toluene, and metals such as cadmium, mercury, chromium, and lead compounds. Annual hazardous air pollutants (HAPs) emissions at the facility measured in tons." t:dataTypeName=number

metric m:so2 p:float l:"SO2 (tons)" d:"Sulfur dioxide isone of a group of highly reactive gasses known as ?oxides of sulfur.? The largest sources of SO2 emissions are from fossil fuel combustion at power plants (73%) and other industrial facilities (20%). Smaller sources of SO2 emissions include industrial processes such as extracting metal from ore, and the burning of high sulfur containing fuels by locomotives, large ships, and non-road equipment. SO2 is linked with a number of adverse effects on the respiratory system. Annual sulfur dioxide emissions at the facility measured in tons." t:dataTypeName=number

entity e:4ry5-tfin l:"Title V Emissions Inventory: Beginning 2010" t:attribution="Environmental Conservation, Department of" t:url=https://data.ny.gov/api/views/4ry5-tfin

property e:4ry5-tfin t:meta.view v:id=4ry5-tfin v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/chemical/68524.html v:averageRating=0 v:name="Title V Emissions Inventory: Beginning 2010" v:attribution="Environmental Conservation, Department of"

property e:4ry5-tfin t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:4ry5-tfin t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| year | county     | municipality  | dec_id     | facility_name                                    | sic_code | voc   | nox   | co    | co2      | particulates | pm10 | pm2_5 | haps | so2   | 
| ==== | ========== | ============= | ========== | ================================================ | ======== | ===== | ===== | ===== | ======== | ============ | ==== | ===== | ==== | ===== | 
| 2010 | Nassau     | Hempstead     | 1282001085 | CARBO INDUSTRIES PROPERTY                        | 5171     | 22.81 | 0     | 0     |          | 0            | 0    | 0     | 0    | 0     | 
| 2010 | Oneida     | Ava           | 6302400009 | AVA LANDFILL                                     | 4953     | 4.21  | 1.96  | 10.67 |          | 5.78         | 5.78 | 0     | 0.23 | 6.06  | 
| 2010 | Niagara    | Niagara       | 9293000032 | TAM CERAMICS LLC                                 | 3295     | 0     | 0     | 0     |          | 0            | 0    | 0     | 0    | 0     | 
| 2011 | Oneida     | Ava           | 6302400009 | AVA LANDFILL                                     | 4953     | 6.4   | 5.62  | 29.55 | 26601.04 | 1.72         | 1.72 | 0.01  | 0.69 | 18.65 | 
| 2012 | Oneida     | Ava           | 6302400009 | AVA LANDFILL                                     | 4953     | 6.95  | 6.08  | 32.69 | 29448.39 | 1.5          | 1.5  | 0     | 0.74 | 19.7  | 
| 2012 | Oneida     | Ava           | 6302400025 | WM ONEIDA HERKIMER RENEWABLE ENERGY FACILITY     | 4911     | 0.06  | 8.97  | 33.62 | 9932.26  | 2.07         | 2.07 | 0     | 0    | 9.21  | 
| 2013 | Oneida     | Ava           | 6302400009 | AVA LANDFILL                                     | 4953     | 5.84  | 2.97  | 14.78 | 15689.41 | 3.24         | 3.24 | 0.01  | 0.33 | 8.44  | 
| 2013 | Oneida     | Ava           | 6302400025 | WM ONEIDA HERKIMER RENEWABLE ENERGY FACILITY     | 4911     | 0.16  | 27.89 | 99.16 | 23015.94 | 4.79         | 4.79 | 0     | 0.78 | 21.34 | 
| 2010 | Queens     | Queens (6306) | 2630600067 | ST JOHNS UNIVERSITY                              | 8221     | 0.76  | 13.9  | 11.3  |          | 1.05         | 1.05 | 1.04  | 0    | 0.62  | 
| 2010 | Chautauqua | French Creek  | 9064200016 | TENNESSEE GAS PIPELINE CO COMPRESSOR STATION 224 | 4922     | 16.98 | 33.3  | 57.99 |          | 0.13         | 0.13 | 0.12  | 0    | 0.09  | 
```