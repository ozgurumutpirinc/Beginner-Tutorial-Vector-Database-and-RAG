# Beginner-Tutorial-Vector-Database-and-RAG

In this notebook, I show how can we build a vector database and RAG pipeline.

<b>Because there are just 200 rows in that dataset, Retrieval part is not healthy and clear. However structure of RAG and Vector Database is this.</b>

Firstly we clean data. Then we select as our content column as page content. We can create a metadata with other columns. We can add a filter in query with metadata.

After that we create a vectordatabase(I used Chroma) and embedding process on data is done.

Finally we create our query.
