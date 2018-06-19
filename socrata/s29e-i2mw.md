# OCIO IT Project Oversight Documents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ocio-it-project-oversight-documents-c420b) |
| Metadata | [Link](https://data.wa.gov/api/views/s29e-i2mw) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/s29e-i2mw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/s29e-i2mw/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | s29e-i2mw |
| Name | OCIO IT Project Oversight Documents |
| Attribution | Office of the CIO |
| Category | Procurements and Contracts |
| Tags | it projects ocio |
| Created | 2014-07-30T19:39:22Z |
| Publication Date | 2015-04-08T15:58:21Z |

## Description

Project oversight documents. See OCIO IT Project Oversight Summary (https://data.wa.gov/resource/k495-fmg2) for main project information.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | project             | Project             | text          | text          |
| Yes      | series tag     | document            | Document            | url           | url           |
| Yes      | series tag     | type                | Type                | text          | text          |
| Yes      | series tag     | decision_document   | Decision Document   | checkbox      | checkbox      |
| Yes      | numeric metric | risk_security_level | Risk Security Level | number        | number        |
| Yes      | numeric metric | budget              | Budget              | money         | money         |
| No       |                | project_start       | Project Start       | calendar_date | calendar_date |
| No       |                | project_end         | Project End         | calendar_date | calendar_date |
| Yes      | time           | date_received       | Date Received       | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_start,project_end
```

## Data Commands

```ls
series e:s29e-i2mw d:2014-07-18T00:00:00.000Z t:project="Enterprise Document Management System" t:document="http://waocio.force.com/sfc/servlet.shepherd/version/download/068U0000001AFNNIA4?asPdf=false&" t:decision_document=true t:type="Decision Document" m:risk_security_level=2 m:budget=6297510

series e:s29e-i2mw d:2014-03-31T00:00:00.000Z t:project="Enterprise Document Management System" t:document="http://waocio.force.com/sfc/servlet.shepherd/version/download/068U0000000b0IaIAI?asPdf=false&" t:decision_document=false t:type="Status Report" m:risk_security_level=2

series e:s29e-i2mw d:2013-01-10T00:00:00.000Z t:project="Enterprise Document Management System" t:document="http://waocio.force.com/sfc/servlet.shepherd/version/download/068U0000000ZCo1IAG?asPdf=false&" t:decision_document=true t:type="Investment Plan" m:risk_security_level=2 m:budget=6297510
```

## Meta Commands

```ls
metric m:risk_security_level p:integer l:"Risk Security Level" t:dataTypeName=number

metric m:budget p:double l:Budget t:dataTypeName=money

entity e:s29e-i2mw l:"OCIO IT Project Oversight Documents" t:attribution="Office of the CIO" t:url=https://data.wa.gov/api/views/s29e-i2mw

property e:s29e-i2mw t:meta.view v:id=s29e-i2mw v:category="Procurements and Contracts" v:attributionLink=http://www.ocio.wa.gov/its-transparent-project-dashboard v:averageRating=0 v:name="OCIO IT Project Oversight Documents" v:attribution="Office of the CIO"

property e:s29e-i2mw t:meta.view.license v:name="Public Domain"

property e:s29e-i2mw t:meta.view.owner v:id=2cik-4ce4 v:screenName="Jason McKee" v:displayName="Jason McKee"

property e:s29e-i2mw t:meta.view.tableauthor v:id=2cik-4ce4 v:screenName="Jason McKee" v:roleName=publisher v:displayName="Jason McKee"
```

## Top Records

```ls
| project                               | document                                                                                                                                     | type                     | decision_document | risk_security_level | budget     | project_start       | project_end         | date_received       | 
| ===================================== | ============================================================================================================================================ | ======================== | ================= | =================== | ========== | =================== | =================== | =================== | 
| Enterprise Document Management System | [http://waocio.force.com/sfc/servlet.shepherd/version/download/068U0000000bOYQIA2?asPdf=false&, EDMS PM Monthly Status Jan 2014.pdf]         | Status Report            | false             |                     |            |                     |                     | 2014-05-08T00:00:00 | 
| Enterprise Document Management System | [http://waocio.force.com/sfc/servlet.shepherd/version/download/068U0000001AFNNIA4?asPdf=false&, EDMS Hold Approval.pdf]                      | Decision Document        | true              | 2                   | 6297510.00 | 2013-01-01T00:00:00 | 2017-01-02T00:00:00 | 2014-07-18T00:00:00 | 
| Enterprise Document Management System | [http://waocio.force.com/sfc/servlet.shepherd/version/download/068U0000000b6XQIAY?asPdf=false&, EDMS QA Report December 2013.pdf]            | Quality Assurance Report | false             |                     |            |                     |                     | 2014-04-22T00:00:00 | 
| Enterprise Document Management System | [http://waocio.force.com/sfc/servlet.shepherd/version/download/068U0000000b0IaIAI?asPdf=false&, EDMS State PM Monthly Report March 2014.pdf] | Status Report            | false             | 2                   |            |                     |                     | 2014-03-31T00:00:00 | 
| Enterprise Document Management System | [http://waocio.force.com/sfc/servlet.shepherd/version/download/068U0000000bOYOIA2?asPdf=false&, EDMS State PM Monthly Report April 2014.pdf] | Status Report            | false             |                     |            |                     |                     | 2014-05-08T00:00:00 | 
| Enterprise Document Management System | [http://waocio.force.com/sfc/servlet.shepherd/version/download/068U0000000b6XSIAY?asPdf=false&, EDMS QA Report January 2014.pdf]             | Quality Assurance Report | false             |                     |            |                     |                     | 2014-04-22T00:00:00 | 
| Enterprise Document Management System | [http://waocio.force.com/sfc/servlet.shepherd/version/download/068U0000000ZCo1IAG?asPdf=false&, EDMS DIS Investment Plan FINAL.pdf]          | Investment Plan          | true              | 2                   | 6297510.00 | 2013-01-01T00:00:00 | 2017-01-02T00:00:00 | 2013-01-10T00:00:00 | 
| Enterprise Document Management System | [http://waocio.force.com/sfc/servlet.shepherd/version/download/068U0000000bOYNIA2?asPdf=false&, EDMS QA Report April 2014.pdf]               | Quality Assurance Report | false             |                     |            |                     |                     | 2014-05-08T00:00:00 | 
| Enterprise Document Management System | [http://waocio.force.com/sfc/servlet.shepherd/version/download/068U0000000b6XUIAY?asPdf=false&, EDMS Quality Assurance Plan 12-2013.pdf]     | Quality Assurance Report | false             |                     |            |                     |                     | 2014-04-22T00:00:00 | 
| Enterprise Document Management System | [http://waocio.force.com/sfc/servlet.shepherd/version/download/068U0000000b6XRIAY?asPdf=false&, EDMS QA Report February 2014.pdf]            | Quality Assurance Report | false             |                     |            |                     |                     | 2014-04-22T00:00:00 | 
```