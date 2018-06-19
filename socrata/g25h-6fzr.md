# DEPRACATED 2012 April special drop boxes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-april-special-drop-boxes-e7d0e) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/g25h-6fzr) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/g25h-6fzr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/g25h-6fzr/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | g25h-6fzr |
| Name | DEPRACATED 2012 April special drop boxes |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | election, vote, voter, voting, ballot drop box |
| Created | 2011-07-20T18:24:29Z |
| Publication Date | 2012-03-12T18:04:41Z |

## Description

King County ballot drop box locations for the April 2012 special election. Ballot drop boxes close at 8:00 p.m. on April 17.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag  | ballot_drop_box        | Ballot drop box        | text      | text        |
| No       |             | box_address            | Box address            | text      | text        |
| Yes      | series tag  | box_city               | Box city               | text      | text        |
| Yes      | series tag  | box_state              | Box state              | text      | text        |
| Yes      | series tag  | box_zip_code           | Box Zip Code           | text      | text        |
| Yes      | series tag  | description            | Description            | text      | text        |
| Yes      | series tag  | photo                  | Photo                  | photo     | photo       |
| Yes      | series tag  | in_use                 | In use                 | checkbox  | checkbox    |
| Yes      | series tag  | chinese                | Chinese                | text      | text        |
| Yes      | series tag  | chinese_description    | Chinese description    | text      | text        |
| Yes      | series tag  | vietnamese             | Vietnamese             | text      | text        |
| Yes      | series tag  | vietnamese_description | Vietnamese description | text      | text        |
| Yes      | series tag  | directions             | Directions             | url       | url         |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = box_address
```

## Data Commands

```ls
series e:g25h-6fzr d:2012-01-01T00:00:00.000Z t:directions="http://maps.google.com/maps?q=15670+NE+85th+Street+redmond&hl=en&sll=47.384607,-122.237717&sspn=0.011507,0.024462&gl=us&z=16" t:box_city=Redmond t:box_state=WA t:ballot_drop_box="Redmond City Hall" t:box_zip_code=98052 t:photo=zsOmGziJvyPKfbk2r9GHRe4C14OGiLGVSHoSMrXbObI t:chinese=????Redmond???? m:row_number.g25h-6fzr=1

series e:g25h-6fzr d:2012-01-01T00:00:00.000Z t:directions="http://maps.google.com/maps?q=401+4th+Avenune+N.+kent&hl=en&sll=47.530358,-122.034202&sspn=0.011475,0.024462&gl=us&z=16" t:box_city=Kent t:box_state=WA t:ballot_drop_box="Regional Justice Center" t:box_zip_code=98032 t:description="Near parking garage entrance" t:in_use=true t:vietnamese="S? T? ph?p khu v?c" t:chinese_description=??????? t:photo=-N50jdiB4PFd9HkliR6dboJM_xNPbZUodYF2SFmvJno t:chinese=?????? t:vietnamese_description="G?n l?i v?o b?i ??u xe" m:row_number.g25h-6fzr=2

series e:g25h-6fzr d:2012-01-01T00:00:00.000Z t:directions="http://maps.google.com/maps?q=57th+Street+%26+22nd+Avenue+NW+seattle&hl=en&sll=47.682741,-122.25953&sspn=0.011441,0.024462&gl=us&z=16" t:box_city=Seattle t:box_state=WA t:ballot_drop_box="Ballard Branch Library" t:box_zip_code=98107 t:photo=-za5Jg-ZGYDMdxR8f7Rj7rReE2d0KCJadnDek2GRlHw t:chinese=???Ballard?????? m:row_number.g25h-6fzr=3
```

## Meta Commands

```ls
metric m:row_number.g25h-6fzr p:long l:"Row Number"

entity e:g25h-6fzr l:"DEPRACATED 2012 April special drop boxes" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/g25h-6fzr

property e:g25h-6fzr t:meta.view v:id=g25h-6fzr v:category="Election operations" v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name="DEPRACATED 2012 April special drop boxes" v:attribution="King County Elections"

property e:g25h-6fzr t:meta.view.license v:name="Public Domain"

property e:g25h-6fzr t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:g25h-6fzr t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| ballot_drop_box                     | box_address                            | box_city         | box_state | box_zip_code | description                  | photo                                       | in_use | chinese                   | chinese_description | vietnamese                       | vietnamese_description     | directions                                                                                                                                                                             | 
| =================================== | ====================================== | ================ | ========= | ============ | ============================ | =========================================== | ====== | ========================= | =================== | ================================ | ========================== | ====================================================================================================================================================================================== | 
| Redmond City Hall                   | 15670 NE 85th Street                   | Redmond          | WA        | 98052        |                              | zsOmGziJvyPKfbk2r9GHRe4C14OGiLGVSHoSMrXbObI |        | ????Redmond????           |                     |                                  |                            | [http://maps.google.com/maps?q=15670+NE+85th+Street+redmond&hl=en&sll=47.384607,-122.237717&sspn=0.011507,0.024462&gl=us&z=16, Directions]                                             | 
| Regional Justice Center             | 401 4th Avenue N.                      | Kent             | WA        | 98032        | Near parking garage entrance | -N50jdiB4PFd9HkliR6dboJM_xNPbZUodYF2SFmvJno | true   | ??????                    | ???????             | S? T? ph?p khu v?c               | G?n l?i v?o b?i ??u xe     | [http://maps.google.com/maps?q=401+4th+Avenune+N.+kent&hl=en&sll=47.530358,-122.034202&sspn=0.011475,0.024462&gl=us&z=16, Directions]                                                  | 
| Ballard Branch Library              | 57th Street & 22nd Avenue NW           | Seattle          | WA        | 98107        |                              | -za5Jg-ZGYDMdxR8f7Rj7rReE2d0KCJadnDek2GRlHw |        | ???Ballard??????          |                     |                                  |                            | [http://maps.google.com/maps?q=57th+Street+%26+22nd+Avenue+NW+seattle&hl=en&sll=47.682741,-122.25953&sspn=0.011441,0.024462&gl=us&z=16, Directions]                                    | 
| King County Elections               | 919 SW Grady Way                       | Renton           | WA        | 98057        |                              | etZqbOKne4meC7wLICTILQrQrVNteODZZuYu7bJrWxU | true   | ?????                     |                     | H?i ??ng b?u c? qu?n King        |                            | [http://www.kingcounty.gov/Sites/elections/aboutus/directions.aspx, Directions]                                                                                                        | 
| Federal Way City Hall               | 33325 8th Avenue South                 | Federal Way      | WA        | 98003        |                              | le6uCaUYdZf5PdIJ8VX2YNnhW4Hj-SsHToZlbNay_wg | true   | ????Federal Way????       |                     | H?i tr??ng th?nh ph? Federal Way |                            | [http://maps.google.com/maps?q=33325+8th+Avenue+South+98003&hl=en&sll=47.617346,-122.131479&sspn=0.011456,0.024462&gl=us&z=16, Directions]                                             | 
| King County Administration Building | 500 4th Avenue                         | Seattle          | WA        | 98104        |                              | yE3JQJI9QHzhRcWK86c-Ivvvqvt5_HsbX49p55U3ZRo | true   | ??????                    |                     | T?a nh? h?nh ch?nh qu?n King     |                            | [http://maps.google.com/maps?q=500+4th+Avenue,+Seattle,+WA&hl=en&sll=47.679112,-122.130895&sspn=0.011442,0.024462&gl=us&z=16, Directions]                                              | 
| Tahoma School District Office       | 25720 Maple Valley-Black Diamond Rd SE | Maple Valley     | WA        | 98038        |                              | QIkUNhUMe88F0MF4HVdsq1J_fK99YduphtbMf6Ql1kQ |        | ????Tahoma??????          |                     |                                  |                            | [http://maps.google.com/maps?q=25720+Maple+Valley-Black+Diamond+Rd+SE&hl=en&sll=47.679112,-122.130895&sspn=0.011442,0.024462&gl=us&z=16, Directions]                                   | 
| Lake Forest Park City Hall          | 17425 Ballinger Way NE                 | Lake Forest Park | WA        | 98155        |                              | dnfDLkLf6Gb6dfH-tj40W90HTz_EKrZBk7VMo7NvB00 |        | ?????Lake Forest Park???? |                     |                                  |                            | [http://maps.google.com/maps?q=17425+Ballinger+Way+NE+98155&hl=en&sll=47.530358,-122.034202&sspn=0.011475,0.024462&gl=us&z=16, Directions]                                             | 
| Issaquah City Hall                  | 130 East Sunset Way                    | Issaquah         | WA        | 98027        |                              | IPBW45mzAKQhA8NhASJmOAkzJ7zSdlLjJjIBhw1miRI | true   | ????Issaquah????          |                     | H?i tr??ng th?nh ph? Issaquah    |                            | [http://maps.google.com/maps?q=130+East+Sunset+Way+98027&hl=en&ll=47.530358,-122.034202&spn=0.011475,0.024462&sll=47.303966,-122.326567&sspn=0.011524,0.024462&gl=us&z=16, Directions] | 
| Magnuson Park                       | 6344 NE 74th Street                    | Seattle          | WA        | 98115        | Use NE 74th Street entrance  | azoWlR9x63m6YBOXh7avkzJEJ08VBtQzIckGnhegiYc |        | Magnuson??                | ??NE 74th St??      |                                  | D?ng l?i v?o ???ng NE 74th | [http://maps.google.com/maps?q=6344+NE+74th+Street+seattle&hl=en&sll=47.60298,-122.329738&sspn=0.011459,0.024462&gl=us&z=16, Directions]                                               | 
```