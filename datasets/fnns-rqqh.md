# Weatherization Assistance Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/weatherization-assistance-program) |
| Metadata | [Link](https://data.austintexas.gov/api/views/fnns-rqqh) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/fnns-rqqh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/fnns-rqqh/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | fnns-rqqh |
| Name | Weatherization Assistance Program |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | weatherization, assistance, weatherization assistance program, energy, savings |
| Created | 2016-09-06T16:43:36Z |
| Publication Date | 2016-09-30T18:29:51Z |

## Description

Austin Energy offers free weatherization services to qualifying low-income, elderly and physically/mentally disabled customers. Each of the homes reduces its energy use by an average of about 1,200 kilowatt-hours annually due to these improvements. The program provides up to $1,500 in home improvements including installation of attic insulation, sealing and repair of ducts, solar screen installations, weather stripping around entry doors, and minor home repairs necessary to improve the effectiveness of the efficiency improvements.

In FY 2010, Austin Energy received a grant of nearly $5.9 million from American Recovery and Reinvestment Act (ARRA) funds that allowed for the weatherization of 1,064 homes and apartments for low-income, elderly, and disabled customers within Austin Energy’s service area. Under this program, each dwelling received, on average, about $5,000 worth of improvements including new energy efficient appliances and air conditioning and heating equipment.

Because Austin Energy's implementation of the program was so successful, the utility received additional funding on three separate occasions in the amounts of $2.1 million, $200,000 and $1 million, for total funds of $9.2 million. This allowed the utility to nearly double the number of units receiving this enhanced free weatherization. 
Under the Federal Weatherization Program which ended April 30, 2012, Austin Energy weatherized  1,886 homes, 77% more than the original goal of 1,064 homes. The homes were occupied by 4,529 people of whom 645 were elderly, 572 had disabilities and 758 were children under the age of 5. On average, each of the homes will save about 1,200 kilowatt-hours annually in energy costs due to the improvements.

*In FY 2010 127 of the 456 homes received weatherization through the use of ARRA funds. 
*In FY 2011 all homes received weatherization through the use of ARRA funds. 
*In FY 2012, the 715 homes used both ARRA funds and AE funds.
*Numbers are lower than expected in FY 2013 due to the late start of the program efforts.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | time           | fiscal_year_2                  | Fiscal Year                    | calendar_date | calendar_date |
| Yes      | numeric metric | homes_receiving_weatherization | Homes Receiving Weatherization | number        | number        |
```

## Time Field

```ls
Value = fiscal_year_2
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:fnns-rqqh d:2006-09-01T00:00:00.000Z m:homes_receiving_weatherization=720

series e:fnns-rqqh d:2007-09-01T00:00:00.000Z m:homes_receiving_weatherization=632

series e:fnns-rqqh d:2008-09-01T00:00:00.000Z m:homes_receiving_weatherization=505
```

## Meta Commands

```ls
metric m:homes_receiving_weatherization p:integer l:"Homes Receiving Weatherization" t:dataTypeName=number

entity e:fnns-rqqh l:"Weatherization Assistance Program" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/fnns-rqqh

property e:fnns-rqqh t:meta.view v:id=fnns-rqqh v:category=Utility v:averageRating=0 v:name="Weatherization Assistance Program" v:attribution="Austin Energy"

property e:fnns-rqqh t:meta.view.license v:name="Public Domain"

property e:fnns-rqqh t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:fnns-rqqh t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```