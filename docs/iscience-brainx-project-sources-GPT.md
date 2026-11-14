# iScience and Brain-X project pages: source checks

Author: GPT (Codex) · Date: 2026-11-14

## iScience

- Published article: https://doi.org/10.1016/j.isci.2026.116671
- Open-access full text and figure captions: https://pmc.ncbi.nlm.nih.gov/articles/PMC13355829/
- Original figures 1, 2, 3 and 5 were obtained from the article's linked NCBI image assets. They are encoded as lossless WebP with no cropping or content changes. Display width is limited to the source resolution (approximately 740 pixels).
- Main claims checked against Results: 171 HCP participants; 7T diffusion MRI; 643 and 1,403 clusters after hierarchical merging; pre-merge counts 1,719 and 4,189; strict and relaxed ICA annotation rules.
- HCP 3T resting-state fMRI is distinguished from 7T diffusion MRI.
- Functional annotations and TW-dFC uncertainty are described as descriptive. No anatomical ground-truth or causal functional claim is added.
- The SWM dataset DOI is `10.57760/sciencedb.28793`, distinct from the underlying whole-brain resource `10.57760/sciencedb.28989`.
- Authors and order match the published article; Hiuying Yip is not marked as co-first author.
- CC BY 4.0 attribution appears in the footer.

## Brain-X

- Published article: https://doi.org/10.1002/brx2.70037
- Source: the author's existing published PDF, 18 pages, cross-checked with the Wiley full text.
- Figures extracted using `pdfimages`: Figure 1 (page 4), Figure 2 (page 9), Figure 4 (page 10), Figure 6 (page 11). Assets are lossless WebP without cropping or redrawing.
- Regional associations are scoped to the paper's recorded female/male groups. Identity ratings are described as separate continuous self-report items.
- The SEM is described as an exploratory statistical model. Its arrows are not presented as evidence of causal direction.
- The total indirect association with fusiform thickness is retained as nonsignificant (`p = 0.106`, Results §3.2.2), alongside the individual terms, to avoid overstating the model.
- The source dataset is AOMIC ID1000, OpenNeuro accession `ds003097`, as identified by the paper's ethics and data statements. No unverified analysis-code repository is linked.
- Sample-size discrepancy in the published source: Abstract/Methods report 544; Results §3.1 reports 554 (278 + 276); Table 1 labels groups 278 and 286. The project page does not choose one of these conflicting final sample counts. Its four overview labels describe source collection, MRI field strength, cortical regions and identity ratings instead.
- The PDF's embedded Creative Commons link confirms CC BY 4.0; footer attribution uses the paper's 2025 copyright year.

## Delivery scope

Both pages use four published figures, explanatory summaries, source links and downloadable BibTeX. They add no new analyses or interactive scientific demonstrations. The original NeuroImage page keeps its existing content and default attribution.
