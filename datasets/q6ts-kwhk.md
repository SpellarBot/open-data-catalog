# Equine Death and Breakdown

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/equine-death-and-breakdown) |
| Metadata | [Link](https://data.ny.gov/api/views/q6ts-kwhk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/q6ts-kwhk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/q6ts-kwhk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | q6ts-kwhk |
| Name | Equine Death and Breakdown |
| Attribution | New York State Gaming Commission |
| Category | Government & Finance |
| Tags | horse racing, death, breakdown, injury |
| Created | 2013-02-20T18:09:14Z |
| Publication Date | 2017-04-20T10:10:21Z |

## Description

The Equine Death and Breakdown report lists horses that have broken down, been injured, or have died at New York State race tracks.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| No       |             | year                    | Year                    | number        | number        |
| Yes      | time        | incident_date           | Incident Date           | calendar_date | calendar_date |
| Yes      | series tag  | incident_type           | Incident Type           | text          | text          |
| Yes      | series tag  | track                   | Track                   | text          | text          |
| Yes      | series tag  | inv_location            | Inv Location            | text          | text          |
| Yes      | series tag  | racing_type_description | Racing Type Description | text          | text          |
| Yes      | series tag  | division                | Division                | text          | text          |
| Yes      | series tag  | weather_conditions      | Weather Conditions      | text          | text          |
| Yes      | series tag  | horse                   | Horse                   | text          | text          |
| Yes      | series tag  | trainer                 | Trainer                 | text          | text          |
| Yes      | series tag  | jockey_driver           | Jockey Driver           | text          | text          |
| Yes      | series tag  | incident_description    | Incident Description    | text          | text          |
| Yes      | series tag  | death_or_injury         | Death or Injury         | text          | text          |
```

## Time Field

```ls
Value = incident_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:q6ts-kwhk d:2009-03-04T00:00:00.000Z t:incident_type="EQUINE DEATH" t:incident_description="Private Details-Tr. John Terranova-fell on track-fx LF cannon bone-euthanized" t:division=Thoroughbred t:death_or_injury=Euthanasia t:inv_location=Aqueduct t:horse="Private Details" t:track="Aqueduct Racetrack (NYRA)" t:racing_type_description=Racing t:trainer="JOHN P. TERRANOVA II" m:row_number.q6ts-kwhk=1

series e:q6ts-kwhk d:2009-03-04T00:00:00.000Z t:incident_type="ON-TRACK ACCIDENT" t:incident_description="Private Details-Tr. John Terranova-fell  fx LF cannon bone  euthanized" t:division=Thoroughbred t:horse="Private Details" t:track="Aqueduct Racetrack (NYRA)" t:racing_type_description=Racing t:trainer="JOHN P. TERRANOVA II" m:row_number.q6ts-kwhk=2

series e:q6ts-kwhk d:2009-03-04T00:00:00.000Z t:incident_type="ON-TRACK ACCIDENT" t:incident_description="All Bets Off-Tr. Bruce Levine-fell over downed horse-minor cuts & scrapes-horse ok" t:division=Thoroughbred t:inv_location=Aqueduct t:horse="All Bets Off" t:track="Aqueduct Racetrack (NYRA)" t:racing_type_description=Racing t:trainer="B E. LEVINE" m:row_number.q6ts-kwhk=3
```

## Meta Commands

```ls
metric m:row_number.q6ts-kwhk p:long l:"Row Number"

entity e:q6ts-kwhk l:"Equine Death and Breakdown" t:attribution="New York State Gaming Commission" t:url=https://data.ny.gov/api/views/q6ts-kwhk

property e:q6ts-kwhk t:meta.view v:id=q6ts-kwhk v:category="Government & Finance" v:attributionLink=http://breakdown.gaming.ny.gov/ v:averageRating=0 v:name="Equine Death and Breakdown" v:attribution="New York State Gaming Commission"

property e:q6ts-kwhk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:q6ts-kwhk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:q6ts-kwhk t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | incident_date       | incident_type      | track                                | inv_location | racing_type_description | division     | weather_conditions | horse             | trainer              | jockey_driver | incident_description                                                                   | death_or_injury | 
| ==== | =================== | ================== | ==================================== | ============ | ======================= | ============ | ================== | ================= | ==================== | ============= | ====================================================================================== | =============== | 
| 2009 | 2009-03-04T00:00:00 | EQUINE DEATH       | Aqueduct Racetrack (NYRA)            | Aqueduct     | Racing                  | Thoroughbred |                    | Private Details   | JOHN P. TERRANOVA II |               | Private Details-Tr. John Terranova-fell on track-fx LF cannon bone-euthanized          | Euthanasia      | 
| 2009 | 2009-03-04T00:00:00 | ON-TRACK ACCIDENT  | Aqueduct Racetrack (NYRA)            |              | Racing                  | Thoroughbred |                    | Private Details   | JOHN P. TERRANOVA II |               | Private Details-Tr. John Terranova-fell fx LF cannon bone euthanized                   |                 | 
| 2009 | 2009-03-04T00:00:00 | ON-TRACK ACCIDENT  | Aqueduct Racetrack (NYRA)            | Aqueduct     | Racing                  | Thoroughbred |                    | All Bets Off      | B E. LEVINE          |               | All Bets Off-Tr. Bruce Levine-fell over downed horse-minor cuts & scrapes-horse ok     |                 | 
| 2009 | 2009-03-04T00:00:00 | ON-TRACK ACCIDENT  | Aqueduct Racetrack (NYRA)            | Aqueduct     | Racing                  | Thoroughbred |                    | Hot Chile Soup    | ENRIQUE ARROYO       |               | Hot Chile Soup-Tr. Enrique Arroyo-fell over downed horse-minor cuts & scrapes-horse ok |                 | 
| 2009 | 2009-03-04T00:00:00 | ON-TRACK ACCIDENT  | Aqueduct Racetrack (NYRA)            | Aqueduct     | Racing                  | Thoroughbred |                    | One Dream Union   | BRUCE R. BROWN       |               | One Dream Union-Tr. Bruce Brown-fell over downed horse-minor cuts & scrapes-horse ok   |                 | 
| 2009 | 2009-03-04T00:00:00 | ON-TRACK ACCIDENT  | Aqueduct Racetrack (NYRA)            | Aqueduct     | Racing                  | Thoroughbred |                    | Truly Devine      | GARY C. CONTESSA     |               | Truly Devine-Tr. Gary Contessa-fell over downed horse minor cuts & scrapes horse ok    |                 | 
| 2009 | 2009-03-05T00:00:00 | EQUINE DEATH       | Aqueduct Racetrack (NYRA)            | Aqueduct     | Racing                  | Thoroughbred | Clear & Cold       | Sigh You          |                      |               | Sigh You-Tr. Patrick Kelly-Euthanasia-Left Front Sesamoid FX                           |                 | 
| 2009 | 2009-03-06T00:00:00 | STEWARDS/VETS LIST | Saratoga Gaming & Raceway            |              | Racing                  | Harness      |                    | Raid the Bank N   | ELAINE M. ELMORE     |               | Raid the Bank N-Tr. Elaine Elmore-performed poorly-will no longer run                  |                 | 
| 2009 | 2009-03-24T00:00:00 | STEWARDS/VETS LIST | Monticello Raceway & Mighty M Gaming | MR           | Racing                  | Harness      | Cloudy/cold        | Grouse A          | TODD J. MARCIANO     |               | Grouse A-Tr. Todd Marciano- reinjured lower LF bow tendon-given rest time              |                 | 
| 2009 | 2009-03-28T00:00:00 | STEWARDS/VETS LIST | Aqueduct Racetrack (NYRA)            | Aqueduct     | Racing                  | Thoroughbred | Cloudy             | Dr. Silver Packet | JOHN P. CAMPO JR     |               | Dr. Silver Packet-Tr. John Campo-horse hurt stifle-walked off track                    |                 | 
```