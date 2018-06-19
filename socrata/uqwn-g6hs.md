# Street Vendors - Merchants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-vendors-merchants-3ea60) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/uqwn-g6hs) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/uqwn-g6hs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/uqwn-g6hs/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | uqwn-g6hs |
| Name | Street Vendors - Merchants |
| Attribution | EGIS |
| Tags | street, merchant, vendor |
| Created | 2013-11-22T19:35:02Z |
| Publication Date | 2013-11-22T19:42:35Z |

## Description

Street vendor locations of Merchants

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| No       |             | id          | Id         | text      | number      |
| Yes      | series tag  | licensenum  | LicenseNum | text      | text        |
| Yes      | series tag  | vendorname  | VendorName | text      | text        |
| Yes      | series tag  | vendorhome  | VendorHome | text      | text        |
| Yes      | series tag  | vendoraddr  | VendorAddr | text      | text        |
| Yes      | series tag  | itemssold   | ItemsSold  | text      | text        |
| Yes      | series tag  | cartdescr   | CartDescr  | text      | text        |
| No       |             | st          | ST         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,st
```

## Data Commands

```ls
series e:uqwn-g6hs d:2013-11-22T11:35:05.000Z t:vendorname="Abdul-Ghani, Christina ""The Bullpen Bar""" t:licensenum=DM000066 t:vendoraddr="Island north of 508 Washington Blvd" t:itemssold="Tee shirts, koozies, dog shirts, cups" t:cartdescr="6' table w/pegboard" t:vendorhome="1307 W. Joppa Road" m:row_number.uqwn-g6hs=1

series e:uqwn-g6hs d:2013-11-22T11:35:05.000Z t:vendorname="Almuid, Daud / Absatou Cisse" t:licensenum=DM000001 t:vendoraddr="NWC of Saratoga & Eutaw Sts" t:itemssold="Incense, body oils, novelties, African & Islamic Clothing, T-shirts, Sweatshirts, socks & flowers" t:cartdescr="One 6' by 3' table" t:vendorhome="1717 W. North Ave." m:row_number.uqwn-g6hs=2

series e:uqwn-g6hs d:2013-11-22T11:35:05.000Z t:vendorname="Almuid, Daud / Absatou Cisse" t:licensenum=DM000002 t:vendoraddr="SEC of Howard & Saratoga Sts. To be on Saratoga, 12 ft. east of Howard St." t:itemssold="Incense, body oils, novelties African & Islamic Clothing T-shirts, Sweatshirts, socks & flowers" t:cartdescr="One 6' by 3' table with metal racks attached on 3 sides. Merchanise should not extend the length of the table beyond a total of 8 ft, height should not exceed 5 ft." t:vendorhome="1717 W. North Ave." m:row_number.uqwn-g6hs=3
```

## Meta Commands

```ls
metric m:row_number.uqwn-g6hs p:long l:"Row Number"

entity e:uqwn-g6hs l:"Street Vendors - Merchants" t:attribution=EGIS t:url=https://data.baltimorecity.gov/api/views/uqwn-g6hs

property e:uqwn-g6hs t:meta.view v:id=uqwn-g6hs v:attributionLink=http://www.baltimorecity.gov/OfficeoftheMayor/MayoralOffices/InformationTechnology/EnterpriseGeographicInformationServices.aspx v:averageRating=0 v:name="Street Vendors - Merchants" v:attribution=EGIS

property e:uqwn-g6hs t:meta.view.license v:name="Public Domain"

property e:uqwn-g6hs t:meta.view.owner v:id=jp5u-a9z8 v:profileImageUrlMedium=/api/users/jp5u-a9z8/profile_images/THUMB v:profileImageUrlLarge=/api/users/jp5u-a9z8/profile_images/LARGE v:screenName="brad chranko" v:profileImageUrlSmall=/api/users/jp5u-a9z8/profile_images/TINY v:displayName="brad chranko"

property e:uqwn-g6hs t:meta.view.tableauthor v:id=jp5u-a9z8 v:profileImageUrlMedium=/api/users/jp5u-a9z8/profile_images/THUMB v:profileImageUrlLarge=/api/users/jp5u-a9z8/profile_images/LARGE v:screenName="brad chranko" v:profileImageUrlSmall=/api/users/jp5u-a9z8/profile_images/TINY v:displayName="brad chranko"
```

## Top Records

```ls
| :updated_at | id | licensenum | vendorname                               | vendorhome         | vendoraddr                                                                 | itemssold                                                                                                                                                         | cartdescr                                                                                                                                                            | st | 
| =========== | == | ========== | ======================================== | ================== | ========================================================================== | ================================================================================================================================================================= | ==================================================================================================================================================================== | == | 
| 1385120105  | 0  | DM000066   | Abdul-Ghani, Christina "The Bullpen Bar" | 1307 W. Joppa Road | Island north of 508 Washington Blvd                                        | Tee shirts, koozies, dog shirts, cups                                                                                                                             | 6' table w/pegboard                                                                                                                                                  | MD | 
| 1385120105  | 0  | DM000001   | Almuid, Daud / Absatou Cisse             | 1717 W. North Ave. | NWC of Saratoga & Eutaw Sts                                                | Incense, body oils, novelties, African & Islamic Clothing, T-shirts, Sweatshirts, socks & flowers                                                                 | One 6' by 3' table                                                                                                                                                   | MD | 
| 1385120105  | 0  | DM000002   | Almuid, Daud / Absatou Cisse             | 1717 W. North Ave. | SEC of Howard & Saratoga Sts. To be on Saratoga, 12 ft. east of Howard St. | Incense, body oils, novelties African & Islamic Clothing T-shirts, Sweatshirts, socks & flowers                                                                   | One 6' by 3' table with metal racks attached on 3 sides. Merchanise should not extend the length of the table beyond a total of 8 ft, height should not exceed 5 ft. | MD | 
| 1385120105  | 0  | DM000068   | Solomon, Damon                           | 1224 Turpin Lane   | SWC of Park & Fayette St                                                   | hats, t-shirts, light-up toys, balloons, toys, novelties                                                                                                          | pushcart 4' high x 4' wide                                                                                                                                           | MD | 
| 1385120105  | 0  | DM000007   | Bishop-El, Wliiam & Jeneen               | 2542 Cecil Ave.    | Eastside of Light St, North of Lombard in front of planter area            | Instant Photos, Leather goods, Oils, Sunglasses                                                                                                                   | Photo Back Drop One - 6' x 3' table                                                                                                                                  | MD | 
| 1385120105  | 0  | DM000004   | Bishop-El, William & Jeneen              | 2542 Cecil Ave.    | Market Place & Water St.-to be on the westside of Market Pl, mid-block     | Jewelry, Incense, body oils, tapes, t-shirts, Leather goods, African & American art, health aids, summer & winter wear                                            | One table 6' x 3' w/ extensions not to exceed a total of 8'. Height not to exceed 5'.                                                                                | MD | 
| 1385120105  | 0  | DM000006   | Bishop-El, Wliiam & Jeneen               | 2542 Cecil Ave.    | South side of Baltimore St @ Hanover St.                                   | Jewelry, incense, body oils, leather goods, summer wear, winter, wear, novelties (toys), sunglasses, books, tapes, African & American Art, Health Aids & t-shirts | One table 6' by 3' w/ extensions not to exceed a total of 8'. Height not to exceed 5'.                                                                               | MD | 
| 1385120105  | 0  | DM000008   | Bishop-El, Wliiam & Jeneen               | 2542 Cecil Ave.    | NS of E. Pratt St, NEC Light & Pratt                                       | Instant Photos                                                                                                                                                    | 1-10 x 10 Pop Tent 2-Back Drops 1-12 Volt Battery - MUST BE COVERED                                                                                                  | MD | 
| 1385120105  | 0  | DM000010   | Bishop-El, Wliiam & Jeneen               | 2542 Cecil Ave.    | NWC of Calvert St & Wilkens Ln.                                            | Jewelry, incense, oils, tapes, leather goods, African & American Art Health Aids and T-shirts                                                                     | ONE table, 4' long, 2 1/2' wide, 3' high and one display case 2' by 4'                                                                                               | MD | 
| 1385120105  | 0  | DM000009   | Bishop-El, William & Jeneen              | 2542 Cecil Ave.    | SEC Baltimore & Greene Sts.                                                | Jewelry, incense, body oils, tapes, t-shirts, leather goods, African & American art, health aids, summer & winter wear                                            | One table 6' x 3' w/ extensions not to exceed a total of 8'. Height not to exceed 5'.                                                                                | MD | 
```