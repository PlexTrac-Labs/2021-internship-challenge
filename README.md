# PlexTrac 2021 Summer Internship Challenge

This summer PlexTrac is looking to bring an intern on to do some work importing and mutating data in our platform.  You'll be taking multiple disparate formats as input and will be transforming them into the same underlying data structure to normalize various external formats into our platform.

### The task at hand...

Your mission, should you choose to accept, is to write a couple of Python scripts to parse data from multiple formats and transform them into the same data structure for further processing.  

Please consult the files for your inputs:
- data.xml 
- data.csv 

Both should be output as JSON, consult the following for the format:
- sample_output.json

Minimum Viable Product (MVP):
- Convert XML to JSON
- Convert CSV to JSON

Extra Credit:
- De-duplication of entries
- Write unit tests that validate each parser is functioning correctly and outputs the proper format

To get started, fork this repository and add the following items:

- parser-xml.py -- this should include the code to read and parse data.xml then save a JSON file using the structure from sample_output.json
- parser-csv.py -- this should include the code to read and parse data.csv then save a JSON file using the structure from sample_output.json

The rest is up to you.
