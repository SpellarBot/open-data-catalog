# Lobbyist Client Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-client-directory-d1b5d) |
| Metadata | [Link](https://data.sfgov.org/api/views/u4y3-k4vs) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/u4y3-k4vs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/u4y3-k4vs/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | u4y3-k4vs |
| Name | Lobbyist Client Directory |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, lobbyist, client, directory |
| Created | 2012-04-26T21:08:06Z |
| Publication Date | 2014-09-29T21:49:07Z |

## Description

Directory of Clients of  Lobbyists; there are multiple records if there is more than one Lobbyist for a Client.  This list includes both current and past clients for each lobbyist.Lobbyist clients are disclosed by lobbyists registered with the Ethics Commission on a monthly basis.  This dataset updates automatically every night.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | client           | Client           | text      | text        |
| Yes      | series tag  | lobbyist         | Lobbyist         | text      | text        |
| Yes      | series tag  | lobbyist_firm    | Lobbyist_Firm    | text      | text        |
| Yes      | series tag  | client_phone     | Client_Phone     | text      | text        |
| No       |             | client_address   | Client_Address   | text      | text        |
| No       |             | client_address_2 | Client_Address_2 | text      | text        |
| Yes      | series tag  | client_city      | Client_City      | text      | text        |
| Yes      | series tag  | client_state     | Client_State     | text      | text        |
| Yes      | series tag  | client_zip       | Client_Zip       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = client_address,client_address_2
```

## Data Commands

```ls
series e:u4y3-k4vs d:2017-02-10T00:09:35.000Z t:client_zip=94109 t:lobbyist_firm="Sgc Strategic Communications" t:client="Alla Eddine Beddar Benhamimi" t:lobbyist="Cassolato, Stefano" t:client_phone=4153416575 t:client_state=CA t:client_city="San Francisco" m:row_number.u4y3-k4vs=1

series e:u4y3-k4vs d:2017-02-10T00:09:35.000Z t:client_zip=94109 t:lobbyist_firm="Sgc Strategic Communications" t:client="City Rent-A-Car" t:lobbyist="Cassolato, Stefano" t:client_phone=4155963734 t:client_state=CA t:client_city="San Francisco" m:row_number.u4y3-k4vs=2

series e:u4y3-k4vs d:2017-03-03T16:22:23.000Z t:client_zip=94116 t:lobbyist_firm="The Marquez Law Group" t:client="Victor Nguyen- Proposed Mcd" t:lobbyist="Marquez, Victor M." t:client_phone=4159900857 t:client_state=CA t:client_city="San Francisco" m:row_number.u4y3-k4vs=3
```

## Meta Commands

```ls
metric m:row_number.u4y3-k4vs p:long l:"Row Number"

entity e:u4y3-k4vs l:"Lobbyist Client Directory" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/u4y3-k4vs

property e:u4y3-k4vs t:meta.view v:id=u4y3-k4vs v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org/ethics/2012/01/lobbyist-database-api.html v:averageRating=0 v:name="Lobbyist Client Directory" v:attribution="San Francisco Ethics Commission"

property e:u4y3-k4vs t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:u4y3-k4vs t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:u4y3-k4vs t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| :updated_at | client                       | lobbyist             | lobbyist_firm                | client_phone | client_address                 | client_address_2 | client_city   | client_state | client_zip | 
| =========== | ============================ | ==================== | ============================ | ============ | ============================== | ================ | ============= | ============ | ========== | 
| 1486685375  | Alla Eddine Beddar Benhamimi | Cassolato, Stefano   | Sgc Strategic Communications | 4153416575   | 2718 Hyde St.                  |                  | San Francisco | CA           | 94109      | 
| 1486685375  | City Rent-A-Car              | Cassolato, Stefano   | Sgc Strategic Communications | 4155963734   | 1500 Van Ness Ave.             |                  | San Francisco | CA           | 94109      | 
| 1488558143  | Victor Nguyen- Proposed Mcd  | Marquez, Victor M.   | The Marquez Law Group        | 4159900857   | 563 Dewey Blvd                 |                  | San Francisco | CA           | 94116      | 
| 1488558143  | Hbk Engineering              | Lopez, Marisol       | Platinum Advisors            | 3124320076   | 921 WEST VAN BUREN STREET #100 |                  | CHICAGO       | IL           | 60607      | 
| 1488558143  | Tzk Broaway, Llc             | Anderson, Darius     | Platinum Advisors            | 916-443-8891 | 1215 K STREET, SUITE 1150      |                  | SACRAMENTO    | CA           | 95814      | 
| 1488558143  | Airbnb, Inc.                 | Middlebrook, Matt    | Airbnb                       | 4156623254   | 888 Brannan St.                |                  | San Francisco | CA           | 94103      | 
| 1488558143  | Golden State Warriors        | Lopez, Marisol       | Platinum Advisors            | 5109862200   | 1011 BROADWAY                  |                  | OAKLAND       | CA           | 94607      | 
| 1488558143  | Tcig                         | Sarjapur, Melinda A. | Reuben, Junius & Rose, Llp   | 4155679000   | 1650 Jackson, No. 505          |                  | San Francisco | CA           | 94109      | 
| 1488558143  | Brandon Muller               | Kevlin, John         | Reuben, Junius & Rose, Llp   | 949-456-0297 | 32681 Caspian Sea Dr.          |                  | Dana Point    | CA           | 92629      | 
| 1488558143  | Stricklin/john               | Frattin, Daniel      | Reuben, Junius & Rose, Llp   | 415-355-0900 | 601 Van Ness,No. 3606          |                  | San Francisco | CA           | 94102      | 
```