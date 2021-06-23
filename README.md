# Qiqqa Docu Base

The Qiqqa Library and Document internal server: this one provides all functionality re Qiqqa Library management, PDF document storage & processing, *anything that has to do with the documents stored in your Qiqqa Libraries*.

## Technologies Used

The PDF document processing is based on Artifex' MuPDF 👍 and augments these with several other important components:

- SQLite for the Qiqqa library database(s),
- Crow for the web server logic,
- cURL for all client-side interfacing to these (and other) web servers, both local and *remote*,
- ...
-
