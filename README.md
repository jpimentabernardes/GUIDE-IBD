### Code to create the molecular report for prospective multicenter trial (GUIDE IBD). 

# Dynamic Biomarker Guidance of Anti-TNF Therapy in IBD: A prospective multicenter trial (GUIDE IBD)
Reference for blood and biopsy samples as well as inflammtion references.
Pipeline ran per patient included the the molecular board arm per timepoint. The reports were comulative per patients.

### Manuscript under preparation.

Additional information:

MOLECULAR REPORT GENERATION
Principal component analysis (PCA) was performed separately on blood and biopsy reference groups using normalized expression values of the respective biomarker panel. PCA was employed to identify molecular patterns corresponding to baseline, remission, and non-remission states. Confidence regions for reference groups were estimated using multivariate t-distributions at 0.90, 0.80, and 0.70 confidence levels.
For each query sample, normalized qPCR expression data were projected into the pre-defined PCA space of the corresponding reference cohort. The molecular report was cumulative: for each patient, every new sample collected added a data point to the PCA plot, allowing for tracking molecular trajectories over time in relation to baseline, remission, and non-remission states.

INFLAMMATION SCORE
In addition to the molecular score, an inflammation score was created to contextualize molecular profiles with established clinical markers of systemic and intestinal inflammation. This score was based on routinely collected clinical parameters, including C-reactive protein (CRP, mg/L), leukocyte counts (×10³/µL) in blood, and fecal calprotectin (mg/kg stool), when available. Reference ranges for each parameter were set using the respective reference cohort. Individual values were linearly scaled to a 0-100 range based on the observed minimum and maximum values within the reference dataset. The scaled parameters were then averaged for each sample to produce a combined inflammation score. 
Inflammation scores of reference samples were displayed as a histogram representing the distribution of inflammatory burden across the cohort, with lower values indicating minimal inflammation and higher values indicating increased inflammatory activity. Query samples were overlaid onto this reference distribution, allowing for longitudinal evaluation of inflammatory patterns in individual patients across treatment time points.

