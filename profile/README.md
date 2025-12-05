## Neurocomputational Approaches to Emotion Representation (EmoRep)
Codebase for: "Decoding of arousal and valence from fMRI data obtained during emotion inductions"
Supporting NIMH Grant : R01-MH124112-01

<!--

TODO:
- Introduction
- Description of project
- Links to papers
- Description of workflow-repository mapping

-->

### Basic workflow:

1. Collect simultaneous fMRI and physio data during task presentation : (See Experiments tab for [NDAR Collection](https://nda.nih.gov/edit_collection.html?id=3639))
1. Build BIDS rawdata data structures from acquired sourcedata and NKI archive: [build_rawdata](https://github.com/labarlab-emorep-AVClassify/build_rawdata)
1. Check data quality: [func_mriqc](https://github.com/labarlab-emorep-AVClassify/func_mriqc)
1. Pre-process MRI data: [func_preprocess](https://github.com/labarlab-emorep-AVClassify/func_preprocess)
1. Model functional MRI data: [func_model](https://github.com/labarlab-emorep-AVClassify/func_model)
1. Decode arousal and valence from fMRI data: [av_regression](https://github.com/labarlab-emorep-AVClassify/av_regression)
