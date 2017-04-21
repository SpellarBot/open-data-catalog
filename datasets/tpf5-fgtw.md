# Lobbyist Data - Historical - Lobbyist Registry - 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-lobbyist-registry-2011-3476b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/tpf5-fgtw) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/tpf5-fgtw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/tpf5-fgtw/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | tpf5-fgtw |
| Name | Lobbyist Data - Historical - Lobbyist Registry - 2011 |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | lobbyists, historical |
| Created | 2011-09-30T08:00:42Z |
| Publication Date | 2013-01-23T19:45:51Z |

## Description

All lobbyist registration fillings submitted to the Board of Ethics during the 2011 reporting period. / All lobbyists must register with the City of Chicago Board of Ethics by filing a Statement of Registration within five business days of engaging in lobbying activity and annually thereafter by January 20th. Lobbyist registration information is submitted to the Board of Ethics in paper form and is available in its entirety in the Board's offices. 
Data Owner:  Board of Ethics 
[http://j.mp/mbH9BN] /
Time Period: January 1, 2011 to present /
Related Applications:  Registered Lobbyist List [http://bit.ly/FOctNY]
2010 Lobbyist Registry 
[http://j.mp/kyZ4HP]

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type | Render Type |
| ======== | =========== | ========================== | ========================== | ========= | =========== |
| Yes      | time        | filing_year                | FILING YEAR                | number    | number      |
| Yes      | series tag  | lobbyist_last_name         | LOBBYIST LAST NAME         | text      | text        |
| Yes      | series tag  | lobbyist_first_name        | LOBBYIST FIRST NAME        | text      | text        |
| Yes      | series tag  | lobbyist_middle_initial    | LOBBYIST MIDDLE INITIAL    | text      | text        |
| No       |             | lobbyist_address           | LOBBYIST ADDRESS           | text      | text        |
| Yes      | series tag  | lobbyist_city              | LOBBYIST CITY              | text      | text        |
| Yes      | series tag  | state                      | STATE                      | text      | text        |
| Yes      | series tag  | lobbyist_zip               | LOBBYIST ZIP               | text      | number      |
| Yes      | series tag  | registered_employers_names | REGISTERED EMPLOYERS NAMES | text      | text        |
| Yes      | series tag  | lobbying_clients_name      | LOBBYING CLIENTS NAME      | text      | text        |
```

## Time Field

```ls
Value = filing_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = lobbyist_address
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:tpf5-fgtw l:"Lobbyist Data - Historical - Lobbyist Registry - 2011" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/tpf5-fgtw

property e:tpf5-fgtw t:meta.view v:id=tpf5-fgtw v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Historical - Lobbyist Registry - 2011" v:attribution="City of Chicago"

property e:tpf5-fgtw t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:tpf5-fgtw t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| filing_year | lobbyist_last_name | lobbyist_first_name | lobbyist_middle_initial | lobbyist_address                                            | lobbyist_city | state | lobbyist_zip | registered_employers_names        | lobbying_clients_name                      | 
| =========== | ================== | =================== | ======================= | =========================================================== | ============= | ===== | ============ | ================================= | ========================================== | 
| 2011        | Pfleger            | Erika               |                         | Kane Center Clinical Legal Studies, 6025 S. University Ave. | Chicago       | IL    | 60637        | Institute for Justice             | Institute for Justice                      | 
| 2011        | Phelps             | Suzanne             | E                       | 4773 Austin Trace                                           | Zionsville    | IN    | 46077        | Chrysalis Consulting LLC          | Chrysalis Consulting LLC                   | 
| 2011        | Phipps             | Garrett             | A                       | 205 N Michigan Ave #2510                                    | Chicago       | IL    | 60601        | Skyway Concession Company LLC     | Skyway Concession Co., LLC                 | 
| 2011        | Pilewski           | Joseph              | E                       | 311 S. Wacker Dr., Ste. 4200                                | Chicago       | IL    | 60606        | Duff and Phelps LLC               | Loretto Hospital                           | 
| 2011        | Pilewski           | Joseph              | E                       | 311 S. Wacker Dr., Ste. 4200                                | Chicago       | IL    | 60606        | Duff and Phelps LLC               | Lawson Products, Inc                       | 
| 2011        | Pilewski           | Joseph              | E                       | 311 S. Wacker Dr., Ste. 4200                                | Chicago       | IL    | 60606        | Duff and Phelps LLC               | Federal-Mogul Corp.                        | 
| 2011        | Pilewski           | Joseph              | E                       | 311 S. Wacker Dr., Ste. 4200                                | Chicago       | IL    | 60606        | Duff and Phelps LLC               | Sinai Health System                        | 
| 2011        | Pilewski           | Joseph              | E                       | 311 S. Wacker Dr., Ste. 4200                                | Chicago       | IL    | 60606        | Duff and Phelps LLC               | Clarke Group (FKA Clarke Mosquito Control) | 
| 2011        | Pineiro            | Carlos              |                         | 71 South Wacker Dr., Ste. 500                               | Chicago       | IL    | 60606        | Goldman, Sachs & Co.              | Goldman, Sachs & Co                        | 
| 2011        | Pink               | Allison             |                         | 222 W. Adams, Ste. 520                                      | Chicago       | Il    | 60606        | Siebert Brandford Shank & Co, LLC | Siebert Brandford Shank & Co, LLC          | 
```