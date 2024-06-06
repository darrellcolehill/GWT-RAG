# GWT-RAG
Allows Bible Translators to ask questions about a word/phrase and recieve answers with context retrived from Greek word definitions found in the [en_gwt repo](https://content.bibletranslationtools.org/WycliffeAssociates/en_gwt). 

## How to run (using current Chroma DB)
1) Run LM Studio 
2) Run python script

## How do update Chroma DB
1) Create an input folder at the root directory of the project
2) Place new input markdown files in the input folder
3) Run the data_generation notebook


## MISC
* The given Chroma DB is created by embedding the markdown files found in the [en_gwt repo](https://content.bibletranslationtools.org/WycliffeAssociates/en_gwt).
