# R-shiny-app-segmentation-analysis
The R Shiny app for segmentation enables the analytical steps of the analysis
of market segmentation in both the a priori and a posteriori cases. In general
the app is divided into two main parts that illustrate the two statistical techniques
used: cluster analysis (both hierarchical and nonhierarchical) and logistic regression
(both binary, in the case of two segments, and multinomial, in the case of more than
two groups). The first technique allows the segments to be formed by grouping the statistical units
of the user-loaded dataset according to the variables (bases) in the
dataset. This step is only necessary in case the user is interested in
segment a posteriori: in the event that the user has already derived the groups (case
a priori), having established the segmentation criterion according to which to subdivide the units
statistics through the variable-criterion, it will be possible to go directly to the next technique.
Logistic regression deals with the stage of describing the groups, a step
fundamental for both the a priori and a posteriori approaches. In the dataset to be
included for this type of analysis will have to include the groups variable in the first
column; in case it was deemed appropriate to also perform the clustering technique
through the R shiny app, the dataset to be downloaded will already contain the groups in the first column,
therefore, in the description phase, it will be possible to upload the file downloaded at the end of the
previous step, taking care to replace the grouping variables with those chosen to segment.
