# cmap_data_BQ_toolkit_instruction
This is the git repo for instructions of retrieving data using using Python cmapBQ package (with BQ toolkit)
Note: It's the best to use google colab; easy to upload the json key file then retrieving data
## Useful links/tutorials:
- GEO CMap LINCS User Guide v2.1 https://docs.google.com/document/d/1q2gciWRhVCAAnlvF2iRLuJ7whrGP6QjpsCMq1yWz7dU/edit# -> Understand the whole story of LINCS dataset (Highly Recommend)
- YouTube tutorial by CMap (highly recommend): https://www.youtube.com/watch?v=CpH12ntRut4   (Highly Recommend)

  - In this session, we review various modes for accessing the expanded CMap LINCS gene expression resource, which now contains over 3M gene expression profiles. Data access modes include web applications at https://clue.io and the CMap BigQuery python toolkit. This workshop was hosted on December 17, 2020.
  - Related links:
    - CMap website: https://clue.io
    - LINCS website: https://lincsproject.org
    - Github repository with notebooks: https://github.com/cmap/lincs-worksho...
    - CMap BQ toolkit documentation: https://cmapbq.readthedocs.io
- cmapBQ user guide: https://cmapbq.readthedocs.io/en/latest/setup-guide.html (Highly Recommend)
- Github repo for cmapBQ data access section: https://github.com/cmap/lincs-workshop-2020/tree/main/notebooks/data_access

Ways to directly get the data (Used for small dataset such as metadata)
![截屏2021-07-28 上午11 53 00](https://user-images.githubusercontent.com/57332047/127260871-f64059e4-2455-43dd-a753-577b0f01fd55.png)

![截屏2021-07-28 上午11 53 54](https://user-images.githubusercontent.com/57332047/127261071-62926bc9-96e6-4366-9625-c4069a36d9d8.png)

![截屏2021-07-28 上午11 55 07](https://user-images.githubusercontent.com/57332047/127261085-80986eed-7955-4107-9f81-a3678cfbcbc8.png)

![截屏2021-07-28 上午11 55 23](https://user-images.githubusercontent.com/57332047/127261096-34ab05a6-1f14-45d1-ac72-d8182f410582.png)


Way to get large dataset, filtered what you want then retrieve it:
Use Cmap BQ toolkit
