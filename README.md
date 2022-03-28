# Project Ideas 
List of project and ideas I would like to implement or see implemented. Open and looking for collaboration. Some of these ideas might already be implemented somewhere by someone, don't hesitate to send me the links (

## Data Science
### Pandas pre-join visualiser


### F-string multi-line pretty formatting 
The f-string is lacking at least one feature that would make them even better:  
the ability to align different lines on specific character. 


### Scikit-Learn : invert transform for specific columns
Having a method to apply the inverse transform method on a transformed columned.
For exemple, once having used `StandardScaler().transform(data)`, being able to apply a function like `StandardScaler().inverse_transform(data)`
video anmiation sync on bpm
site animations live on bpm

## Pandas power up

### Prejoin visualiser
Before deciding whether to do a left, right, inner or outer join, it can be useful to see what would the results produce in terms of # and % of matches, of multi matches (1-n or 1-1 relationships)

### Missing values visualizer

### Utils:

* Quick data pipeline : split num/cat, display insightful info (missing values w dtypes,)
* reset index for multi index with same name — sometimes has the same names (dt.month, dt.day)
* sampling de valeurs non nulles pour avoir une idée des colonnes
* missing values avec percentage
* encodage ordinal lorsqu’il y a peu de valeurs différentes
* multiple successive similar joins (without appending suffixes), order counts
* when joining the same table with itself, no need to put suffixes (if no diff)
* cascade filling (a column contains value from the column 1, unless it is null, it is col 2, ….)

## Apps and softwares
### Receipt Manager
Mobile app stocking receipt, under picture or form formats. With an OCR, key information should be read and stored in a structured database.
The goal is to eventually have democratized a dematerialized receipt system, certainly using public and private keys.


### Perfect project manager, from A to Z
* kanban 
* CR management (track) : follup after reports, steps t
* time spent on tasks
* inspired by rules of project mgmt (modern and traditional)

### Job application assistant
* Applications tracker : Inspired by my current spreadsheet : target list, state of application, comments for me, comments for future candidates
* Application filler : automatic fill w parsed resume
* CRM w LinkedIN

### GAN animations w/ beatmatching & more
animations made for screens on parties light setup
* generate animation
* matched on BPM, and ideally w/ more syncing on music (v0 : frequencies)

## Low bandwith web
A browser and/or a web extension allowing to reduce the bandwith (no animation, small versions of images or none, no tracking) while keeping responsivity and desired UI/UX.
