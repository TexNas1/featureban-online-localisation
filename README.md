# Featureban Online localisation files

The game: https://tools.flowfast.io/featureban

You can suggest fixes to existing localisation files or create pull requests with new languages.

## How to add a new language to the Featureban Online

1. Clone this repository
2. Copy `en` directory to a new language directory (2 chars code like `ru`)
3. Make changes inside the copied files (see folder structure below)
4. Make pull request 
5. We will review, test and accept it (if it works)

## Folder structure

```
lang
  translations.json - translation keys, preserve them all for a new language
  help - ingame instructions for the iterations, preserve all hbs files, structure inside files can be changed if you want so
  assets - images, that used inside instructions. You can have different set of images, yet rules must keep the same meaning as for the other language
  dictionaries – game themes, you don't need to translate them or add new ones, it's optional
```


Good luck! :-)
