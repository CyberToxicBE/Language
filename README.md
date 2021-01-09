# Language

## Modify any translations
To modify any translations, please open a PR with the updated version of this repo.
Make sure to use LF as line seperator and do not remove any untranslated keys of the language (just leave them english)

You should not change usage of placeholders (`%0`, `%1`,..) which means that for example `%0` will always stay as a player, changing their sorting would not affect any changes on the value.
**Sample string:**
 
```Player %0 sent you %1 Coins!``` 

is now the default string. 

In another language you might change order of the sentence to keep it's sence.

Do it like that:
```You got %1 Coins from Player %0!```
This is **valid**, 
keeping the placeholders at their position like

```You got %0 Coins from Player %1!```

is **invalid**!
