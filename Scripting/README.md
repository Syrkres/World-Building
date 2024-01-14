# Scripting
The following files are scripting files including CustomJs, Templates, Inline Scripts.

**Note:** oRPG.js is uploaded  individually as it contains the rules which I update frequently. It is also in the ZIP file (grab the latest).


## Required Plugins:
These files minimally require the following Addons:
- CustomJs - (required core as the main script is written using this)
- Templates - Allows use of the CustomJS scripts in templates
- InlineScripts - Allows use of the CustomJS scripts and enhances them

### oRG.js (CustomJS) Internal Functions:
The following are the main functions of oRPG.js. There are many more internal functions but these are the main ones.
- listRules - Lists all the Rules (see genereateRul)
- generateRul - takes an UPPERCASE string (RULE) which it generates a return string
- generateFullName - generates a full name based on race, gender, species
- generateFirstName - generates a first name based on race, gender, species
- generateLastName - generates a last name based on race, gender, species
- generateCharacter - generates NPC front matter based on race, gender, species
- generateWrittenBook - generates a random book description
- generateSpirit - generates a random spirit based on race

### Templates
The following are some sample templates


### Inline Scripts
The following is the main inline script which includes function
- oRPG.sfile.md - has a bunch of helper methods to call customJS methods.
