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

# Object types
Each object is a "man made object". It is not classified by a tag or attribute whether it is one of three kinds: (a) architectural object, building (church, palazzo, temple ...), (b) work of art in a building (usually with iconography, fresco, sculpture ...), (c) work of art in a collection (sculpture, painting, drawing ...). There are only these three types of objects, (b) and (c) have relation to a buildung `<aob26>` or a collection `<aob28>`.

# Photographs
Each photo is described as a child of an object `<a8450 text="Foto">` and can describe a physical positive, negative or a digital image, including date, photographer, owner, copyright and other metadata. Due to the fact that a photograph is also a "man made object" and can be part of a collection and the other fact that a photo could describe more than one object (e.g. three sculptures from two different artists) there are some conflicts in the strict hierarchical structure which can be confusing while mapping the documents to another standard.

# Examples
The file `BHR-objects-from-British-Museum-London.xml` contains object collection documents with descriptions of works of art from the British Museum London. `obj\@DID` and `a8450\@id` should be ignored in this example, they refer only in a specific context to an ID and are no global identifiers. It was created by exporting a Hida ULD/TXT (Cp437 encoded) file to a XML (UTF-8 encoded) file with Hertziana tags. XML tags are decribed by each aspect number `<a5000>` (OBJ doc. n.) `<a3100>` (artist name) etc. listed in the MIDAS handbook (Bove/Heusinger/Kailus) or defined by a MIDAS.DEF or MIDAS.XML file.

# Comparison to Data from Pharos partners
Rome, Galleria Spada, inv. 203; Bibliotheca Hertziana : http://foto.biblhertz.it/exist/foto/obj08014278; Fondazione Zeri: http://data.fondazionezeri.unibo.it/id/artwork/17204/item.html
