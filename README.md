# Multimodal PDFs Data Store

## Idea

<p>Take PDFs, split the text, tables and images and store the text embedding of the summary of the text, tables and images into a vector DB and store the actual text, tables and images in a Document store (later in ElasticSearch) and then convert it into a standard boilerplate code to automate this entire process.<p></p>

<hr>

### Branch: data-extraction

Here is the part of the extraction of multimodal data consisting of Text, tables and images using the ```unstructured``` library. The next step is generating the summaries of these data elements for the further steps.

<br>

![Flowchart - extraction.png](<https://media-hosting.imagekit.io/14303059fb6648c1/Flowchart%20-%20extraction.png?Expires=1838120694&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=UtZDNehmrNKGbh~PjvKbIaXkxukTWixINLQdM8giVr8Hl5msj2ss2tjaNhj7~lXcqPv6VeqdCKy~VWQiBlQOkTzUGuZdohpnCpkr6xNK1M~8JcaD60RxFDr~1trM2gbS9lIFU8yrtYLyNx5rnGW-MURJu9Ryhmjm0N5GR627kkD2pXcCKULARZdkESSukKFA3-wFvdtzZ0pkUJ4bHmzRlAuX7~NMmaAIn0vUGhVEvl40spmKkPZOyr0FZQxB5GWw8rqaGZ3yyb6dmxXJDVFQVDfmQe16Zi-eNWPAIu-ssy6I0lLilxx1Frq9AFB3u6Pol3Wfqu7jcb9X96gH2mmeRg__>)
