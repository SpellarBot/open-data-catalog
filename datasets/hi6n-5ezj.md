# Comptroller - Comprehensive Annual Financial Report (CAFR)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/comptroller-comprehensive-annual-financial-report-cafr) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/hi6n-5ezj) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hi6n-5ezj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hi6n-5ezj/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | hi6n-5ezj |
| Name | Comptroller - Comprehensive Annual Financial Report (CAFR) |
| Attribution | Cook County Comptroller |
| Category | Finance & Administration |
| Tags | cafr |
| Created | 2016-06-23T01:19:31Z |
| Publication Date | 2016-07-01T00:15:42Z |

## Description

The County has prepared the CAFR in accordance with Generally Accepted Accounting Principles (GAAP). GAAP require that management provide a  narrative introduction, overview and analysis to accompany the basic financial statements in the form of a Management Discussion & Analysis (MD&A). The letter of transmittal in this report is designed to compliment the MD&A and should be read in conjunction with it.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| Yes      | series tag  | link        | Link        | url       | url         |
| Yes      | time        | fiscal_year | Fiscal Year | number    | number      |
| Yes      | series tag  | notes       | Notes       | text      | text        |
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
entity e:hi6n-5ezj l:"Comptroller -  Comprehensive Annual Financial Report (CAFR)" t:attribution="Cook County Comptroller" t:url=https://datacatalog.cookcountyil.gov/api/views/hi6n-5ezj

property e:hi6n-5ezj t:meta.view v:id=hi6n-5ezj v:category="Finance & Administration" v:averageRating=0 v:name="Comptroller -  Comprehensive Annual Financial Report (CAFR)" v:attribution="Cook County Comptroller"

property e:hi6n-5ezj t:meta.view.license v:name="Public Domain"

property e:hi6n-5ezj t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:hi6n-5ezj t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| link                                                                                               | fiscal_year | notes                       | 
| ================================================================================================== | =========== | =========================== | 
| [http://opendocs.cookcountyil.gov/comptroller/cafr/Cook-County-2014-Report-FINAL.pdf, 2014 Report] | 2014        |                             | 
| [http://opendocs.cookcountyil.gov/comptroller/cafr/2013-CAFR.pdf, 2013 Report]                     | 2013        |                             | 
| [http://opendocs.cookcountyil.gov/comptroller/cafr/2012-CAFR-For-Website-Upload1.pdf, 2012 Report] | 2012        |                             | 
| [http://opendocs.cookcountyil.gov/comptroller/cafr/cc_2011CAFR.pdf, 2011 Report]                   | 2011        |                             | 
| [http://opendocs.cookcountyil.gov/comptroller/cafr/2010_CAFR.pdf, 2010 Report]                     | 2010        |                             | 
| [http://opendocs.cookcountyil.gov/comptroller/cafr/cc_2009CAFR_Letter.pdf, 2009 Letter]            | 2009        | Letter issued June 10, 2011 | 
| [http://opendocs.cookcountyil.gov/comptroller/cafr/cc_2008CAFR.pdf, 2008 Report]                   | 2008        |                             | 
| [http://opendocs.cookcountyil.gov/comptroller/cafr/07_CAFR_CookCounty.pdf, 2007 Report]            | 2007        |                             | 
| [http://opendocs.cookcountyil.gov/comptroller/cafr/06_CAFR_CookCounty.pdf, 2006 Report]            | 2006        |                             | 
| [http://opendocs.cookcountyil.gov/comptroller/cafr/05_CAFR_CookCounty.pdf, 2005 Report]            | 2005        |                             | 
```