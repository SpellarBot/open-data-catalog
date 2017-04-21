# Pet Events

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-events-7a2d1) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/3rpu-sz4q) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/3rpu-sz4q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/3rpu-sz4q/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 3rpu-sz4q |
| Name | Pet Events |
| Created | 2011-05-25T22:51:56Z |
| Publication Date | 2014-07-14T20:57:56Z |

## Description

Base dataset for the Pet Events Calendar

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| Yes      | time        | startdatetime  | StartDateTime  | calendar_date | calendar_date |
| No       |             | enddatetime    | EndDateTime    | calendar_date | calendar_date |
| Yes      | series tag  | eventname      | EventName      | text          | text          |
| Yes      | series tag  | location       | Location       | text          | text          |
| No       |             | address        | Address        | text          | text          |
| Yes      | series tag  | city           | City           | text          | text          |
| Yes      | series tag  | state          | State          | text          | text          |
| Yes      | series tag  | zip            | ZIP            | text          | text          |
| Yes      | series tag  | additionalinfo | AdditionalInfo | text          | text          |
| Yes      | series tag  | url            | Website        | url           | url           |
```

## Time Field

```ls
Value = startdatetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = enddatetime,address
```

## Data Commands

```ls
series e:3rpu-sz4q d:2013-05-02T00:00:00.000Z t:zip=98032 t:location="RASKC Pet Adoption Center" t:state=WA t:additionalinfo="Info/RSVP: sarah.luthens@kingcounty.gov or 206-296-3946" t:city=Kent t:eventname="Fostering Animals 101" m:row_number.3rpu-sz4q=1

series e:3rpu-sz4q d:2013-05-04T00:00:00.000Z t:zip=98155 t:location="Spartan Rec Center" t:state=WA t:city=Shoreline t:eventname="Average Joe Cat Show" m:row_number.3rpu-sz4q=2

series e:3rpu-sz4q d:2013-05-05T00:00:00.000Z t:zip=98003 t:location="Mud Bay Federal Way" t:state=WA t:city="Federal Way" t:eventname="Pet Adoptions at Mud Bay" m:row_number.3rpu-sz4q=3
```

## Meta Commands

```ls
metric m:row_number.3rpu-sz4q p:long l:"Row Number"

entity e:3rpu-sz4q l:"Pet Events" t:url=https://data.kingcounty.gov/api/views/3rpu-sz4q

property e:3rpu-sz4q t:meta.view v:id=3rpu-sz4q v:averageRating=0 v:name="Pet Events"

property e:3rpu-sz4q t:meta.view.license v:name="Public Domain"

property e:3rpu-sz4q t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:3rpu-sz4q t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| startdatetime       | enddatetime         | eventname                     | location                                | address                                      | city                 | state | zip   | additionalinfo                                          | url          | 
| =================== | =================== | ============================= | ======================================= | ============================================ | ==================== | ===== | ===== | ======================================================= | ============ | 
| 2013-05-02T00:00:00 | 2013-05-02T00:00:00 | Fostering Animals 101         | RASKC Pet Adoption Center               | 21615 64th Ave S                             | Kent                 | WA    | 98032 | Info/RSVP: sarah.luthens@kingcounty.gov or 206-296-3946 | [null, null] | 
| 2013-05-04T00:00:00 | 2013-05-04T00:00:00 | Average Joe Cat Show          | Spartan Rec Center                      | 202 NE 185th St                              | Shoreline            | WA    | 98155 |                                                         | [null, null] | 
| 2013-05-05T00:00:00 | 2013-05-05T00:00:00 | Pet Adoptions at Mud Bay      | Mud Bay Federal Way                     | 1706 S 320th St                              | Federal Way          | WA    | 98003 |                                                         | [null, null] | 
| 2013-05-05T00:00:00 | 2013-05-05T00:00:00 | Cinco de Mayo Pet Adoptions   | Sunrise Village Petsmart                | 10309 156th St E                             | Puyallup             | WA    | 98374 |                                                         | [null, null] | 
| 2013-05-09T00:00:00 | 2013-05-09T00:00:00 | Fostering Animals 101         | RASKC Pet Adoption Center               | 21615 64th Ave S                             | Kent                 | WA    | 98032 | Info/RSVP: sarah.luthens@kingcounty.gov or 206-296-3946 | [null, null] | 
| 2013-05-11T00:00:00 | 2013-05-11T00:00:00 | Pet Adoptions at Petco        | Crossroads and Aurora Village locations | 15600 NE 8th St, Suite 1 and 1241 N 205th St | Bellevue and Seattle | WA    |       |                                                         | [null, null] | 
| 2013-05-11T00:00:00 | 2013-05-11T00:00:00 | Pet Bereavement Support Group | RASKC Pet Adoption Center               | 21615 64th Ave S                             | Kent                 | WA    | 98032 |                                                         | [null, null] | 
| 2013-05-12T00:00:00 | 2013-05-12T00:00:00 | Pet Adoptions at Petco        | Crossroads and Aurora Village locations | 15600 NE 8th St, Suite 1 and 1241 N 205th St | Bellevue and Seattle | WA    |       |                                                         | [null, null] | 
| 2013-05-16T00:00:00 | 2013-05-16T00:00:00 | Fostering Animals 101         | RASKC Pet Adoption Center               | 21615 64th Ave S                             | Kent                 | WA    | 98032 | Info/RSVP: sarah.luthens@kingcounty.gov or 206-296-3946 | [null, null] | 
| 2013-05-18T00:00:00 | 2013-05-18T00:00:00 | Petpalooza                    | Game Farm Park                          |                                              | Auburn               | WA    |       |                                                         | [null, null] | 
```