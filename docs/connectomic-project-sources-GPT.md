# NeuroImage project page: source and content checks

Author: GPT (Codex) · Date: 2026-11-14

## Source

Published version: Yip et al., NeuroImage 326 (2026), 121704.
DOI: https://doi.org/10.1016/j.neuroimage.2026.121704
Publisher PDF filename: `1-s2.0-S1053811926000224-main.pdf` (12 pages).
The author's existing local copy was used. No new analysis was performed.

## Figures

Figures were extracted directly using `pdfimages`, then encoded as lossless WebP without cropping or redrawing.

| Website asset | Original | PDF page |
| --- | --- | --- |
| `images/connectomic-cluster/figure-1-pipeline.webp` | Figure 1: construction pipeline | 3 |
| `images/connectomic-cluster/figure-3-atlas.webp` | Figure 3: region-pair cluster matrix | 6 |
| `images/connectomic-cluster/figure-5-subclusters.webp` | Figure 5: geometry, AF/CST subdivisions, individual correspondence | 7 |
| `images/connectomic-cluster/figure-6-consistency.webp` | Figure 6: overlap distribution | 8 |

The PDF identifies the article as CC BY 4.0. Author, journal, DOI and license attribution appear in the project footer.

## Claims used

- 171 HCP participants; 7T acquisition: Methods §2.1.
- 33,256 / 65,184 clusters in the 7-/17-network schemes: Results §3.1.
- AF and CST subdivisions: Figure 5(b), randomly selected examples.
- Individual correspondence: Figure 5(c); overlap distribution: Figure 6.
- Dataset DOI and subject-level cluster availability: Data and code availability, page 10.
- Co-first authorship: title-page footnote.

## Numerical presentation

The abstract reports median Davies–Bouldin scores below 0.35, while the plotted Figure 4(b) values are around 1.2. Figure 6 also includes individual points below 97%, despite the abstract/caption's blanket description of values exceeding 97%. The project page does not repeat either blanket numerical claim. It presents Figure 6 unchanged and describes its distribution as concentrated around 98%, explicitly as a within-cohort comparison. Figure 4 is not used.

## Scope

This release is a static project page with the published figures, explanatory text and source links. It contains no 3D viewer, new experimental results, or claims of validation outside the construction cohort.
