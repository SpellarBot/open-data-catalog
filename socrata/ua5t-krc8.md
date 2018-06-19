# DOI Insurance Produsers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/doi-insurance-produsers) |
| Metadata | [Link](https://data.illinois.gov/api/views/ua5t-krc8) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ua5t-krc8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ua5t-krc8/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ua5t-krc8 |
| Name | DOI Insurance Produsers |
| Category | Social/Healthcare |
| Tags | doi producers |
| Created | 2016-12-02T18:19:09Z |
| Publication Date | 2016-12-02T18:22:59Z |

## Description

as of 12/02/2016

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | last_name      | Last_Name      | text      | text        |
| Yes      | series tag  | first_name     | First_Name     | text      | text        |
| No       |             | address_line_1 | Address_Line_1 | text      | text        |
| No       |             | address_line_2 | Address_Line_2 | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
| Yes      | series tag  | state          | State          | text      | text        |
| Yes      | series tag  | zip            | ZIP            | text      | text        |
| Yes      | series tag  | loa            | LOA            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_line_1,address_line_2
```

## Data Commands

```ls
series e:ua5t-krc8 d:2016-12-02T18:19:14.000Z t:loa="Life,Variable Contracts,Health" t:zip=84101 t:first_name=JASON t:state=UT t:last_name="A ALONA" t:city="SALT LAKE CITY" m:row_number.ua5t-krc8=1

series e:ua5t-krc8 d:2016-12-02T18:19:14.000Z t:loa="Life,Variable Contracts,Health" t:zip=46240 t:first_name=SCOTT t:state=IN t:last_name="A HEARN" t:city=INDIANAPOLIS m:row_number.ua5t-krc8=2

series e:ua5t-krc8 d:2016-12-02T18:19:14.000Z t:loa=Health t:zip=13601 t:first_name=MARIE t:state=NY t:last_name="A MANDA" t:city=WATERTOWN m:row_number.ua5t-krc8=3
```

## Meta Commands

```ls
metric m:row_number.ua5t-krc8 p:long l:"Row Number"

entity e:ua5t-krc8 l:"DOI Insurance Produsers" t:url=https://data.illinois.gov/api/views/ua5t-krc8

property e:ua5t-krc8 t:meta.view v:id=ua5t-krc8 v:category=Social/Healthcare v:averageRating=0 v:name="DOI Insurance Produsers"

property e:ua5t-krc8 t:meta.view.owner v:id=aauq-aa8g v:screenName="Suzann Rhodes" v:displayName="Suzann Rhodes"

property e:ua5t-krc8 t:meta.view.tableauthor v:id=aauq-aa8g v:screenName="Suzann Rhodes" v:roleName=publisher v:displayName="Suzann Rhodes"
```

## Top Records

```ls
| :updated_at | last_name | first_name | address_line_1                         | address_line_2        | city           | state | zip        | loa                            | 
| =========== | ========= | ========== | ====================================== | ===================== | ============== | ===== | ========== | ============================== | 
| 1480702754  | A ALONA   | JASON      | 49 NORTH 400 WEST                      |                       | SALT LAKE CITY | UT    | 84101      | Life,Variable Contracts,Health | 
| 1480702754  | A HEARN   | SCOTT      | 510 E. 96TH ST.                        | SUITE 500             | INDIANAPOLIS   | IN    | 46240      | Life,Variable Contracts,Health | 
| 1480702754  | A MANDA   | MARIE      | 146 ARSENAL ST.                        |                       | WATERTOWN      | NY    | 13601      | Health                         | 
| 1480702754  | A'HEARN   | JULIE      | HARMON & HARMON INSURANCE AGENCY, INC. | 200 S WESTERN AVE     | ABINGDON       | IL    | 61410-1656 | Life,Fire,Casualty             | 
| 1480702754  | AABERG    | CHAD       | 501 S CHERRY ST STE 490                |                       | DENVER         | CO    | 80246-1327 | Life,Variable Contracts,Health | 
| 1480702754  | AADALEN   | AMY        | MORGAN STANLEY                         | 225 S 6TH ST STE 5100 | MINNEAPOLIS    | MN    | 55402-4606 | Life,Variable Contracts,Health | 
| 1480702754  | AAKRE     | JOHN       | 3735 GOLDEN EAGLE LP SE                |                       | OLYMPIA        | WA    | 98513      | Life,Variable Contracts,Health | 
| 1480702754  | AALONA    | MAKAI      | 49 NORTH 400 WEST                      |                       | SALT LAKE CITY | UT    | 84101      | Life,Variable Contracts,Health | 
| 1480702754  | AAMODT    | ROBERT     | 630 NORTH MAIN STREET                  |                       | FARMINGTON     | UT    | 84025      | Life,Variable Contracts,Health | 
| 1480702754  | AANAND    | RAJA       | 966 OCEANSIDE TERRACE                  |                       | BARTLETT       | IL    | 60103      | Life,Variable Contracts,Health | 
```