# Inspector General - Proposed Legislation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inspector-general-proposed-legislation) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/jtuj-feep) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/jtuj-feep/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/jtuj-feep/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | jtuj-feep |
| Name | Inspector General - Proposed Legislation |
| Attribution | Cook County Office of the Independent Inspector General |
| Category | Finance & Administration |
| Tags | oiig |
| Created | 2016-05-18T21:19:00Z |
| Publication Date | 2017-01-24T18:03:28Z |

## Description

The OIIG has issued the following proposed legislation.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | series tag  | link        | Link        | url           | url           |
| Yes      | time        | date_issued | Date Issued | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_issued
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jtuj-feep d:2015-10-06T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/inspector-general/proposed-legislation/Electronic-Mail-Requirement.pdf m:row_number.jtuj-feep=1

series e:jtuj-feep d:2015-04-23T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/inspector-general/proposed-legislation/State-Legislation-for-IG-Oversight-of-County-and-County-Funded-Officials1.pdf m:row_number.jtuj-feep=2

series e:jtuj-feep d:2014-05-30T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/inspector-general/proposed-legislation/Proposed-Amendments-to-the-Lobbyist-Registration-Ordinance.pdf m:row_number.jtuj-feep=3
```

## Meta Commands

```ls
metric m:row_number.jtuj-feep p:long l:"Row Number"

entity e:jtuj-feep l:"Inspector General - Proposed Legislation" t:attribution="Cook County Office of the Independent Inspector General" t:url=https://datacatalog.cookcountyil.gov/api/views/jtuj-feep

property e:jtuj-feep t:meta.view v:id=jtuj-feep v:category="Finance & Administration" v:averageRating=0 v:name="Inspector General - Proposed Legislation" v:attribution="Cook County Office of the Independent Inspector General"

property e:jtuj-feep t:meta.view.license v:name="Public Domain"

property e:jtuj-feep t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:jtuj-feep t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| link                                                                                                                                                                                                                              | date_issued         | 
| ================================================================================================================================================================================================================================= | =================== | 
| [http://opendocs.cookcountyil.gov/inspector-general/proposed-legislation/Electronic-Mail-Requirement.pdf, Electronic Mail Requirement]                                                                                            | 2015-10-06T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/proposed-legislation/State-Legislation-for-IG-Oversight-of-County-and-County-Funded-Officials1.pdf, State Legislation for IG Oversight of County and County Funded Officials] | 2015-04-23T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/proposed-legislation/Proposed-Amendments-to-the-Lobbyist-Registration-Ordinance.pdf, Lobbyist Registration Ordinance Amendments]                                              | 2014-05-30T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/proposed-legislation/Procurement-Contact-Log.pdf, Procurement Contact Log]                                                                                                    | 2014-02-05T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/proposed-legislation/Authority-for-Peer-Review-1-2-14.pdf, Authority for Peer Review 1-2-14]                                                                                  | 2014-02-02T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/proposed-legislation/OIIG-Ordinance-7-30-13.pdf, OIIG Ordinance]                                                                                                              | 2013-07-30T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/proposed-legislation/Jurisdiction-of-County-Offices-of-Inspectors-General-in-Illinios.pdf, Jurisdiction of County Offices of Inspectors General in Illinios]                  | 2013-03-11T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/proposed-legislation/Veterans-Preference-01-29-13.pdf, Veterans Preference]                                                                                                   | 2013-01-29T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/proposed-legislation/Veterans-Preference.pdf, Veterans Preference]                                                                                                            | 2013-01-24T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/proposed-legislation/Ethical-Violations-in-Unincorporated-Districts-Senator-Christine-Radogno.pdf, Ethical Violations in Unincorporated District, Sen. Christine Radogno]     | 2013-01-18T00:00:00 | 
```