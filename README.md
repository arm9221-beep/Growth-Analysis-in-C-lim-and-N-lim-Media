# Growth Analysis in C-lim and N-lim Media

Website presenting fluconazole (FLC) growth curve assays in carbon-limited (C-lim) and nitrogen-limited (Gln-lim / N-lim) media, run over two experiment dates, followed by a combined dose-response analysis.

Live site: published via GitHub Pages from this repository's `main` branch.

## Contents

- `index.html` — landing page linking to all growth assay reports and the combined analysis, plus a summary of the experimental process.
- `july9/` — July 9 growth curve report (HTML + Rmd source), testing FLC concentrations 2&ndash;32 &mu;g/mL.
- `july14/` — July 14 growth curve report (HTML + Rmd source), testing FLC concentrations 8&ndash;128 &mu;g/mL.
- `combined/` — combined dose-response IC50 analysis (HTML + Rmd source) of the July 9 and July 14 data, comparing N-lim to C-lim media.

Growth assays were run for 72 hours because slow growth was anticipated in the nutrient-limited media. The tested FLC concentration range was raised between the July 9 and July 14 assays because the first assay did not show a clear dropoff in effectiveness as concentration increased.

Dose-response method adapted from the [Babraham Bioinformatics IC50 tutorial](https://www.youtube.com/watch?v=yZRvzYsWqJw).
