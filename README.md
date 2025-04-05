# Multimodal PDFs Data Store

## Idea

<p>Take PDFs, split the text, tables and images and store the text embedding of the summary of the text, tables and images into a vector DB and store the actual text, tables and images in a Document store (later in ElasticSearch) and then convert it into a standard boilerplate code to automate this entire process.<p></p>

<hr>

### Branch: vector-store

This step is vector embeddings of the summaries and data storage while the relation between the summary and the data is not lost using ```Vector``` store and ```Doc``` store.

<br>

![Flowchart - VectorStore.png](<https://media-hosting.imagekit.io/02fe437cfcfc4dd1/Flowchart%20-%20VectorStore.png?Expires=1838444030&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=rzjR5~fMBZ6drvCxvCOyjbFI3mfqjLFtGAWz4FPRf1NawsPph4S8TvXBGOHrkGwgg5xhS0Y6d22rRaYnpsS4b9Jnx5YCQs1E3e8IAyaJlVFbSeBSMXoJzihewu-KYL17FrtnaPIZQNd1rhdSCCXl~2oO9xdjQvSXwlC63so8DooikKpVKbuiFXtxBJaqxVurZyPBIjp9g8Zd7UGV754ooJ4PLOP4XPAKN8Ckc6TtDXxpMhi9oDT2m99jLbmEO61ijt7Zrs0XhtNUdfEuAl5vDxG~cqs2JfsvD35NRcUuVQJhexOG28eI8qMWPXAdgrs8PpM3ro2bO1Rp4EeO4FxyIQ__>)
