# pdf-repair
pdf-repair is a Google cloud run job that takes a bucket name and list of GCS URLs to PDF files and sends them through a repair/cleanup.  
This is required as some files on the internet have errors that doesn't allow them to be opened in pdf-lib so they can be annotated.
To save time/resources, send only those files that could not be opened and scanned using pdf-lib. 
**Parameters:**
* bucket_name : GCS bucket name
* file_paths : The files to send through PDF repair
