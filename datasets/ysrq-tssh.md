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
series e:ysrq-tssh d:2015-12-04T15:39:35.000Z t:draft_permit_comments="Our lake has hired aqua technex for over 10 years to spray-every year to keep the costs down we spend hours posting each property before and remove all signs as required to assure we abide by the requirements.  this new purposal would impact the price and I fear many neighbors would no longer be able to afford the spray costs which would then effect the overall use of our lake,  right now its in beautiful condition and many fisherman and families do not fear swimming and get tangled in the lilies,  please do NOT consider this new rule." t:name="becky argyle/Mission Lake-Kitsap County" m:row_number.ysrq-tssh=1

series e:ysrq-tssh d:2015-12-04T20:58:15.000Z t:draft_permit_comments="While I fully support a safe and standard method of treating lakes for noxious weeds, I am not in favor of any further regulation at this time that would incur further cost to the companies doing treatment. Those costs would be directly passed down to property owners, who are struggling to find ways to finance these treatments already. Property owners are already bearing the burden of maintaining lake health of waters owned by the state through no fault of their own. If the DOE wishes to further regulate chemical treatments on state owned bodies of water, perhaps the DOE should consider providing more funding to property owners to maintain these waters" t:name="mark silberling" m:row_number.ysrq-tssh=2

series e:ysrq-tssh d:2015-12-07T09:14:42.000Z t:draft_permit_comments="Our first concern is the new requirement that the applicator return to the lake and remove the signed Ecology requires be posted.  This is something that will add between $500 and $1,000 to the cost of completing noxious aquatic weed control for the clients that require these services.  There should be an exception that the sponsor organization or the homeowners we work for can remove these signs.


This permit keeps one of the primary tools we have to fight toxic algae blooms as experimental when it is completely operational world wide.  Phoslock is a technology that was developed 25 years ago by the Australian National Science Academy.  It sequesters phosphorus with a nontoxic technology and that lowers the carrying capacity for a lake or pond to develop toxic algae blooms.  The alternatives that are allowed are Alum buffered with Sodium Aluminate, this blend can be extremely toxic to fish and there have been two major fish kills from the introduction of these technologies to Washington Lakes in the past few years.  This has occurred when the buffer Sodium Aluminate is added to the mix.  This compound is extremely dangerous to handle.  There are over 20 published papers in peer reviewed scientific journals that support the operational use of this technology, it should be considered operational so there are alternatives to the more toxic technologies to turn back phosphorus pollution. 


In the past decades, Sonar aquatic herbicide has been used to effectively eradicate the invasive aquatic weed Eurasian Milfoil using a whole lake treatment scenario.  This practice would effectively be banned by this permit.  The laws in Washington State prohibit actions that would impair the control of noxious aquatic weeds and not having access to this technology where appropriate would impair Eurasian Milfoil Control Efforts.  In addition, there has been one infestation of Hydrilla in Washington State and that infestation was eradicated using whole lake treatment technology.  If Hydrilla returns, and as a Class A noxious weed its eradication is mandated, this permit will limit the ability to attack this plant." t:name="Terry McNabb" m:row_number.ysrq-tssh=3
```

## Meta Commands

```ls
metric m:row_number.ysrq-tssh p:long l:"Row Number"

entity e:ysrq-tssh l:"Aquatic Pesticide and Algae Management Draft General Permit Comments" t:url=https://data.wa.gov/api/views/ysrq-tssh

property e:ysrq-tssh t:meta.view v:id=ysrq-tssh v:category="Natural Resources & Environment" v:averageRating=0 v:name="Aquatic Pesticide and Algae Management Draft General Permit Comments"

property e:ysrq-tssh t:meta.view.owner v:id=us76-w9xc v:screenName="Tim Lewis" v:displayName="Tim Lewis"

property e:ysrq-tssh t:meta.view.tableauthor v:id=us76-w9xc v:screenName="Tim Lewis" v:roleName=publisher v:displayName="Tim Lewis"
```