# Checkouts by Title

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/checkouts-by-title) |
| Metadata | [Link](https://data.seattle.gov/api/views/tmmm-ytt6) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/tmmm-ytt6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/tmmm-ytt6/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | tmmm-ytt6 |
| Name | Checkouts by Title |
| Attribution | Seattle Public Library |
| Category | Community |
| Tags | horizon, overdrive, freegal, hoopla, zinio, e-book, circulation, seattle public library, checkout |
| Created | 2017-01-31T20:39:17Z |
| Publication Date | 2017-02-09T18:41:21Z |

## Description

This dataset includes a monthly count of Seattle Public Library checkouts by title for physical and electronic items. The dataset begins with checkouts that occurred in April 2005.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | usageclass      | UsageClass      | text      | text        |
| Yes      | series tag     | checkouttype    | CheckoutType    | text      | text        |
| Yes      | series tag     | materialtype    | MaterialType    | text      | text        |
| Yes      | time           | checkoutyear    | CheckoutYear    | number    | number      |
| Yes      | numeric metric | checkoutmonth   | CheckoutMonth   | number    | number      |
| Yes      | numeric metric | checkouts       | Checkouts       | number    | number      |
| Yes      | series tag     | title           | Title           | text      | text        |
| Yes      | series tag     | creator         | Creator         | text      | text        |
| Yes      | series tag     | subjects        | Subjects        | text      | text        |
| Yes      | series tag     | publisher       | Publisher       | text      | text        |
| Yes      | series tag     | publicationyear | PublicationYear | text      | text        |
```

## Time Field

```ls
Value = checkoutyear
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tmmm-ytt6 d:2009-01-01T00:00:00.000Z t:usageclass=Physical t:title="One last dance" t:checkouttype=Horizon t:subjects="Domestic fiction, Mothers and daughters Fiction, Fathers and daughters Fiction, Adultery Fiction, Trials Murder Fiction, Parent and adult child Fiction, Wedding anniversaries Fiction, Sisters Family relationships Fiction" t:materialtype=BOOK m:checkoutmonth=1 m:checkouts=1

series e:tmmm-ytt6 d:2009-01-01T00:00:00.000Z t:usageclass=Physical t:title="Langston Hughes" t:checkouttype=Horizon t:subjects="American poetry 20th century" t:materialtype=SOUNDDISC m:checkoutmonth=1 m:checkouts=1

series e:tmmm-ytt6 d:2009-01-01T00:00:00.000Z t:usageclass=Physical t:title="The golden house of Nero; some aspects of Roman architecture." t:checkouttype=Horizon t:subjects="Rome Italy Domus Aurea, Architecture Roman, City planning Italy Rome, Cities and towns Ancient" t:publicationyear=[1960] t:materialtype=BOOK t:publisher="University of Michigan Press" t:creator="Bo?thius, Axel, 1889-1969" m:checkoutmonth=1 m:checkouts=1
```

## Meta Commands

```ls
metric m:checkoutmonth p:integer l:CheckoutMonth d:"The month of checkout for this record." t:dataTypeName=number

metric m:checkouts p:integer l:Checkouts d:"A count of the number of times the title was checked out within the ?Checkout Month?." t:dataTypeName=number

entity e:tmmm-ytt6 l:"Checkouts by Title" t:attribution="Seattle Public Library" t:url=https://data.seattle.gov/api/views/tmmm-ytt6

property e:tmmm-ytt6 t:meta.view v:id=tmmm-ytt6 v:category=Community v:attributionLink=https://www.spl.org v:averageRating=0 v:name="Checkouts by Title" v:attribution="Seattle Public Library"

property e:tmmm-ytt6 t:meta.view.license v:name="Public Domain"

property e:tmmm-ytt6 t:meta.view.owner v:id=vzfw-utud v:profileImageUrlMedium=/api/users/vzfw-utud/profile_images/THUMB v:profileImageUrlLarge=/api/users/vzfw-utud/profile_images/LARGE v:screenName=SPL v:profileImageUrlSmall=/api/users/vzfw-utud/profile_images/TINY v:displayName=SPL

property e:tmmm-ytt6 t:meta.view.tableauthor v:id=vzfw-utud v:profileImageUrlMedium=/api/users/vzfw-utud/profile_images/THUMB v:profileImageUrlLarge=/api/users/vzfw-utud/profile_images/LARGE v:screenName=SPL v:profileImageUrlSmall=/api/users/vzfw-utud/profile_images/TINY v:roleName=publisher v:displayName=SPL
```

## Top Records

```ls
| usageclass | checkouttype | materialtype | checkoutyear | checkoutmonth | checkouts | title                                                                                                                                              | creator                   | subjects                                                                                                                                                                                                                     | publisher                    | publicationyear | 
| ========== | ============ | ============ | ============ | ============= | ========= | ================================================================================================================================================== | ========================= | ============================================================================================================================================================================================================================ | ============================ | =============== | 
| Physical   | Horizon      | BOOK         | 2009         | 1             | 1         | One last dance                                                                                                                                     |                           | Domestic fiction, Mothers and daughters Fiction, Fathers and daughters Fiction, Adultery Fiction, Trials Murder Fiction, Parent and adult child Fiction, Wedding anniversaries Fiction, Sisters Family relationships Fiction |                              |                 | 
| Physical   | Horizon      | SOUNDDISC    | 2009         | 1             | 1         | Langston Hughes                                                                                                                                    |                           | American poetry 20th century                                                                                                                                                                                                 |                              |                 | 
| Physical   | Horizon      | BOOK         | 2009         | 1             | 1         | The golden house of Nero; some aspects of Roman architecture.                                                                                      | Bo?thius, Axel, 1889-1969 | Rome Italy Domus Aurea, Architecture Roman, City planning Italy Rome, Cities and towns Ancient                                                                                                                               | University of Michigan Press | [1960]          | 
| Physical   | Horizon      | BOOK         | 2009         | 1             | 2         | Folk knits / Melinda Coss.                                                                                                                         | Coss, Melinda             | Knitting Patterns, Sweaters                                                                                                                                                                                                  | Trafalgar Square Pub.,       | 1991.           | 
| Physical   | Horizon      | BOOK         | 2009         | 1             | 1         | S?ji no j?? ga oshieru sekaiichi no sentaku jutsu = talking dirty laundry with the Queen of Clean / Rinda Kobu ; Hiroo Manami yaku.                | Cobb, Linda               | House cleaning Handbooks manuals etc, Housekeeping Handbooks manuals etc                                                                                                                                                     | ?tisuto Hausu,               | 2001.           | 
| Physical   | Horizon      | VIDEODISC    | 2009         | 1             | 3         | Post office                                                                                                                                        |                           | Video recordings for the hearing impaired, Childrens films, United States Postal Service Juvenile films, Postal service United States Juvenile films                                                                         |                              |                 | 
| Physical   | Horizon      | BOOK         | 2009         | 1             | 1         | Birthing the elephant : the woman's go-for-it! guide to overcoming the big challenges of launching a business / Karin Abarbanel and Bruce Freeman. | Abarbanel, Karin          | New business enterprises Management, Women owned business enterprises Management, Entrepreneurship                                                                                                                           | Ten Speed Press,             | c2008.          | 
| Physical   | Horizon      | BOOK         | 2009         | 1             | 2         | Springwater wedding                                                                                                                                |                           | Love stories, Montana Fiction                                                                                                                                                                                                |                              |                 | 
| Physical   | Horizon      | BOOK         | 2009         | 1             | 6         | Jake the philharmonic dog / Karen Lefrak ; illustrated by Marcin Baranski.                                                                         | LeFrak, Karen             | Dogs Fiction, Orchestra Juvenile fiction, Musical instruments Juvenile fiction                                                                                                                                               | Walker & Company,            | 2006.           | 
| Physical   | Horizon      | MUSIC        | 2009         | 1             | 1         | Best of Creedence Clearwater Revival                                                                                                               |                           | Guitar music Rock, Rock music 1961 1970                                                                                                                                                                                      |                              |                 | 
```