## Versioning
Restructuring.NewShortcuts.OtherChanges

## General
Application-specific shortcuts should be done for Microsoft or popular generic apps (i.e. Browsers, File Explorer...) only and have their own category.


## Translations
Translations are currently being done manually via ChatGPT with the following prompt. Change "czech" at the end for a different language.
```
Answer with an md codeblock.
To the very beginning, add a line saying "This text was translated to {Language} by ChatGPT." This declaration should also be in {language} and without the quotes.

Translate the following, including the line informing about the translation that you added, to {language}. STAY AS CLOSE TO THE ORIGINAL TEXT AS POSSIBLE, copy it SENTENCE BY SENTENCE, almost WORD BY WORD. Stay as close as you can to translating it word by word, while keeping correct {language} grammar. Keep the context of windows shortcuts in mind when translating words. Don't translate names (i.e. Microsoft Word shouldn't be translated). Keep the markdown formatting as-is.

Additionally, translate the line "This text was translated to {Language} by ChatGPT." to {language}. Don't keep it in english!

This is the langauge and the text:

{czech}
```

Then paste [README.md](./README.md) in markdown format.

If ChatGPT stops early, send ```continue, and dont forget to keep everything in a code block``` until done.\
Check the breaks for errors, easiest done by switching to prefview and searching for the first couple of word in the 2nd and subsequent code blocks.
