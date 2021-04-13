# PlexTrac 2021 Summer Internship Challenge

This summer PlexTrac is looking to bring an intern on to do some work importing and mutating data in our platform.  This will involve converting multiple disparate formats into the same underlying data structure in an effort to normalize various external formats into our platform.

### The task at hand...

Your mission, should you choose to accept, is to write a couple of Python scripts to parse a couple of different formats and transform them into the same data structure for output.  

Please consult the files while writing your parsers:
- data.xml (input)
- data.csv (input)
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
