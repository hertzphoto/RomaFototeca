# OAI Repository of the Photographic Collection Database
    
`Base-URL = https://oai.biblhertz.it/foto/oai-pmh`

`Set = obj, kue, objkue`

`metadataPrefix = raw`

## Identify:

https://oai.biblhertz.it/foto/oai-pmh?verb=Identify

## ListSets: information about the Sets

- obj: objects/artworks with object IDs beginning with 08 and with photos 
- kue: artists biographies, ID beginning with 08, only edited at Bibliotheca Hertziana Fototeca 
- objkue: objects and artists

https://oai.biblhertz.it/foto/oai-pmh?verb=ListSets

## ListIdentifiers

Listing identifiers of object set:

https://oai.biblhertz.it/foto/oai-pmh?verb=ListIdentifiers&set=obj&metadataPrefix=raw


## GetRecord

Show raw data from object with identifier 08127672 (Rubens painting of Sebastian at Galleria Corsini, Rome):

https://oai.biblhertz.it/foto/oai-pmh?verb=GetRecord&identifier=oai::obj::08127672&metadataPrefix=raw


## ListRecords: updating data records from actual objects

Example: objects changed in February 2019

https://oai.biblhertz.it/foto/oai-pmh?verb=ListRecords&from=2019-02-01T00:00:00Z&until=2019-02-28T23:59:59Z&metadataPrefix=raw&set=obj
