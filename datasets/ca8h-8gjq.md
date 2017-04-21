# Index Crimes by County and Agency: Beginning 1990

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/index-crimes-by-county-and-agency-beginning-1990) |
| Metadata | [Link](https://data.ny.gov/api/views/ca8h-8gjq) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ca8h-8gjq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ca8h-8gjq/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ca8h-8gjq |
| Name | Index Crimes by County and Agency: Beginning 1990 |
| Attribution | New York State Division of Criminal Justice Services |
| Category | Public Safety |
| Tags | index crime, public safety, ucr |
| Created | 2013-02-15T20:06:23Z |
| Publication Date | 2016-09-27T22:07:15Z |

## Description

The Division of Criminal Justice Services (DCJS) collects crime reports from more than 500 New York State police and sheriffs' departments. DCJS compiles these reports as New York's official crime statistics and submits them to the FBI under the National Uniform Crime Reporting (UCR) Program. UCR uses standard offense definitions to count crime in localities across America regardless of variations in crime laws from state to state. In New York State, law enforcement agencies use the UCR system to report their monthly crime totals to DCJS. The UCR reporting system collects information on seven crimes classified as Index offenses which are most commonly used to gauge overall crime volume. These include the violent crimes of murder/non-negligent manslaughter, forcible rape, robbery, and aggravated assault; and the property crimes of burglary, larceny, and motor vehicle theft. Police agencies may experience reporting problems that preclude accurate or complete reporting. The counts represent only crimes reported to the police but not total crimes that occurred.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | county              | County              | text      | text        |
| Yes      | series tag     | agency              | Agency              | text      | text        |
| Yes      | time           | year                | Year                | number    | number      |
| Yes      | numeric metric | months_reported     | Months Reported     | number    | number      |
| Yes      | numeric metric | total_index_crimes  | Index Total         | number    | number      |
| Yes      | numeric metric | violent             | Violent Total       | number    | number      |
| Yes      | numeric metric | murder              | Murder              | number    | number      |
| Yes      | numeric metric | forcible_rape       | Rape                | number    | number      |
| Yes      | numeric metric | robbery             | Robbery             | number    | number      |
| Yes      | numeric metric | aggravated_assault  | Aggravated Assault  | number    | number      |
| Yes      | numeric metric | property            | Property Total      | number    | number      |
| Yes      | numeric metric | burglary            | Burglary            | number    | number      |
| Yes      | numeric metric | larceny             | Larceny             | number    | number      |
| Yes      | numeric metric | motor_vehicle_theft | Motor Vehicle Theft | number    | number      |
| Yes      | series tag     | region              | Region              | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ca8h-8gjq d:2015-01-01T00:00:00.000Z t:region="Non-New York City" t:county=Albany t:agency="Albany City PD" m:murder=5 m:larceny=2637 m:robbery=234 m:forcible_rape=46 m:aggravated_assault=505 m:burglary=470 m:total_index_crimes=4004 m:property=3214 m:violent=790 m:months_reported=12 m:motor_vehicle_theft=107

series e:ca8h-8gjq d:2014-01-01T00:00:00.000Z t:region="Non-New York City" t:county=Albany t:agency="Albany City PD" m:murder=8 m:larceny=3069 m:robbery=237 m:forcible_rape=26 m:aggravated_assault=496 m:burglary=680 m:total_index_crimes=4638 m:property=3871 m:violent=767 m:months_reported=12 m:motor_vehicle_theft=122

series e:ca8h-8gjq d:2013-01-01T00:00:00.000Z t:region="Non-New York City" t:county=Albany t:agency="Albany City PD" m:murder=8 m:larceny=3241 m:robbery=227 m:forcible_rape=32 m:aggravated_assault=526 m:burglary=702 m:total_index_crimes=4877 m:property=4084 m:violent=793 m:months_reported=12 m:motor_vehicle_theft=141
```

## Meta Commands

```ls
metric m:months_reported p:integer l:"Months Reported" d:"Number of months an individual agency reported for the year." t:dataTypeName=number

metric m:total_index_crimes p:integer l:"Index Total" d:"Includes sum of Murder, Rape, Robbery, Aggravated Assault, Burglary, Larceny and Motor Vehicle Theft." t:dataTypeName=number

metric m:violent p:integer l:"Violent Total" d:"Subtotal includes Murder, Rape, Robbery and Aggravated Assault." t:dataTypeName=number

metric m:murder p:integer l:Murder d:"One count per victim. The willful killing of one human being by another. Excludes deaths caused by negligence, suicide, or justifiable homicides, and attempts to murder, which are classified as assault." t:dataTypeName=number

metric m:forcible_rape p:integer l:Rape d:"One count per victim. Penetration, no matter how slight, of the vagina or anus with any body part or object, or oral penetration by a sex organ of another person, without the consent of the victim." t:dataTypeName=number

metric m:robbery p:integer l:Robbery d:"One count per victim. The taking or attempting to take anything of value from the care, custody, or control of a person or persons by force or threat of force or violence and/or by putting the victim in fear." t:dataTypeName=number

metric m:aggravated_assault p:integer l:"Aggravated Assault" d:"One count per victim. The unlawful attack by one person upon another for the purpose of inflicting severe or aggravated bodily injury. This type of assault is usually accompanied by the use of a weapon or by means likely to produce death or great bodily harm, and also includes attempts to commit murder." t:dataTypeName=number

metric m:property p:integer l:"Property Total" d:"Subtotal includes Burglary, Larceny and Motor Vehicle Theft." t:dataTypeName=number

metric m:burglary p:integer l:Burglary d:"One count per victim. The unlawful entry of a structure to commit a felony or theft. The use of force to gain entry is not required to classify an offense as Burglary." t:dataTypeName=number

metric m:larceny p:integer l:Larceny d:"One count per victim. The unlawful taking, carrying, leading, or riding away of property from the possession or constructive possession of another. It includes crimes such as shoplifting, purse snatching, bicycle thefts, etc., in which no use of force, violence, or fraud occurs. This offense category does not include offenses such as embezzlement, forgery, or bad checks." t:dataTypeName=number

metric m:motor_vehicle_theft p:integer l:"Motor Vehicle Theft" d:"One count per victim. The theft or attempted theft of a motor vehicle, including automobiles, trucks, buses, motorcycles, and snowmobiles." t:dataTypeName=number

entity e:ca8h-8gjq l:"Index Crimes by County and Agency: Beginning 1990" t:attribution="New York State Division of Criminal Justice Services" t:url=https://data.ny.gov/api/views/ca8h-8gjq

property e:ca8h-8gjq t:meta.view v:id=ca8h-8gjq v:category="Public Safety" v:attributionLink=http://www.criminaljustice.ny.gov/crimnet/ojsa/crimereporting/index.htm v:averageRating=0 v:name="Index Crimes by County and Agency: Beginning 1990" v:attribution="New York State Division of Criminal Justice Services"

property e:ca8h-8gjq t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ca8h-8gjq t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ca8h-8gjq t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| county | agency         | year | months_reported | total_index_crimes | violent | murder | forcible_rape | robbery | aggravated_assault | property | burglary | larceny | motor_vehicle_theft | region            | 
| ====== | ============== | ==== | =============== | ================== | ======= | ====== | ============= | ======= | ================== | ======== | ======== | ======= | =================== | ================= | 
| Albany | Albany City PD | 2015 | 12              | 4004               | 790     | 5      | 46            | 234     | 505                | 3214     | 470      | 2637    | 107                 | Non-New York City | 
| Albany | Albany City PD | 2014 | 12              | 4638               | 767     | 8      | 26            | 237     | 496                | 3871     | 680      | 3069    | 122                 | Non-New York City | 
| Albany | Albany City PD | 2013 | 12              | 4877               | 793     | 8      | 32            | 227     | 526                | 4084     | 702      | 3241    | 141                 | Non-New York City | 
| Albany | Albany City PD | 2012 | 12              | 5123               | 799     | 5      | 41            | 245     | 508                | 4324     | 887      | 3285    | 152                 | Non-New York City | 
| Albany | Albany City PD | 2011 | 12              | 5539               | 933     | 4      | 29            | 320     | 580                | 4606     | 890      | 3547    | 169                 | Non-New York City | 
| Albany | Albany City PD | 2010 | 12              | 5616               | 978     | 3      | 41            | 314     | 620                | 4638     | 923      | 3489    | 226                 | Non-New York City | 
| Albany | Albany City PD | 2009 | 12              | 5252               | 1002    | 9      | 43            | 327     | 623                | 4250     | 877      | 3140    | 233                 | Non-New York City | 
| Albany | Albany City PD | 2008 | 12              | 5490               | 1061    | 10     | 48            | 372     | 631                | 4429     | 1034     | 3170    | 225                 | Non-New York City | 
| Albany | Albany City PD | 2007 | 12              | 5378               | 1132    | 3      | 45            | 376     | 708                | 4246     | 963      | 2997    | 286                 | Non-New York City | 
| Albany | Albany City PD | 2006 | 12              | 6059               | 1228    | 5      | 51            | 389     | 783                | 4831     | 1062     | 3528    | 241                 | Non-New York City | 
```