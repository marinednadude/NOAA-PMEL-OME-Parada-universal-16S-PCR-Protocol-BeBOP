---
#MIOP terms
methodology_category: Omics analysis
project: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group protocols
purpose: PCR [OBI:0000415]
analyses: PCR [OBI:0000415]
geographic_location: North East Pacific Ocean [GAZ:00013765], Bering Sea [GAZ:00008990], Arctic Ocean [GAZ:00000323]
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
local_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine biome [ENVO:00000447], marine benthic biome [ENVO:01000024]
environmental_medium: sea water [ENVO:00002149]
target:  16S rRNA sequencing assay targeting V4-V5 region [EUPATH:0000813],  Bacterial 16S RNA [NCIT:C105370]
creator: Shannon Brown, Han Weinrich, Zachary Gold
materials_required: vortexer [OBI:0400118], PCR instrument [OBI:0000989]
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 210
personnel_required: 1
language: en
issued: 2025-04-30
audience: scientists
publisher: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies

# FAIRe terms
pcr_0_1: 1
inhibition_check_0_1: not applicable
inhibition_check: not applicable
thermocycler: Applied Biosystems Veriti 96-well thermal cycler
assay_name: ssu16sv4v5_parada
assay_validation: The assay has been validated through mutli-step in-silico, in-vitro, and in-situ validations. In addition to repeat analysis with alternate assays and intra/inter species tests. See BeBOP for citations.
targetTaxonomicAssay: 16S rRNA gene sequencing targeting the V4-V5 region using primers 16S 515F-Y and 16S 926R-Y
targetTaxonomicScope: universal
target_gene: 16S rRNA (SSU prokaryote)
target_subfragment: V4-V5 (515-926)
ampliconSize: 336-486
pcr_primer_forward: GTGYCAGCMGCCGCGGTAA
pcr_primer_reverse: CCGYCAATTYMTTTRAGTTT
pcr_primer_name_forward: 16S 515F-Y
pcr_primer_name_reverse: 16S 926R-Y
pcr_primer_reference_forward: https://doi.org/10.1111/1462-2920.13023
pcr_primer_reference_reverse: https://doi.org/10.1111/1462-2920.13023
pcr_primer_vol_forward: 0.75
pcr_primer_vol_reverse: 0.75
pcr_primer_conc_forward: 5.0
pcr_primer_conc_reverse: 5.0
probeReporter: not applicable
probeQuencher: not applicable
probe_seq: not applicable
probe_ref: not applicable
probe_conc: not applicable
commercial_mm: AmpliTaq Gold Fast PCR Master Mix
custom_mm: PCR reactions were run in 25 uL reaction volumes, with 2 uL of DNA, 10 uL of AmpliTaq Gold, 11.5 uL of water, and 0.75 uL of each primer (5 uM).
block_seq: not applicable
block_ref: not applicable
block_taxa: not applicable
amplificationReactionVolume: 25
pcr_dna_vol: 2.0
pcr_rep: 1.0
nucl_acid_amp: https://doi.org/10.5281/zenodo.11398127
pcr_cond: initial denaturation:98_0.5;normal_cycling;denaturation:95_0.75;annealing:50_0.75;elongation:68_1.5;final elongation:68_5;30
annealingTemp: 50
pcr_cycles: 30
pcr_analysis_software: missing":" not provided
pcr_method_additional: Quality was validated via confirmation of a product on a gel.
---

# NOAA PMEL OME Parada universal 16S PCR Protocol

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for list and definitions.

### Authors

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Shannon Brown | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0000-0001-9808-2638 |2024-02-01|
| Han Weinrich  | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0009-0007-6063-0986 |2024-02-01|
|Sean McAllister	|Ocean Molecular Ecology, NOAA PMEL & UW CICOES	|0000-0001-6654-3495	|2024-02-01|
|Matt Galaska	|Ocean Molecular Ecology, NOAA PMEL|	0000-0002-4257-0170	|2024-02-01|
|Zachary Gold	|Ocean Molecular Ecology, NOAA PMEL	|0000-0003-0490-7630	|2024-02-01|

- All authors known to have contributed to the preparation of this protocol should be listed, including those who filled in the template.
- Visit <https://orcid.org/> to register for an ORCID.

#### Internal Protocols

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE |
| ------------- | ------------ | ------------ | ------------ |
| OME Gel electrophoresis protocol (in progress)  | TBD | 0.0| TBD |

#### External Protocols

| PROTOCOL NAME | LINK | VERSION | RELEASE DATE |
| --------- | --------------------- | ------- | ------------ |
| Environmental DNA (eDNA) 16S metabarcoding Illumina MiSeq NGS PCR Protocol V.2| https://mbari-bog.github.io/MBON-Protocols/eDNA_16S_PCR_V3.html | V2 | 2021-11-01 |

### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2024-02-01 | Initial release |
| 1.1.0 | 2025-04-30 | Addition of FAIR eDNA terms in YAML frontmatter and formatting edits |

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|16S v4 rRNA |16S ribosomal nucleic acid sequencing assay targeting V4 gene region|
|BSC	|Biosafety cabinet|
|CICOES| Cooperative Institute for Climate, Ocean, & Ecosystem Studies
|eDNA	|environmental DNA|
|EtOH| Ethanol|
|IDT| Integrated DNA Technologies
|MBARI| Monterey Bay Aquarium Research Institute|
|MBON	|Marine Biodiversity Observation Network|
|NOAA|National Oceanic and Atmospheric Administration|
|NTC	|No template control
|OME	|Ocean Molecular Ecology
|PCR| Polymerase chain reaction |
|PMEL	|Pacific Marine Environmental Laboratory|
|PPE    | Personal protective equipment |
|UW| University of Washington
|WC-OBON|West Coast Ocean Biomolecular Observing Network|

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Extraction blank  | Extraction negative control. Typically nuclease-free water or empty filter run through the DNA extraction process to control for contamination in the DNA extraction step. |
| Field blank  | Sampling negative control. Typically distilled or reverse osmosis water run through a filter like an seawater eDNA sample to control for contamination in the field sampling step. |
| No template control | PCR negative control. Typically nuclease-free water loaded in place of a sample on a PCR to control for contamination in the PCR step. |
| Positive control  | PCR positive control. Typically a synthetic DNA strand, non-indigenous DNA extract, or intentionally designed mock community loaded in place of a sample on a PCR to control for contamination and index hopping in the PCR step. |

## BACKGROUND

### Summary

This protocol is for amplifying the 16S rRNA v4-v5 region. The primers (forward: 515F-Y, reverse: 926R) were first presented in [Parada et al. 2015](https://doi.org/10.1111/1462-2920.13023) with 515-Y modified from [Quince et al. 2011](https://doi.org/10.1186/1471-2105-12-38). We note these are identical primers to those used by the [NOAA CalCOFI Ocean Genomics Program](https://www.protocols.io/view/amplicon-library-preparation-bmuck6sw?step=5&comment_id=130454) and the [Fuhrman lab](https://www.protocols.io/view/fuhrman-lab-515f-926r-16s-and-18s-rrna-gene-sequen-j8nlkpd1g5r7/v2) albiet with a different chemistry and thermocycling conditions than both. We note that the forward primer is identical to the [Earth Microbiome Project](https://earthmicrobiome.org/protocols-and-standards/16s/), but uses a different reverse primer. The target amplicon size is 336 - 486 base pairs.

This primer set is universal, amplifying organisms from across the tree of life. However, with the limited DNA quantity of invertebrates/vertebrates in the water column, this primer set effectively targets microbes (e.g., Bacteria, Archaea, phytoplankton, single celled organisms), and is not recommended for monitoring of multicellular organisms.

The protocol presented here is intended as the first PCR of a two-step PCR next generation sequencing library preparation using Illumina Nextera Unique Dual Indices. Our written protocol does not include the second PCR step in which unique library-specific barcodes are attached to each round 1 PCR product. 

### Method description and rationale

This protocol was chosen because it has been widely and historically used by the Monterey Bay Aquarium Research Institute (MBARI), a leader in the field of eDNA research and an important partner in the Marine Biodiversity Observation Network (MBON) and West Coast Ocean Biomolecular Observing Network (WC-OBON), to generate marine eDNA time series. Our protocol uses the same primers, polymerase, and thermocycling conditions as MBARI and MBON. We intentionally chose this protocol to promote standardization of ocean biomolecular observations and easily facilitate integration of PMEL OME eDNA data with MBARI and MBON eDNA time series.

This amplification protocol is accessible to most molecular biology labs.

### Spatial coverage and environment(s) of relevance

This protocol has been used to amplify extracted DNA from thousands of filtered sea water samples taken from coastal stations off the western coast of North America in the Northeastern Pacific Ocean, Bering Sea and Arctic Ocean (primarily off California, Oregon, Washington, and Alaska). Samples collected range in depth from surface ocean (epipelagic biome) to just off bottom (benthic biome) at varying distances from shore (coastal to off-shelf). 

### Personnel Required

One person with molecular biology experience.

### Safety

This protocol does not involve any hazardous chemicals, although standard precautions including wearing PPE should be taken to avoid skin and eye exposure to chemical reagents.

### Training requirements

Molecular biology training (including, at a minimum, sterile technique, pipetting small volumes, and programming and running PCR thermocyclers) is required to conduct this protocol.

### Time required to execute the procedure

PCR preparation and running the PCR protocol for a single 96-well plate takes 3.5 hours (210 minutes), 120 mins of which is the thermocycler run time. Additional plates can be run simultaneously without greatly increasing the time required. 

## EQUIPMENT
For a 96-well Plate:

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment**|
|Pipetter: 1-10 μl|Pipetman P10L|Gilson|1|Can be substituted with any accurate pipettor|
|Pipetter: 20 - 200 uL	|Pipetman P200L|Gilson|	1|Can be substituted with any accurate pipettor|
|Pipetter: 100-1000 uL	|Pipetman P1000	|Gilson	|1|Can be substituted with any accurate pipettor|
|BioSafety II cabinet|Biological safety cabinet (INT-1100A2)|Kewaunee|1|Can be substituted with generic - internal UV light required|
|Thermocycler|Veriti 96-well thermal cycler |Applied Biosystems| 1|	Can be substituted with generic|
| Mini-centrifuge | Personal mini centrifuge  | BioExcell | 1 | Can be substituted with generic, but needs to fit 1.5-2.0 mL tubes |
| Vortex | Analog vortex mixer | Fisher Scientific | 1 | Can be substituted with generic|
| Plate spinner | [Salad spinner]( https://doi.org/10.3390/mps3020041) | Cuisinart | 1| Can be substituted with generic or plate centrifuge |
| Foil roller | Rubber roller | Generic | 1 ||
| PCR cooler rack | PCR cooler 0.2-0.5 mL | Eppendorf | 1 | Can be substituted with generic|
| 1.5 mL tube cooler rack | Benchtop cooler | Thermo Scientific  | 1 | Can be subsituted with generic |
| 2 mL tube rack | Microcentrifuge tube rack | VWR | 1 | Can be substituted with generic |
| 0.2 mL PCR plate rack | PCR tube rack for 0.2 mL micro-tubes | Fisher Scientific | 1 | Can be substituted with generic |
|Wash bottle|Safety Wash Bottle for Ethanol 500mL|VWR|1|Can be substituted with generic - must be sterilized before use|
|Wash bottle|Safety Wash Bottle for Hypochlorite Bleach 500mL|VWR|1|Can be substituted with generic - must be sterilized before use|
|Freezer|Freezer capable of reaching and maintaining -20°C|Generic|1| Used to store DNA and PCR reagents **NOTE: A separate freezer should be used to store PCR products if possible.**|
|Fridge| Refrigerator capable of reaching and maintaining 4°C|Generic|1|Used to store some PCR reagents **NOTE: A separate fridge should be used to hold PCR products if possible.**|
|Trash bag holder|Bel-Art scienceware bench-top biohazard holders|Fisher Scientific|1|Can be substituted with generic|
|Cryoboxes|TruCool hinged lid cryoboxes|VWR|2| Can be substituted with generic - must be sterilized before use |
| **Consumable equipment** |
| 1000 μL pipette tips | TipOne RPT filter tips 1000 μL XL graduated | USA Scientific | 4 | Can be subsituted with generic - must be sterile and filtered |
| 200 μL pipette tips  | TipOne RPT filter tips 200 μL graduated| USA Scientific |4 | Can be subsituted with generic - must be sterile and filtered |
| 10 μL pipette tips  | TipOne RPT filter tips 10 μL graduated | USA Scientific | 96 | Can be subsituted with generic - must be sterile and filtered |
| PCR plates | Twin.tec LoBind PCR plates, semi-skirted (96-wells)| Eppendorf | 1 | Can be subsituted with generic - must be DNA low retention |
| PCR aluminum foil | Adhesive sterile PCR foil seals | VWR| 2 | Can be substituted with generic - must be sterile |
| 2 mL tubes | Snap cap DNA LoBind 2.0 mL tubes, PCR-clean| Eppendorf |5 | Can be substituted with generic - must be sterile |
| 1.5 mL tubes | Snap cap DNA LoBind 1.5 mL tubes, PCR-clean| Eppendorf |2 | Can be substituted with generic - must be sterile |
| Kimwipes | Delicate task wipes | Kimtech | 5 | |
| Nitrile gloves | Powder Free Nitrile Gloves | Fisher Scientific | 4 | Can be subsituted with generic nitrile gloves. Does not come sterile, must be sterilized before use (10% bleach followed by 70% EtOH) |
|Trash bags for BSC|Teivio 1.2 Gallon 360 Counts Strong Trash Bags|Teivio|1|Can be substituted with generic|
| Lab notebook | Durable, hardcover lab notebook | Generic | 1 | Dedicated to the lab space|
| Writing utensils | Sharpies and pens | Generic | 2 | Dedicated to the lab extraction space. Not made of wood - must be able to be wiped down with bleach/EtOH  |
|**Optional Equipment**|||			
|Repeater Pipetter: 10-300  μL|E1-ClipTip electronic single channel pipette, 10-300 μL |ThermoFisher|	1|Can be substituted with generic - not required but reduces protocol time|
| 300 μl repeater pipette tips | ClipTip 300 filtered sterile tips| Thermo Scientific| 2| Can be substituted with generic. Must fit repeater pipette. Must be sterile and filtered. |
|8-channel multichannel pipetter: 1-10 μL| Pipetman Multichannel P8X10|	Gilson|	1|Can be substituted with generic. Not required but reduces protocol time.|
| UV crosslinker | UV crosslinker AH (115V), 234100 | Boekel Scientific  | 1 | Can be substituted with generic - recommended not required |
| **Chemicals** |
| PCR master mix 2x|AmpliTaq Gold Fast PCR master mix | Applied Biosystems | 1040 μl per plate | Store at 4°C |
| Forward primer | Custom oligo | IDT |78 μl per plate | Store at -20°C|
| Reverse primer| Custom oligo | IDT | 78 μl per plate| Store at -20°C |
| Nuclease free water | UltraPure DNase/RNase-free distilled water | ThermoFisher | 1196 μl per plate| |
| Positive control| gBlocks HiFi Gene Fragments | IDT | 2 μl per plate |Store at -20°C |
| 70% EtOH | Molecular grade ethanol| Generic | 40 mL | |
| 10% bleach| Hypochlorite bleach |Clorox| 40 mL | Remake every ~5 days as bleach decomposes quickly at 10% concentration |

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumable may need to be sterilized, some commercial solution may need to be diluted or shielded from light during the operating procedure.

## STANDARD OPERATING PROCEDURE

### Protocol

#### Preparation

1. Sterilize workspaces and durable equipment, including pipettes within the BSC with 10% bleach. Then wipe down all surfaces and equipment with 70% EtOH.
4. If you have a UV crosslinker available, UV pipettes and tube racks regularly for 2 minutes. 
5. Run the UV light in the BSC for 30 minutes before starting work.
6. Label all PCR plates both on the side of the plate and on the top of the foil (in the plate margins). Recommended labeling scheme includes plate name, primer, date of PCR, and personnel initials.

#### PCR

**Primer Sequences without Adapters**: PCR primer sequences (target sequence bolded)  

| PCR Primer Name | Direction | Sequence (5’ -> 3’)|
| ----- | ----- | ----- |
| 16S 515F-Y| Forward |**GTGYCAGCMGCCGCGGTAA** |
| 16S 926R-Y | Reverse | **CCGYCAATTYMTTTRAGTTT** |

**Primer Sequences Used**: PCR primer sequences with Illumina Adapters
(Adapter sequence + **target sequence bolded**)
| PCR Primer Name | Direction | Sequence (5’ -> 3’)|
| ----- | ----- | ----- |
|16S Microbial - Nex - F| Forward | TCGTCGGCAGCGTCAGATGTGTATAAGAGACAG**GTGYCAGCMGCCGCGGTAA** |
|16S Microbial - Nex - R | Reverse |GTCTCGTGGGCTCGGAGATGTGTATAAGAGACAG**CCGYCAATTYMTTTRAGTTT**  |

**Reaction Mixture**: **Reaction Mixture**: PCR reagents, volumes, initial, and final concentrations

| Reagent |Volume (μL) per plate| Volume (μL) per reaction | Intial concentration| Final concentration|
| ----- | ----- | ----- |----- |-----|
|AmpliTaq Gold Fast PCR Master Mix  |1040|  10|100% | 40%|
| Forward Primer| 78| 0.75|5 μM | 0.15 μM |
| Reverse Primer |78| 0.75|5 μM |0.15 μM |
| Nuclease-Free Water |1196| 11.5| N/A|N/A |
| Template DNA|N/A| 2 | 100%|8% |
| **Total**|**2392**| **25** | **N/A** |**N/A**|

This table breaks down the mixture per plate and per reaction. When running full plates (96-wells), each reagent volume was multipled by 104 (96+8 extra sample volumes to account for pipetting error) when preparing the final master mix.

**PCR Cycling Program**: 

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
|Initial denaturation|	95°C	|10min|	1X
|**Normal Cycling**||||
|Denaturation|	95°C|	45s|	30X|
|Annealing|	50°C|	45s	|30X|
|Extension 	|68°C	|90s	|30X|
|Final extension	|68°C	| 5min	|1X|
|Hold	|4°C	|∞	|1X|

**Step-by-Step Instructions:**

*Note: When possible, PCR set-up should be carried out in a separate pre-PCR space that is distinct from where the post-PCR space where thermocyclers are located and all post-PCR processing is performed. No equipment, consumables, or reagents should be shared between pre- and post-PCR spaces with a unidirectional flow of sample processing.*

1. Set out primers and positive control to thaw.
2. Vortex and spin down thawed positive control, primers, and nuclease free water. Then tap/flick AmpliTaq rather than vortexing before spinning down. Thawed reagents should be stored in a cooling block or fridge when not in use.
3. Pool reagents to make final master mix, as denoted in above in reagent mixture table.
4. Set out template DNA to thaw if frozen.
5. Aliquot 23 μL of final master mix into each well of the PCR plate. The plate should sit in a cold block to ensure the reagents remain at a low temperature.
6. Add 2 μL DNA template to each well (See [Protocol Sample Sheet](https://docs.google.com/spreadsheets/d/1GiYxSuAibLr0o4OulZFxdJbhuhW9fhLBwIDK_UkXR90/edit?usp=sharing)), but reserve two wells for the positive control and a no template control (NTC). 
7. To one well each, add 2 μL of the positive control and 2 μL of nuclease-free water for the NTC.
8. Seal the PCR plate with foil.
9. Spin down the plate, and then transport in cooler blocks before placing in thermocycler.
10.  Run thermocycler protocol.

### Quality control

1. Plates should be removed from the thermocycler  after the run completes and stored at 4°C until run on a gel. Storing the PCR product at -20˚C is ideal for 1-6 month term storage, while -80˚C is ideal for long-term storage.
2. Run gel visualization to confirm successful PCR. [NOAA-PMEL-OME-GelVisualization-Protocol pending]

**Positive Control**

A positive control is used in every PCR run to verify success of the PCR reaction. In place of template DNA, 2 μL of positive control diluted to 10^3 copies/µL is used. One well per plate is alotted for the positive control. The positive control used for 16S is Dromedary camel (*Camelus dromedarius*). The reference mitogenome used to develop the positive control sequence can be found on GenBank: [Accession OP378546.1](https://www.ncbi.nlm.nih.gov/nuccore/OP378546.1). We based the positive control off of the 12S gene. The resulting accession had 2 mismatches in the forward primer as well as 1 mistmatch in the reverse primer and thus we modified the positive control to use the exact primer sequence to avoid mismatches.

|Positive Control Sequence|
|--------------------------|
|AGGGCCGGTAAATTTCGTGCCAGCCGCCGCGGTAATACGATTAGCCCGAATTAATGGAAATCCGGCGTAAAGCGTGTTAATGAGTAACTAATAAATAGAGTTAAGTCTTGGCCAGGATGTAAAAATCTATGACCAACGTAAAAATAAACTACGAAAGTGACCCTAATACGATCTGCTACACGACAGCTAAGACCCAAACTGGGATTAGATACCCCACTATGCTCAGCCTTAAACCTAAGTGATTATAACAACAAAATCACTCGCCAGAGTACTACTAGCAACAGCTTAAAACTCAAAGGAATTGGCGGTGCTTCATACCCCCTAGAGG|

**Negative Control**

Nuclease-free water is used as a no template control (NTC) when setting up each PCR plate. One well per plate is alloted to a NTC. NTCs should be run in addition to both field blanks and extraction blanks.

### Basic troubleshooting guide

**Issue 1**: Streaking is observed for sample wells in gel but positive control band appears normal. 

**Solution**: Dilute the sample DNA to a 1:10 dilution with nuclease-free water. If smearing is still observed using a 1:10 dilution, dilute the DNA samples further to a 1:100 dilution. If the samples do not amplify under these conditions the sample likely is inhibited or has too little target DNA and thus is unlikely to yield valuable results. Alternative solutions include cleaning DNA extractions with a commercial clean up kit.

**Issue 2**: No bands were observed in the PCR, including the positive control.

**Solution**: The PCR likely failed. Check reagents to confirm they were not mishandled or expired and rerun the PCR. If positive control fails again, reagents or positive control are likely compromised. 

**Issue 3**: Band observed in no template control.

**Solution**: The PCR was likely contaminated. Sterilize lab space thoroughly and rerun with new aliquots of reagents.

## REFERENCES

1. Parada, A. E., Needham, D. M., & Fuhrman, J. A. (2016). Every base matters: assessing small subunit rRNA primers for marine microbiomes with mock communities, time series and global field samples. Environmental microbiology, 18(5), 1403-1414. https://doi.org/10.1111/1462-2920.13023
2. Quince, C., Lanzen, A., Davenport, R. J., & Turnbaugh, P. J. (2011). Removing noise from pyrosequenced amplicons. BMC bioinformatics, 12(1), 1-18. https://doi.org/10.1186/1471-2105-12-38

## APPENDIX A: DATASHEETS
[Protocol Sample Sheet](https://docs.google.com/spreadsheets/d/1s7szAHg76gwpfFVI4zRDsZpTAtSnIlmH/edit?gid=627408593#gid=627408593)
