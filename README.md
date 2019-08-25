# Project Report: Google Summer of Code 2019 @InterMine

## 💥 Project Description:

> The current InterMine interface is powered by JSPs (example: http://www.flymine.org) and will be discontinued in the next few years. InterMine is already building a new interface named BlueGenes which is a web interface to query & view data from 30+ mines worldwide from same familiar interface.

<p style="font-size: 18px; text-align: center; color: black">
<b>The project aimed to develop standalone data visualization tools for BlueGenes which could possibly be useful to biologists using the interface.</b>
</p>

## 😁 What I developed?

<p class="viz-heading">⛳️ Visualization 1: <b>Tissue Expression Visualizer</b></p>

- _Tissue Expression Visualizer_ can help users (biologists) to visualize tissue expression values and tissue expression by stage values with help of expression graphs.

- They easily can let you know which tissues are up-regulated, down-regulated or normal.

- It provides a clear interface to sort and filter data. Also, expression by stage graph clearly depicts higher expression values on later stages and lower ones earlier based on colour shades.

Code Repository: https://github.com/intermine/bluegenes-tissue-expression-visualizer

NPM Module: https://www.npmjs.com/package/@intermine/bluegenes-tissue-expression-visualizer

---

<p class="viz-heading">⛳️ Visualization 2: <b>3D Protein Visualizer</b></p>

- _3D Protein Visualizer_ helps visualize protein structures in different types of viewer in 3D. Users can select the PDB (Protein Data Bank) id they want to visualize and the visualizer fetches them from the RCSB data source.

Code Repository: https://github.com/intermine/bluegenes-protein-visualizer

NPM Module: https://www.npmjs.com/package/@intermine/bluegenes-protein-visualizer

---

<p class="viz-heading">⛳️ Visualization 3: <b>Multiple Sequence Alignment Viewer</b></p>

- _Multiple Sequence Alignment Viewer_ helps visualize relation and linkages between the proteins associated with a particular gene. For example, check the value of first column the M, M and M being the same colour makes it more eye catching.

Code Repository: https://github.com/intermine/bluegenes-msa-viewer

NPM Module: https://www.npmjs.com/package/@intermine/bluegenes-msa-viewer

---

<p class="viz-heading">⛳️ Visualization 4: <b>Expression Value Box+Swarm Visualizer</b></p>

- _Expression Box+Swarm Visualizer_ helps visualize expression data using combination of box and swarm plots. It shows disease and organism expression data on separate box plots side by side giving a five pointer summary of dataset and clearly showing which organism part has higher expression value and which area needs more attention. On hovering more information is shown.


Code Repositories:

- Visualizer Frontend: https://github.com/intermine/bluegenes-expression-box-swarm-visualizer

- Alignment Service: https://github.com/intermine/sequence-alignment-service

NPM Module: https://www.npmjs.com/package/@intermine/bluegenes-expression-box-swarm-visualizer

---

<p class="viz-heading">⛳️ Visualization 5: <b>GO Term Visualizer</b></p>

> ### GO Term vs P-value

- It helps visualize GO-term  (Gene Ontology Term) plotted against P values.
- The enrichment analysis on a list is to see if a particular GO term is over represented in that list like “cancer”.

> ### GO Term vs Gene Count

- It can be used to visualize GO Terms vs Gene Count. Again, each bar in the bar-chart is labelled by the annotation corresponding to the particular GO Term.


Code Repository: https://github.com/intermine/bluegenes-GO-term-visualizer

NPM Module: https://www.npmjs.com/package/@intermine/bluegenes-go-term-visualizer

---

<p class="viz-heading">⛳️ Visualization 6: <b>Protein Atlas Tissue Expression</b></p>

- _Protein Atlas Tissue Expression_ helps visualize overall and singular antibody staining values in different organs and cells respectively.
- Uses heatmap to properly show different antibody staining levels.

Code Repository: https://github.com/intermine/bluegenes-protein-atlas-tissue-expression-visualizer

NPM Module: https://www.npmjs.com/package/@intermine/bluegenes-protein-atlas-tissue-expression-visualizer

---

<p class="viz-heading">⛳️ Visualization 7 & 8: <b>Tissue and Disease ArrayExpress</b></p>

- Two separate visualisations for tissue and disease expression, using ArrayExpress data from HumanMine.

Code Repositories:
- https://github.com/intermine/bluegenes-tissue-expression-arrayexpress-visualizer
- https://github.com/intermine/bluegenes-disease-expression-arrayexpress-visualizer

NPM Modules:
- https://www.npmjs.com/package/@intermine/bluegenes-tissue-expression-arrayexpress-visualizer
- https://www.npmjs.com/package/@intermine/bluegenes-disease-expression-arrayexpress-visualizer

---
