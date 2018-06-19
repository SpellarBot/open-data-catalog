# 311 Information Requests by Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-information-requests-by-month-61cfb) |
| Metadata | [Link](https://data.sfgov.org/api/views/hrr4-hjc6) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/hrr4-hjc6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/hrr4-hjc6/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | hrr4-hjc6 |
| Name | 311 Information Requests by Month |
| Category | City Infrastructure |
| Created | 2014-05-30T21:05:55Z |
| Publication Date | 2017-03-01T20:52:09Z |

## Description

SF311 launched its current knowledge base in July 2012. This dataset shows the title of the articles in our knowledge base that are used to answer information requests, and the number of times they were accessed by our Customer Service Representatives on a call. This dataset is updated on a monthly basis.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag     | knowledge_base_article_title | Knowledge Base Article Title | text      | text        |
| Yes      | numeric metric | feb_17                       | Feb-17                       | number    | number      |
| Yes      | numeric metric | jan_17                       | Jan-17                       | number    | number      |
| Yes      | numeric metric | dec_16                       | Dec-16                       | number    | number      |
| Yes      | numeric metric | nov_16                       | Nov-16                       | number    | number      |
| Yes      | numeric metric | oct_16                       | Oct-16                       | number    | number      |
| Yes      | numeric metric | sep_16                       | Sep-16                       | number    | number      |
| Yes      | numeric metric | aug_16                       | Aug-16                       | number    | number      |
| Yes      | numeric metric | jul_16                       | Jul-16                       | number    | number      |
| Yes      | numeric metric | jun_16                       | Jun-16                       | number    | number      |
| Yes      | numeric metric | may_16                       | May-16                       | number    | number      |
| Yes      | numeric metric | apr_16                       | Apr-16                       | number    | number      |
| Yes      | numeric metric | mar_16                       | Mar-16                       | number    | number      |
| Yes      | numeric metric | feb_16                       | Feb-16                       | number    | number      |
| Yes      | numeric metric | jan_16                       | Jan-16                       | number    | number      |
| Yes      | numeric metric | dec_15                       | Dec-15                       | number    | number      |
| Yes      | numeric metric | nov_2015                     | Nov-15                       | number    | number      |
| Yes      | numeric metric | oct_15                       | Oct-15                       | number    | number      |
| Yes      | numeric metric | sep_15                       | Sep-15                       | number    | number      |
| Yes      | numeric metric | aug_15                       | Aug-15                       | number    | number      |
| Yes      | numeric metric | jul_15                       | Jul-15                       | number    | number      |
| Yes      | numeric metric | june_15                      | Jun-15                       | number    | number      |
| Yes      | numeric metric | may_15                       | May-15                       | number    | number      |
| Yes      | numeric metric | apr_15                       | Apr-15                       | number    | number      |
| Yes      | numeric metric | mar_15                       | Mar-15                       | number    | number      |
| Yes      | numeric metric | feb_15                       | Feb-15                       | number    | number      |
| Yes      | numeric metric | jan_15                       | Jan-15                       | number    | number      |
| Yes      | numeric metric | dec_14                       | Dec-14                       | number    | number      |
| Yes      | numeric metric | nov_14                       | Nov-14                       | number    | number      |
| Yes      | numeric metric | oct_14                       | Oct-14                       | number    | number      |
| Yes      | numeric metric | sep_14                       | Sep-14                       | number    | number      |
| Yes      | numeric metric | aug_14                       | Aug-14                       | number    | number      |
| Yes      | numeric metric | jul_14                       | Jul-14                       | number    | number      |
| Yes      | numeric metric | jun_14                       | Jun-14                       | number    | number      |
| Yes      | numeric metric | may                          | May-14                       | number    | number      |
| Yes      | numeric metric | april                        | Apr-14                       | number    | number      |
| Yes      | numeric metric | march                        | Mar-14                       | number    | number      |
| Yes      | numeric metric | february                     | Feb-14                       | number    | number      |
| Yes      | numeric metric | january                      | Jan-14                       | number    | number      |
| Yes      | numeric metric | dec_13                       | Dec-13                       | number    | number      |
| Yes      | numeric metric | nov_13                       | Nov-13                       | number    | number      |
| Yes      | numeric metric | oct_13                       | Oct-13                       | number    | number      |
| Yes      | numeric metric | sep_13                       | Sep-13                       | number    | number      |
| Yes      | numeric metric | aug_13                       | Aug-13                       | number    | number      |
| Yes      | numeric metric | jul_13                       | Jul-13                       | number    | number      |
| Yes      | numeric metric | jun_13                       | Jun-13                       | number    | number      |
| Yes      | numeric metric | may_13                       | May-13                       | number    | number      |
| Yes      | numeric metric | apr_13                       | Apr-13                       | number    | number      |
| Yes      | numeric metric | mar_13                       | Mar-13                       | number    | number      |
| Yes      | numeric metric | feb_13                       | Feb-13                       | number    | number      |
| Yes      | numeric metric | jan_13                       | Jan-13                       | number    | number      |
| Yes      | numeric metric | dec_12                       | Dec-12                       | number    | number      |
| Yes      | numeric metric | nov_12                       | Nov-12                       | number    | number      |
| Yes      | numeric metric | oct_12                       | Oct-12                       | number    | number      |
| Yes      | numeric metric | sep_12                       | Sep-12                       | number    | number      |
| Yes      | numeric metric | aug_12                       | Aug-12                       | number    | number      |
| Yes      | numeric metric | jul_12                       | Jul-12                       | number    | number      |
| Yes      | numeric metric | total                        | Total                        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hrr4-hjc6 d:2017-03-01T20:48:35.000Z t:knowledge_base_article_title="TTX: Gross Receipts/Payroll Tax - Annual Return" m:total=1569 m:mar_13=0 m:may_16=0 m:mar_15=0 m:may_15=0 m:mar_16=0 m:may_13=0 m:dec_15=0 m:dec_14=0 m:dec_16=0 m:feb_13=0 m:march=0 m:january=0 m:feb_16=0 m:feb_15=0 m:apr_16=0 m:nov_2015=0 m:apr_15=0 m:feb_17=1228 m:february=0 m:june_15=0 m:jul_13=0 m:oct_12=0 m:oct_13=0 m:jul_14=0 m:oct_14=0 m:jul_15=0 m:jul_16=0 m:oct_15=0 m:oct_16=0 m:sep_14=0 m:sep_15=0 m:sep_16=0 m:apr_13=0 m:sep_12=0 m:sep_13=0 m:jun_16=0 m:jun_14=0 m:nov_14=0 m:jun_13=0 m:nov_13=0 m:may=0 m:nov_16=0 m:april=0 m:nov_12=0 m:aug_12=0 m:aug_13=0 m:aug_14=0 m:aug_16=0 m:aug_15=0 m:jan_15=0 m:jan_16=0 m:jan_17=341 m:dec_13=0 m:jul_12=0 m:dec_12=0 m:jan_13=0

series e:hrr4-hjc6 d:2017-03-01T20:48:35.000Z t:knowledge_base_article_title="Police Reports - Teleserve" m:total=38283 m:mar_13=526 m:may_16=1073 m:mar_15=633 m:may_15=598 m:mar_16=830 m:may_13=495 m:dec_15=720 m:dec_14=631 m:dec_16=1168 m:feb_13=485 m:march=566 m:january=537 m:feb_16=776 m:feb_15=495 m:apr_16=921 m:nov_2015=571 m:apr_15=536 m:feb_17=1037 m:february=456 m:june_15=549 m:jul_13=596 m:oct_12=584 m:oct_13=583 m:jul_14=616 m:oct_14=615 m:jul_15=447 m:jul_16=1048 m:oct_15=579 m:oct_16=1341 m:sep_14=574 m:sep_15=719 m:sep_16=1029 m:apr_13=584 m:sep_12=649 m:sep_13=646 m:jun_16=1089 m:jun_14=587 m:nov_14=638 m:jun_13=569 m:nov_13=517 m:may=573 m:nov_16=1185 m:april=567 m:nov_12=546 m:aug_12=591 m:aug_13=567 m:aug_14=763 m:aug_16=1057 m:aug_15=608 m:jan_15=538 m:jan_16=785 m:jan_17=1267 m:dec_13=529 m:jul_12=69 m:dec_12=482 m:jan_13=543

series e:hrr4-hjc6 d:2017-03-01T20:48:35.000Z t:knowledge_base_article_title="Birth Certificates - All Matters" m:total=47170 m:mar_13=1022 m:may_16=1056 m:mar_15=824 m:may_15=681 m:mar_16=1304 m:may_13=971 m:dec_15=781 m:dec_14=593 m:dec_16=803 m:feb_13=1023 m:march=943 m:january=886 m:feb_16=1109 m:feb_15=750 m:apr_16=1141 m:nov_2015=604 m:apr_15=666 m:feb_17=1006 m:february=821 m:june_15=780 m:jul_13=944 m:oct_12=665 m:oct_13=835 m:jul_14=834 m:oct_14=813 m:jul_15=749 m:jul_16=866 m:oct_15=657 m:oct_16=961 m:sep_14=748 m:sep_15=760 m:sep_16=883 m:apr_13=1011 m:sep_12=749 m:sep_13=810 m:jun_16=1147 m:jun_14=781 m:nov_14=661 m:jun_13=863 m:nov_13=671 m:may=745 m:nov_16=927 m:april=843 m:nov_12=663 m:aug_12=875 m:aug_13=880 m:aug_14=850 m:aug_16=1075 m:aug_15=714 m:jan_15=882 m:jan_16=1013 m:jan_17=1107 m:dec_13=722 m:jul_12=94 m:dec_12=590 m:jan_13=1018
```

## Meta Commands

```ls
metric m:feb_17 p:integer l:Feb-17 t:dataTypeName=number

metric m:jan_17 p:integer l:Jan-17 t:dataTypeName=number

metric m:dec_16 p:integer l:Dec-16 t:dataTypeName=number

metric m:nov_16 p:integer l:Nov-16 t:dataTypeName=number

metric m:oct_16 p:integer l:Oct-16 t:dataTypeName=number

metric m:sep_16 p:integer l:Sep-16 t:dataTypeName=number

metric m:aug_16 p:integer l:Aug-16 t:dataTypeName=number

metric m:jul_16 p:integer l:Jul-16 t:dataTypeName=number

metric m:jun_16 p:integer l:Jun-16 t:dataTypeName=number

metric m:may_16 p:integer l:May-16 t:dataTypeName=number

metric m:apr_16 p:integer l:Apr-16 t:dataTypeName=number

metric m:mar_16 p:integer l:Mar-16 t:dataTypeName=number

metric m:feb_16 p:integer l:Feb-16 t:dataTypeName=number

metric m:jan_16 p:integer l:Jan-16 d:"Knowledge Articles referenced in Jan 2016" t:dataTypeName=number

metric m:dec_15 p:integer l:Dec-15 d:"Knowledge Articles referenced in Dec 2015" t:dataTypeName=number

metric m:nov_2015 p:integer l:Nov-15 d:"Knowledge Articles referenced in Nov 2015" t:dataTypeName=number

metric m:oct_15 p:integer l:Oct-15 t:dataTypeName=number

metric m:sep_15 p:integer l:Sep-15 t:dataTypeName=number

metric m:aug_15 p:integer l:Aug-15 t:dataTypeName=number

metric m:jul_15 p:integer l:Jul-15 t:dataTypeName=number

metric m:june_15 p:integer l:Jun-15 t:dataTypeName=number

metric m:may_15 p:integer l:May-15 t:dataTypeName=number

metric m:apr_15 p:integer l:Apr-15 t:dataTypeName=number

metric m:mar_15 p:integer l:Mar-15 t:dataTypeName=number

metric m:feb_15 p:integer l:Feb-15 t:dataTypeName=number

metric m:jan_15 p:integer l:Jan-15 t:dataTypeName=number

metric m:dec_14 p:integer l:Dec-14 t:dataTypeName=number

metric m:nov_14 p:integer l:Nov-14 t:dataTypeName=number

metric m:oct_14 p:integer l:Oct-14 t:dataTypeName=number

metric m:sep_14 p:integer l:Sep-14 t:dataTypeName=number

metric m:aug_14 p:integer l:Aug-14 t:dataTypeName=number

metric m:jul_14 p:integer l:Jul-14 t:dataTypeName=number

metric m:jun_14 p:integer l:Jun-14 t:dataTypeName=number

metric m:may p:integer l:May-14 t:dataTypeName=number

metric m:april p:integer l:Apr-14 t:dataTypeName=number

metric m:march p:integer l:Mar-14 t:dataTypeName=number

metric m:february p:integer l:Feb-14 t:dataTypeName=number

metric m:january p:integer l:Jan-14 t:dataTypeName=number

metric m:dec_13 p:integer l:Dec-13 t:dataTypeName=number

metric m:nov_13 p:integer l:Nov-13 t:dataTypeName=number

metric m:oct_13 p:integer l:Oct-13 t:dataTypeName=number

metric m:sep_13 p:integer l:Sep-13 t:dataTypeName=number

metric m:aug_13 p:integer l:Aug-13 t:dataTypeName=number

metric m:jul_13 p:integer l:Jul-13 t:dataTypeName=number

metric m:jun_13 p:integer l:Jun-13 t:dataTypeName=number

metric m:may_13 p:integer l:May-13 t:dataTypeName=number

metric m:apr_13 p:integer l:Apr-13 t:dataTypeName=number

metric m:mar_13 p:integer l:Mar-13 t:dataTypeName=number

metric m:feb_13 p:integer l:Feb-13 t:dataTypeName=number

metric m:jan_13 p:integer l:Jan-13 t:dataTypeName=number

metric m:dec_12 p:integer l:Dec-12 t:dataTypeName=number

metric m:nov_12 p:integer l:Nov-12 t:dataTypeName=number

metric m:oct_12 p:integer l:Oct-12 t:dataTypeName=number

metric m:sep_12 p:integer l:Sep-12 t:dataTypeName=number

metric m:aug_12 p:integer l:Aug-12 t:dataTypeName=number

metric m:jul_12 p:integer l:Jul-12 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:hrr4-hjc6 l:"311 Information Requests by Month" t:url=https://data.sfgov.org/api/views/hrr4-hjc6

property e:hrr4-hjc6 t:meta.view v:id=hrr4-hjc6 v:category="City Infrastructure" v:averageRating=0 v:name="311 Information Requests by Month"

property e:hrr4-hjc6 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:hrr4-hjc6 t:meta.view.owner v:id=isin-8y46 v:profileImageUrlMedium=/api/users/isin-8y46/profile_images/THUMB v:profileImageUrlLarge=/api/users/isin-8y46/profile_images/LARGE v:screenName=AndyM v:profileImageUrlSmall=/api/users/isin-8y46/profile_images/TINY v:displayName=AndyM

property e:hrr4-hjc6 t:meta.view.tableauthor v:id=isin-8y46 v:profileImageUrlMedium=/api/users/isin-8y46/profile_images/THUMB v:profileImageUrlLarge=/api/users/isin-8y46/profile_images/LARGE v:screenName=AndyM v:profileImageUrlSmall=/api/users/isin-8y46/profile_images/TINY v:roleName=publisher v:displayName=AndyM
```

## Top Records

```ls
| :updated_at | knowledge_base_article_title                                                  | feb_17 | jan_17 | dec_16 | nov_16 | oct_16 | sep_16 | aug_16 | jul_16 | jun_16 | may_16 | apr_16 | mar_16 | feb_16 | jan_16 | dec_15 | nov_2015 | oct_15 | sep_15 | aug_15 | jul_15 | june_15 | may_15 | apr_15 | mar_15 | feb_15 | jan_15 | dec_14 | nov_14 | oct_14 | sep_14 | aug_14 | jul_14 | jun_14 | may | april | march | february | january | dec_13 | nov_13 | oct_13 | sep_13 | aug_13 | jul_13 | jun_13 | may_13 | apr_13 | mar_13 | feb_13 | jan_13 | dec_12 | nov_12 | oct_12 | sep_12 | aug_12 | jul_12 | total | 
| =========== | ============================================================================= | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======== | ====== | ====== | ====== | ====== | ======= | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | === | ===== | ===== | ======== | ======= | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ===== | 
| 1488401315  | TTX: Gross Receipts/Payroll Tax - Annual Return                               | 1228   | 341    | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0        | 0      | 0      | 0      | 0      | 0       | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0   | 0     | 0     | 0        | 0       | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 1569  | 
| 1488401315  | Police Reports - Teleserve                                                    | 1037   | 1267   | 1168   | 1185   | 1341   | 1029   | 1057   | 1048   | 1089   | 1073   | 921    | 830    | 776    | 785    | 720    | 571      | 579    | 719    | 608    | 447    | 549     | 598    | 536    | 633    | 495    | 538    | 631    | 638    | 615    | 574    | 763    | 616    | 587    | 573 | 567   | 566   | 456      | 537     | 529    | 517    | 583    | 646    | 567    | 596    | 569    | 495    | 584    | 526    | 485    | 543    | 482    | 546    | 584    | 649    | 591    | 69     | 38283 | 
| 1488401315  | Birth Certificates - All Matters                                              | 1006   | 1107   | 803    | 927    | 961    | 883    | 1075   | 866    | 1147   | 1056   | 1141   | 1304   | 1109   | 1013   | 781    | 604      | 657    | 760    | 714    | 749    | 780     | 681    | 666    | 824    | 750    | 882    | 593    | 661    | 813    | 748    | 850    | 834    | 781    | 745 | 843   | 943   | 821      | 886     | 722    | 671    | 835    | 810    | 880    | 944    | 863    | 971    | 1011   | 1022   | 1023   | 1018   | 590    | 663    | 665    | 749    | 875    | 94     | 47170 | 
| 1488401315  | Marriage All Matters                                                          | 944    | 942    | 819    | 952    | 980    | 816    | 1128   | 873    | 1007   | 901    | 934    | 990    | 844    | 784    | 643    | 303      | 239    | 364    | 308    | 356    | 404     | 300    | 395    | 405    | 291    | 414    | 333    | 366    | 417    | 467    | 403    | 434    | 415    | 411 | 516   | 457   | 400      | 466     | 420    | 448    | 523    | 543    | 536    | 786    | 500    | 364    | 361    | 398    | 227    | 278    | 165    | 178    | 243    | 210    | 251    | 42     | 28894 | 
| 1488401315  | Treasurer and Tax Collector: Property Tax Payments                            | 782    | 794    | 1763   | 1491   | 1456   | 882    | 659    | 707    | 781    | 116    | 230    | 140    | 184    | 120    | 302    | 311      | 864    | 120    | 97     | 120    | 367     | 132    | 332    | 172    | 101    | 104    | 81     | 0      | 0      | 0      | 0      | 0      | 0      | 0   | 0     | 0     | 0        | 0       | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 13208 | 
| 1488401315  | Haven't Received/Status Of - Business Registration Certificate/License        | 733    | 580    | 466    | 610    | 767    | 766    | 992    | 838    | 537    | 381    | 561    | 701    | 561    | 769    | 782    | 769      | 838    | 886    | 1290   | 1567   | 784     | 1284   | 1132   | 922    | 1004   | 286    | 194    | 237    | 307    | 337    | 253    | 372    | 106    | 68  | 83    | 94    | 121      | 24      | 12     | 14     | 26     | 16     | 15     | 15     | 18     | 35     | 52     | 64     | 115    | 142    | 164    | 91     | 0      | 0      | 0      | 0      | 23781 | 
| 1488401315  | City Employee Phone Book Directory, Employee Locator, Employment Verification | 489    | 488    | 501    | 548    | 659    | 504    | 669    | 493    | 600    | 510    | 568    | 532    | 498    | 507    | 509    | 476      | 531    | 555    | 454    | 429    | 419     | 425    | 501    | 508    | 451    | 484    | 463    | 452    | 605    | 498    | 481    | 474    | 523    | 468 | 459   | 517   | 420      | 537     | 370    | 394    | 436    | 412    | 462    | 466    | 420    | 475    | 510    | 530    | 485    | 550    | 374    | 450    | 394    | 311    | 340    | 32     | 26616 | 
| 1488401315  | SFMTA - Residential Parking Permits (RPP) Eligibility                         | 480    | 564    | 441    | 418    | 497    | 534    | 645    | 572    | 684    | 518    | 397    | 649    | 555    | 565    | 413    | 458      | 514    | 679    | 746    | 455    | 503     | 401    | 384    | 488    | 343    | 453    | 359    | 346    | 448    | 434    | 445    | 337    | 311    | 243 | 250   | 69    | 124      | 144     | 67     | 138    | 204    | 206    | 273    | 285    | 236    | 227    | 284    | 245    | 204    | 225    | 149    | 168    | 157    | 87     | 106    | 7      | 20134 | 
| 1488401315  | SFMTA Parking Enforcement - Blocked Driveway                                  | 432    | 499    | 368    | 464    | 677    | 363    | 411    | 389    | 243    | 113    | 112    | 120    | 118    | 171    | 101    | 88       | 140    | 133    | 90     | 75     | 50      | 80     | 76     | 85     | 101    | 92     | 91     | 90     | 157    | 113    | 166    | 158    | 131    | 180 | 228   | 197   | 126      | 177     | 139    | 62     | 102    | 108    | 119    | 60     | 31     | 20     | 22     | 39     | 15     | 13     | 15     | 30     | 48     | 43     | 48     | 3      | 8322  | 
| 1488401315  | SFMTA Parking Violation - Pay a Citation                                      | 335    | 329    | 341    | 328    | 372    | 330    | 433    | 399    | 411    | 189    | 164    | 198    | 166    | 227    | 205    | 220      | 234    | 220    | 189    | 145    | 128     | 117    | 128    | 114    | 104    | 97     | 91     | 77     | 137    | 91     | 92     | 44     | 37     | 25  | 62    | 42    | 39       | 45      | 36     | 21     | 38     | 41     | 21     | 37     | 46     | 40     | 26     | 26     | 28     | 28     | 10     | 24     | 43     | 35     | 35     | 7      | 7447  | 
```