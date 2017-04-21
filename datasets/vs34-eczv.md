# Board of Ethics - Advisory Opinions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/board-of-ethics-advisory-opinions) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/vs34-eczv) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/vs34-eczv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/vs34-eczv/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | vs34-eczv |
| Name | Board of Ethics - Advisory Opinions |
| Attribution | Cook County Board of Ethics |
| Category | Finance & Administration |
| Created | 2016-06-22T18:35:56Z |
| Publication Date | 2016-12-22T20:00:36Z |

## Description

By ordinance, the investigations and considerations by the Board of Ethics of potential violations of the Ethics Ordinance are confidential. County Code, ? 2-592. As a matter of policy, the Board also maintains as confidential the identity of the requestors of advisory opinions. Board of Ethics Rules & Regulations, ? 4.10. The Board, however, is undertaking to make its final determinations available to the public with such deletions as may be necessary to prevent disclosure of any information the Board determines to be confidential.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | subject     | Subject     | url       | url         |
| Yes      | series tag  | case_number | Case Number | text      | text        |
| Yes      | series tag  | type        | Type        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vs34-eczv d:2016-12-22T20:00:15.000Z t:case_number=17A01 t:subject=http://opendocs.cookcountyil.gov/ethics/advisory-opinions/17A01-Advisory_Opinion-Lobbyist_Registration_Ordinance.pdf t:type="Advisory Opinion" m:row_number.vs34-eczv=1

series e:vs34-eczv d:2016-12-22T20:00:15.000Z t:case_number="15 A 0001" t:subject=http://opendocs.cookcountyil.gov/ethics/advisory-opinions/15-A-0001-ADVISORY-OPINION-Contracting-with-a-Current-County-Employee-for-Public-Information-Redacted-for-Publication.pdf t:type="Advisory Opinion" m:row_number.vs34-eczv=2

series e:vs34-eczv d:2016-12-22T20:00:15.000Z t:case_number="14 A 0001" t:subject=http://opendocs.cookcountyil.gov/ethics/advisory-opinions/14-A-0001-ADVISORY-OPINION-Electronic-Communications-During-Election-Periods.pdf t:type="Advisory Opinion" m:row_number.vs34-eczv=3
```

## Meta Commands

```ls
metric m:row_number.vs34-eczv p:long l:"Row Number"

entity e:vs34-eczv l:"Board of Ethics - Advisory Opinions" t:attribution="Cook County Board of Ethics" t:url=https://datacatalog.cookcountyil.gov/api/views/vs34-eczv

property e:vs34-eczv t:meta.view v:id=vs34-eczv v:category="Finance & Administration" v:averageRating=0 v:name="Board of Ethics - Advisory Opinions" v:attribution="Cook County Board of Ethics"

property e:vs34-eczv t:meta.view.license v:name="Public Domain"

property e:vs34-eczv t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:vs34-eczv t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| :updated_at | subject                                                                                                                                                                                                                                                                                                                       | case_number | type                                           | 
| =========== | ============================================================================================================================================================================================================================================================================================================================= | =========== | ============================================== | 
| 1482436815  | [http://opendocs.cookcountyil.gov/ethics/advisory-opinions/17A01-Advisory_Opinion-Lobbyist_Registration_Ordinance.pdf, Lobbyist Registration Ordinance]                                                                                                                                                                       | 17A01       | Advisory Opinion                               | 
| 1482436815  | [http://opendocs.cookcountyil.gov/ethics/advisory-opinions/15-A-0001-ADVISORY-OPINION-Contracting-with-a-Current-County-Employee-for-Public-Information-Redacted-for-Publication.pdf, Contracting with a Current County Employee for Public Information (Redacted for Publication)]                                           | 15 A 0001   | Advisory Opinion                               | 
| 1482436815  | [http://opendocs.cookcountyil.gov/ethics/advisory-opinions/14-A-0001-ADVISORY-OPINION-Electronic-Communications-During-Election-Periods.pdf, Electronic Communications During Election Periods]                                                                                                                               | 14 A 0001   | Advisory Opinion                               | 
| 1482436815  | [http://opendocs.cookcountyil.gov/ethics/advisory-opinions/13-A-0008-ADVISORY-OPINION-Distribution-of-Produce-by-Cook-County-Farm-Bureau-at-the-County-Board-Meeting.pdf, Distribution of Produce by Cook County Farm Bureau at the County Board Meeting]                                                                     | 13 A 0008   | Advisory Opinion                               | 
| 1482436815  | [http://opendocs.cookcountyil.gov/ethics/advisory-opinions/13-A-0007-ADVISORY-OPINION-Allocating-County-Funds-for-Pens-Pencils-Magnets-and-Similar-Items-and-Youth-Stipends-Redacted-for-Publication.pdf, Allocating County Funds for Pens, Pencils, Magnets and Similar Items and Youth Stipends (Redacted for Publication)] | 13 A 0007   | Advisory Opinion                               | 
| 1482436815  | [http://opendocs.cookcountyil.gov/ethics/advisory-opinions/13-A-0006-ADVISORY-OPINION-Providing-Volunteer-Legal-Services-to-Persons-in-Chicago-Policy-Custody-Redacted-for-Publication.pdf, Providing Volunteer Legal Services to Persons in Chicago Policy Custody (Redacted for Publication)]                               | 13 A 0006   | Advisory Opinion                               | 
| 1482436815  | [http://opendocs.cookcountyil.gov/ethics/advisory-opinions/13-A-0004-ADVISORY-OPINION-Use-of-County-Funds-to-Purchase-Creamer-Sweetener-and-Similar-Items.pdf, Use of County Funds to Purchase Creamer, Sweetener and Similar Items]                                                                                          | 13 A 0004   | Advisory Opinion                               | 
| 1482436815  | [http://opendocs.cookcountyil.gov/ethics/advisory-opinions/13-A-0002-ADVISORY-OPINION-Sponsorship-by-a-County-Vendor-Redacted-for-Publication.pdf, Sponsorship by a County Vendor (Redacted for Publication)]                                                                                                                 | 13 A 0002   | Advisory Opinion                               | 
| 1482436815  | [http://opendocs.cookcountyil.gov/ethics/advisory-opinions/12-A-0013-ADVISORY-OPINION2-Request-for-Reconsideration-and-Letter-of-Clarification-Redacted-for-Publication.pdf, Request for Reconsideration and Letter of Clarification (Redacted for Publication)]                                                              | 12 A 0013   | Advisory Opinion ? Request for Reconsideration | 
| 1482436815  | [http://opendocs.cookcountyil.gov/ethics/advisory-opinions/12-A-0013-ADVISORY-OPINION1-Use-or-Disclosure-of-Confidential-Information-and-Post-Employment-Restrictions-Redacted-for-Publication.pdf, Use or Disclosure of Confidential Information and Post Employment Restrictions (Redacted for Publication)]                | 12 A 0013   | Advisory Opinion                               | 
```