# Summary

The UD_Italian-VIT corpus, annotated according to the UD annotation scheme, was obtained by conversion from VIT (Venice Italian Treebank), developed at the Laboratory of Computational Linguistics of the Università Ca' Foscari in Venice (Delmonte et al. 2007; Delmonte 2009).

# Introduction

VIT originated as a constituency based treebank following the theoretical framework described in (Delmonte et al. 2007), and was later on converted into a dependency representation in ConLL-X format (Delmonte 2009).

VIT includes linguistic materials of diverse nature, extracted from five different text genres: news, burocratic, political, scientific and literary genres (Delmonte et al. 2007).

Similarly to what we did for other Italian treebanks, the UD version of the VIT treebank was obtained by first converting to an unriched version of the MIDT (Merged Italian Dependency Treebank) scheme, and then by means of a further conversion step from MIDT+ to UD v2. conversion was followed by a series of semi-automatic harmonization steps, in order to compensate for several differences in the use of the target annotation scheme with respect to the other Italian treebanks.

The splitting into training, devel and test was done maintaining as much as possible the original sequence and respecting the proportions indicated in the guidelines (80%, 10%, 10%).

# Acknowledgments

We are indebted to Rodolfo Del Monte and his collaborators, Antonella Bristot and Sara Tonelli, for the initial work on the VIT treebank; we also acknowledge the contribution of Linda Alfieri and Elzara Khaialieva who implmented the conversion process from VIT to MIDT+, setting up the automatic conversion rules and checking the treebank manually.

## References

* Tamburini F. (2017). Semgrex-Plus: a Tool for Automatic 
 Dependency-Graph Rewriting In Proc. of the Fourth International 
 Conference on Dependency Linguistics - Depling 2017, Pisa, 18-20 
 September 2017, 248-254.
 
 * Alfieri L., Tamburini F. (2016). (Almost) Automatic Conversion of the 
 Venice Italian Treebank into the Merged Italian Dependency Treebank 
 Format. In Proc. of the Third Italian Conference on Computational 
 Linguistics - CLiC-IT 2016, Napoli, 5-6 December 2016, 19-23.
 
 * Rodolfo Delmonte (2009). Treebanking in VIT: from Phrase Structure to 
 Dependency Representation. In Sergei Nirenburg (ed.) Language 
 Engineering for Lesser-Studied Languages, pages 51–81. IOS Press, 
 Amsterdam, The Netherlands.
 
 * Rodolfo Delmonte, Antonella Bristot, and Sara Tonelli (2007). VIT - 
 Venice Italian Treebank: Syntactic and Quantitative Features. In Proc. 
 Sixth International Workshop on Treebanks and Linguistic Theories.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.4
License: CC BY-NC-SA 3.0
Includes text: yes
Genre: nonfiction news
Lemmas: converted from manual
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Tamburini, Fabio; Simi, Maria; Bosco, Cristina
Contributing: elsewhere
Contact: simi@di.unipi.it
===============================================================================
</pre>
