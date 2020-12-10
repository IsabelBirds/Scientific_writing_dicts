# Scientific writing dicts

 A stash of dictionaries for use in scientific writing.

I plan to make:

- A personal dictionary - sample names and terms I use or misspell a lot.
- Aspden lab specific terms - names, common techniques and cell types.
- General bioinformatic terms - software names, variables, terminology.
- Species list - scientific names.

Some words will be added manually, others by scraping relevant papers or books, and filtering out words already in the standard dictionary.
Filtering performed using english dict from [Code Spell Checker](https://github.com/streetsidesoftware/cspell-dicts/blob/master/dictionaries/en_GB/src/wordsEnGb.txt).

## VS Code

Files in final_dicts/VSCode are for Code Spell Checker in VS Code. To add, edit your settings.json file, eg:

    "cSpell.customUserDictionaries": [
        
        {"name": "aspdenlab","path": "/Users/isabelbirds/Documents/GitHub/Scientific_writing_dicts/final_dicts/Aspden_dict.txt},
        {"name": "isabel","path": "/Users/isabelbirds/Documents/GitHub/Scientific_writing_dicts/final_dict/Isabel_personal_dict.txt"}
    ]

## MS Word

Files in final_dicts/MSWord are for MS Word. Please note that the main aim of this repo is for working in latex with Code Spell Checker which is case insensitive, so some cases may be missed (e.g. uORFs will be flagged). This should be adequate for spell checking, however.

To add a custom dict, go to Preferences, Spelling & Grammar, Dictionaries, Add, and select your .dic file.
