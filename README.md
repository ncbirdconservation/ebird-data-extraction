# ebird-data-extraction
Python script to extract data from downloadable eBird Basic Dataset (EBD) and eBird Reference Dataset (ERD) files. EBD/ERD files must be obtained from www.ebird.org.

## Features
* parse_ebd_records.py - Extract data based on species, year, state, county, month or any combination
  * parameters must be hardcoded
* parse_ebd_observer_records.py - Using observer file output from parse_ebd_records.py, extracts all checklists from these observers (restrictions on parameters above available). Allows analysis of the "home range" of a subset of birders (i.e., Where have the birders who visited during a festival also visited?)

## Future Enhancements
* Modify current parse_ebd_records.py file to parse the checklist file (ERD)
