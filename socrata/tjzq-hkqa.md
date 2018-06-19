# HGBP Restaurants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hgbp-restaurants-f03aa) |
| Metadata | [Link](https://data.hawaii.gov/api/views/tjzq-hkqa) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/tjzq-hkqa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/tjzq-hkqa/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | tjzq-hkqa |
| Name | HGBP Restaurants |
| Attribution | DBEDT, State of Energy |
| Category | Economic Development |
| Tags | green restaurants, sustainable, dbedt, hawaii |
| Created | 2013-08-22T00:34:35Z |
| Publication Date | 2014-04-03T00:33:58Z |

## Columns

```ls
| Included | Schema Type | Field Name       | Name                    | Data Type | Render Type |
| ======== | =========== | ================ | ======================= | ========= | =========== |
| No       | time        | :updated_at      | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | restaurant_names | Restaurant Name         | html      | html        |
| Yes      | series tag  | phone            | Restaurant Phone Number | phone     | phone       |
| Yes      | series tag  | website          | Restaurant Website      | url       | url         |
| Yes      | series tag  | logo             | Logo                    | photo     | photo       |
| Yes      | series tag  | green_report     | Green report            | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tjzq-hkqa d:2013-08-21T17:56:22.000Z t:logo=SgPL51-snqpsEOFnODJeQHxLq8Wij4rJC97H9EvMmLY t:phone_number="(808) 487-0091" t:website=http://www.gyotakuhawaii.com t:phone_type=Work t:green_report=http://energy.hawaii.gov/wp-content/uploads/2011/10/Gyotaku-Highlights-2010.pdf t:restaurant_names="<p><span>Gyotaku Japanese Restaurant</span></p>" m:row_number.tjzq-hkqa=1

series e:tjzq-hkqa d:2013-08-21T18:01:17.000Z t:logo=W1tUNPFFSLw0Z8G_3xI5pbGU4iR90TH6-aK4eA69dbE t:phone_number="(808) 396-5662" t:website=http://www.konabrewingco.com t:phone_type=Work t:green_report=http://energy.hawaii.gov/wp-content/uploads/2012/03/Final-Kona-Brewing-Company-Press-Packet-2012.pdf t:restaurant_names="<p><span>Kona Brewing Company&rsquo;s Kona Pub &amp; Brewery</span></p>" m:row_number.tjzq-hkqa=2

series e:tjzq-hkqa d:2014-04-02T17:32:21.000Z t:logo=XqLJk4KPsOJxuGq78OkFcHyck8_JeXzoD8jAA_oNufs t:phone_number="(808) 955-7383" t:website=http://www.hardrock.com t:phone_type=Work t:green_report=http://energy.hawaii.gov/wp-content/uploads/2012/03/Final-Hard-Rock-Cafe-Waikiki-Press-Packet-2012.pdf t:restaurant_names="<p>Hard Rock Cafe, Honolulu</p>" m:row_number.tjzq-hkqa=3
```

## Meta Commands

```ls
metric m:row_number.tjzq-hkqa p:long l:"Row Number"

entity e:tjzq-hkqa l:"HGBP Restaurants" t:attribution="DBEDT, State of Energy" t:url=https://data.hawaii.gov/api/views/tjzq-hkqa

property e:tjzq-hkqa t:meta.view v:id=tjzq-hkqa v:category="Economic Development" v:averageRating=0 v:name="HGBP Restaurants" v:attribution="DBEDT, State of Energy"

property e:tjzq-hkqa t:meta.view.owner v:id=av98-wszh v:screenName="Jonathan Chin" v:displayName="Jonathan Chin"

property e:tjzq-hkqa t:meta.view.tableauthor v:id=av98-wszh v:screenName="Jonathan Chin" v:roleName=editor v:displayName="Jonathan Chin"
```

## Top Records

```ls
| :updated_at | restaurant_names                          | phone                  | website                                | logo                                        | green_report                                                                                                   | 
| =========== | ========================================= | ====================== | ====================================== | =========================================== | ============================================================================================================== | 
| 1377107782  | Gyotaku Japanese Restaurant               | [(808) 487-0091, Work] | [http://www.gyotakuhawaii.com, null]   | SgPL51-snqpsEOFnODJeQHxLq8Wij4rJC97H9EvMmLY | [http://energy.hawaii.gov/wp-content/uploads/2011/10/Gyotaku-Highlights-2010.pdf, 2010]                        | 
| 1377108077  | Kona Brewing Company?s Kona Pub & Brewery | [(808) 396-5662, Work] | [http://www.konabrewingco.com, null]   | W1tUNPFFSLw0Z8G_3xI5pbGU4iR90TH6-aK4eA69dbE | [http://energy.hawaii.gov/wp-content/uploads/2012/03/Final-Kona-Brewing-Company-Press-Packet-2012.pdf, 2012]   | 
| 1396459941  | Hard Rock Cafe, Honolulu                  | [(808) 955-7383, Work] | [http://www.hardrock.com, null]        | XqLJk4KPsOJxuGq78OkFcHyck8_JeXzoD8jAA_oNufs | [http://energy.hawaii.gov/wp-content/uploads/2012/03/Final-Hard-Rock-Cafe-Waikiki-Press-Packet-2012.pdf, 2012] | 
| 1396459995  | IL Gelato Hawaii                          | [(808) 542-9276, Work] | [http://www.ilgelato-hawaii.com, null] | n4i0s8gj2sXDAbg97XPEO5GprcC-olqTIfE4AcLrGGc | [http://energy.hawaii.gov/wp-content/uploads/2012/03/Final-IL-Gelato-Presspacket-2012.pdf, 2012]               | 
```