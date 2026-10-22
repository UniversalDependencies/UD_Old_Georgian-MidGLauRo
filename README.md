# Summary

A treebank for Middle Georgian, containig morphosyntactic annotations of *Amirandarejaniani*, V (XII cent.) and *Rusudaniani*, III (XVII cent.).

# Introduction

UD_Old_Georgian-MidGLauro is a treebank based on the novels *Amirandarejaniani*, V (XII cent.) and *Rusudaniani*, III (XVII cent.). The text is retrieved from [GNC](gnc.gov.ge). The sentences are annotated through a semi-automated workflow: [UD_Old_Georgian-OGLauRo](https://github.com/UniversalDependencies/UD_Old_Georgian-OGLauRo) is used as few-shot examples, together with additional guidelines specific for Middle Georgian and Ilia Abuladze's [ძველი ქართული ენის ლექსიკონი (მასალები)](http://www.nplg.gov.ge/gwdict/index.php?a=index&d=57), to prompt Large Language Models (LLMs) to prepare a draft annotation, which is then corrected manually.

# Acknowledgments

We are greatful to the creators of the Georgian National Corpus (GNC) for making these texts available online.

## References

For the details of annotation principles, see Lin, Chia-Wei and Diego Luinetti (2026). 

``` bibtex
@article{Lin-2026,
 author = {Lin, Chia-Wei and Luinetti, Diego},
 doi = {10.5334/johd.559},
 journal = {Journal of Open Humanities Data},
 keyword = {en},
 month = {Jul},
 title = {Building a Treebank for the Book of Ezra in the Old Georgian Oshki Bible},
 year = {2026}
}
```

# Changelog

* 2026-11-15 v2.19
  * Initial release in Universal Dependencies.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.19
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: fiction
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Lin, Chia-Wei; Luinetti, Diego
Contributing: here
Contact: d.luinetti@unimarconi.it
===============================================================================
</pre>
