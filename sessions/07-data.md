# 07. Data

2022.01.18

## Agenda
1. Updates on goal progress
2. Scheduling showcase
3. Data Cleaning with OpenRefine

## Meeting notes
Note-taker: Kari
### Notes, Session 7
- Install new application: OpenRefine
- Updates
 1. Kari: databasing – how to make the process faster? Excel first, and only THEN integrate with Access; make a report and export to Excel, then reorder as needed and re-export to Access; Python might be a good option for making a new form, if not for this project then for the future
 2. Alexis: work for presentation – Henry Chapman Mercer’s Tiles of the New World; clickable objects that move to the relevant part of the text! Next step: overlapping images while retaining functionality
 3. Mallory: StoryMaps is turning out to be quite unwieldy – problem with computer? With image hosting? Would using a different browser help? Scalar (but Scalar doesn’t let you annotate deep zoom images, which might be a problem)?
- Presentations
 1. Length: 10 minutes or so a person, plus Q&A
 2. Goal: to demonstrate what we’ve been learning this semester!
 3. Scheduling: 12:30/2, some Wednesday in February (preferably a VCC off-week)
- Data
 1. Great to be able to deal with lots of data at once instead of piece-by-piece!
 2. Data can be thought of quantitatively, but can also be represented visually – anything that can, in one way or another, be stored and accessed as binary 
 3. Important things to know how to do with data include: importing/exporting derivative datasets, sorting/filtering/faceting data, fixing errors and inconsistencies at scale, splitting columns with multiple values, introducing regular expressions
 4. Types of data
    - Tabular: basically, anything that can be represented with rows and columns (e.g., latitude and longitude) (only one value can be represented per row)
    - Graph: basically, data that can be represented by nodes and edges (multiple values can be represented per category) – websites are examples of directed graph     data
    - Both human- and machine-readable types of data exist, and are not always the same
    - Tidy data: applying standard ways of optimally formatting data for use with the programming language R
-	OpenRefine
  1. Instead of documents, OpenRefine has projects
  2. To load something, go to “Create Project” and then “Choose Files”; the data will then be read and parsed, some settings may have to be changed; must be specified if items are to be identified as numbers, or else they will be identified as text – this must be done for each column
    - CSV = comma separated values
    - TSV = tab separated values
    - Sorting
    - Filtering
    - Text filters = good for identifying relevant entries quickly
    - Faceting
    - Transforming cells
    - Trimming whitespace
    - Clustering: can make other tasks, like trimming whitespace, more efficient; can be more or less effective depending on consistency of values
-	To-do before next session…
  1. Finish OpenRefine tutorial (continue along the same lines with visualization exercises during next session?)
  2. Logs



### Business
- Updates & announcements
- Other business

### Data
- [Open Refine workshop](https://github.com/tri-cods/tidy-data)

## Action items
- [ ] Add your updates by Monday morning
- [ ] Other

[<<< Previous](06-juncture.md) | [Next >>>](08-map.md)

[Return to syllabus](../syllabus.md)

[Home](../README.md)
