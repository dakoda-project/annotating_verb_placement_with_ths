# MAVPC Annotations

This repository contains the data release for the Linguistic Annotation Workshop 2025 Paper 

"Where it’s at: Annotating Verb Placement Types in Learner Language" .

The annotations were carried out manually by members of the [Dakoda](dakoda.org) project on data drawn from the DISKO and MERLIN corpora .

For detais of the sampling, we refer you to the above paper.

# File contents

The table file presents the annotations as a list, where each row represents a single  annotation layer on either the Learner or the Target Hypothesis layer for a given verb instance.


* anno_round - the round of annotation during which the instance was annotated
* aid - a running id for the instance within its document
* docid  - id of the document (file names as in MERLIN and DISKO)
* layer - indication whether instances is from the L(earner) or T(arget)H(ypothesis) layer
* category - category annotated (finiteness, verb placement, word order etc)
* form  - the token annotated
* 1. Goldstandard - gold standard label for the instance
* 2. Goldstandard - potentially a second plausible gold standard label for the instances
* A1 - the label given by annotator A1
* A2 - the label given by annotator A2
* A3 - the label given by annotator A3  
* A4 - the label given by annotator A4
* A5 - the label given by annotator A5 
* A1_sent - the sentence as segmented by A1
* A2_sent - the sentence as segmented by A2
* A3_sent - the sentence as segmented by A3 
* A4_sent - the sentence as segmented by A4
* A5_sent - the sentence as segmented by A5

NB: for the agreement calculations in the paper, we did  not consider A4 since we lacked labels from them for two rounds and for one category of another round.

# Reference

```bibtex
@inproceedings{mavpc,
  title        = {Where it’s at: Annotating Verb Placement Types in Learner Language},
  author       = {Josef Ruppenhofer and Annette Portmann and Matthias Schwendemann and Christine Renker and Katrin Wisniewski and Torsten Zesch},
  year         = 2025,
  month        = {to appear},
  booktitle    = {Proceedings of the 19th Linguistic Annotation Workshop},
  publisher    = {Association for Computational Linguistics,
  pages        = {000-999},

}
```