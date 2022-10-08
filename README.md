# Usage:
There are currently four options to use:
- English-English thesaurus: `-t`
- English-English definition: `-d`
- German-English translation: `-g`
- Chemical elements: `-e`

First two options should be run on an `input.txt` file, but other options can be run directly from the cli:
```bash
lang -g Achtung
lang -e Gold
```
Add words to the `input.txt` file, this script will read them line by line and then searches them the selected database and output the translations in the `out.txt` file.
