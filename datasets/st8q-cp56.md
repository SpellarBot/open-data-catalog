# IEMA Radon Measurement and Mitigation Professionals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iema-radon-measurement-and-mitigation-professionals-0cef6) |
| Metadata | [Link](https://data.illinois.gov/api/views/st8q-cp56) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/st8q-cp56/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/st8q-cp56/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | st8q-cp56 |
| Name | IEMA Radon Measurement and Mitigation Professionals |
| Category | Public Health |
| Created | 2011-09-29T15:13:34Z |
| Publication Date | 2011-10-21T21:13:46Z |

## Description

List of Radon Measurement and Mitigation Professionals and Technicians Licensed in the state of Illinois.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type | Render Type |
| ======== | =========== | ======================== | ======================== | ========= | =========== |
| No       | time        | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag  | lastname                 | LASTNAME                 | text      | text        |
| Yes      | series tag  | firstname                | FIRSTNAME                | text      | text        |
| Yes      | series tag  | category                 | CATEGORY                 | text      | text        |
| Yes      | series tag  | professional_responsible | PROFESSIONAL RESPONSIBLE | text      | text        |
| Yes      | series tag  | business_name            | BUSINESS NAME            | text      | text        |
| Yes      | series tag  | county                   | COUNTY                   | text      | text        |
| Yes      | series tag  | email                    | EMAIL                    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:st8q-cp56 d:2011-09-29T08:13:36.000Z t:business_name="Speaker of the House Home Inspections" t:category="Measurement Professional" t:email=keninspector@gmail.com t:county="Du Page" t:lastname=Jacobson t:firstname=Kenneth m:row_number.st8q-cp56=1

series e:st8q-cp56 d:2011-09-29T08:13:36.000Z t:business_name="Speaker of the House Home Inspections" t:category="Measurement Professional" t:email=eemass@comcast.net t:county="Du Page" t:lastname=Massart t:firstname=Edward m:row_number.st8q-cp56=2

series e:st8q-cp56 d:2011-09-29T08:13:36.000Z t:business_name="LN Brady Enterprises, Inc" t:category="Measurement Professional" t:email=lnbrady67@yahoo.com t:county="Du Page" t:lastname=Brady t:firstname=Lawrence m:row_number.st8q-cp56=3
```

## Meta Commands

```ls
metric m:row_number.st8q-cp56 p:long l:"Row Number"

entity e:st8q-cp56 l:"IEMA Radon Measurement and Mitigation Professionals" t:url=https://data.illinois.gov/api/views/st8q-cp56

property e:st8q-cp56 t:meta.view v:id=st8q-cp56 v:category="Public Health" v:averageRating=0 v:name="IEMA Radon Measurement and Mitigation Professionals"

property e:st8q-cp56 t:meta.view.owner v:id=fx6u-bzri v:screenName=Paul v:displayName=Paul

property e:st8q-cp56 t:meta.view.tableauthor v:id=fx6u-bzri v:screenName=Paul v:roleName=publisher v:displayName=Paul
```

## Top Records

```ls
| :updated_at | lastname | firstname | category                 | professional_responsible | business_name                         | county  | email                       | 
| =========== | ======== | ========= | ======================== | ======================== | ===================================== | ======= | =========================== | 
| 1317284016  | Jacobson | Kenneth   | Measurement Professional |                          | Speaker of the House Home Inspections | Du Page | keninspector@gmail.com      | 
| 1317284016  | Massart  | Edward    | Measurement Professional |                          | Speaker of the House Home Inspections | Du Page | eemass@comcast.net          | 
| 1317284016  | Brady    | Lawrence  | Measurement Professional |                          | LN Brady Enterprises, Inc             | Du Page | lnbrady67@yahoo.com         | 
| 1317284016  | Schuman  | Jeffrey   | Mitigation Professional  |                          | Heritage Radon Mitigation, Inc.       | Kane    | heritageradon@sbcglobal.net | 
| 1317284016  | Westman  | Wayne     | Mitigation Professional  |                          | ARMS Radon Mitigation Service, Inc    | Kane    | wwestman@sbcglobal.net      | 
| 1317284016  | De Boer  | Lawrence  | Measurement Technician   | Michael Firnsin          | DIMAR Enterprises, Inc                | Du Page |                             | 
| 1317284016  | Firnsin  | Michael   | Measurement Professional |                          | DIMAR Enterprises, Inc                | Du Page | miwema@aol.com              | 
| 1317284016  | Forde    | Peter     | Measurement Technician   | Michael Firnsin          | DIMAR Enterprises, Inc                | Du Page | miwema@aol.com              | 
| 1317284016  | Spencer  | Guy       | Mitigation Professional  |                          | VSI Radon Reduction Corp.             | Du Page |                             | 
| 1317284016  | Cotner   | Stuart    | Measurement Technician   | Tom Hener                | Castle Home Inspections Inc.          | Du Page | wercastlehome@sbcglobal.net | 
```