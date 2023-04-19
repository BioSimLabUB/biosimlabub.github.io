---
layout: page
title: RNA structure and folding
description: study RNA folding using computer simulations
img: assets/img/projects/RNA.png
publications: project^=*RNA folding
importance: 2
category: current
---

<div class="row">
  <div class="col-sm-6 mt-3 mt-md-0">
RNA–a highly charged biomolecule–can fold upon itself to form diverse secondary and tertiary structures to perform a vast array of cellular functions. Folding of RNA requires <i>counterions, especially Mg<sup>2+</sup></i>, to reach a competently active state. Simulations of RNA folding in the presence of ions have been, and still are, demanding due to the long timescale and a large number of particles in the system. Using liquid state theory, we devised a method to <b>treat monovalent ions implicitly, while retaining explicit divalent ions</b> in the RNA folding simulations. This method drastically speeds up the simulations while maintaining their accuracy, allowing us to perform simulations to study the folding of larger and more biologically relevant RNAs. Additionally, the accurate treatment of ion-RNA interactions reveals the importance of <b>Mg<sup>2+</sup> in bridging specific RNA tertiary structures</b>. Such molecularly detailed knowledge of how ions facilitate RNA folding deepens our understanding of the process, which could potentially be helpful in future RNA design and therapeutics. Other groups have used our method to investigate the folding of other RNAs, such as riboswitches.
  </div>
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include figure.html path="assets/img/projects/rRNA_fingerprint.png" class="img-fluid round z-depth-1" %}
  </div>
</div>
