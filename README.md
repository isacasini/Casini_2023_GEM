# Casini_GEM_2023
Supplemental data sets (Data S1, S3-S7) for the article: Casini, I., McCubbin, T., Esquivel-Elizondo, S., Luque, G.G., Evseeva, D., Fink, C., Beblawy, S., Youngblut, N.D., Aristilde, L., Huson, D., Drager, A., Ley, R., Marcellin, E., Angenent, L.T., Molitor, B. 2023. An integrated systems-biology approach reveals differences in formate metabolism in the genus Methanothermobacter. *iScience*.

Data S1: Contains the supplemental tables (Table S1-S17).
- Table S1: Details on access to genome assembly information in NCBI.
- Table S2: Methylation patterns of the three microbes elucidated through PacBio sequencing
- Table S3: COG categorization of the genomes of the following microbes: ΔH, M. thermautotrophicus ΔH; ZZ, M. thermautotrophicus Z-245; and MM, M. marburgensis Marburg
- Table S4.: Differences between new and old genome sequences in M. thermautotrophicus H and M. marburgensis Marburg
- Table S5: Summary of fermentation production rates
- Table S6: Differential protein expression analysis of proteins that mapped to reactions in the model
- Table S7: ATPM flux ranges for different constraints (ranging from biomass production maximization to ATPM maximization; with the assumption that the biomass compositions are the same for the three microbes).
- Table S8: Tools used for the genome assembly and methylation pattern detection: ΔH, M. thermautotrophicus ΔH; ZZ, M. thermautotrophicus Z-245; and MM, M. marburgensis Marburg
- Table S9: Microbe specific primers. The primers for M. thermautotrophicus Z-245 and M. marburgensis Marburg bind on the respective plasmids
- Table S10: Calibration gas levels for Agilent 490 MicroGC, red values are not used in the calibration curve
- Table S11: Dilution of continuous media (including adjusted sodium formate concentrations) based on base and acid feeds
- Table S12: The comparison of the acetate transporter and acetyl-CoA synthetase/acetate-CoA ligase genes in the old and new genome sequences and their presence in the transcriptomics and proteomics data of Methanothermobacter thermautotrophicus ΔH. The rank of transcript and protein abundance is also listed.
- Table S13: Genes in top 100 most abundant transcripts that are responsible for reactions in the model
- Table S14: Proteins in top 100 most abundant gene products (based on averaged iBAQ values) that are responsible for reactions in the model
- Table S15: Percent of average relative abundance of proteins (of proteome) involved in methanogenesis (based on iBAQ values) normalized to the number of subunits found to how many would be present (each * indicates one subunit was missing)
- Table S16: Ratios of Eha to Ehb based on the averages within each microbe (normalized to the number of subunits detected)
- Table S17: Number of genes related to biomass synthesis either up and down regulated in MM to the other microbes (from the transcriptomics study): ΔH, M. thermautotrophicus ΔH; ZZ, M. thermautotrophicus Z-245; and MM, M. marburgensis Marburg

Data S3: Excel workbook with fermentation data from first experiment, period 2.

- Sheets 1-12: Time series data of OD600, gCDW, H2, CO2, CH4, mmol/h and mmol/gCDW/h for all bioreactors
- Sheets 13-15: OD600, gCDW, dilution rates
- Sheets 16-23: Averaged steady-state time points for H2, CO2, CH4, and biomass
- Sheet 24: Media salinity calculation
- Sheet 25: Dissolved CO2 calculation
- Sheet 26: Carbon balance before gross measurement analysis/adjustment
- Sheet 27: Steady-state data after gross measurement analysis (which is used for modeling)
- Sheet 28: ANOVA analysis of potential influence of O2 intrusion on the gas uptake and production rates for the M. Marburgensis Marburg bioreactor replicate (S1R2) during the first fermentation (period 2)

Data S4: Excel workbook with omics data.

- Sheets 1-3: Transcriptomics individual ΔH, ZZ, MM
- Sheets 4-6: Transcriptomics differential expression MM_ΔH, ZZ_ΔH, ZZ_MM
- Sheets 7-9: Proteomics individual ΔH, ZZ, MM
- Sheets 10-12: Proteomics differential expression MM_ΔH, ZZ_ΔH, ZZ_MM
- Sheet 13: Relative abundances of Wolfe Cycle transcripts
- Sheet 14: Relative abundances of Wolfe Cycle proteins (iBAQ)
- Sheet 15: Relative abundances of Eha/Ehb transcripts/proteins (iBAQ)
- Sheet 16: Pan-genome
- Sheet 17: Comparison of new and old gene loci for Methanthermobacter thermautotrophicus ΔH (ΔH)
- Sheet 18: Comparison of new and old gene loci for Methanthermobacter marburgensis Marburg (MM)

Data S5: Excel workbook with FBA simulations with GEMs.

- Sheets 1-3: FBA results of constraining the GEMs on test conditions for ΔH, ZZ, MM
- Sheets 4-6: FBA results of constraining GEMs on fermentation data (gross measurement adjusted) normal/Gimme Transcriptomics/Gimme Proteomics for ΔH, ZZ, MM

Data S6: Excel workbook with fermentation data from second experiment.

- Sheets 1-12: Time series data of OD600, gCDW, H2, CO2, CH4, Na-formate mmol/h and mmol/gCDW/h for all bioreactors
- Sheets 13-15: OD600, gCDW, dilution rates
- Sheets 16-19: Averaged steady-state time points for H2, CO2, CH4, and Na-formate

Data S7: GitHub repository with relevant scripts
- Script 1: Gross measurement error analysis .ipynb
-	Script 2: Modeling 1 (CobraPy) used for model validation (tests the different conditions) .ipynb
-	Script 3: Modeling 2 (CobraPy) used for model verification (constraints with fermentation data -adjusted with gross measurement error) .ipynb
-	Script 4: Transcriptomics differential expression notebook in R .ipynb
-	Script 5: Pan-proteome maker (w/ iBAQ script) .ipynb
-	Script 6: MATLAB file to run FBAs through GIMME (COBRA Toolbox) .mat
