# Scientific writing dicts

 A stash of dictionaries for use in scientific writing.
 Suggestions of useful papers appreciated.

Some words are added manually, others by scraping relevant papers or books, and filtering out words already in the standard dictionary.
Filtering performed using english dict from [Code Spell Checker](https://github.com/streetsidesoftware/cspell-dicts/blob/master/dictionaries/en_GB/src/wordsEnGb.txt).

Contains:

- A personal dictionary - sample names and terms I use or misspell a lot.
- Aspden lab specific terms - members and collaborator names, and words scraped from a few of our publications ([papers used so far](papers)).
- General bioinformatic terms ([papers used so far](papers)).
- Species list - names from ensembl. *To do - add flybase species*.


## [VS Code](final_dicts/VSCode)

Files for Code Spell Checker in VS Code. To add, edit your settings.json file, eg:

    "cSpell.customUserDictionaries": [
        
        {"name": "aspdenlab","path": "/Users/isabelbirds/Documents/GitHub/Scientific_writing_dicts/final_dicts/VSCode/Aspden_dict.txt},
        {"name": "isabel","path": "/Users/isabelbirds/Documents/GitHub/Scientific_writing_dicts/final_dict/VSCode/Isabel_personal_dict.txt"}
    ]

## [MS Word](final_dicts/MSWord)

Files for MS Word. Please note that the main aim of this repo is for working in latex with Code Spell Checker which is case insensitive, so some cases may be missed (e.g. uORFs will be flagged). This should be adequate for spell checking, however.

To add a custom dict, go to Preferences, Spelling & Grammar, Dictionaries, Add, and select your .dic file.
