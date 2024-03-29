##  Abuse is Contextual, What about NLP? The Role of Context in Abusive Language Annotation and Detection

This repository contains a subset of the English dataset originally developed by Founta et al. (2018) for abusive language detection, which we have enriched with context (i.e. tweets preceding an annotated message), when available. The tweets (with and without context) have then been re-annotated as abusive or not by the same pool of Amazon Mechanical Turk crowd-workers following exactly the same annotation guidelines. 
Files are in tsv format.

The dataset is released under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.

In `_context` file, the annotator could read the context while annotating. In `_nocontext`, only the tweet text is shown to the annotator.

Columns:
* ID of the annotated tweet
* Annotation (1 = hate, 0 = not hate)
* Preceeding context tweet IDs

## Publications
Stefano Menini, Alessio Palmero Aprosio and Sara Tonelli. Abuse is Contextual, What about NLP? The Role of Context in Abusive Language Annotation and Detection, arxiv, 2021 https://arxiv.org/abs/2103.14916
