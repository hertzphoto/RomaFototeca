# Data structure of the photographic collection of the Bibliotheca Hertziana
Photographic information are located in child tags within object documents.

`<obj>
  <a8450 text="Foto">...</a8450>
</obj>`

Each document was transformed from a text file (.TXT or unload file .ULD) of a hierarchical data base built by [Startext Hida](http://www.startext.de/produkte/hida/hida) to XML code with a Perlscript ULD2XML (by Christoph Glorius and Martin Raspe, Bibliotheca Hertziana, Max Planck Institute for Art History).

`blk= obj
...  \n
8450= Foto
...\n`
