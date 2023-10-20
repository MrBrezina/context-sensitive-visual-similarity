# Context-sensitive studies of visual similarity

This paper reports on a series of studies conducted to examine the perceived similarity that underlies the visual coherence in typefaces (fonts). Character similarity was studied in a range of common typefaces intended for continuous reading in Cyrillic, Devanagari, and Latin scripts. A new experimental approach was used to obtain data that would allow for enquiry of internal character representations in some detail to better understand character similarity relationships, particularly in the context of typeface design. Participants were presented with character triplets and asked to pick the odd one out, thus judging the remaining two characters as more similar. Providing context for similarity judgements created a cognitively simple, yet challenging task that allowed testing under common viewing conditions without limiting participants’ vision or exposure time. The studies were conducted online to collect a large number of responses from participants with diverse professional and linguistic backgrounds and varying degrees of fluency in the scripts studied. The diverse selection of typefaces, world scripts, and participants challenged the robustness of the method and illustrated its transferability across world scripts. The context-aware method, the linguistic and typographic considerations, and the vast data set are significant contributions to visual similarity discourse and empirical research. A view of visual coherence that is supported by readers’ perceptions can be used to assist designers in their creative process, help with typeface quality assessments, and contribute to further research in typeface design, typography, reading acquisition and readability in a multilingual context.

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
