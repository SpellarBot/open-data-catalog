# HGBP Hotels & Resorts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hgbp-hotels-resorts-7eece) |
| Metadata | [Link](https://data.hawaii.gov/api/views/m3r4-2ghp) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/m3r4-2ghp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/m3r4-2ghp/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | m3r4-2ghp |
| Name | HGBP Hotels & Resorts |
| Category | Economic Development |
| Tags | green, business, hotel, resort, hospitality |
| Created | 2014-03-15T01:14:45Z |
| Publication Date | 2014-04-03T00:17:49Z |

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | hotel_name         | Hotel Name         | text      | text        |
| Yes      | series tag  | hotel_phone_number | Hotel Phone Number | text      | text        |
| Yes      | series tag  | hotel_website      | Hotel Website      | url       | url         |
| Yes      | series tag  | 1st_green_report   | Most recent Report | url       | url         |
| Yes      | series tag  | logo               | Logo               | photo     | photo       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:m3r4-2ghp d:2014-03-14T18:47:33.000Z t:logo=NuLjf14YlUBUrhMtBjoQrvQlg7ewRbqNPrEAcTpC7XM t:1st_green_report=http://energy.hawaii.gov/wp-content/uploads/2011/10/Marriott-Waiohai-Beach-Club-Highlights-2010.pdf t:hotel_phone_number="(808) 742-4400" t:hotel_name="Marriott Waiohai Beach Club" t:hotel_website=http://www.marriott.com/hotels/travel/lihwi-marriotts-waiohai-beach-club/ m:row_number.m3r4-2ghp=1

series e:m3r4-2ghp d:2014-03-14T18:48:28.000Z t:logo=_DfQ0zS2KOdwVq0PKcsq-1Bz4k-6OWV2Elaex4Smh00 t:1st_green_report=http://energy.hawaii.gov/wp-content/uploads/2012/04/Westin-KOR-Villas-Press-Packet-04.26.13.pdf t:hotel_phone_number="(808) 667-3200" t:hotel_name="Westin Kaanapali Ocean Resort Villas" t:hotel_website=http://www.westinkaanapali.com/ m:row_number.m3r4-2ghp=2

series e:m3r4-2ghp d:2014-03-14T18:48:40.000Z t:logo=3qVNReCHUfqQGDszX5NiHdSPgq237Ps3fQhl8cLUcRo t:1st_green_report=http://energy.hawaii.gov/wp-content/uploads/2011/10/Wailea-Beach-Marriott-Highlights-2010.pdf t:hotel_phone_number="(808) 879-1922" t:hotel_name="Wailea Beach Marriott Resort & Spa" t:hotel_website=http://www.marriott.com/hotels/travel/hnmmc-wailea-beach-marriott-resort-and-spa/ m:row_number.m3r4-2ghp=3
```

## Meta Commands

```ls
metric m:row_number.m3r4-2ghp p:long l:"Row Number"

entity e:m3r4-2ghp l:"HGBP Hotels & Resorts" t:url=https://data.hawaii.gov/api/views/m3r4-2ghp

property e:m3r4-2ghp t:meta.view v:id=m3r4-2ghp v:category="Economic Development" v:averageRating=0 v:name="HGBP Hotels & Resorts"

property e:m3r4-2ghp t:meta.view.owner v:id=av98-wszh v:screenName="Jonathan Chin" v:displayName="Jonathan Chin"

property e:m3r4-2ghp t:meta.view.tableauthor v:id=av98-wszh v:screenName="Jonathan Chin" v:roleName=editor v:displayName="Jonathan Chin"
```

## Top Records

```ls
| :updated_at | hotel_name                           | hotel_phone_number | hotel_website                                                                                                           | 1st_green_report                                                                                            | logo                                        | 
| =========== | ==================================== | ================== | ======================================================================================================================= | =========================================================================================================== | =========================================== | 
| 1394822853  | Marriott Waiohai Beach Club          | (808) 742-4400     | [http://www.marriott.com/hotels/travel/lihwi-marriotts-waiohai-beach-club/, Marriott Waiohai Beach Club]                | [http://energy.hawaii.gov/wp-content/uploads/2011/10/Marriott-Waiohai-Beach-Club-Highlights-2010.pdf, 2010] | NuLjf14YlUBUrhMtBjoQrvQlg7ewRbqNPrEAcTpC7XM | 
| 1394822908  | Westin Kaanapali Ocean Resort Villas | (808) 667-3200     | [http://www.westinkaanapali.com/, Westin Kaanapali Ocean Resort Villas]                                                 | [http://energy.hawaii.gov/wp-content/uploads/2012/04/Westin-KOR-Villas-Press-Packet-04.26.13.pdf, 2013]     | _DfQ0zS2KOdwVq0PKcsq-1Bz4k-6OWV2Elaex4Smh00 | 
| 1394822920  | Wailea Beach Marriott Resort & Spa   | (808) 879-1922     | [http://www.marriott.com/hotels/travel/hnmmc-wailea-beach-marriott-resort-and-spa/, Wailea Beach Marriott Resort & Spa] | [http://energy.hawaii.gov/wp-content/uploads/2011/10/Wailea-Beach-Marriott-Highlights-2010.pdf, 2010]       | 3qVNReCHUfqQGDszX5NiHdSPgq237Ps3fQhl8cLUcRo | 
| 1394822971  | Hyatt Regency Maui Resort & Spa      | (808) 661-1234     | [http://maui.hyatt.com/en/hotel/home.html, Hyatt Regency Maui Resort & Spa]                                             | [http://energy.hawaii.gov/wp-content/uploads/2011/10/Hyatt-Regency-Maui-2009.pdf, 2009]                     | ODrTLlbXLHFF9prMUyC2OuFG3sr4ffa2CQCKOHBV4uM | 
| 1394822991  | Fairmont Kea Lani                    | (808) 875-4100     | [http://www.fairmont.com/kea-lani-maui/, Fairmont Kea Lani]                                                             | [http://energy.hawaii.gov/wp-content/uploads/2011/10/Fairmont-Kea-Lani-Maui-Highlights-2010.pdf, 2010]      | 7hS9OulQYpLlWCj3U0-ECtAYSU7WIwLSqnUlCN0BIl0 | 
| 1394823067  | Moana Surfrider                      | (808) 922-3111     | [http://www.moana-surfrider.com/, Moana Surfrider]                                                                      | [http://energy.hawaii.gov/wp-content/uploads/2012/03/Moana-2009.pdf, 2009]                                  | GHy6_7cIN2jYnfnsCF5I7py8MQz2mV7QsHNp7m961SM | 
| 1394823085  | Ko Olina Marriot Beach Club          | (808) 679-4700     | [http://www.marriott.com/hotels/travel/hnlko-marriotts-ko-olina-beach-club/, Ko Olina Marriot Beach Club]               | [http://energy.hawaii.gov/wp-content/uploads/2011/10/Marriott-Ko-Olina-Highlights-2010.pdf, 2010]           | XEjteSM7QsCeuDo_y4S7-n6J1uu3k4Q_rh0wvRgGFsE | 
| 1394823126  | Hyatt Regency Waikiki                | (808) 923-1234     | [http://www.waikiki.hyatt.com/en/hotel/home.html, Hyatt Regency Waikiki]                                                | [http://energy.hawaii.gov/wp-content/uploads/2012/04/Hyatt-Regency-Waikiki-Press-Packet-04.26.13.pdf, 2013] | UKMQSV9LeLC9TBYPRnH7y5vopA5rPMhoqoe9t1gUyZ4 | 
| 1394823198  | Hawaii Prince Hotel Waikiki          | (808) 956-1111     | [http://www.princeresortshawaii.com/hawaii-prince-hotel-waikiki/index.php, Hawaii Prince Hotel Waikiki]                 | [http://energy.hawaii.gov/wp-content/uploads/2012/03/Hawaii-Prince-Hotel-Waikiki-Golf-Club.pdf, 2006]       | yngkHuYJCAHzVnBbnD3yonWIPeqMHPsbrHRjwQYlFm4 | 
| 1394823219  | Aqua Bamboo Waikiki                  | (808) 954-7412     | [http://www.aquabamboo.com/, Aqua Bamboo Waikiki]                                                                       | [http://energy.hawaii.gov/wp-content/uploads/2011/10/AquaBamboo_pressrelease.pdf, 2010]                     | WwE9U4l4PFm1bjzON8fTFMYuwRMX3f-v7TnlgRJ_XJ0 | 
```