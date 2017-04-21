# Human Rights - Decisions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/human-rights-decisions) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/b5sv-ucke) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/b5sv-ucke/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/b5sv-ucke/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | b5sv-ucke |
| Name | Human Rights - Decisions |
| Attribution | Cook County Commission on Human Rights |
| Created | 2016-06-22T21:21:18Z |
| Publication Date | 2017-04-13T21:20:21Z |

## Description

The Commission investigates, mediates and, if warranted, adjudicates violations of the Cook County Human Rights Ordinance.  If you believe that you have been the victim of unlawful discrimination in the protected areas of employment, housing, public accommodations, credit or access to County programs, services or contracts, contact the Cook County Commission on Human Rights for an intake interview. https://www.cookcountyil.gov/service/complaint-filing-and-investigation

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | complainant_name | Complainant Name | text          | text          |
| Yes      | series tag  | respondent_name  | Respondent Name  | text          | text          |
| Yes      | series tag  | case_number      | Case Number      | text          | text          |
| Yes      | series tag  | order_type       | Order Type       | text          | text          |
| Yes      | time        | decision_date    | Decision Date    | calendar_date | calendar_date |
| Yes      | series tag  | link             | Link             | url           | url           |
```

## Time Field

```ls
Value = decision_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:b5sv-ucke d:2016-07-19T00:00:00.000Z t:case_number=2015PA001 t:respondent_name="108 North State Street (Chicago) Owner, LLC; Allied Barton Security Services" t:link=http://opendocs.cookcountyil.gov/human-rights/decisions/2015PA001-07192016-2.pdf t:order_type="Notice of Evidentiary Conference" t:complainant_name=Blakemore m:row_number.b5sv-ucke=1

series e:b5sv-ucke d:2016-07-19T00:00:00.000Z t:case_number=2015PA001 t:respondent_name="108 North State Street (Chicago) Owner, LLC; Allied Barton Security Services" t:link=http://opendocs.cookcountyil.gov/human-rights/decisions/2015PA001-07192016-1.pdf t:order_type="Order Denying Motion to Dismiss in Whole or in Part" t:complainant_name=Blakemore m:row_number.b5sv-ucke=2

series e:b5sv-ucke d:2016-07-14T00:00:00.000Z t:case_number=2013E030 t:respondent_name="AllState-Louis Dodd Agency" t:link=http://opendocs.cookcountyil.gov/human-rights/decisions/2013E030-07142016.pdf t:order_type="Commission's Decision and Order on Liability and Damages" t:complainant_name=Robertson m:row_number.b5sv-ucke=3
```

## Meta Commands

```ls
metric m:row_number.b5sv-ucke p:long l:"Row Number"

entity e:b5sv-ucke l:"Human Rights - Decisions" t:attribution="Cook County Commission on Human Rights" t:url=https://datacatalog.cookcountyil.gov/api/views/b5sv-ucke

property e:b5sv-ucke t:meta.view v:id=b5sv-ucke v:averageRating=0 v:name="Human Rights - Decisions" v:attribution="Cook County Commission on Human Rights"

property e:b5sv-ucke t:meta.view.license v:name="Public Domain"

property e:b5sv-ucke t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:b5sv-ucke t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| complainant_name | respondent_name                                                              | case_number | order_type                                               | decision_date       | link                                                                                                                                                                                                                                                                                                                                               | 
| ================ | ============================================================================ | =========== | ======================================================== | =================== | ================================================================================================================================================================================================================================================================================================================================================== | 
| Blakemore        | 108 North State Street (Chicago) Owner, LLC; Allied Barton Security Services | 2015PA001   | Notice of Evidentiary Conference                         | 2016-07-19T00:00:00 | [http://opendocs.cookcountyil.gov/human-rights/decisions/2015PA001-07192016-2.pdf, 2015PA001-07192016-2]                                                                                                                                                                                                                                           | 
| Blakemore        | 108 North State Street (Chicago) Owner, LLC; Allied Barton Security Services | 2015PA001   | Order Denying Motion to Dismiss in Whole or in Part      | 2016-07-19T00:00:00 | [http://opendocs.cookcountyil.gov/human-rights/decisions/2015PA001-07192016-1.pdf, 2015PA001-07192016-1]                                                                                                                                                                                                                                           | 
| Robertson        | AllState-Louis Dodd Agency                                                   | 2013E030    | Commission's Decision and Order on Liability and Damages | 2016-07-14T00:00:00 | [http://opendocs.cookcountyil.gov/human-rights/decisions/2013E030-07142016.pdf, 2013E030-07142016]                                                                                                                                                                                                                                                 | 
| LaCaria          | Gail's Carriage Inn, Inc.                                                    | 2015E002    | Scheduling Order                                         | 2016-07-12T00:00:00 | [http://opendocs.cookcountyil.gov/human-rights/decisions/2015E002-07122016.pdf, 2015E002-07122016]                                                                                                                                                                                                                                                 | 
| LaCaria          | Gail's Carriage Inn, Inc.                                                    | 2015E002    | Scheduling Order                                         | 2016-06-15T00:00:00 | [http://opendocs.cookcountyil.gov/human-rights/decisions/LaCaria-v.-Gails-Carriage-Inn-Inc-Case-No-2015E002-Scheduling-Order-June-15-2016.pdf, LaCaria-v.-Gails-Carriage-Inn-Inc-Case-No-2015E002-Scheduling-Order-June-15-2016]                                                                                                                   | 
| Almazan          | Liuna Laborers Local Union 225                                               | 2015E014    | Evidentiary Determination-Lack of Substantial Evidence   | 2016-06-01T00:00:00 | [http://opendocs.cookcountyil.gov/human-rights/decisions/Almazan-v.-Liuna-Laborers-Local-Union-225-Case-No-2015E014-Order-of-Dismissal-June-1-2016-LSE.pdf, Almazan-v.-Liuna-Laborers-Local-Union-225-Case-No-2015E014-Order-of-Dismissal-June-1-2016-LSE]                                                                                         | 
| Blakemore        | 108 North State Street (Chicago) Owner, LLC; Allied Barton Security Services | 2015PA001   | Notice of Evidentiary Conference                         | 2016-05-23T00:00:00 | [http://opendocs.cookcountyil.gov/human-rights/decisions/Blakemore-v.-108-North-State-Street-Chicago-Owner-LLC-et-al.-Case-No.-2015PA001-Notice-of-Evidentiary-Conference-May-23-2016.pdf, Blakemore-v.-108-North-State-Street-Chicago-Owner-LLC-et-al.-Case-No.-2015PA001-Notice-of-Evidentiary-Conference-May-23-2016]                           | 
| Walker           | Cook County Sheriff's Office                                                 | 2008E017    | Administrative Review of Petition for Writ of Certiorari | 2016-05-20T00:00:00 | [http://opendocs.cookcountyil.gov/human-rights/decisions/Cook-County-Sheriffs-Office-v.-Cook-County-Commission-on-Human-Rights-et-al-2016-IL-App-1st-150718-1st-Dist-May-20-2016-formerly-2008E017.pdf, Cook-County-Sheriffs-Office-v.-Cook-County-Commission-on-Human-Rights-et-al-2016-IL-App-1st-150718-1st-Dist-May-20-2016-formerly-2008E017] | 
| LaCaria          | Gail's Carriage Inn, Inc.                                                    | 2015E002    | Scheduling Order                                         | 2016-05-03T00:00:00 | [http://opendocs.cookcountyil.gov/human-rights/decisions/LaCaria-v.-Gails-Carriage-Inn-Inc.-Case-No.-2015E002-Scheduling-Order-May-3-2016.pdf, LaCaria-v.-Gails-Carriage-Inn-Inc.-Case-No.-2015E002-Scheduling-Order-May-3-2016]                                                                                                                   | 
| Mykhashula       | Schiller Park Check Exchange, Inc.                                           | 2015PA007   | Order of Dismissal-Withdrawn or Settled                  | 2016-05-02T00:00:00 | [http://opendocs.cookcountyil.gov/human-rights/decisions/Mykhashula-v.-Schiller-Park-Check-Exchange-Inc.-Case-No.-2015PA007-Order-of-Dismissal-May-2-2016-Withdrawn.pdf, Mykhashula-v.-Schiller-Park-Check-Exchange-Inc.-Case-No.-2015PA007-Order-of-Dismissal-May-2-2016-Withdrawn]                                                               | 
```