# Aquatic Pesticide and Algae Management Draft General Permit Comments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aquatic-pesticide-and-algae-management-draft-general-permit-comments) |
| Metadata | [Link](https://data.wa.gov/api/views/ysrq-tssh) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/ysrq-tssh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/ysrq-tssh/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | ysrq-tssh |
| Name | Aquatic Pesticide and Algae Management Draft General Permit Comments |
| Category | Natural Resources & Environment |
| Tags | ecology, plants, algae |
| Created | 2015-11-03T16:20:07Z |
| Publication Date | 2015-12-23T17:34:06Z |
| Rows Updated | 2015-12-23T17:32:37Z |

## Description

The Aquatic Plant and Algae Management General Permit (permit) is a combined National Pollutant Discharge Elimination System (NPDES) and State Waste Discharge General Permit. It covers the in-water and shoreline (including roadsides and ditch banks) treatment of native and noxious plants and algae. It also covers nutrient inactivation treatments. The permit allows the discharge of a specific list of aquatic labeled herbicides, algaecides, biological water clarifiers, adjuvants, marker dyes, and nutrient inactivation products into the freshwaters of Washington. These are comments received on the draft permit.

## Columns

```ls
| Included | Schema Type | Field Name                    | Name                            | Data Type | Render Type |
| ======== | =========== | ============================= | =============================== | ========= | =========== |
| No       | time        | :updated_at                   | updated_at                      | meta_data | meta_data   |
| Yes      | series tag  | name                          | Name                            | text      | text        |
| Yes      | series tag  | attachment                    | Attachment                      | document  | document    |
| Yes      | series tag  | attachment_2                  | Attachment 2                    | document  | document    |
| Yes      | series tag  | draft_permit_comments         | Draft Permit Comments           | html      | html        |
| Yes      | series tag  | factsheet_comments            | Factsheet Comments              | html      | html        |
| Yes      | series tag  | sepa_determination_comments   | SEPA Determination Comments     | html      | html        |
| Yes      | series tag  | notice_of_intent_noi_comments | Notice of Intent (NOI) Comments | html      | html        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:ysrq-tssh l:"Aquatic Pesticide and Algae Management Draft General Permit Comments" t:url=https://data.wa.gov/api/views/ysrq-tssh

property e:ysrq-tssh t:meta.view v:id=ysrq-tssh v:category="Natural Resources & Environment" v:averageRating=0 v:name="Aquatic Pesticide and Algae Management Draft General Permit Comments"

property e:ysrq-tssh t:meta.view.owner v:id=us76-w9xc v:screenName="Tim Lewis" v:roleName=publisher v:displayName="Tim Lewis"

property e:ysrq-tssh t:meta.view.tableauthor v:id=us76-w9xc v:screenName="Tim Lewis" v:roleName=publisher v:displayName="Tim Lewis"
```