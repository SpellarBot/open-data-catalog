# Building Permits Since 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-permits-since-2009-86a01) |
| Metadata | [Link](https://data.illinois.gov/api/views/stav-rdug) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/stav-rdug/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/stav-rdug/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | stav-rdug |
| Name | Building Permits Since 2009 |
| Attribution | City of Rockford |
| Category | Municipality |
| Tags | building permits |
| Created | 2013-01-17T19:00:37Z |
| Publication Date | 2013-01-17T20:19:49Z |

## Description

List of all building permits issued since 2009

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | time           | dateissued         | DateIssued         | calendar_date | calendar_date |
| Yes      | series tag     | permitno           | PermitNo           | text          | text          |
| Yes      | series tag     | pin                | PIN                | text          | text          |
| Yes      | series tag     | contractordba      | ContractorDBA      | text          | text          |
| Yes      | series tag     | contractorfullname | ContractorFullName | text          | text          |
| Yes      | numeric metric | valuation          | Valuation          | money         | money         |
| Yes      | series tag     | ownerfullname      | OwnerFullName      | text          | text          |
| Yes      | series tag     | description        | Description        | text          | text          |
```

## Time Field

```ls
Value = dateissued
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:stav-rdug d:2011-11-07T00:00:00.000Z t:contractorfullname="CLM Midwest" t:permitno=MULCOM20112059 t:pin=11-16-429-001 t:description="dumpster enclosure 6' wood" m:valuation=6000

series e:stav-rdug d:2009-07-01T00:00:00.000Z t:contractorfullname="Gastel, Judd" t:permitno=MECH20091767 t:pin=12-19-178-011 t:description="repl 2.5 ton a/c" t:ownerfullname="Reafler, Nancy & Robert" t:contractordba="Norstar Heating & Cooling" m:valuation=0

series e:stav-rdug d:2009-09-11T00:00:00.000Z t:contractorfullname="Bethesda Covenant Church" t:permitno=MULCOM20091590 t:pin=11-25-226-018 t:description="Temporary freestanding sign from September 12 to September 20th 2009 for Bethesda Alley Walk.  Note that actual sign is 2.5 feet x 2.5 feet.  Size was entered as 3' in Hansen because there is no allowance for anything other than even foot measurements." t:ownerfullname="Bethesda Covenant Church" m:valuation=0
```

## Meta Commands

```ls
metric m:valuation p:double l:Valuation t:dataTypeName=money

entity e:stav-rdug l:"Building Permits Since 2009" t:attribution="City of Rockford" t:url=https://data.illinois.gov/api/views/stav-rdug

property e:stav-rdug t:meta.view v:id=stav-rdug v:category=Municipality v:averageRating=0 v:name="Building Permits Since 2009" v:attribution="City of Rockford"

property e:stav-rdug t:meta.view.owner v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:displayName=Glenn

property e:stav-rdug t:meta.view.tableauthor v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:roleName=publisher v:displayName=Glenn
```

## Top Records

```ls
| dateissued          | permitno       | pin           | contractordba             | contractorfullname                            | valuation | ownerfullname                                 | description                                                                                                                                                                                                                                                | 
| =================== | ============== | ============= | ========================= | ============================================= | ========= | ============================================= | ========================================================================================================================================================================================================================================================== | 
| 2011-11-07T00:00:00 | MULCOM20112059 | 11-16-429-001 |                           | CLM Midwest                                   | 6000.00   |                                               | dumpster enclosure 6' wood                                                                                                                                                                                                                                 | 
| 2009-07-01T00:00:00 | MECH20091767   | 12-19-178-011 | Norstar Heating & Cooling | Gastel, Judd                                  | 0.00      | Reafler, Nancy & Robert                       | repl 2.5 ton a/c                                                                                                                                                                                                                                           | 
| 2009-09-11T00:00:00 | MULCOM20091590 | 11-25-226-018 |                           | Bethesda Covenant Church                      | 0.00      | Bethesda Covenant Church                      | Temporary freestanding sign from September 12 to September 20th 2009 for Bethesda Alley Walk. Note that actual sign is 2.5 feet x 2.5 feet. Size was entered as 3' in Hansen because there is no allowance for anything other than even foot measurements. | 
| 2009-09-01T00:00:00 | DEVLOP20091003 |               |                           | Arnold Lundgren & Associates                  | 0.00      |                                               | Grading Permit, drainage and stormwater review                                                                                                                                                                                                             | 
| 2011-08-02T00:00:00 | PLUM20111757   | 12-22-329-028 | Picks Service & Installs  | Hartwig, Edward                               | 750.00    | Stanfa, Steve                                 | 40 gallon gas water heater 34,000 BTU                                                                                                                                                                                                                      | 
| 2011-04-07T00:00:00 | ROW20111319    |               |                           | Testing Services Corp., Jeff Martin           | 0.00      |                                               | 6" diameter soil boring                                                                                                                                                                                                                                    | 
| 2009-08-25T00:00:00 | DEVLOP20091012 | 12-26-126-006 |                           | Carlson Brothers Inc                          | 0.00      |                                               | stream and wetland restoration                                                                                                                                                                                                                             | 
| 2010-03-03T00:00:00 | DEVLOP20091011 |               |                           | Unitarian Universalist Church, David Schubert | 0.00      | Unitarian Universalist Church, David Schubert | Installation of stormwater ditch                                                                                                                                                                                                                           | 
| 2011-04-08T00:00:00 | DEVLOP20111002 |               |                           | County of Winnebago                           | 0.00      |                                               | Replace Cunningham Rd bridge over the south branch of Kent Creek - just west of Horace Ave                                                                                                                                                                 | 
| 2009-05-27T00:00:00 | DEVLOP20091004 |               |                           | Arnold Lundgren & Associates                  | 0.00      |                                               | sanitary sewer main expansion                                                                                                                                                                                                                              | 
```