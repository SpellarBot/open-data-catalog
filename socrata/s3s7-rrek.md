# OCA Self Insurance Fund Close Out

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oca-self-insurance-fund-close-out) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/s3s7-rrek) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/s3s7-rrek/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/s3s7-rrek/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | s3s7-rrek |
| Name | OCA Self Insurance Fund Close Out |
| Attribution | Montgomery County, MD |
| Category | Law/Judicial |
| Tags | law, lawsuit, self insurance fund, litigation |
| Created | 2016-05-17T20:44:40Z |
| Publication Date | 2016-06-07T14:02:33Z |

## Description

Office of the County Attorney Self Insurance Fund Close Out

## Columns

```ls
| Included | Schema Type | Field Name       | Name              | Data Type     | Render Type   |
| ======== | =========== | ================ | ================= | ============= | ============= |
| Yes      | series tag  | matter_id        | Matter No         | text          | text          |
| Yes      | series tag  | matter_title     | Matter Title      | text          | text          |
| Yes      | series tag  | type             | Type of Law       | text          | text          |
| Yes      | time        | date_opened      | Date Opened       | calendar_date | calendar_date |
| Yes      | series tag  | status           | Status            | text          | text          |
| No       |             | statusdate       | Status Date       | calendar_date | calendar_date |
| Yes      | series tag  | agency           | Department/Agency | text          | text          |
| Yes      | series tag  | case_category    | Matter Category   | text          | text          |
| Yes      | series tag  | disposition      | Disposition Code  | text          | text          |
| No       |             | disposition_date | Disposition Date  | calendar_date | calendar_date |
| No       |             | incident_date    | Incident Date     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_opened
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = statusdate,disposition_date,incident_date
```

## Data Commands

```ls
series e:s3s7-rrek d:2013-09-04T00:00:00.000Z t:matter_id=L13-00344 t:status=Open t:matter_title="FIELD, JONATHAN v.  JEWELL, WAVOR, et al." t:agency="Department of Transportation - Ride-On" t:case_category=Tort-Ride-On t:type="SIF Lawsuit" m:row_number.s3s7-rrek=1

series e:s3s7-rrek d:2014-08-21T00:00:00.000Z t:matter_id=L14-00286 t:status=Open t:matter_title="HOWARD, CAROLYN, et al. v. MONTGOMERY COUNTY, MARYLAND, et al." t:agency="Police Department" t:case_category="Tort-Wrongful Death" t:type="SIF Lawsuit" m:row_number.s3s7-rrek=2

series e:s3s7-rrek d:2015-07-21T00:00:00.000Z t:matter_id=15-002619 t:status=Open t:matter_title="DATES, CRAIG, et al. v. THOMAS KOENIG, et al." t:agency="Police Department" t:case_category="Civil Rights-Other" t:type="SIF Lawsuit" m:row_number.s3s7-rrek=3
```

## Meta Commands

```ls
metric m:row_number.s3s7-rrek p:long l:"Row Number"

entity e:s3s7-rrek l:"OCA Self Insurance Fund Close Out" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/s3s7-rrek

property e:s3s7-rrek t:meta.view v:id=s3s7-rrek v:category=Law/Judicial v:averageRating=0 v:name="OCA Self Insurance Fund Close Out" v:attribution="Montgomery County, MD"

property e:s3s7-rrek t:meta.view.license v:name="Public Domain"

property e:s3s7-rrek t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:s3s7-rrek t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| matter_id | matter_title                                                       | type        | date_opened         | status | statusdate          | agency                                 | case_category             | disposition | disposition_date | incident_date       | 
| ========= | ================================================================== | =========== | =================== | ====== | =================== | ====================================== | ========================= | =========== | ================ | =================== | 
| L13-00344 | FIELD, JONATHAN v. JEWELL, WAVOR, et al.                           | SIF Lawsuit | 2013-09-04T00:00:00 | Open   | 2015-10-20T00:00:00 | Department of Transportation - Ride-On | Tort-Ride-On              |             |                  | 2013-07-10T00:00:00 | 
| L14-00286 | HOWARD, CAROLYN, et al. v. MONTGOMERY COUNTY, MARYLAND, et al.     | SIF Lawsuit | 2014-08-21T00:00:00 | Open   | 2015-07-14T00:00:00 | Police Department                      | Tort-Wrongful Death       |             |                  | 2014-02-19T00:00:00 | 
| 15-002619 | DATES, CRAIG, et al. v. THOMAS KOENIG, et al.                      | SIF Lawsuit | 2015-07-21T00:00:00 | Open   | 2015-07-21T00:00:00 | Police Department                      | Civil Rights-Other        |             |                  | 2015-01-15T00:00:00 | 
| 15-002662 | NASSA, NSIBENU COMFORT v. ANDRE T. LUCAS, JR, ET AL.               | SIF Lawsuit | 2015-07-27T00:00:00 | Open   | 2015-07-27T00:00:00 | Department of Transportation - Ride-On | Tort-Ride-On              |             |                  | 2014-10-17T00:00:00 | 
| L06-00041 | Jonesville/ Jerusalem Road - Heirs of Rosa Dorsey; 19505 Jerusalem | SIF Lawsuit | 2006-10-06T00:00:00 | Open   | 2006-10-06T00:00:00 | Montgomery County Government           |                           |             |                  |                     | 
| 16-000605 | Tu, An Thai v. Knott [4] [injunction]                              | SIF Appeal  | 2016-02-02T00:00:00 | Open   | 2016-02-02T00:00:00 | Police Department                      | Civil Rights-False Arrest |             |                  |                     | 
| L11-00160 | REYAZUDDIN, YASMIN v. MONTGOMERY COUNTY, MARYLAND;                 | SIF Lawsuit | 2011-04-14T00:00:00 | Open   | 2011-04-14T00:00:00 | Health and Human Services              | Employment-Other          |             |                  | 2010-02-05T00:00:00 | 
| 16-000797 | SHILLING, CAROL v. IRA THOMAS, ET AL.                              | SIF Lawsuit | 2016-02-10T00:00:00 | Open   | 2016-02-10T00:00:00 | Board of Education                     | Tort-Other                |             |                  | 2012-10-01T00:00:00 | 
| 16-000764 | TAYLOR, MARCUS DEAN v. ISIAH LEGGETT, et al.                       | SIF Lawsuit | 2016-02-05T00:00:00 | Open   | 2016-02-09T00:00:00 | Police Department                      |                           |             |                  |                     | 
| L11-00180 | NNP II-CLARKSBURG, LLC v. MONTGOMERY COUNTY;                       | SIF Lawsuit | 2011-04-25T00:00:00 | Open   | 2011-04-25T00:00:00 | County Council                         |                           |             |                  | 2010-10-26T00:00:00 | 
```