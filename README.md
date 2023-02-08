# Seedwing Dogma TextMate bundle

This is a TextMate bundle for the policy definition language of Seedwing, named "Dogma".

This project should also work as a VScode addon.

## State

This language definition focuses on some low-hanging fruits and isn't a full mapping of the language.

## Making changes to the language

The TextMate language is authored in the YAML file. It then needs to be converted to JSON for some editors
(like VScode). This is done by running:

```shell
npm run convert
```

The CI ensures that both files are in sync.