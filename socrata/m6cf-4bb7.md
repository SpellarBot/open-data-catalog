# State of Hawaii Elected Officials

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-hawaii-elected-officials-6ed59) |
| Metadata | [Link](https://data.hawaii.gov/api/views/m6cf-4bb7) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/m6cf-4bb7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/m6cf-4bb7/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | m6cf-4bb7 |
| Name | State of Hawaii Elected Officials |
| Attribution | capitol IT Manager |
| Category | Government-Wide Support |
| Tags | house, senate |
| Created | 2012-11-09T22:12:25Z |
| Publication Date | 2013-01-07T20:30:08Z |

## Description

Legislators with contact info, district and location

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type | Render Type |
| ======== | =========== | ======================= | ======================= | ========= | =========== |
| No       | time        | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | last_name               | Last Name               | text      | text        |
| Yes      | series tag  | first_name              | First name              | text      | text        |
| Yes      | series tag  | chamber                 | Chamber                 | text      | text        |
| Yes      | series tag  | distinct_name           | Distinct Name           | text      | text        |
| Yes      | series tag  | party                   | Party                   | text      | text        |
| Yes      | series tag  | district_number         | District Number         | text      | number      |
| Yes      | series tag  | room_number             | Room Number             | text      | number      |
| Yes      | series tag  | phone_number            | Phone Number            | text      | text        |
| Yes      | series tag  | fax_number              | Fax Number              | text      | text        |
| No       |             | e_mail_address          | E-mail Address          | text      | text        |
| Yes      | series tag  | description_of_district | Description of District | text      | text        |
| Yes      | series tag  | leadership_position     | Leadership Position     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = e_mail_address
```

## Data Commands

```ls
series e:m6cf-4bb7 d:2013-01-07T12:29:06.000Z t:room_number=419 t:fax_number=808-586-6521 t:first_name="Henry J.C." t:leadership_position="Henry J.C. Aquino" t:phone_number=808-586-6520 t:last_name=Aquino t:description_of_district=Waipahu t:distinct_name=Aquino t:party=D t:district_number=38 t:chamber=H m:row_number.m6cf-4bb7=1

series e:m6cf-4bb7 d:2013-01-07T12:29:06.000Z t:room_number=403 t:fax_number=808-586-8469 t:first_name=Karen t:leadership_position="Karen Awana" t:phone_number=808-586-8465 t:last_name=Awana t:description_of_district="Ewa Villages, Kalaeloa, Honokai Hale, Nanakai Gardens, Ko Olina, Kahe Point, Nanakuli, Lualualei, Maili" t:distinct_name=Awana t:party=D t:district_number=43 t:chamber=H m:row_number.m6cf-4bb7=2

series e:m6cf-4bb7 d:2013-01-07T12:29:06.000Z t:room_number=331 t:first_name="Della Au" t:leadership_position="Della Au Belatti" t:phone_number=808-586-9425 t:last_name=Belatti t:description_of_district="Makiki, Tantalus, Papakolea, McCully, Pawaa, Manoa" t:distinct_name=Belatti t:party=D t:district_number=24 t:chamber=H m:row_number.m6cf-4bb7=3
```

## Meta Commands

```ls
metric m:row_number.m6cf-4bb7 p:long l:"Row Number"

entity e:m6cf-4bb7 l:"State of Hawaii Elected Officials" t:attribution="capitol IT Manager" t:url=https://data.hawaii.gov/api/views/m6cf-4bb7

property e:m6cf-4bb7 t:meta.view v:id=m6cf-4bb7 v:category="Government-Wide Support" v:attributionLink=http://www.capitol.hawaii.gov v:averageRating=0 v:name="State of Hawaii Elected Officials" v:attribution="capitol IT Manager"

property e:m6cf-4bb7 t:meta.view.license v:name="Creative Commons Attribution | No Derivative Works 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by-nd/3.0/legalcode v:logoUrl=images/licenses/cc30bynd.png

property e:m6cf-4bb7 t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:m6cf-4bb7 t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | last_name | first_name         | chamber | distinct_name | party | district_number | room_number | phone_number | fax_number   | e_mail_address                  | description_of_district                                                                                 | leadership_position       | 
| =========== | ========= | ================== | ======= | ============= | ===== | =============== | =========== | ============ | ============ | =============================== | ======================================================================================================= | ========================= | 
| 1357561746  | Aquino    | Henry J.C.         | H       | Aquino        | D     | 38              | 419         | 808-586-6520 | 808-586-6521 | repaquino@capitol.hawaii.gov    | Waipahu                                                                                                 | Henry J.C. Aquino         | 
| 1357561746  | Awana     | Karen              | H       | Awana         | D     | 43              | 403         | 808-586-8465 | 808-586-8469 | repawana@capitol.hawaii.gov     | Ewa Villages, Kalaeloa, Honokai Hale, Nanakai Gardens, Ko Olina, Kahe Point, Nanakuli, Lualualei, Maili | Karen Awana               | 
| 1357561746  | Belatti   | Della Au           | H       | Belatti       | D     | 24              | 331         | 808-586-9425 |              | repbelatti@capitol.hawaii.gov   | Makiki, Tantalus, Papakolea, McCully, Pawaa, Manoa                                                      | Della Au Belatti          | 
| 1357561746  | Brower    | Tom                | H       | Brower        | D     | 22              | 315         | 808-586-8520 |              | repbrower@capitol.hawaii.gov    | Waikiki, Ala Moana                                                                                      | Tom Brower                | 
| 1357561746  | Lee       | Chris              | H       | C. Lee        | D     | 51              | 313         | 808-586-9450 | 808-586-9456 | repclee@capitol.hawaii.gov      | Kailua, Waimanalo                                                                                       | Chris Lee                 | 
| 1357561746  | Cabanilla | Rida T.R.          | H       | Cabanilla     | D     | 41              | 442         | 808-586-6080 | 808-586-6081 | repcabanilla@capitol.hawaii.gov | Ewa Villages, Ewa Beach, Ewa Gentry, Ocean Pointe, West Loch                                            | Rida T.R. Cabanilla       | 
| 1357561746  | Cachola   | Romy M.            | H       | Cachola       | D     | 30              | 421         | 808-586-6010 | 808-586-6011 | repcachola@capitol.hawaii.gov   | Sand Island, Mokauea, Kapalama, Kalihi Kai                                                              | Romy M. Cachola           | 
| 1357561746  | Carroll   | Mele               | H       | Carroll       | D     | 13              | 405         | 808-586-6790 | 808-586-6779 | repcarroll@capitol.hawaii.gov   | Haiku, Hana, Kaupo, Kipahulu, Nahiku, Paia, Kahoolawe, Molokini, Lanai, Moloka'i, Molokini              | Mele Carroll              | 
| 1357561746  | Cheape    | Lauren Kealohilani | H       | Cheape        | R     | 45              | 439         | 808-586-9490 | 808-586-9496 | repcheape@capitol.hawaii.gov    | Schofield, Mokuleia, Waialua, Kunia, Waipio Acres, Mililani                                             | Lauren Kealohilani Cheape | 
| 1357561746  | Choy      | Isaac W.           | H       | Choy          | D     | 23              | 404         | 808-586-8475 |              | repchoy@capitol.hawaii.gov      | Manoa, Punahou, University, Moiliili                                                                    | Isaac W. Choy             | 
```