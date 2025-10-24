# DERIP

##### Derived Immunogenicty Predictor

Derip aims to use combined data from tried and tested models as well as locally computed peptide specific features to predict the immunogenicity of a given peptide.

Its original purpose is to be a sub-part of a wider projects regarding immune response and engineering in the field of Gene Therapy.



## Usage

The main model is stored as a .xgb file which is the standard file format for XGBOOST models.

As of now the model needs explicitly all the features in the format used in training(ESM-2) however it can be quite easily programmed to compute all features from the fundamental features, which are the Peptide and the MHC-I molecule.



## Issues and Limitation

*Quality* Data regarding immune response is hard to come by which is the reason many models use any assays as signs of immunogenicity include our own because the dataset of this model is the **Deepimmuno** dataset with extra features added on top.

The major contribution as expected comes from the Peptides and the MHC-I molecules themselves hence further enrichment of existing data is not a valid option new data or external help is required to overcome this issue.



## Other Models

**ESM**: https://github.com/facebookresearch/esm

**MHCflurry**: https://github.com/openvax/mhcflurry

**DeepImmuno**: https://github.com/frankligy/DeepImmuno

**DeepTAP**: https://github.com/xuezhang335/DeepTAP

**Pepsickle**: https://github.com/pdxgx/pepsickle

