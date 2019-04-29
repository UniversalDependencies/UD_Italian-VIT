# Summary

The UD_Italian-VIT corpus was obtained by conversion from VIT (Venice Italian Treebank), developed at the Laboratory of Computational Linguistics of the Università Ca' Foscari in Venice (Delmonte et al. 2007; Delmonte 2009).

# Introduction

VIT originated as a constituency based treebank following the theoretical framework described in (Delmonte et al. 2007), and was later converted into a dependency representation in ConLL-X format (Delmonte 2009).

VIT includes linguistic materials of diverse nature, extracted from five different text genres: news, burocratic, political, scientific and literary genres (Delmonte et al. 2007).

Similarly to what we did for other Italian treebanks, the UD version of the VIT treebank was obtained by first converting to an unriched version of the MIDT (Merged Italian Dependency Treebank) scheme (Bosco, Montemagni, Simi 2012). Then a further conversion step from MIDT+ to UDv2 was performed. Conversion was followed by a series of semi-automatic harmonization steps, in order to compensate for several differences in the use of the target annotation scheme with respect to the other Italian treebanks.

The splitting into training, devel and test was done maintaining as much as possible the original sequence and respecting the proportions indicated in the guidelines (80%, 10%, 10%).

# Acknowledgments

We are indebted to Rodolfo Del Monte and his collaborators, Antonella Bristot and Sara Tonelli, for the initial work on the VIT treebank; we also acknowledge the contribution of Linda Alfieri and Elzara Khaialieva to the implementation of the conversion process from VIT to MIDT+, which consisted in setting up the automatic conversion rules and in checking the treebank manually.

## References

 * Alfieri L., Tamburini F. (2016). (Almost) Automatic Conversion of the 
 Venice Italian Treebank into the Merged Italian Dependency Treebank 
 Format. In Proc. of the Third Italian Conference on Computational 
 Linguistics - CLiC-IT 2016, Napoli, 5-6 December 2016, 19-23.
 
* Bosco C., Montemagni S., Simi, M. (2012) Harmonization and Merging of two Italian Dependency Treebanks, Workshop on Merging of Language Resources, in Proceedings of LREC 2012, Workshop on Language Resource Merging, Instanbul, May 2012, ELRA, pp. 23-30.
 
* Rodolfo Delmonte, Antonella Bristot, and Sara Tonelli (2007). VIT - 
 Venice Italian Treebank: Syntactic and Quantitative Features. In Proc. 
 Sixth International Workshop on Treebanks and Linguistic Theories.
 
* Delmonte, R. (2009). Treebanking in VIT: from Phrase Structure to 
 Dependency Representation. In Sergei Nirenburg (ed.) Language 
 Engineering for Lesser-Studied Languages, pages 51–81. IOS Press, 
 Amsterdam, The Netherlands.
 
* Tamburini F. (2017). Semgrex-Plus: a Tool for Automatic 
 Dependency-Graph Rewriting In Proc. of the Fourth International 
 Conference on Dependency Linguistics - Depling 2017, Pisa, 18-20 
 September 2017, 248-254.

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
