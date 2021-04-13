# PlexTrac 2021 Summer Internship Challenge

This summer PlexTrac is looking to bring an intern on to do some work importing and mutating data in our platform.  You'll be taking multiple disparate formats as input and will be transforming them into the same underlying data structure to normalize various external formats into our platform.

### The task at hand...

Your mission, should you choose to accept, is to write a couple of Python scripts to parse data from multiple formats and transform them into the same data structure for further processing.  

#### Minimum Viable Product (MVP):
- Convert the XML in data.xml into the JSON format in sample_output.json and save as xml_output.json
- Convert the CSV data from data.csv into the JSON format in sample_output.json and save as csv_output.json

#### Extra Credit:
- De-duplication of entries - group items from different hostnames but matching name/severity together
- Write unit tests that validate each parser is functioning correctly and outputs the proper format

### Getting started

Fork this repository and add the following items:

- parser-xml.py -- this should include the code for reading/parsing data.xml and saving xml_output.json
- parser-csv.py -- this should include the code for reading/parsing data.csv and saving csv_output.json

The rest is up to you.
