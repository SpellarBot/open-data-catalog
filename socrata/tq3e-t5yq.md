# Lobbyist Data - Lobbyists

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-lobbyists) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/tq3e-t5yq) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/tq3e-t5yq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/tq3e-t5yq/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | tq3e-t5yq |
| Name | Lobbyist Data - Lobbyists |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | ethics, lobbyists |
| Created | 2015-04-24T21:58:19Z |
| Publication Date | 2015-10-20T22:06:25Z |

## Description

Lobbyists registered with the Chicago Board of Ethics since 2012.  Due to requirements for lobbyists to re-register and the importance of showing year for most lobbying-related data, the same lobbyist often will have multiple records.  See http://www.cityofchicago.org/city/en/depts/ethics/provdrs/lobby.html for more information on the Board of Ethics' role in regulating and reporting on lobbying in Chicago.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| No       |             | year           | YEAR           | number        | number        |
| Yes      | series tag  | lobbyist_id    | LOBBYIST_ID    | text          | number        |
| Yes      | series tag  | salutation     | SALUTATION     | text          | text          |
| Yes      | series tag  | first_name     | FIRST_NAME     | text          | text          |
| Yes      | series tag  | middle_initial | MIDDLE_INITIAL | text          | text          |
| Yes      | series tag  | last_name      | LAST_NAME      | text          | text          |
| Yes      | series tag  | suffix         | SUFFIX         | text          | text          |
| No       |             | address_1      | ADDRESS_1      | text          | text          |
| No       |             | address_2      | ADDRESS_2      | text          | text          |
| Yes      | series tag  | city           | CITY           | text          | text          |
| Yes      | series tag  | state          | STATE          | text          | text          |
| Yes      | series tag  | zip            | ZIP            | text          | text          |
| Yes      | series tag  | country        | COUNTRY        | text          | text          |
| Yes      | series tag  | email          | EMAIL          | text          | text          |
| Yes      | series tag  | phone          | PHONE          | text          | text          |
| Yes      | series tag  | fax            | FAX            | text          | text          |
| Yes      | series tag  | employer_id    | EMPLOYER_ID    | text          | number        |
| Yes      | series tag  | employer_name  | EMPLOYER_NAME  | text          | text          |
| Yes      | time        | created_date   | CREATED_DATE   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = created_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_1,address_2,year
```

## Data Commands

```ls
series e:tq3e-t5yq d:2015-06-09T14:10:04.000Z t:first_name=Marilyn t:employer_id=4089 t:zip=60610 t:phone=312-822-0505 t:fax=312-822-0568 t:email=mkatz@mkcpr.com t:lobbyist_id=6152 t:employer_name="MK Communications" t:last_name=Katz t:state=IL t:salutation=Ms t:country="United States" t:city=Chicago m:row_number.tq3e-t5yq=1

series e:tq3e-t5yq d:2015-06-09T14:10:04.000Z t:zip=60638 t:employer_id=4090 t:phone=773-586-8181 t:fax=773-586-8182 t:lobbyist_id=6153 t:middle_initial=J t:employer_name="Intergovernmental Consulting Group, Inc" t:state=Il t:city=Chicago t:country="United States" t:first_name=Mark t:email=mfary.icg@sbcglobal.net t:last_name=Fary t:salutation=Mr m:row_number.tq3e-t5yq=2

series e:tq3e-t5yq d:2015-06-09T14:10:04.000Z t:zip=60603 t:employer_id=4091 t:phone=312-346-7500 t:fax=312-580-2201 t:lobbyist_id=6154 t:middle_initial=P t:employer_name="Thompson Coburn LLP (dba Thompson Coburn Fagel Haber)" t:state=IL t:suffix=Esq t:city=Chicago t:country="United States" t:first_name=Clinton t:email=chansen@tcfhlaw.com t:last_name=Hansen t:salutation=Mr m:row_number.tq3e-t5yq=3
```

## Meta Commands

```ls
metric m:row_number.tq3e-t5yq p:long l:"Row Number"

entity e:tq3e-t5yq l:"Lobbyist Data - Lobbyists" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/tq3e-t5yq

property e:tq3e-t5yq t:meta.view v:id=tq3e-t5yq v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Lobbyists" v:attribution="City of Chicago"

property e:tq3e-t5yq t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:tq3e-t5yq t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| year | lobbyist_id | salutation | first_name | middle_initial | last_name | suffix | address_1                          | address_2 | city        | state | zip   | country       | email                        | phone        | fax          | employer_id | employer_name                                         | created_date | 
| ==== | =========== | ========== | ========== | ============== | ========= | ====== | ================================== | ========= | =========== | ===== | ===== | ============= | ============================ | ============ | ============ | =========== | ===================================================== | ============ | 
| 2011 | 6152        | Ms         | Marilyn    |                | Katz      |        | 350 W. Hubbard St. #200            |           | Chicago     | IL    | 60610 | United States | mkatz@mkcpr.com              | 312-822-0505 | 312-822-0568 | 4089        | MK Communications                                     |              | 
| 2011 | 6153        | Mr         | Mark       | J              | Fary      |        | 6808 W. Archer Ave                 |           | Chicago     | Il    | 60638 | United States | mfary.icg@sbcglobal.net      | 773-586-8181 | 773-586-8182 | 4090        | Intergovernmental Consulting Group, Inc               |              | 
| 2011 | 6154        | Mr         | Clinton    | P              | Hansen    | Esq    | 55 E. Monroe St. 40th Flr          |           | Chicago     | IL    | 60603 | United States | chansen@tcfhlaw.com          | 312-346-7500 | 312-580-2201 | 4091        | Thompson Coburn LLP (dba Thompson Coburn Fagel Haber) |              | 
| 2011 | 6155        | Mr         | Kenneth    | G              | Snyder    |        | 55 W. Van Buren                    |           | Chicago     | IL    | 60605 | United States | ksnyder@unitehere.org        | 312-663-4373 | 312-986-3828 | 4092        | Unite Here Local 1                                    |              | 
| 2011 | 6156        | Mr         | Jerome     | F              | Mytych    |        | 2004 Miner St., 2nd Floor          |           | Des Plaines | IL    | 60016 | United States | jm6714@att.com               | 847-759-5261 | 847-759-5263 | 4093        | AT&T Illinois                                         |              | 
| 2011 | 6157        | Mr         | COURTNEY   | C              | NOTTAGE   |        | 222 NORTH LASALLE STREET SUITE 300 |           | CHICAGO     | IL    | 60601 | United States | courtneynottage@aol.com      | 312-704-3812 | 312-368-4944 | 4094        | Fletcher, O'Brien, Kasper & Nottage, PC               |              | 
| 2011 | 6158        | Mr         | MICHAEL    | J              | KASPER    |        | 222 NORTH LASALLE STREET SUITE 300 |           | CHICAGO     | IL    | 60601 | United States | mjkasper60@aol.com           | 314-704-3292 | 312-368-4944 | 4095        | Fletcher, O'Brien, Kasper & Nottage, PC               |              | 
| 2011 | 6159        | Mr         | Richard    | J              | Guidice   |        | 350 W. 22nd Street, #106           |           | Lombard     | IL    | 60148 | United States | ccgillinois@msn.com          | 6309167400   | 6309167900   | 4096        | Capitol Consulting Group Illionis, LLC                |              | 
| 2011 | 6160        | Mr         | Anthony    | B              | Abbinante |        | 333 W. Wacker Drive, Suite 1100    |           | Chicago     | IL    | 60606 | United States | anthony.abbinante@diageo.com | 3122793464   | 3122793537   | 4740        | Diageo NA                                             |              | 
| 2011 | 6161        | Mr         | Dennis     | E              | Sexton    |        | 12 E. Erie St.                     |           | Chicago     | Il    | 60611 | United States | cidrovo@carpentersunion.org  | 3129511509   | 3129881722   | 4097        | Chicago Regional Council of Carpenters                |              | 
```