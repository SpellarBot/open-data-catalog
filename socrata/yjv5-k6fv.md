# Inspector General - Employment Plan Officer Semi-Annual Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inspector-general-employment-plan-officer-semi-annual-reports) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/yjv5-k6fv) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/yjv5-k6fv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/yjv5-k6fv/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | yjv5-k6fv |
| Name | Inspector General - Employment Plan Officer Semi-Annual Reports |
| Attribution | Cook County Office of the Independent Inspector General |
| Category | Finance & Administration |
| Created | 2016-07-26T18:16:46Z |
| Publication Date | 2017-03-16T15:31:29Z |

## Description

Pursuant to the Employment Plan, the OIIG Employment Plan Officer will issue semi-annual reports every March 15 and September 15 to the President, the IIG, and the Compliance Administrator, while acting, describing his or her activities during the prior six months, including, but not limited to: (i) auditing activities as required by this OIIG Employment Plan; (ii) any violations of the OIIG Employment Plan discovered; (iii) any remedial actions recommended; and (iv) any corrective action taken by the IIG to address the violations.  These reports can be accessed below.

## Columns

```ls
| Included | Schema Type | Field Name | Name | Data Type     | Render Type   |
| ======== | =========== | ========== | ==== | ============= | ============= |
| Yes      | series tag  | link       | Link | url           | url           |
| Yes      | time        | date       | Date | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:yjv5-k6fv d:2016-03-15T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/inspector-general/employment/semi-annual/Employment-Plan-Officers-Semi-Annual-Report-March-2016.pdf m:row_number.yjv5-k6fv=1

series e:yjv5-k6fv d:2015-09-15T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/inspector-general/employment/semi-annual/Employment-Plan-Officers-Semi-Annual-Report-September-2015.pdf m:row_number.yjv5-k6fv=2

series e:yjv5-k6fv d:2015-03-13T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/inspector-general/employment/semi-annual/Employment-Plan-Officers-Semi-Annual-Report-March-2015.pdf m:row_number.yjv5-k6fv=3
```

## Meta Commands

```ls
metric m:row_number.yjv5-k6fv p:long l:"Row Number"

entity e:yjv5-k6fv l:"Inspector General - Employment Plan Officer Semi-Annual Reports" t:attribution="Cook County Office of the Independent Inspector General" t:url=https://datacatalog.cookcountyil.gov/api/views/yjv5-k6fv

property e:yjv5-k6fv t:meta.view v:id=yjv5-k6fv v:category="Finance & Administration" v:averageRating=0 v:name="Inspector General - Employment Plan Officer Semi-Annual Reports" v:attribution="Cook County Office of the Independent Inspector General"

property e:yjv5-k6fv t:meta.view.license v:name="Public Domain"

property e:yjv5-k6fv t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:yjv5-k6fv t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| link                                                                                                                                                                                                    | date                | 
| ======================================================================================================================================================================================================= | =================== | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/semi-annual/Employment-Plan-Officers-Semi-Annual-Report-March-2016.pdf, Employment Plan Officer?s Semi-Annual Report March 2016]         | 2016-03-15T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/semi-annual/Employment-Plan-Officers-Semi-Annual-Report-September-2015.pdf, Employment Plan Officer?s Semi-Annual Report September 2015] | 2015-09-15T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/semi-annual/Employment-Plan-Officers-Semi-Annual-Report-March-2015.pdf, Employment Plan Officer?s Semi-Annual Report March 2015]         | 2015-03-13T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/semi-annual/Employment-Plan-Officers-Semi-Annual-Report-September-2014.pdf, Employment Plan Officer?s Semi-Annual Report September 2014] | 2014-09-15T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/semi-annual/Semi-Annual-Report-3-15-14.pdf, Employment Plan Officer?s Semi-Annual Report March 2014]                                     | 2014-03-15T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/semi-annual/Semi-Annual-Report-9-16-13.pdf, Employment Plan Officer?s Semi-Annual Report September 2013]                                 | 2013-09-16T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/semi-annual/Employment-Plan-Officers-Semi-Annual-Report-September-2016.pdf, Employment Plan Officer's Semi-Annual Report September 2016] | 2016-09-15T00:00:00 | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/semi-annual/Employment-Plan-Officers-Semi-Annual-Report-March-2017.pdf, Employment Plan Officer's Semi-Annual Report March 2017]         | 2017-03-15T00:00:00 | 
```