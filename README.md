# Guidelines for submission of Proteomics data

## MIAPE (Minimum Information about a Proteomics Experiment)

> MIAPE guidelines describe the minimum information that should be included when reporting a proteomics experiment.
> The information must describe the experiment completely and allow potential recreation of the work.
> MIAPE guidelines do not:
> 1. make judgement on data quality, or
> 2. to fix data format for its representation, or
> 3. to establish how experiments are conducted.

MIAPE modules for mass spectrometry (MIAPE - MS)
1. process through which a sample is analyzed in a mass spectrometer to generate the raw files
2. process that generates the processed spectra or peak lists
3. the employed equipment:
      1. configuration
      2. MS acquisition parameters

MIAPE modules for mass spectrometry informatics (MIAPE - MSI)
1. process by which mass spectra are analyzed to identify proteins and peptides that exist in the sample
      1. All database search processes (software and parameters)
      2. any performed de-novo analysis
      3. any statistical analysis or post-processing of the identification data.

MIAPE modules for mass spectrometry quantification (MIAPE - Quant)
1. performed data process
     1. quantification by mass spectrometry
        1. labelling-based techniques
        2. chemical (iTRAQ, TMT, ICPL)
        3. metabolic 
     2. label-free techniques
        1. spectral counting
        2. chromatogram alignment
     2. targeted quantification techniques
        1. Multiple / Selected Reaction Monitoring (MRM / SRM)
