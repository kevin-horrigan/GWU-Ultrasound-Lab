# Safety

The GW safety requirements that apply to this lab, and the source documents they come from.

`reference/` holds the GW originals as downloaded on 2026-09-09. They are committed rather than
linked because GW reorganises its safety sites and a dead link is worse than a dated copy. **Check
`safety.gwu.edu` and `researchsafety.gwu.edu` for newer revisions before relying on any of them**;
several are marked "draft" by GW itself.

Chemical-specific findings, the SDS register and the current state of the store are in
[`Chemicals/`](Chemicals/README.md). This page is the program around it.

## Who to call

GW splits lab safety across two offices, and the split is not obvious.

| Need | Office | Contact |
|---|---|---|
| **Chemicals**: hygiene plan, inventory, SDS, hazardous waste, hazard information sheets | **Environmental Health & Safety (EHS)** | **202-994-4347**, safety@gwu.edu |
| Anything happening now: spill, exposure, a dry shock-sensitive container | **GW Emergency Services** | **202-994-6111** or 911 |
| Waste pickup once something is declared waste | FixIt | `fixit.assetworks.io/ready` |
| Biosafety, radiation, laser, IBC and IACUC | **Office of Research Safety (ORS)** | Ross Hall B-05 |
| Lab close-out and space clearance | **ORS** | 30 days notice required |

**Phone numbers disagree between sources.** ORS documents print **202-994-8258**, while the ORS
website lists **202-994-2407** and **202-994-1813**. EHS is **202-994-4347** consistently. Email
reaches ORS at both `researchsafety@gwu.edu` and `labsafety@gwu.edu` depending on the document.
Addresses differ too: EHS is given as Ross Hall B05 on the PPE sheet and Phillips Hall B-148/101 on
the waste checklist. If a call matters, try EHS first, since chemicals are the live issue here.

## Two PIs share this space

SEH 5290 is a **multiple-PI laboratory**: Zderic and Kay. That is why the blank form in
`reference/` is the **multiple-PI** version of the Hazard Information Sheet rather than the single-PI
one, and it changes several things.

**The hazard sheet needs both PIs.** The 2026 form provides four PI blocks, each with its own
Principal Investigator, Dept & Email, Alternate Contact, **24-hour phone**, and **Bench ID**. The
2019 sheet names only Dr Zderic. If Kay's group works in the same room, that sheet is incomplete as
well as stale, and a responder calling the only number on it may reach someone who does not own the
material involved.

**Chemical ownership has to be attributable.** The photographs show containers hand-marked "Kay",
"Efimov" and "KAY LAB", and the inventory the CHP asks for is per laboratory space, not per person.
In a shared room the practical questions are: who owns each container, who replaces it, and whose
budget disposes of it.

**Which matters most for the picric acid.** It is marked **"Efimov"**, and Efimov is neither of the
two current PIs. Orphaned material from a departed group is common in shared space and the
close-out guidelines are explicit that *"items left behind by vacating Investigators will become the
responsibility of the Department."* So the disposal cost question has an answer, and it is worth
raising with EHS on the same call rather than letting it stall the removal.

**Practices apply to everyone in the room.** Segregating the cyanides, restraining the gas cylinders
or designating an area for particularly hazardous substances affects both groups, so those are
decisions for both PIs rather than one.

## This lab is BSL-2

That is not a small addition to the chemical picture. It brings in a second regulator, a second
governing manual, an **annual ORS inspection**, and, if any human-derived material is handled, the
OSHA Bloodborne Pathogens Standard.

`reference/Biosafety Level One_Two_Inspection Checklist_final 2025.docx` is the self-inspection form,
84 questions. Work through it directly rather than relying on the summary below. The headline items:

**The Biosafety Manual is a physical binder with required contents.** A current copy of GW's
Biosafety Manual, lab contact information, documented lab-specific training, emergency, spill and
exposure procedures, approved IBC paperwork, training certificates for every member, lab-specific
SOPs, and it must be accessible to everyone.

**The door sign is a BSL-2 requirement in its own right.** It must carry the **biosafety level**,
required immunisations, emergency contact numbers, and the PPE needed to enter. This is separate
from, and additional to, the Hazard Information Sheet the CHP asks for. `GW_Biohazard_sign_template_2023.pdf`
is the template. The 2026 Hazard Information Sheet also has a **BioSafety Level** field, which
should read 2.

**Training, with real renewal intervals:**

| Training | Who | How often |
|---|---|---|
| Biosafety & Bloodborne Pathogens (ORS) | Anyone working with biohazards, toxins, rDNA, or with occupational exposure to human blood or OPIM | **Annually** (OSHA) |
| Laboratory Safety Training, in person (HEMS) | Everyone working in a lab | **Annually** |
| Biosafety Cabinet training (CDC) | Anyone using a BSC | Once |
| NIH/IBC Guidelines | Everyone on an IBC protocol | Every 5 years |
| Biological shipping (IATA) | One lab member, if shipping biologicals or dry ice | Every 2 years |
| N-95 / PAPR fit test | Anyone on respiratory-protection projects | **Annually** (OSHA) |
| Lentiviral vector | Anyone on lentiviral projects | Once |
| Hazardous Waste Management | Anyone handling hazardous waste | See waste program |

**Containment and facilities**, from the checklist: BSC certified **within the past year** and kept
clear of the air grilles; sealed rotors or safety cups in centrifuges; posted autoclave procedures;
**biohazard symbol on any fridge or freezer** holding biohazardous material; self-closing door;
handwashing sink; eyewash; no carpet; non-fabric chairs; bench tops impervious to water and
disinfectant; vacuum lines HEPA-filtered or disinfectant-trapped; inward airflow without
recirculation; and a validated decontamination method such as an autoclave.

**Lab coats are worn in the lab, removed before leaving, and must not be taken home to launder.**

### The bloodborne pathogens question

The checklist applies the OSHA Bloodborne Pathogens Standard (29 CFR 1910.1030) to anyone with
occupational exposure to **human blood or "other potentially infectious materials" of human origin,
which it defines to include human cell lines and unfixed tissue**.

This lab's published work uses human islets, human iPSC-derived cardiomyocytes and human cornea. If
material of that kind is handled here, three things follow that are easy to miss:

1. **Hepatitis B vaccination must be offered**, and a declination recorded **in writing** if refused.
2. The **GW Bloodborne Pathogens Exposure Control Plan** must be accessible to personnel.
3. A **medical surveillance programme**, written exposure-incident procedures, and consideration of
   stored serum samples from at-risk personnel.

Worth confirming rather than assuming, since it depends on what is actually handled in SEH 5290 as
opposed to a collaborator's space.

### Animals

Little animal work happens in this space, so many checklist items (infected animals, animal rooms,
respiratory protection around them) will read N/A. IACUC still governs anything that does happen, and
sits with ORS alongside IBC. Answer those questions N/A rather than skipping them, since a blank
reads as unanswered.

### IBC

Recombinant or synthetic nucleic acid work needs **Institutional Biosafety Committee approval**, and
approved IBC paperwork belongs in the Biosafety Manual. Protocols are submitted through **GW iRIS**.
The checklist also asks whether the PI knows which section of the NIH Guidelines the work falls
under, and whether 10 or more litres of culture are present.

## Recurring obligations

This is the part that is easy to let slide, and the 2019 chemical list is what that looks like after
a few years. Ordered by how often it comes round.

| How often | What | Source |
|---|---|---|
| **Weekly** | Flush each eyewash station **30 seconds**; check water is clear, jets work, no leak | Eyewash Station Checklist |
| **Weekly** | Documented lab inspection by authorised personnel | CHP, Appendix 3 |
| **Weekly** | Waste accumulation area inspection, if waste is being accumulated | Waste Area Checklist |
| **First week of every semester** | Update the Hazard Information Sheet posted outside the lab | CHP |
| **Annually, and on every change** | Email the chemical inventory to EHS. Not just annually: **whenever any chemical is added or removed** | CHP |
| **Annually** | Review and update SDS | CHP |
| **Within 60 days** | Waste pickup, counted from the accumulation start date on the container | Hazardous Waste Management |
| **30 days before vacating** | Notify ORS for close-out pre-inspection | Close-Out Guidelines |
| **30 years after last use** | Retain SDS | CHP |

## Standing requirements

**Physical copies in the lab.** The CHP itself, plus any lab-written SOP, plus an SDS for every
chemical stored or used. GW notes an electronic system was planned for 2025; until it exists, paper.

**Particularly hazardous substances.** Acute toxins, select carcinogens and reproductive toxins each
need a designated area, a containment device such as a fume hood, and **written** waste-removal and
decontamination procedures that staff are trained on. In this lab that captures the cyanides,
hydrazine, chloroform, formaldehyde and paraformaldehyde, and trypan blue. See
[`Chemicals/`](Chemicals/README.md).

**Compressed gas.** Labelled with chemical name and primary hazard, secured with a chain or strap so
it cannot be knocked over, cap on when not in use, and **flammables stored away from oxidisers**. The
propane and butane cylinders in the chemical store are worth checking against all four of those.

**Training.** Lab-specific orientation, Laboratory Safety Training, and **Hazardous Waste Management
training for anyone who handles waste**. Records kept for each person's whole time in the lab.

**Dress, from the General Laboratory Safety Rules.** Long trousers and long sleeves, closed-toe shoes
covering the whole foot, long hair tied back, no loose clothing or dangling jewellery. No eating or
drinking, no lip balm or make-up, do not touch your face. Wash hands and remove gloves before
leaving. GW's own wording: *"you will be asked to leave the laboratory if you fail to comply."*

**PPE is not a substitute** for engineering or administrative controls. EHS runs hazard assessments
per task and PPE follows from those.

## What is in reference/

| File | What it is good for |
|---|---|
| `chemical-hygiene-plan-june-2024.pdf` | The governing document. Inventory, SDS, PHS, waste, inspections, appendices incl. the inventory template |
| `2026_multiplePIhazardinfosheet.pdf` | The **current blank** hazard sheet form. NFPA diamond, Special Hazards field, 24-hour contacts, access level |
| `Hazardous Waste Management-12.4.24.pdf` | Waste program and the regulations behind it (RCRA, DC Hazardous Waste Management Act) |
| `Chemical Waste Accumulation Area Sign 2025.pdf` | The sign for a waste area. 60-day limit stated on it |
| `Chemical Waste Accumulation Area Checklist.pdf` | Weekly waste-area inspection form, 16 weeks per sheet |
| `Eyewash Station Checklist_2022 draft V2.pdf` | Weekly eyewash form |
| `GENERAL LABORATORY SAFETY RULES_draft 2022.pdf` | Postable dress and conduct rules |
| `PPE.pdf` | PPE program and selection |
| `ors_laboratory_close-out_guidelines_2023.pdf` | What a PI owes when vacating a space |
| `12-4-19 Written U-Waste Program 2019 FINAL.pdf` | Universal waste: batteries, lamps, mercury devices |
| `GW_Biosafety_Manual_ORS Jun 2024 final ver.pdf` | The biosafety governing document, ORS side |
| `Biosafety Level One_Two_Inspection Checklist_final 2025.docx` | **The BSL-2 self-inspection form, 84 questions. This lab is BSL-2, so it applies** |
| `GW_Biohazard_sign_template_2023.pdf`, `No PPE sign.pdf` | Postable signage templates |
| `posted-list-SEH5290-2019-02-26.jpg` | The **superseded** chemical list found posted for SEH 5290, kept for comparison |

## Open items for this lab

Recorded as observations from the 2026-09-09 chemical review, not as an audit finding. Several
depend on records this repository cannot see.

1. **The posted Hazard Information Sheet is dated 2/26/2019**, is on the retired template, names
   only one of the two PIs, and omits every high-hazard item in the store. The CHP asks for it
   every semester.
2. **Three items need EHS rather than tidying**: picric acid with visible crystallisation, perchloric
   acid from 2015, and cyanides shelved with acids. Details and the reasoning in
   [`Chemicals/`](Chemicals/README.md). **Raised with Dr Zderic by email 2026-09-09.** She is
   checking with Dr Kay before EHS is contacted, which is the right order: the cyanides
   and the Efimov-labelled picric acid read as his group's material, and a shared room
   means a disposal decision is not one PI's to make alone. **Nothing has been moved or
   opened, and nothing should be until that comes back.**
3. **Chemical inventory to EHS** appears not to have been refreshed since 2019.
4. **BSL-2 items unknown from here**, worth walking the 84-question checklist for: Biosafety
   Manual contents, biohazard door sign, BSC certification date, biohazard labels on fridges and
   freezers, training currency for every member, and whether the bloodborne pathogens provisions
   apply to what is actually handled in this room.
5. Also unknown: physical CHP in the lab, SDS binder completeness, weekly inspection records,
   eyewash logs, PHS written procedures, gas cylinder restraint.
