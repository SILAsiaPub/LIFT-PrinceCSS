# LIFT-PrinceCSS
Experiment in typesetting with PrinceXML directly from a LIFT file

## Working so far

- Page lauout including running headers from lexems
- body text
- 2 columns
- Remove unwanted fields (Reversal, gloss, header)
- All vernacular language words bolded
- entry handling with homonym number after lexeme
- First sense inline and following ones new paragraph
- get POS value from attribute
- Examples handled (so far only vernacular and en)
- Handle trait for semantics information
- Make relation label smaller and grey
- Make note label smaller and grey

## Special handling needed so far
- single senses have an order attribute but left empty
- multiple senses have an order attribute that has a whole number in it.
- LIFT files must be ordered (XSLT with ICU rules)

## Things not handled so far
- Root based dictionaries need a way to include sub-entries in the main entry. Probably with XSLT transformation.
- Identical relation types should be joined before running through Prince
- Way to process words in attributes with underscores that need to be converted back to spaces
- Need to create a Reversal index LIFT file from the source LIFT.
- Need to define Letter group starts
- Stem based dictionaries need to be presorted
- Need to look at other traits to see what needs handling




