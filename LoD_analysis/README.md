# Probit Analysis for limit of detection determination in PCR assays

### PURPOSE

Limit of detection (LoD) in PCR assays is the level of analyte that is expected to be detected 95% of the time. This is determined by repeated measurement (10-20 times) at levels of analyte both above and below the expected LoD. A probit model can be fitted against these data to estimate the specific level analyte that can be detected 95% of the time.

Per CLSI EP17A2E Guidance, default recommendations are applied:

1.  Remove Zero Predictor Values.
2.  Apply "log10" transformation on predictors
3.  Use Probit Model
4.  Report 95% LOD (concentration level)

Adapted from: <http://frisby5.blogspot.com/2016/02/probit-model-for-limit-of-detection.html>

An example is included that will generate:

1.  a table of various detection probabilities and estimated copy number
2.  an annotated ggplot graph
