# Multimodal PDFs Data Store

## Idea

<p>Take PDFs, split the text, tables and images and store the text embedding of the summary of the text, tables and images into a vector DB and store the actual text, tables and images in a Document store (later in ElasticSearch) and then convert it into a standard boilerplate code to automate this entire process.<p></p>

<hr>

### Branch: vector-store

This step is vector embeddings of the summaries and data storage while the relation between the summary and the data is not lost using ```Vector``` store and ```Doc``` store.

<br>

![Flowchart - Summary.png](<https://media-hosting.imagekit.io/087ad6174ee34564/Flowchart%20-%20Summary.png?Expires=1838058124&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=lHrEeDFcPNZxrtSPQOJ~t-Woxjfy6jjDumeJmW903e6hHroPIQRWvGHXN7lMAy997UxFrAQ9ATZwfjG9N8ttVV-B8jJ4b~y5Hys-PxKmd2yJYrzYsom12vxc4DiN01Y8-Bb9qMbJp43AwYoqiyHjOwWUEJM4FLPvbwOptqDaHDmihlfFYjLHRptPW9U4nxszmNJYksI-CeZepY5PNk97lxiiqom479hZlR919gX1J8L2sNltbSp6oJEN9F9aikVIQiXkCR052867Ua35Rbxg~MuXY7lnLHRaYyrq5qETIa4FR3IU6NjQXEm~6nYrXl2uHDylaQQ7vZRS5lh3VH3pHg__>)
