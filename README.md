# The CRM Firm File Taxonomy

Project is a native saleforce application designed to make the storing, retrieving and editing of Content faster and easier.

- [Features](#Features)
- [Post Install Config](#Post-Install-Config)

## Features

Easily Tag Files As They are Uploaded

![Easily Tag Files As you upload them](docs/images/tagging_files.gif)

Search driven by your companies values

![Search Features](docs/images/search_features.png)

Enjoy heirarchical navigation we have "folders"

ContentDocumentLink to virtual folder object


## Post Install Config

1. Add the 'Tag and Upload' Global Action to the Global layout or to the layout of any Object

    ![global action](docs/images/global_action.png)

1. Add the Lightining Component "File Viewer" to any lightning Record Page Layout to get a contextual view of related content.

    ![page layout](docs/images/page_layout.png)

1. Curate taxonomy fields by adding custom fields onto the ContentVersion Object to control tagging and searchablity. Add picklists, multipicklists, lookup fields, and others to help define the shape of the documents.
    ![custom fields](docs/images/custom_fields.png)

1. Give users permissions to the taxonomy fields and the permission set for 'FileViewer'.

1. Discover and work with files through the File Viewer tab.
