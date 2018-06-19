# Investor Relations - Credit Agreements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/investor-relations-credit-agreements) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/cppp-8hqt) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/cppp-8hqt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/cppp-8hqt/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | cppp-8hqt |
| Name | Investor Relations - Credit Agreements |
| Attribution | Cook County Bureau of Finance |
| Category | Finance & Administration |
| Created | 2016-07-07T15:41:24Z |
| Publication Date | 2016-07-11T03:32:59Z |

## Description

The County is a party to various credit agreements, including short term notes, Direct Pay variable rate agreements , Direct Placement variable rate agreements, and an operating Line of Credit.  Current credit agreements that the county is a party to are made available below.

## Columns

```ls
| Included | Schema Type | Field Name | Name      | Data Type     | Render Type   |
| ======== | =========== | ========== | ========= | ============= | ============= |
| Yes      | series tag  | type       | Type      | text          | text          |
| Yes      | series tag  | series     | Series    | text          | text          |
| Yes      | series tag  | agreement  | Agreement | url           | url           |
| Yes      | time        | date       | Date      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:cppp-8hqt d:2012-07-30T00:00:00.000Z t:series=2012A t:agreement=http://opendocs.cookcountyil.gov/investor-relations/credit-agreements/2012A_Agmt1.pdf t:type="Direct Purchase Agreement" m:row_number.cppp-8hqt=1

series e:cppp-8hqt d:2012-07-30T00:00:00.000Z t:series=2012A t:agreement=http://opendocs.cookcountyil.gov/investor-relations/credit-agreements/2012A_Indenture.pdf t:type="Direct Purchase Agreement" m:row_number.cppp-8hqt=2

series e:cppp-8hqt d:2016-05-02T00:00:00.000Z t:series=2012A t:agreement=http://opendocs.cookcountyil.gov/investor-relations/credit-agreements/01-First-Amendment-to-Indenture-of-Trust.pdf t:type="Direct Purchase Agreement" m:row_number.cppp-8hqt=3
```

## Meta Commands

```ls
metric m:row_number.cppp-8hqt p:long l:"Row Number"

entity e:cppp-8hqt l:"Investor Relations - Credit Agreements" t:attribution="Cook County Bureau of Finance" t:url=https://datacatalog.cookcountyil.gov/api/views/cppp-8hqt

property e:cppp-8hqt t:meta.view v:id=cppp-8hqt v:category="Finance & Administration" v:averageRating=0 v:name="Investor Relations - Credit Agreements" v:attribution="Cook County Bureau of Finance"

property e:cppp-8hqt t:meta.view.license v:name="Public Domain"

property e:cppp-8hqt t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:cppp-8hqt t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| type                                  | series | agreement                                                                                                                                          | date                | 
| ===================================== | ====== | ================================================================================================================================================== | =================== | 
| Direct Purchase Agreement             | 2012A  | [http://opendocs.cookcountyil.gov/investor-relations/credit-agreements/2012A_Agmt1.pdf, Purchasing Agreement]                                      | 2012-07-30T00:00:00 | 
| Direct Purchase Agreement             | 2012A  | [http://opendocs.cookcountyil.gov/investor-relations/credit-agreements/2012A_Indenture.pdf, Indenture]                                             | 2012-07-30T00:00:00 | 
| Direct Purchase Agreement             | 2012A  | [http://opendocs.cookcountyil.gov/investor-relations/credit-agreements/01-First-Amendment-to-Indenture-of-Trust.pdf, First Amendment to Indenture] | 2016-05-02T00:00:00 | 
| Direct Purchase Agreement             | 2012B  | [http://opendocs.cookcountyil.gov/investor-relations/credit-agreements/2012B_Agmt.pdf, Purchasing Agreement]                                       | 2012-08-23T00:00:00 | 
| Direct Purchase Agreement             | 2012B  | [http://opendocs.cookcountyil.gov/investor-relations/credit-agreements/2012B_Indenture.pdf, Indenture]                                             | 2012-08-23T00:00:00 | 
| Direct Purchase Agreement             | 2012C  | [http://opendocs.cookcountyil.gov/investor-relations/credit-agreements/Purchasing-Agreement.pdf, Purchasing Agreement]                             | 2014-10-15T00:00:00 | 
| Direct Purchase Agreement             | 2012C  | [http://opendocs.cookcountyil.gov/investor-relations/credit-agreements/Indenture.pdf, Indenture]                                                   | 2014-10-15T00:00:00 | 
| Line of Credit Agreement              |        | [http://opendocs.cookcountyil.gov/investor-relations/credit-agreements/Revolving-Credit-Agreement.pdf, Revolving Credit Agreement]                 | 2016-02-25T00:00:00 | 
| Revolving Line of Credit (Tax-Exempt) | 2014D  | [http://opendocs.cookcountyil.gov/investor-relations/credit-agreements/Trust-Indenture.pdf, Trust Indenture]                                       | 2014-10-01T00:00:00 | 
| Revolving Line of Credit (Tax-Exempt) | 2014D  | [http://opendocs.cookcountyil.gov/investor-relations/credit-agreements/Tax-Compliance-Certificate.pdf, Tax Compliance Certificate]                 | 2014-12-19T00:00:00 | 
```