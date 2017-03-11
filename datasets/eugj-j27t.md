# American Recovery And Reinvestment Act Of 2009 ( ARRA)

## Dataset

* [Dataset URL](https://data.ct.gov/api/views/eugj-j27t/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/american-recovery-and-reinvestment-act-of-2009-arra)
* Id = eugj-j27t
* Name = American Recovery And Reinvestment Act Of 2009 ( ARRA)
* Category = Government
* Tags = [arra, opm]
* Created = 2014-06-26T14:59:44Z
* Publication Date = 2014-06-26T15:57:24Z
* Rows Updated = 2014-06-26T14:59:52Z

## Description

Approximately $4.3 million of federal funds was distributed to 159 police departments/municipalities with the primary purpose to assist towns with participating in the American Recovery and Reinvestment Act of 2009 (ARRA) distribution of criminal justice grant funds.  Data fields include: (1) Town Name; (2) Total Award; (3) Total Expenditures; and (4) Summary description of goods and services procured.

## Columns

```ls
| Name             | Field Name       | Data Type | Render Type | Schema Type    | Included | 
| ================ | ================ | ========= | =========== | ============== | ======== | 
| updated_at       | :updated_at      | meta_data | meta_data   | time           | Yes      | 
| Town_Name        | town_name        | text      | text        | series tag     | Yes      | 
| Grant_Number     | grant_number     | text      | text        | series tag     | Yes      | 
| Fed_Grant_Award  | fed_grant_award  | money     | money       | numeric metric | Yes      | 
| Tot_Fed_Expended | tot_fed_expended | money     | money       | numeric metric | Yes      | 
| PROJECT_SUMMARY  | project_summary  | text      | text        | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:eugj-j27t d:2014-06-26T07:59:48.000Z t:town_name=Andover t:grant_number=09RECJAGLO7511 t:project_summary="To enhance community safety and quality of life by enforcing Connecticut motor vehicle laws through special overtime." m:fed_grant_award=9100 m:tot_fed_expended=8842.42

series e:eugj-j27t d:2014-06-26T07:59:48.000Z t:town_name=Ansonia t:grant_number=09RECJAGLO7512 t:project_summary="To increase traffic safety by enforcing speeding laws and identify and address quality of life issues by means of plain cothes officers issigned to the Anti-Crime Unit." m:fed_grant_award=30000 m:tot_fed_expended=30000

series e:eugj-j27t d:2014-06-26T07:59:48.000Z t:town_name=Avon t:grant_number=09RECJAGLO7514 t:project_summary="To purchase Automatic External Defibillators (AED) and radar and laser units to be used in speed enforcement." m:fed_grant_award=30000 m:tot_fed_expended=30000
```

## Meta Commands

```ls
Enhance security for recreation park. Protect town property and public safety for

residents." m:fed_grant_award=9100 m:tot_fed_expended=9072

entity e:eugj-j27t l:"American Recovery And Reinvestment Act Of 2009 ( ARRA)" t:url=https://data.ct.gov/api/views/eugj-j27t

property e:eugj-j27t t:meta.view d:2017-03-03T13:57:13.248Z v:id=eugj-j27t v:category=Government v:averageRating=0 v:name="American Recovery And Reinvestment Act Of 2009 ( ARRA)"

property e:eugj-j27t t:meta.view.owner d:2017-03-03T13:57:13.248Z v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"

property e:eugj-j27t t:meta.view.tableauthor d:2017-03-03T13:57:13.248Z v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```