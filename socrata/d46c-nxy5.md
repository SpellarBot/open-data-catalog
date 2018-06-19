# Investor Relations - Bond Official Statements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/investor-relations-bond-official-statements) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/d46c-nxy5) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/d46c-nxy5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/d46c-nxy5/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | d46c-nxy5 |
| Name | Investor Relations - Bond Official Statements |
| Attribution | Cook County Bureau of Finance |
| Category | Finance & Administration |
| Created | 2016-05-19T02:30:59Z |
| Publication Date | 2016-11-29T19:48:15Z |

## Description

The official statements below provide detailed information about the outstanding bonds issued by the County. The full faith and credit of the County is pledged to the punctual payment of the principal and of interest on General Obligation bonds, with a pledge of home rule sales tax revenues securing the associated sales tax revenue bond issues.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | link        | Link       | url       | url         |
| Yes      | series tag  | type        | Type       | text      | text        |
| Yes      | series tag  | series      | Series     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:d46c-nxy5 d:2016-06-22T09:37:30.000Z t:series=2013 t:link=http://opendocs.cookcountyil.gov/investor-relations/bond-statements/ILCook04a-Final1.pdf t:type="Sales Tax Revenue Bonds" m:row_number.d46c-nxy5=1

series e:d46c-nxy5 d:2016-06-22T09:37:30.000Z t:series="2010 A & C" t:link=http://opendocs.cookcountyil.gov/investor-relations/bond-statements/2011ABCD-OS1.pdf t:type="General Obligation Bond" m:row_number.d46c-nxy5=2

series e:d46c-nxy5 d:2016-06-22T09:37:30.000Z t:series="2010 D & E" t:link=http://opendocs.cookcountyil.gov/investor-relations/bond-statements/Cook_OfficialStatement_2010DE1.pdf t:type="General Obligation Bond" m:row_number.d46c-nxy5=3
```

## Meta Commands

```ls
metric m:row_number.d46c-nxy5 p:long l:"Row Number"

entity e:d46c-nxy5 l:"Investor Relations - Bond Official Statements" t:attribution="Cook County Bureau of Finance" t:url=https://datacatalog.cookcountyil.gov/api/views/d46c-nxy5

property e:d46c-nxy5 t:meta.view v:id=d46c-nxy5 v:category="Finance & Administration" v:averageRating=0 v:name="Investor Relations - Bond Official Statements" v:attribution="Cook County Bureau of Finance"

property e:d46c-nxy5 t:meta.view.license v:name="Public Domain"

property e:d46c-nxy5 t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:d46c-nxy5 t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| :updated_at | link                                                                                                                                         | type                               | series        | 
| =========== | ============================================================================================================================================ | ================================== | ============= | 
| 1466588250  | [http://opendocs.cookcountyil.gov/investor-relations/bond-statements/ILCook04a-Final1.pdf, Sales Tax Revenue Bonds 2013]                     | Sales Tax Revenue Bonds            | 2013          | 
| 1466588250  | [http://opendocs.cookcountyil.gov/investor-relations/bond-statements/2011ABCD-OS1.pdf, General Obligation Bond 2010 A & C]                   | General Obligation Bond            | 2010 A & C    | 
| 1466588250  | [http://opendocs.cookcountyil.gov/investor-relations/bond-statements/Cook_OfficialStatement_2010DE1.pdf, General Obligation Bond 2010 D & E] | General Obligation Bond            | 2010 D & E    | 
| 1466588250  | [http://opendocs.cookcountyil.gov/investor-relations/bond-statements/Cook_OfficialStatement_2010G1.pdf, General Obligation Bond 2010 G]      | General Obligation Bond            | 2010 G        | 
| 1466588250  | [http://opendocs.cookcountyil.gov/investor-relations/bond-statements/cc_GOB_Series2009AB1.pdf, General Obligation Bond 2009 A & B]           | General Obligation Bond            | 2009 A & B    | 
| 1466588250  | [http://opendocs.cookcountyil.gov/investor-relations/bond-statements/cc_GOB_Series2009CDE1.pdf, General Obligation Bond 2009 C, D & E]       | General Obligation Bond            | 2009 C, D & E | 
| 1466588250  | [http://opendocs.cookcountyil.gov/investor-relations/bond-statements/OfficialStatement_Series2006B1.pdf, General Obligation Bond 2006 B]     | General Obligation Bond            | 2006 B        | 
| 1466588250  | [http://opendocs.cookcountyil.gov/investor-relations/bond-statements/Series-2004C-Official-Statement1.pdf, General Obligation Bond 2004 C]   | General Obligation Bond            | 2004 C        | 
| 1467303209  | [http://opendocs.cookcountyil.gov/investor-relations/bond-statements/ILCook09a-FIN.pdf, General Obligation Refunding Bonds Series 2016A]     | General Obligation Refunding Bonds | 2016 A        | 
| 1467303229  | [http://opendocs.cookcountyil.gov/investor-relations/bond-statements/OS-Series-2014A1.pdf, General Obligation Refunding Bonds 2014A]         | General Obligation Refunding Bonds | 2014 A        | 
```