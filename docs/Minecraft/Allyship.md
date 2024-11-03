#### Adding modules

It's quite simple just add to a category, e.g test, and its module name.

```
testEntries.add(new ButtonEntryWidget("test", buttonWidth, buttonHeight, () -> {
    toggleModule("testModule");
}));
```
