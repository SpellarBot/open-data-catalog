# Public Events Permits in Hudson River Park: Beginning 2004

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-events-permits-in-hudson-river-park-beginnning-2004) |
| Metadata | [Link](https://data.ny.gov/api/views/nwx8-ckzy) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/nwx8-ckzy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/nwx8-ckzy/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | nwx8-ckzy |
| Name | Public Events Permits in Hudson River Park: Beginning 2004 |
| Attribution | Hudson River Park Trust (HRPT) |
| Category | Recreation |
| Tags | hrpt, events, permits, recreation |
| Created | 2014-11-04T16:43:02Z |
| Publication Date | 2015-12-23T17:48:01Z |

## Description

This dataset contains a list of events held in Hudson River Park and permitted by Hudson River Park Trust (HRPT), along with the permittee?s name and the name of the entity that paid the permit fee.  Events which do not require a permit are not included.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                   | Data Type | Render Type |
| ======== | =========== | ======================== | ====================== | ========= | =========== |
| Yes      | time        | fiscal_year              | Fiscal Year            | number    | number      |
| Yes      | series tag  | permitted_organization   | Permitted Organization | text      | text        |
| Yes      | series tag  | name_on_permit_fee_check | Funded By              | text      | text        |
| Yes      | series tag  | event_type_name          | Event Type/Name        | text      | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:nwx8-ckzy l:"Public Events Permits in Hudson River Park:  Beginning 2004" t:attribution="Hudson River Park Trust (HRPT)" t:url=https://data.ny.gov/api/views/nwx8-ckzy

property e:nwx8-ckzy t:meta.view v:id=nwx8-ckzy v:category=Recreation v:attributionLink=http://www.hudsonriverpark.org/events v:averageRating=0 v:name="Public Events Permits in Hudson River Park:  Beginning 2004" v:attribution="Hudson River Park Trust (HRPT)"

property e:nwx8-ckzy t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:nwx8-ckzy t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:nwx8-ckzy t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| fiscal_year | permitted_organization               | name_on_permit_fee_check                  | event_type_name                          | 
| =========== | ==================================== | ========================================= | ======================================== | 
| 2014        | Bike The Greenway LLC                | DBA Bike and Roll New York City           | 5 Boro Bike Tour                         | 
| 2014        | Individual                           | Individual                                | Wedding Permit                           | 
| 2014        | Our Lady of Pompeii                  | Seawall Enterprises LLC, DBA Base Fitness | Run/Walk Permit                          | 
| 2014        | NFL                                  | NFL Ventures LP                           | NFL Draft Event - Chelsea Waterside Park | 
| 2014        | Individual                           | Individual                                | Wedding Permit                           | 
| 2014        | LeadDog Marketing                    | LeadDog Marketing                         | 9/11 Memorial 5K Permit                  | 
| 2014        | American Liver Foundation            | American Liver Foundation                 | Liver Life Walk                          | 
| 2014        | Hope & Heroes Children's Cancer Fund | Hope & Heroes Children's Cancer Fund      | Hope & Heroes Walk                       | 
| 2014        | Lily Sarah Grace Fund                | Lily Sarah Grace Fund                     | Special Event                            | 
| 2014        | The Lesbian and Gay Big Apple Corps  | The Lesbian and Gay Big Apple Corps       | Special Event                            | 
```