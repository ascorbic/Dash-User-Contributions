Peewee Docset
=======================

## Description
Peewee is a small, expressive ORM written in python (2.6+, 3.2+).

## Author
Thomas Feldmann

## Docset generation
```bash
git clone https://github.com/coleifer/peewee peewee
cd peewee/docs/
make html
doc2dash --name Peewee --index-page html/index.html html
```

In the generated docset's Info.plist, change "dashIndexFilePath" to "index.html".
