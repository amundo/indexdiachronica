# Index Diachronica Database Project

This repository is a project to convert the Index Diachronica into a 
database. There are several reasons that this is worth doing:

* The Index Diachronica is very large. It sections on  
many languages and language families, as well as a fairly well-structured presentation of
historical sound changes in those languages.
* The Index Diachronica (usually) includes references. This means that the 
database could be checkable by experts in various fields.

However, there are also problems in its current state:

* It is a `.tex` document, not a database. This means that while it is true that
there are probably a dozen examples of how (say) palatalization happens in the i
languages of the world, it’s very difficult to compile those examples in the current
form of the information.
* The references aren’t in a standard format — they’re just formatted text. In an
ideal word there would be an accompanying reference database in a standard format, 
say bibtex or COiNs JSON references, that would make the database importable into 
database software such as Zotero, either in whole or in part.
* There are phonological inventories mixed into the soundchanges. Inventories are awesome,
but they are a separate project. It would make sense to have a separate project, (perhaps
we could call it the _Index Phonologica_!) to handle that. 

