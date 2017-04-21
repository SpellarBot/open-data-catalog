# 33rd Ward Alderman Applicants - 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/33rd-ward-alderman-applicants-2013-b4c18) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ht96-cigt) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ht96-cigt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ht96-cigt/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ht96-cigt |
| Name | 33rd Ward Alderman Applicants - 2013 |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | city council, elections |
| Created | 2013-08-15T16:08:40Z |
| Publication Date | 2013-08-15T19:42:10Z |

## Description

Applicants to the 33rd Ward Alderman vacancy in 2013 with links to applications.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | series tag  | full_name        | FULL NAME        | text      | text        |
| Yes      | series tag  | last_name        | LAST NAME        | text      | text        |
| Yes      | series tag  | first_name       | FIRST NAME       | text      | text        |
| Yes      | series tag  | middle_name      | MIDDLE NAME      | text      | text        |
| Yes      | series tag  | suffix           | SUFFIX           | text      | text        |
| Yes      | series tag  | met_requirements | MET REQUIREMENTS | text      | text        |
| Yes      | series tag  | appointed        | APPOINTED        | text      | text        |
| Yes      | series tag  | application      | APPLICATION      | url       | url         |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ht96-cigt d:2013-01-01T00:00:00.000Z t:first_name=Edmund t:application="http://www.cityofchicago.org/content/dam/city/about/aldermanicapplications/ward 33/JosephSieracki.pdf" t:middle_name=Joseph t:last_name=Sieracki t:met_requirements=Y t:full_name="Edmund Joseph Sieracki" m:row_number.ht96-cigt=1

series e:ht96-cigt d:2013-01-01T00:00:00.000Z t:appointed=Y t:first_name=Deborah t:application="http://www.cityofchicago.org/content/dam/city/about/aldermanicapplications/ward 33/DebMell.pdf" t:middle_name=Lynn t:last_name=Mell t:met_requirements=Y t:full_name="Deborah Lynn Mell" m:row_number.ht96-cigt=2

series e:ht96-cigt d:2013-01-01T00:00:00.000Z t:first_name=Gretchen t:application="http://www.cityofchicago.org/content/dam/city/about/aldermanicapplications/ward 33/GretchenHelmreich.pdf" t:middle_name=Carol t:last_name=Helmreich t:met_requirements=Y t:full_name="Gretchen Carol Helmreich" m:row_number.ht96-cigt=3
```

## Meta Commands

```ls
metric m:row_number.ht96-cigt p:long l:"Row Number"

entity e:ht96-cigt l:"33rd Ward Alderman Applicants - 2013" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/ht96-cigt

property e:ht96-cigt t:meta.view v:id=ht96-cigt v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="33rd Ward Alderman Applicants - 2013" v:attribution="City of Chicago"

property e:ht96-cigt t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:ht96-cigt t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| full_name                | last_name | first_name | middle_name | suffix | met_requirements | appointed | application                                                                                                      | 
| ======================== | ========= | ========== | =========== | ====== | ================ | ========= | ================================================================================================================ | 
| Edmund Joseph Sieracki   | Sieracki  | Edmund     | Joseph      |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/about/aldermanicapplications/ward 33/JosephSieracki.pdf, null]    | 
| Deborah Lynn Mell        | Mell      | Deborah    | Lynn        |        | Y                | Y         | [http://www.cityofchicago.org/content/dam/city/about/aldermanicapplications/ward 33/DebMell.pdf, null]           | 
| Gretchen Carol Helmreich | Helmreich | Gretchen   | Carol       |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/about/aldermanicapplications/ward 33/GretchenHelmreich.pdf, null] | 
| Annisa Michele Wanat     | Wanat     | Annisa     | Wanat       |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/about/aldermanicapplications/ward 33/AnnisaWanat.pdf, null]       | 
| Andrew Amador Tinajero   | Tinajero  | Andrew     | Amador      |        | N                |           | [http://www.cityofchicago.org/content/dam/city/about/aldermanicapplications/ward 33/AmadorTinajero.pdf, null]    | 
| Grace Troccolo Rink      | Rink      | Grace      | Troocol     |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/about/aldermanicapplications/ward 33/GraceRink.pdf, null]         | 
| Sergiusz Piotr Zgrzebski | Zgrzebski | Sergiusz   | Piotr       |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/about/aldermanicapplications/ward 33/PiotrZgrzebski.pdf, null]    | 
| Robert F. Elrick         | Elrick    | Robert     | F.          |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/about/aldermanicapplications/ward 33/RobertElrick.pdf, null]      | 
| Jonathan Andrew Markel   | Markel    | Jonathan   | Markel      |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/about/aldermanicapplications/ward 33/JonMarkel.pdf, null]         | 
| Elizabeth Lynn Gomez     | Gomez     | Lynn       | Gomez       |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/about/aldermanicapplications/ward 33/ElizabethGomez.pdf, null]    | 
```