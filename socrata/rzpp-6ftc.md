# Missouri Alternatives To Abortion Resources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-alternatives-to-abortion-resources-39085) |
| Metadata | [Link](https://data.mo.gov/api/views/rzpp-6ftc) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/rzpp-6ftc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/rzpp-6ftc/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | rzpp-6ftc |
| Name | Missouri Alternatives To Abortion Resources |
| Created | 2014-06-13T13:50:39Z |
| Publication Date | 2016-03-28T20:30:36Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | office_id       | Office ID       | text      | number      |
| Yes      | numeric metric | parent_office   | Parent Office   | number    | number      |
| Yes      | series tag     | agency_name     | Agency Name     | text      | text        |
| Yes      | series tag     | city            | City            | text      | text        |
| Yes      | series tag     | state           | State           | text      | text        |
| Yes      | series tag     | zip             | Zip             | text      | text        |
| Yes      | series tag     | street_address  | Street Address  | text      | text        |
| No       |                | address_line_2  | Address Line 2  | text      | text        |
| Yes      | series tag     | phone           | Phone           | text      | text        |
| Yes      | series tag     | phone2          | Phone2          | text      | text        |
| Yes      | series tag     | website         | Website         | text      | text        |
| Yes      | series tag     | counties_served | Counties Served | text      | text        |
| Yes      | series tag     | social_media    | Social Media    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_line_2
```

## Data Commands

```ls
series e:rzpp-6ftc d:2014-06-13T06:50:43.000Z t:social_media="FB, Twitter" t:zip=65613 t:phone="(417) 777-5433" t:website=http://www.alphahouseprc.org t:state=MO t:counties_served="Cedar, Dade, Greene, Lawrence, Polk" t:street_address="469 S. Albany" t:agency_name="Alpha House" t:office_id=2 t:city=Bolivar m:parent_office=1

series e:rzpp-6ftc d:2014-06-13T06:50:43.000Z t:social_media="FB, Twitter" t:zip=63119 t:phone="(314) 781-6363" t:website=http://www.bethany.org/stlouis t:state=MO t:counties_served="Cape Girardeau, Jasper, Jefferson, Perry, Saline, Scott, St. Charles, St. Louis City, St. Louis County" t:street_address="7520 Big Bend Blvd." t:agency_name="Bethany Christian Services" t:office_id=3 t:city="St. Louis" m:parent_office=1

series e:rzpp-6ftc d:2014-06-13T06:50:43.000Z t:social_media="Facebook, Youtube & Twitter" t:zip=64105 t:phone="(816) 221-4377" t:website=http://catholiccharities-kcsj.org t:state=MO t:counties_served="Bates, Benton, Cass, Clay, Clinton, Henry, Jackson, Johnson, Lafayette, Pettis, Ray" t:street_address="20 West 9th Street, Suite 600" t:agency_name="Catholic Charities of Kansas City-St. Joseph" t:office_id=31 t:city="Kansas City" m:parent_office=30
```

## Meta Commands

```ls
metric m:parent_office p:integer l:"Parent Office" t:dataTypeName=number

entity e:rzpp-6ftc l:"Missouri Alternatives To Abortion Resources" t:url=https://data.mo.gov/api/views/rzpp-6ftc

property e:rzpp-6ftc t:meta.view v:id=rzpp-6ftc v:averageRating=0 v:name="Missouri Alternatives To Abortion Resources"

property e:rzpp-6ftc t:meta.view.owner v:id=xfqs-bcyn v:screenName=whitwo v:displayName=whitwo

property e:rzpp-6ftc t:meta.view.tableauthor v:id=xfqs-bcyn v:screenName=whitwo v:roleName=editor v:displayName=whitwo
```

## Top Records

```ls
| :updated_at | office_id | parent_office | agency_name                                  | city         | state | zip   | street_address                | address_line_2 | phone          | phone2               | website                              | counties_served                                                                                                                                                                                        | social_media                               | 
| =========== | ========= | ============= | ============================================ | ============ | ===== | ===== | ============================= | ============== | ============== | ==================== | ==================================== | ====================================================================================================================================================================================================== | ========================================== | 
| 1402642243  | 2         | 1             | Alpha House                                  | Bolivar      | MO    | 65613 | 469 S. Albany                 | P.O. Box 644   | (417) 777-5433 |                      | http://www.alphahouseprc.org         | Cedar, Dade, Greene, Lawrence, Polk                                                                                                                                                                    | FB, Twitter                                | 
| 1402642243  | 3         | 1             | Bethany Christian Services                   | St. Louis    | MO    | 63119 | 7520 Big Bend Blvd.           |                | (314) 781-6363 |                      | http://www.bethany.org/stlouis       | Cape Girardeau, Jasper, Jefferson, Perry, Saline, Scott, St. Charles, St. Louis City, St. Louis County                                                                                                 | FB, Twitter                                | 
| 1402642243  | 31        | 30            | Catholic Charities of Kansas City-St. Joseph | Kansas City  | MO    | 64105 | 20 West 9th Street, Suite 600 |                | (816) 221-4377 |                      | http://catholiccharities-kcsj.org    | Bates, Benton, Cass, Clay, Clinton, Henry, Jackson, Johnson, Lafayette, Pettis, Ray                                                                                                                    | Facebook, Youtube & Twitter                | 
| 1402642243  | 19        | 19            | Catholic Charities of Southern Missouri      | Springfield  | MO    | 65807 | 424 East Monastery Street     |                | (417) 720-4213 |                      | http://www.ccsomo.org                | Bollinger, Butler, Cape Girardeau, Carter, Douglas, Dunklin, Howell, Iron, Madison, Mississippi, New Madrid, Oregon, Ozark, Pemiscot, Reynolds, Ripley, Scott, Shannon, Stoddard, Texas, Wayne, Wright | Facebook                                   | 
| 1402642243  | 23        | 23            | Faith Maternity Care                         | Fulton       | MO    | 65251 | 1900 Lake Drive               | P.O. Box 6232  | (573) 642-7414 | (573) 642-8184 (fax) | http://www.faithmaternity.com        | Audrain, Boone, Callaway, Camden, Cole, Cooper, Gasconade, Howard, Miller, Moniteau, Montgomery, Morgan, Osage                                                                                         | only used for staying in touch with donors | 
| 1402642243  | 4         | 1             | Free Women's Center of Pulaski County        | Waynesville  | MO    | 65583 | 704 Historic Route 66 West    | Suite 106      | (573) 774-4992 |                      | http://www.supportmyfwc.com          | Pulaski, Phelps                                                                                                                                                                                        | FB                                         | 
| 1402642243  | 6         | 1             | Lifeline Pregnancy Care Center               | Cuba         | MO    | 65453 | 1017 Westside Drive           |                | (573) 885-3040 |                      | http://www.lifelinepcc.com           | Crawford, Dent                                                                                                                                                                                         | none                                       | 
| 1402642243  | 7         | 1             | Lifeline Pregnancy Help Clinic               | Kirksville   | MO    | 63501 | 306 W. Washington Street      | P.O. Box 663   | (660) 665-5688 |                      | http://www.lifelinepregnancyhelp.org | Adair, Knox, Linn, Macon, Putnam, Randolph, Schuyler, Sullivan                                                                                                                                         | FB                                         | 
| 1402642243  | 27        | 27            | Light House                                  | Kansas City  | MO    | 64113 | 400 W. Meyer                  | P.O. Box 22553 | (816) 361-2233 |                      | http://www.lighthousekc.org          | Bates, Benton, Carroll, Cass, Clay, Henry, Jackson, Johnson, Lafayette, Pettis, Platte, Ray, Saline                                                                                                    | Facebook                                   | 
| 1402642243  | 28        | 28            | Mother's Refuge                              | Independence | MO    | 64055 | 14400 E. Hwy 42nd Street      | Suite 220      | (816) 353-8070 |                      | http://www.MothersRefuge.org         | Bates, Benton, Carroll, Cass, Clay, Henry, Jackson, Johnson, Lafayette, Pettis, Platte, Ray, Saline                                                                                                    | Facebook and Twitter                       | 
```