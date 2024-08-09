# GDELT-Data-Processing-Pipeline

GDELT Data Processing Pipeline
This repository contains a Python-based pipeline for processing Global Database of Events, Language, and Tone (GDELT) data. The pipeline automates the following steps:

1.Data Download: Retrieves GDELT event data files from the official GDELT server based on a specified date range.
2.File Extraction: Unzips the downloaded data files into a local directory for further processing.
3.Data Filtering: Filters the event data to extract records related to Nepal, focusing on events associated with the Millennium Challenge Corporation (MCC).
4.Database Insertion: Inserts the filtered data into a ClickHouse database for efficient querying and analysis.

The pipeline is designed to handle large datasets and can be easily adapted to filter data for different countries or events.
