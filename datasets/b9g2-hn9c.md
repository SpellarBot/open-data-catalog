# Lobbyist Data - Lobbyist Gift Report (Deprecated October 2015)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-lobbyist-gift-report-674c3) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/b9g2-hn9c) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/b9g2-hn9c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/b9g2-hn9c/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | b9g2-hn9c |
| Name | Lobbyist Data - Lobbyist Gift Report (Deprecated October 2015) |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | lobbyists, ethics, deprecated |
| Created | 2011-09-30T08:01:22Z |
| Publication Date | 2016-12-06T10:31:01Z |

## Description

OUTDATED. See similar current data at https://data.cityofchicago.org/d/5d79-9xqr -- The lobbyist gift report is part of the Lobbyist Activity Report, a notarized disclosure that must be filed twice each year (January 20th and July 20th) http://bit.ly/q2lRTh. Lobbyists must report every gift given to an official or employee of the City by the lobbyist during the reporting period. All lobbyist gift reports are submitted to the Board of Ethics in paper form and are available in their entirety in the Board's offices. The Board has, since 2000, compiled and posted static lists of all lobbyists and their clients online. / Data Owner: Board of Ethics [http://j.mp/mbH9BN] / Time Period: January 1, 2011 to present / Frequency: Data is updated daily / Related Applications: Registered Lobbyist List [http://bit.ly/FOctNY]

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | filing_year             | FILING YEAR             | number    | number      |
| Yes      | series tag     | lobbyist_last_name      | LOBBYIST LAST NAME      | text      | text        |
| Yes      | series tag     | lobbyist_first_name     | LOBBYIST FIRST NAME     | text      | text        |
| Yes      | series tag     | lobbyist_middle_initial | LOBBYIST MIDDLE INITIAL | text      | text        |
| Yes      | series tag     | employer_name           | EMPLOYER NAME           | text      | text        |
| Yes      | series tag     | recipient_name          | RECIPIENT NAME          | text      | text        |
| Yes      | series tag     | recipient_title         | RECIPIENT TITLE         | text      | text        |
| Yes      | series tag     | recipient_agency_name   | RECIPIENT AGENCY NAME   | text      | text        |
| Yes      | series tag     | gift_description        | GIFT DESCRIPTION        | text      | text        |
| Yes      | numeric metric | value                   | VALUE                   | money     | money       |
| Yes      | numeric metric | filing_period           | FILING PERIOD           | number    | text        |
```

## Time Field

```ls
Value = filing_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:b9g2-hn9c d:2011-01-01T00:00:00.000Z t:lobbyist_first_name=Dennis t:recipient_agency_name="DEPT OF FIRE" t:employer_name="Northern Trust Corporation" t:gift_description=lunch t:recipient_name="Charles Stewart" t:lobbyist_last_name=Anosike t:recipient_title="Dep. Fire Comm" t:lobbyist_middle_initial=O m:value=22.95 m:filing_period=1

series e:b9g2-hn9c d:2011-01-01T00:00:00.000Z t:lobbyist_first_name=John t:recipient_agency_name="MAYOR'S OFFICE" t:employer_name="McGuire Woods Consulting LLC" t:gift_description=meal t:recipient_name="Joan Coogan" t:lobbyist_last_name=Dunn t:recipient_title=Director t:lobbyist_middle_initial=F m:value=14.1 m:filing_period=1

series e:b9g2-hn9c d:2011-01-01T00:00:00.000Z t:lobbyist_first_name=John t:recipient_agency_name="OFFICE OF THE CITY TREASURER" t:employer_name="McGuire Woods Consulting LLC" t:gift_description=meal t:recipient_name="Stephanie Neely" t:lobbyist_last_name=Dunn t:recipient_title=Treasurer t:lobbyist_middle_initial=F m:value=39.41 m:filing_period=1
```

## Meta Commands

```ls
metric m:value p:double l:VALUE t:dataTypeName=money

metric m:filing_period p:integer l:"FILING PERIOD" t:dataTypeName=number

entity e:b9g2-hn9c l:"Lobbyist Data - Lobbyist Gift Report (Deprecated October 2015)" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/b9g2-hn9c

property e:b9g2-hn9c t:meta.view v:id=b9g2-hn9c v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Lobbyist Gift Report (Deprecated October 2015)" v:attribution="City of Chicago"

property e:b9g2-hn9c t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:b9g2-hn9c t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| filing_year | lobbyist_last_name | lobbyist_first_name | lobbyist_middle_initial | employer_name                | recipient_name   | recipient_title | recipient_agency_name        | gift_description | value | filing_period | 
| =========== | ================== | =================== | ======================= | ============================ | ================ | =============== | ============================ | ================ | ===== | ============= | 
| 2011        | Anosike            | Dennis              | O                       | Northern Trust Corporation   | Charles Stewart  | Dep. Fire Comm  | DEPT OF FIRE                 | lunch            | 22.95 | 1             | 
| 2011        | Dunn               | John                | F                       | McGuire Woods Consulting LLC | Joan Coogan      | Director        | MAYOR'S OFFICE               | meal             | 14.1  | 1             | 
| 2011        | Dunn               | John                | F                       | McGuire Woods Consulting LLC | Stephanie Neely  | Treasurer       | OFFICE OF THE CITY TREASURER | meal             | 39.41 | 1             | 
| 2011        | Dunn               | John                | F                       | McGuire Woods Consulting LLC | Joan Coogan      | Director        | MAYOR'S OFFICE               | meal             | 12.12 | 1             | 
| 2011        | Dunn               | John                | F                       | McGuire Woods Consulting LLC | Joan Coogan      | Director        | MAYOR'S OFFICE               | meal             | 15.06 | 1             | 
| 2011        | Dunn               | John                | F                       | McGuire Woods Consulting LLC | Ken Meyer        | Asst.           | MAYOR'S OFFICE               | meal             | 14.1  | 1             | 
| 2011        | Dunn               | John                | F                       | McGuire Woods Consulting LLC | Mara Georges     | Attorney        | DEPT OF LAW                  | meal             | 12.12 | 1             | 
| 2011        | Houlihan           | Margaret            |                         | United Airlines              | Mary O'Connor    | alderman        | CITY COUNCIL                 | breakfast        | 18.95 | 1             | 
| 2011        | Houlihan           | Margaret            |                         | United Airlines              | Brendan riley    | alderman        | CITY COUNCIL                 | breakfast        | 18.95 | 1             | 
| 2011        | Lynch              | Daniel              | J                       | United Airlines              | Patrick O'Connor | alderman        | CITY COUNCIL                 | lunch            | 19.95 | 1             | 
```