---
title: Data Import in metasfresh
layout: default
tags:
  - Data Management
  - Data Import
lang: en
sequence: 10
ref: data_import_metasfresh
---

## Overview
You can quickly import externally stored data (such as Excel spreadsheets with data on business partners or products) into metasfresh through the use of the import feature and thus also bring existing entries up to date. To do so, you first have to format the data appropriately, upload them as a CSV or TXT file and then simply import them via the [actions menu](StartAction).

## Requirements

| Import Data | Corresponding DB Table |
| :---: | :---: |
| Business Partner Data | Import Business Partner |
| Product Data | Import Product |

1. [Add an import format using the appropriate database table](Add_import_format) (see above) where you define the data, or rather the columns, as well as their data types that are to be transferred from the import file into metasfresh.
1. Have an [import file](Import_file_useful_tips) ready containing data formatted according to the import format.<br> ***Format examples:***
 - [Business partner data import](Import_format_example_bpartner)
 - [Product data import](Import_format_example_product)

1. Import your data using the appropriate import format.
 >**Note:** Make sure that the separator from the import file coincides with the one defined in the import format (comma, semicolon, tab, etc.).

 - [Follow these instructions](Import_bpartner_data) to import external data on **business partners** into metasfresh.
 - [Follow these instructions](Import_product_data) to import external data on **products** into metasfresh.
