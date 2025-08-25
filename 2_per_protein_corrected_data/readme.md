# Folder Description
Contains DMS data corrected on a per-protein basis for CVB3 and EVA71. Site MFEs were standardized using the following formula:

For each site i of a protein p:
corrected MFEi=MFEi-min(MFEp)mean(MFEp)-min(MFEp)

So that the average corrected MFE of each protein is 0 and positive and negative scores indicate sites with MFE above or below the average MFE of that particular protein, respectively.

## Files:

aligned_per_prot_corrected_data.csv: Structurally aligned DMS data across proteins for both viruses

- per_prot_corr_cvb3.csv: Per-protein corrected DMS data for CVB3

- per_prot_corr_eva71.csv: Per-protein corrected DMS data for EVA71