# pdf-repair
pdf-repair is a cloud function that takes a bucket name and list of pdf file GCS URLs and sends them through a repair/cleanup.  To save time/resources, send only those find that could not be opened and scanned using pdf-lib. or other library you want to use for annotation.
