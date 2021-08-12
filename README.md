# R_SCT_matching
R code to calculate SCT matching from large datasets of recipients and donors

The code finds recipients and donors from a HistoTrac database, and links them. Mismatches at each of the major loci (HLA-A, B, C, DRB1, DQB1, and DPB1) are calculated, in both the HvG and GvH direction. Matching is then determined for each donor out of 8 (A, B, C, DRB1), out of 10 (A, B, C, DRB1, DQB1), and out of 12 (A, B, C, DRB1, DQB1, DPB1). The code counts bidirectional and unidrectional mismatches appropriately.
