# dynamicFormantDataset

This dataset contains the formant contours of 360 vowels (12 speakers × 10 words × 3 repetitions) that were collected in Glasgow to study the effect of a morphologically-conditioned vowel alternation (stemming from the so-called *Scottish Vowel Length Rule* – see e.g. Ferragne, 2020) on formant trajectories. These vowels occur in minimal pairs like *tide-tied*; the heteromorphemic [d] in the second word causes the preceding vowel to lengthen and to display a different formant pattern from the monomorphemic item.
The file __dataGlasgow.RData__ contains a variable called _dataList_ whose structure is described in this tutorial where I show how to analyse formant trajectories with R: https://www.emmanuelferragne.com/post/formant-dynamics/
The file __preprocessedGlasgowFormantTable.RDS__ stores the smoothed interpolated F1 values in a format that is ggplot-friendly. This file is equivalent to the _meltCenterDF_ variable that can be found at the end of the tutorial I've just mentionned. 
A more detailed description of the data can be found in:
Ferragne, E. (2020). The production and perception of derived phonological contrasts in selected varieties of English. In A. Przewozny, C. Viollain, & S. Navarro, *The Corpus Phonology of English: Multifocal Analyses of Variation* (p. 30-49). Edinburgh University Press.
