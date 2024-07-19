# Recycle_data
Data for chapters 2 and 5 of PhD thesis: Improvements to methods for the quality estimation and refinement of protein quaternary structure models.
Published July 2024 (University of Reading)
Chapter 2 data is a set of datasets containing recycled AF2 (AF2_Scores_AF2_19_10_22.csv) and non-AF2 models (AF2_Scores_next5_19_10_22.csv).
Chapter 5 data uses the same data as chapter 2 but additionally uses all AF2 5 models. These are split into monomers to assess lDDT scores (named monomer_lDDT_AF_rank_x.csv and monomer_lDDT_nonAF_rank_x.csv for recycled AF2 and non-AF2 models 
respectively) and those to assess lDDT-Ca scores (named similarly: lDDT_Calpha_AF_rankx.csv and lDDT_Calpha_nonAF_rankx.csv). The set to assess pTM score are named: monomer_TM_AF_rank_x.csv and monomer_TM_non-AF_rank_x.csv.
Additionally the CASP15 data for monomers is contained in a single dataset named: CASP15_monomer_scores.csv and (models created by MultiFOLD for monomeric CASP15 targets)
Finally the CASP15 multimeric dataset is named: CASP15_multimer_scores.csv

All analysis should be reproducible from these datasets by fllowing the descriptions in the methodology section of the respective chapters.
