# EGP Calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/egp-calendar-8c3f8) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/ih66-9vhb) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/ih66-9vhb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/ih66-9vhb/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | ih66-9vhb |
| Name | EGP Calendar |
| Category | Employees |
| Created | 2013-08-06T22:54:04Z |
| Publication Date | 2016-11-03T20:42:57Z |

## Description

Base dataset for the King County Employee Giving Program (EGP) Annual Giving Drive Calendar

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | event              | Event              | text          | text          |
| Yes      | time        | startdatetime      | StartDateTime      | calendar_date | calendar_date |
| No       |             | enddatetime        | EndDateTime        | calendar_date | calendar_date |
| Yes      | series tag  | building           | Building           | text          | text          |
| Yes      | series tag  | room               | Room               | text          | text          |
| Yes      | series tag  | department         | Department         | text          | text          |
| Yes      | series tag  | division_section   | Division/Section   | text          | text          |
| Yes      | series tag  | additional_info    | Additional Info    | text          | text          |
| Yes      | series tag  | suggested_donation | Suggested Donation | text          | text          |
| Yes      | series tag  | benefits           | Benefits           | text          | text          |
| Yes      | series tag  | added_by           | Added By           | text          | text          |
| Yes      | series tag  | contact_info       | Contact Info       | text          | text          |
```

## Time Field

```ls
Value = startdatetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = enddatetime
```

## Data Commands

```ls
series e:ih66-9vhb d:2016-10-06T11:30:00.000Z t:building="King Street Center Lobby" t:event="Veggie Basket Drawing Extravaganza!" t:additional_info="Donations collected will be provided to Northwest Harvest.
http://www.northwestharvest.org/" m:row_number.ih66-9vhb=1

series e:ih66-9vhb d:2016-10-20T11:30:00.000Z t:building="King Steet Center Lobby" t:event="Vegie Basket Extravaganza!" t:additional_info="Donations collected will be provided to Bats Northwest. 
http://www.batsnorthwest.org/" m:row_number.ih66-9vhb=2

series e:ih66-9vhb d:2016-11-03T11:30:00.000Z t:building="King Stree Center Lobby" t:event="Soup Fest!" t:additional_info="Donations collected will be provided to KC Hope.
http://kchopeprogram.org/_layouts/15/start.aspx#/SitePages/Home.aspx" m:row_number.ih66-9vhb=3
```

## Meta Commands

```ls
metric m:row_number.ih66-9vhb p:long l:"Row Number"

entity e:ih66-9vhb l:"EGP Calendar" t:url=https://data.kingcounty.gov/api/views/ih66-9vhb

property e:ih66-9vhb t:meta.view v:id=ih66-9vhb v:category=Employees v:averageRating=0 v:name="EGP Calendar"

property e:ih66-9vhb t:meta.view.license v:name="Public Domain"

property e:ih66-9vhb t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:ih66-9vhb t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| event                               | startdatetime       | enddatetime         | building                                                                                | room | department | division_section | additional_info                                                                                                                                                                                                                                | suggested_donation | benefits | added_by | contact_info | 
| =================================== | =================== | =================== | ======================================================================================= | ==== | ========== | ================ | ============================================================================================================================================================================================================================================== | ================== | ======== | ======== | ============ | 
| Veggie Basket Drawing Extravaganza! | 2016-10-06T11:30:00 | 2016-10-06T12:30:00 | King Street Center Lobby                                                                |      |            |                  | Donations collected will be provided to Northwest Harvest. http://www.northwestharvest.org/                                                                                                                                                    |                    |          |          |              | 
| Vegie Basket Extravaganza!          | 2016-10-20T11:30:00 | 2016-10-20T12:30:00 | King Steet Center Lobby                                                                 |      |            |                  | Donations collected will be provided to Bats Northwest. http://www.batsnorthwest.org/                                                                                                                                                          |                    |          |          |              | 
| Soup Fest!                          | 2016-11-03T11:30:00 | 2016-11-03T12:30:00 | King Stree Center Lobby                                                                 |      |            |                  | Donations collected will be provided to KC Hope. http://kchopeprogram.org/_layouts/15/start.aspx#/SitePages/Home.aspx                                                                                                                          |                    |          |          |              | 
| BINGO, Brats and Bragging Rights    | 2016-10-31T11:30:00 | 2016-10-31T13:00:00 | King Street Center, 8th Floor Conference Room                                           |      |            |                  | Enjoy a lunch of brats (meat or veggie) while trying your luck with a game of BINGO, and then try your skill at darts! We'll also have a framed picture drawing, and be sure to dress up for Halloween to be entered to win additional prizes! |                    |          |          |              | 
| Cedar Hills Regional Landfill       | 2016-10-11T11:00:00 | 2016-10-18T13:30:00 | CHL - Lunch room                                                                        |      |            |                  | SWD - CHL, Taco Feed to feed the hungry.  Our focus is the Maple Valley Food Bank and Emergency Services #9269. Brenda Loder and Mary Ann Hale are the Lead Ambassador team.                                                                   |                    |          |          |              | 
| KCIT Candy Grams                    | 2016-10-10T00:00:00 | 2016-11-18T23:59:00 | https://kc1.sharepoint.com/teams/itc/events/candygrams/Pages/Candy-Gram-Order-Form.aspx |      |            |                  | Thank your coworkers with a Candy Gram to be delivered on 11/4 or 11/18.  For more information, contact Nicole Maley or Kieu Ton.                                                                                                              |                    |          |          |              | 
| KCIT Online Auction                 | 2016-10-17T00:00:00 | 2016-11-04T23:59:00 | https://kc1.sharepoint.com/teams/DESc/EGP/SitePages/EGP%20Auctions.aspx                 |      |            |                  | Bid on items donated by KCIT staff!  Contact Alex Jacobson or Tommy Lee (IT) for more information.                                                                                                                                             |                    |          |          |              | 
| Taco Feed                           | 2016-10-20T11:00:00 | 2016-10-20T13:30:00 | CSC-Compontent Supply Center                                                            |      |            |                  | Taco Feed/ A couple of speakers                                                                                                                                                                                                                |                    |          |          |              | 
| Spaghetti Feed                      | 2016-11-04T11:00:00 | 2016-11-04T13:30:00 | CSC-Component Supply Center                                                             |      |            |                  | NW Harvest, Make a Wish, Paws and Childrens Hospital, will be our speakers.                                                                                                                                                                    |                    |          |          |              | 
| Safety Meeting/NPO Guest Speaker    | 2016-10-12T00:00:00 | 2016-10-12T23:59:00 | South Facilities Maintenance                                                            |      |            |                  |                                                                                                                                                                                                                                                |                    |          |          |              | 
```