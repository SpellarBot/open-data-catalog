# Municipal Agents for the Elderly Listing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-agents-for-the-elderly-listing) |
| Metadata | [Link](https://data.ct.gov/api/views/dsrn-u9nm) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/dsrn-u9nm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/dsrn-u9nm/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | dsrn-u9nm |
| Name | Municipal Agents for the Elderly Listing |
| Attribution | Department on Aging |
| Category | Health and Human Services |
| Tags | elederly, seniors, aging |
| Created | 2014-04-03T14:00:03Z |
| Publication Date | 2014-08-01T17:55:38Z |

## Description

Listing of Department on Aging Municipal Agents for the Elderly

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | first_name  | First Name | text      | text        |
| Yes      | series tag  | last_name   | Last Name  | text      | text        |
| Yes      | series tag  | agency      | Agency     | text      | text        |
| No       |             | address     | Address    | text      | text        |
| Yes      | series tag  | city_town   | City/Town  | text      | text        |
| No       |             | st          | ST         | text      | text        |
| Yes      | series tag  | zip_code    | Zip Code   | text      | text        |
| Yes      | series tag  | phone       | phone      | text      | text        |
| Yes      | series tag  | fax         | fax        | text      | text        |
| Yes      | series tag  | e_mail      | e-mail     | text      | text        |
| Yes      | series tag  | region      | Region     | text      | number      |
| Yes      | series tag  | none        | (none)     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,st
```

## Data Commands

```ls
series e:dsrn-u9nm d:2014-08-01T10:53:40.000Z t:first_name="Remove Edward Slattery from List" m:row_number.dsrn-u9nm=1

series e:dsrn-u9nm d:2014-08-01T10:53:40.000Z t:city_town="Ledyard (Gales Ferry)" t:region=3 t:first_name=Lauren t:phone="(860) 464-0471" t:fax="(860) 464-2124" t:zip_code=00635 t:last_name=Rapp t:e_mail=senior.director@ledyardct.org t:agency="Ledyard Senior Center" m:row_number.dsrn-u9nm=2

series e:dsrn-u9nm d:2014-08-01T10:54:00.000Z t:city_town=Hartford t:region=4 t:first_name=Elby t:phone="(860) 757-4796" t:fax="(860) 723-8528" t:zip_code=06112 t:last_name=Gonzalez-Schwapp t:e_mail=egonzalezscwapp@hartford.gov t:agency="Health and Human Services" m:row_number.dsrn-u9nm=3
```

## Meta Commands

```ls
metric m:row_number.dsrn-u9nm p:long l:"Row Number"

entity e:dsrn-u9nm l:"Municipal Agents for the Elderly Listing" t:attribution="Department on Aging" t:url=https://data.ct.gov/api/views/dsrn-u9nm

property e:dsrn-u9nm t:meta.view v:id=dsrn-u9nm v:category="Health and Human Services" v:averageRating=0 v:name="Municipal Agents for the Elderly Listing" v:attribution="Department on Aging"

property e:dsrn-u9nm t:meta.view.license v:name="Public Domain"

property e:dsrn-u9nm t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:dsrn-u9nm t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | first_name                       | last_name        | agency                     | address            | city_town             | st | zip_code | phone          | fax            | e_mail                              | region | none | 
| =========== | ================================ | ================ | ========================== | ================== | ===================== | == | ======== | ============== | ============== | =================================== | ====== | ==== | 
| 1406890420  | Remove Edward Slattery from List |                  |                            |                    |                       |    |          |                |                |                                     |        |      | 
| 1406890420  | Lauren                           | Rapp             | Ledyard Senior Center      | 12 Van Tassell Dr  | Ledyard (Gales Ferry) | CT | 00635    | (860) 464-0471 | (860) 464-2124 | senior.director@ledyardct.org       | 3      |      | 
| 1406890440  | Elby                             | Gonzalez-Schwapp | Health and Human Services  | 2 Holcomb St.      | Hartford              | CT | 06112    | (860) 757-4796 | (860) 723-8528 | egonzalezscwapp@hartford.gov        | 4      |      | 
| 1406890440  | Kerry Ann                        | Kielbasa         | Granby Senior Center       | 15 North Granby Rd | Granby                | CT | 06035    | (860) 844-5351 | (860) 844-8848 | kkielbasa@granby-ct.gov             | 4      |      | 
| 1406890440  | Heather                          | Castrilli        | Madison Senior Center      | 29 Bradley Road    | Madison               | CT | 06443    | (203) 245-5687 | (203) 318-0670 | castrillih@madisonct.org            | 2      |      | 
| 1406890440  | Judith                           | Amarone          | Joyce Budrow Senior Center | 189 Pool Rd        | North Haven           | CT | 06473    | (203) 239-5432 | (203) 234-2130 | seniorcenter@town.north-haven.ct.us | 2      |      | 
| 1406890440  | Lucy                             | Smegielski       | Prospect Senior Center     | 6 Center St        | Prospect              | CT | 06712    | (203) 758-5300 | (203) 758-3837 | lulubelle4u@hotmail.com             | 5      |      | 
| 1406890440  | Melba                            | Neville          | Dept. of Human Serv.       | 77 Main St         | New Canaan            | CT | 06840    | (203) 594-3000 | (860) 594-3132 | melba.neville@ci.new-canaan.ct.us   | 1      |      | 
| 1406890440  | Joel                             | Sekorski         | Sullivan Senior Center     | 88 East Albert St  | Torrington            | CT | 06790    | (860) 489-2211 | (860) 489-2529 | joel_sekorski@torringtonct.org      | 5      |      | 
| 1406890440  | Susan                            | Consoli          | Old Saybrook Town Hall     | 322 Main St.       | Old Saybrook          | CT | 06475    | (860) 395-3188 | (860) 395-3189 | sconsoli@town.old-saybrook.ct.us    | 3      |      | 
```