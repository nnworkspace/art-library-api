# API Story :: Art Inventory at Alpha Org

## Purpose

We keep track of all the art works for Alpha Org.

## Data

Data we include in an artwork record are
- name of the artwork
- author(s) of the artwork
- serial number of the artwork
- photos of the artwork
- description of the artwork
- date obtained
- market value in Euro at the time of accquisition
- condition
- storage location
- status
- comments

We also track the date/time the record was created and the last date/time it was updated.
We keep copies of the records, even after they have been deleted.

## Actions

Typical actions on the artwork records include:
- getting the list of artworks
- reading a single record
- creating / updating / deleting records.

You can update the status of a single record.
You can get a filtered list of all records (support for filtering by name, authors and status)

## Rules
to be added.

## Processing
Each artwork has a unique identifier in the system. We use the combination of 
- last name of the first author, 
- the first word of the artwork name
- date obtained to Alpha Org

We add another digit if the combination above is not unique.

Default status of a newly added artwork is "staging".

