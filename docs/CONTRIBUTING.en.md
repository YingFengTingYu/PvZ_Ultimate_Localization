# Contributing translations

You can help with text, images, or proofreading in a language you know well. A few corrected sentences or one finished button are useful contributions; you do not need to translate a whole language at once.

Contribute directly through this GitHub repository. Edit the text files or images, then open a pull request for review. You do not need to build the game or sign up for a separate translation service.

## Translating text

Text files are in [assets/files](../assets/files):

| Language | File |
| --- | --- |
| English | [LawnStrings_en.txt](../assets/files/LawnStrings_en.txt) |
| Spanish | [LawnStrings_es.txt](../assets/files/LawnStrings_es.txt) |
| Simplified Chinese | [LawnStrings_zh_cn.txt](../assets/files/LawnStrings_zh_cn.txt) |
| Traditional Chinese | [LawnStrings_zh_tw.txt](../assets/files/LawnStrings_zh_tw.txt) |

Open the file in a text editor that supports UTF-8. Each entry has an identifier followed by the text shown in the game:

```text
[PEASHOOTER]
Peashooter

[PEASHOOTER_TOOLTIP]
Shoots peas at the enemy
```

Translate the name and description. Keep the identifiers in square brackets unchanged, and do not add square brackets to the translated text. Also keep placeholders and formatting tags such as `{SHORTLINE}`, `{KEYWORD}`, and `{STAT}`.

Use natural wording and keep plant, zombie, and mode names consistent with existing translations. Short labels need to fit on buttons. Jokes may need adapting rather than translating word for word; a brief explanation of your choice helps the reviewer.

If a line is unclear, ask with its identifier and, if possible, a screenshot. Machine translation can help you understand a line, but please read and edit suggestions yourself before submitting them.

For a new language, contact [YingFengTingYu](https://github.com/YingFengTingYu) first so we can agree on the language name, files, and fonts.

## Translating images

The current game images are in [assets/resources/locales](../assets/resources/locales), grouped by language: `en-us`, `es-es`, `zh-cn`, and `zh-tw`.

Find the image you want to change, then look for a PSD with the same name and relative folder under [source/locales](../source/locales). Where there is only a PNG, use it as a reference and keep the editable source you create. If you cannot find a matching source file, ask the maintainer before starting a large redraw.

Some PSDs have language groups and alternative text layers. Show only the layers you need. **Font files are not included; contact [YingFengTingYu](https://github.com/YingFengTingYu) if you need them.** Check missing-font messages before relying on the preview.

Keep the lettering readable at its in-game size and close to the original style. Check the normal, highlighted, and pressed versions of a button together. Before exporting, compare the canvas dimensions and transparency with the existing game PNG; the PSD canvas may be different.

Please send the editable PSD, the finished PNG, and a preview. Keep the original filename and place the PNG in the folder for the language you are translating. Do not include font files.

## Sending your work

Keep each pull request focused on one language or a related set of images. Include a short note about what you changed, anything you are unsure about, and whether you have checked the result in the game. The maintainer will review the changes and arrange their inclusion in the game.

If you do not use Git, you can send the edited files to the maintainer instead. For an unclear line, a cut-off label, or another translation problem, open an [issue](https://github.com/YingFengTingYu/PvZ_Ultimate_Localization/issues) with the language and a screenshot if available.
