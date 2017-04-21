# Lobbyist Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-directory-2441d) |
| Metadata | [Link](https://data.sfgov.org/api/views/exbu-si57) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/exbu-si57/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/exbu-si57/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | exbu-si57 |
| Name | Lobbyist Directory |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, lobbyist, directory, registered, individual, firm, photo |
| Created | 2012-04-26T19:37:35Z |
| Publication Date | 2014-09-29T21:19:31Z |

## Description

The directory of individual lobbyists contains a list of all lobbyists registered with the San Francisco Ethics Commission.This dataset updates automatically every night.

## Columns

```ls
| Included | Schema Type | Field Name      | Name               | Data Type     | Render Type   |
| ======== | =========== | =============== | ================== | ============= | ============= |
| Yes      | series tag  | fullname        | FullName           | text          | text          |
| Yes      | series tag  | firmname        | FirmName           | text          | text          |
| Yes      | series tag  | filerid         | FilerId            | text          | text          |
| No       |             | addressline1    | AddressLine1       | text          | text          |
| No       |             | addressline2    | AddressLine2       | text          | text          |
| No       |             | addresscity     | AddressCity        | text          | text          |
| No       |             | addressstate    | AddressState       | text          | text          |
| No       |             | addresszip      | AddressZip         | text          | text          |
| Yes      | series tag  | phonebusiness   | PhoneBusiness      | text          | text          |
| Yes      | series tag  | email           | Email              | text          | text          |
| Yes      | series tag  | firstname       | FirstName          | text          | text          |
| Yes      | series tag  | lastname        | LastName           | text          | text          |
| Yes      | series tag  | picture         | Picture            | url           | url           |
| No       |             | report_year     | Latest_Report_Year | number        | text          |
| Yes      | time        | terminationdate | TerminationDate    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = terminationdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = addressline1,addressline2,addresscity,addressstate,addresszip,report_year
```

## Data Commands

```ls
series e:exbu-si57 d:0001-01-01T00:00:00.000Z t:picture=http://netfile.com/Sunlight/sf/lobbyist/picture/2017/1/SFO-112455 t:firmname="Loeven and Associates LLC" t:email=lewis@lewisloeven.com t:phonebusiness=4158605567 t:lastname=Loeven t:filerid=SFO-112455 t:firstname=Lewis t:fullname="Loeven, Lewis" m:row_number.exbu-si57=1

series e:exbu-si57 d:0001-01-01T00:00:00.000Z t:picture=http://netfile.com/Sunlight/sf/lobbyist/picture/2017/1/SFO-154186 t:firmname="Marathon Asset Management LP" t:email=cshort@marathonfund.com t:phonebusiness=2125003065 t:lastname=Short t:filerid=SFO-154186 t:firstname=Charles t:fullname="Short, Charles" m:row_number.exbu-si57=2

series e:exbu-si57 d:0001-01-01T00:00:00.000Z t:picture=http://netfile.com/Sunlight/sf/lobbyist/picture/2017/1/SFO-153485 t:firmname="Coalition for Better Housing" t:email=battime@sbcglobal.net t:phonebusiness="510 835-5103" t:lastname=Turner t:filerid=SFO-153485 t:firstname=Brook t:fullname="Turner, Brook" m:row_number.exbu-si57=3
```

## Meta Commands

```ls
metric m:row_number.exbu-si57 p:long l:"Row Number"

entity e:exbu-si57 l:"Lobbyist Directory" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/exbu-si57

property e:exbu-si57 t:meta.view v:id=exbu-si57 v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org/ethics/2012/01/lobbyist-database-api.html v:averageRating=0 v:name="Lobbyist Directory" v:attribution="San Francisco Ethics Commission"

property e:exbu-si57 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:exbu-si57 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:exbu-si57 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| fullname         | firmname                               | filerid    | addressline1                | addressline2 | addresscity   | addressstate | addresszip | phonebusiness  | email                       | firstname | lastname | picture                                                                   | report_year | terminationdate     | 
| ================ | ====================================== | ========== | =========================== | ============ | ============= | ============ | ========== | ============== | =========================== | ========= | ======== | ========================================================================= | =========== | =================== | 
| Loeven, Lewis    | Loeven and Associates LLC              | SFO-112455 | 5140 Diamond Heights Blvd   | 301A         | San Francisco | CA           | 94131      | 4158605567     | lewis@lewisloeven.com       | Lewis     | Loeven   | [http://netfile.com/Sunlight/sf/lobbyist/picture/2017/1/SFO-112455, null] | 2017        | 0001-01-01T00:00:00 | 
| Short, Charles   | Marathon Asset Management LP           | SFO-154186 | One Bryant Park             | 38th Floor   | Manhattan     | NY           | 10036      | 2125003065     | cshort@marathonfund.com     | Charles   | Short    | [http://netfile.com/Sunlight/sf/lobbyist/picture/2017/1/SFO-154186, null] | 2017        | 0001-01-01T00:00:00 | 
| Turner, Brook    | Coalition for Better Housing           | SFO-153485 | 906 York Street             |              | Oakland       | CA           | 94610      | 510 835-5103   | battime@sbcglobal.net       | Brook     | Turner   | [http://netfile.com/Sunlight/sf/lobbyist/picture/2017/1/SFO-153485, null] | 2017        | 0001-01-01T00:00:00 | 
| Beatty, Heather  | First Eagle Investment Management, LLC | SFO-154578 | 1345 Avenue of the Americas | 48th Floor   | New York      | NY           | 10105      | 2126983170     | heather.beatty@feim.com     | Heather   | Beatty   | [http://netfile.com/Sunlight/sf/lobbyist/picture/2017/1/SFO-154578, null] | 2017        | 0001-01-01T00:00:00 | 
| Carroll, Kevin   | HOTEL COUNCIL OF SAN FRANCISCO         | SFO-153768 | 323 GEARY STREET, #203      |              | SAN FRANCISCO | CA           | 94102      | (415) 391-5197 | kcarroll@hotelcouncilsf.org | Kevin     | Carroll  | [http://netfile.com/Sunlight/sf/lobbyist/picture/2017/1/SFO-153768, null] | 2017        | 0001-01-01T00:00:00 | 
| Beecher, Richard | Fortress Capital Formation, Llc        | SFO-153862 | 1345 Avenue of the Americas | 47th Floor   | Manhattan     | NY           | 10105      | 2124795312     | rbeecher@fortress.com       | Richard   | Beecher  | [http://netfile.com/Sunlight/sf/lobbyist/picture/2015/1/SFO-153862, null] | 2015        | 2015-03-31T00:00:00 | 
| Ross, James      | James Ross                             | SFO-153386 | 870 Market Street           | Suite 880    | San Francisco | CA           | 94102      | 4158240582     | jim@jimrossconsulting.com   | James     | Ross     | [http://netfile.com/Sunlight/sf/lobbyist/picture/2015/1/SFO-153386, null] | 2015        | 2015-06-30T00:00:00 | 
| Jordan, Taylor   | Barbary Coast Consulting               | SFO-153512 | 38 Mason Street             |              | San Francisco | CA           | 94102      | 4153640000     | jordan@barcoast.com         | Taylor    | Jordan   | [http://netfile.com/Sunlight/sf/lobbyist/picture/2016/1/SFO-153512, null] | 2016        | 2016-05-31T00:00:00 | 
| Lewis, Leah      | Cisco Systems, Inc.                    | SFO-153894 | 170 West Tasman Dr.         |              | San Jose      | CA           | 95134      | 4153896800     | llcisco@nmgovlaw.com        | Leah      | Lewis    | [http://netfile.com/Sunlight/sf/lobbyist/picture/2015/1/SFO-153894, null] | 2015        | 2015-11-30T00:00:00 | 
| Reyes, Rudolph   | Verizon Corp Rsrcs Group LLC           | SFO-153977 | 201 Spear Street, 7th Floor |              | San Francisco | CA           | 94105      | 415-228-1465   | rudy.reyes@verizon.com      | Rudolph   | Reyes    | [http://netfile.com/Sunlight/sf/lobbyist/picture/2015/1/SFO-153977, null] | 2015        | 2015-11-30T00:00:00 | 
```