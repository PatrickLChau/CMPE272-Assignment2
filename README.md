# CMPE272-Assignment2
----------------
Includes the LangFlow JSON and the unstructured data used for the vectorised information.

As for the DB schema definition, the vectorised DB is named GenAI_DB, uses the default keyspace that has a collection called "commerce". 
The collection has a strict size of 4096 dimensions. Furthermore, the tables include the $vector, a unique "_id" identifier per item in the table,
the "page_content" content that is cut into chunks for each item, and the "metadata". 
