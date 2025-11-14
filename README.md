# Contextual visual similarity: introducing the study method and exploring the effects of typeface design and expertise in Cyrillic, Devanagari, and Latin scripts

Although perceptual similarity is highly contextual, visual similarity of characters (letters) is typically investigated using stimuli that do not control for contextual effects, e.g., comparison of pairs, identification of single characters. Moreover, most character similarity studies focus on a single typeface (font) or study under conditions that are detrimental to the quality of the designs (e.g., low resolution or low contrast), which makes it challenging to generalize their findings. To obtain data that permit a more detailed and realistic enquiry of character similarity relationships, the study reported in this paper used a contextual similarity task. Participants were presented with character triplets and asked to pick the odd one out, thus judging the remaining characters as more similar. To demonstrate the method’s robustness and transferability across scripts, this cognitively simple yet challenging task was used with a diverse selection of typefaces, world scripts, and participants (n = 1721). The results showed that the contextual similarity task is sensitive to the effects of typeface design and elicits similarity judgements that are hard to predict using pairwise data. Comparisons across groups of participants showed effects of design expertise, nativity, and fluency in relevant scripts.

## What is included

### The study website

A simple website built using HTML/CSS and javascript. After completion by a participant, it submits collected responses to external services such as [GetForm](https://getform.io).

See `website/`.

The script used to generate the SVG samples from the fonts is also included (`data/generate-samples-for-study.ipynb`).

### The data collected

See `data/` for CSVs and graphics. Included is the preprocessed data as well as the aggregated data, such as:

- responses to individual triplet trials
- similarity matrices for typefaces (8x8)
- similarity matrices for scripts (sparse)
- tables with distinctiveness measures
- typeface comparisons

### The statistical procedures

As IPython notebooks in the `data/` folder.

- preprocessing the raw data from the studies
- statistical analysis of the data
- comparisons of the results between typefaces

## Licence

All content of this repository is available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
