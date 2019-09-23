# Query parameters

This table is a list of query parameters for object and photo data at the photographic collection of the Bibliotheca Hertziana, Max Planck Institute for Art History, Rome/ Italy. The parameters are reduced from `a` to `z` to get a limited list of max. 25 fields. Parameter `q` is reserved for a query in all fields. Every single parameter can include one or more of the listed MIDAS elements. The right column shows the corresponding fields of CIDOC/CRM and SCHEDA F and suggests some possible mappings.

|  KEY | OBJECT / PHOTO | DESCRIPTION | `M:` MIDAS @ MPI BH ROME| `C:` [CIDOC/CRM](http://www.cidoc-crm.org); `F:` SCHEDA F; `Z:` [ZUCCARO](http://zuccaro.biblhertz.it/) ETC.
| ------------- | ------------- | -------- | -------- | -------- |
| __parameter__ | __parent element__ | __element names__ | __element numbers__ | __element references__ |
|  | root | data | a9902 _Bibliotheca Hertziana_ | __photographic collection__ |
|  | __OBJ__ | object | obj | `C:`__E22 [Man-Made Object](http://www.cidoc-crm.org/Entity/e22-man-made-object/version-6.2), [Künstlicher Gegenstand](http://cidoc-crm.gnm.de/wiki/E22_K%C3%BCnstlicher_Gegenstand); `F:` OG: OGGETTO__; `Z:` PRINTS, SCULPTURES, DRAWINGS, PAINTINGS, APPLIED ARTS |
|  | __FTO__ | photo | a8450 | `C:`__E36 [Visual Item](http://www.cidoc-crm.org/Entity/e36-visual-item/version-6.2), [Bildliches](http://cidoc-crm.gnm.de/wiki/E36_Bildliches) < E73 [Information Object](http://www.cidoc-crm.org/Entity/E73-Information-Object/Version-6.2), [Informationsgegenstand](http://cidoc-crm.gnm.de/wiki/E73_Informationsgegenstand); `F:` INV: INVENTARIO__ ; `Z:` IMAGE_METADATA, DIGITAL_SCANS  |
|`a`|OBJ|artist name, attribution, artist_ID|a3100, a3090, a31nn, a31bh, a3105, a3000, a30gn|E21 'Artist'; AUTN: AUTORE - Nome scelto|
|`b`|OBJ|building, "Bauwerk", building_id|a5202, a5204, a2700, a2730, a2750, a2780, a5014, a26gn|E22 P1 is identified by (identifies)|
|`c`|OBJ|category classification|a5230, a5220|E55 'Type_Object/Type_Class'; SGT: SOGGETTO|
|`d`|OBJ|date of object or event|a5064, a2996, a3496|E52 'Date_Object'|
|`e`|OBJ|event name, relation|a5060, aob30, aob40, a5007||
|`f`|FTO|file, photo numbers, image_ID|a8540, a8540h, a84bh, a85bh, a8472|E42 'Identifier'; INVT: Numero di inventario di categoria|
|`g`|OBJ|geographic location, city|a5108, a2664, a2662, a2864|E44 'Place Appellation'|
|`h`|FTO|holding or photo archive, signature of photo department, photographer, copyright information |a8460, a8498, a8515, a8490, a8541, a8577|E19 'Photo Subcollection'; UBFC: UBICAZIONE FOTO - Collocazione, INVC: INVENTARIO - Collocazione dell'inventario|
|`i`|OBJ|institution, collection, museum|a2900/ a2930/ a2940|E53 'Collection', E78 'Collection Name'|
|`j`|OBJ|inv./cat. number in collection, institution_id|a28gn, a2950, a2952, a2960, a2962, a9075|E31 'ID_Catalogue'|
|`k`|OBJ, FTO|artists or persons role|a3475, a3470, a4475, a4485, ('photographer' if a8490)|E12 'Production'|
|`l`|OBJ|literature, bibliography, source, library reference|a8350, a8330/ a8334, a8150||
|`m`|OBJ|material, measure, technique|a5260, a5300, a5360, a5358||
|`n`|FTO|negative number, information on negative|a8470, a8476||
|`o`|OBJ|object_ID|a5000, a5001, a5002, a5003, a50gn|E42 'ID_OBJ'|
|`p`|OBJ, FTO|person, portrait, (photographer), person_id|a40gn, a4100, a5500 if '61B', a2910, (a8490) |E39 'Actor/Owner'; AUFN: AUTORE DELLA FOTOGRAFIA - Nome scelto|
|`q`|OBJ, FTO|QUERY ALL|\*||
|`r`|FTO|reproduction type, photo technique, photo size, file size|a8482, a8478, a8487, a8480, a8542||
|`s`|OBJ|school, style|a5130||
|`t`|OBJ, FTO|title of object, photo detail|a5200, a52bh, a8510|E35 'Title'; SGL: SOGGETTO TITOLO|
|`u`|OBJ, FTO|url: museum collection online|a290i||
|`v`|OBJ|visual information: iconclass, iconography|a5500, a5510, a5520||
|`w`|OBJ|world wide web resources|www||
|`x`|OBJ, FTO|cross references, relations, internal resources|bhr mpi||
|`y`|FTO|year, date of photo taken|a8494|E52 'Date_Photo'; LRD: LUOGO E DATA DELLA RIPRESA - Data"|
|`z`|FTO|acquisition date of photo|a8496|E52 'Date of Acquisition'; INVD: INVENTARIO - Data di inventariazione|
