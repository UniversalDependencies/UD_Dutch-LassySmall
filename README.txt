
# Summary

This corpus contains sentences from the Wikipedia section of the Lassy Small Treebank.
Universal Dependency annotation was generated automatically from the original annotation in Lassy.

# Introduction

The Lassy Small Treebank (https://www.let.rug.nl/~vannoord/Lassy/) is a manually verified treebank for Dutch, annotated with both phrasal nodes and dependency labels (as in the German Tiger treebanks and as in earlier treebank efforts for Dutch). The annotation was converted automatically to UD.  The (XQuery) conversion script is available for download at https://github.com/gossebouma/lassy2ud. It can be used to convert additional material annotated according to Lassy/CGN guidelines or annotated automatically using the Alpino parser.

As not all material in the Lassy Small Treebank can be made freely available, only the material from the Wikipedia (wiki) section is included in UD_Dutch-LassySmall. The train, development, and test sections consist of 6641, 350, and 350 sentences, respectively, taken from a random shuffle of the original dataset.

# Acknowledgements

Gosse Bouma is responsible for the conversion. Gertjan van Noord helped in sorting out various issues with the original data.

# References

Gosse Bouma and Gertjan van Noord, Increasing Return on annotation investment:
the automatic construction of a Universal Dependency treebank for Dutch (http://aclweb.org/anthology/W17-0403)
in: Proceedings of the Universal Dependencies Workshop, Gothenburg, 22 May 2017

van Noord G. et al. (2013) Large Scale Syntactic Annotation of Written Dutch: Lassy. In: Spyns P., Odijk J. (eds) Essential Speech and Language Technology for Dutch. Theory and Applications of Natural Language Processing. Springer, Berlin, Heidelberg https://doi.org/10.1007/978-3-642-30910-6_9


Changelog

03-11-2017
  * data compliant with UD 2.0 guidelines
  * various bug fixes to ensure compatibility with UD Dutch corpus

Older
  * No changes since UD release 1.3.

=== Machine-readable metadata =================================================
Data available since: UD v1.3
License: CC BY-SA 4.0
Includes text: yes
Genre: wiki
Lemmas: converted from manual
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributing: elsewhere
Contributors: Bouma, Gosse; van Noord, Gertjan
Contact: g.bouma@rug.nl
===============================================================================
