### uni-trans/www-trans

#### Introduction

```js
This is a JavaScript program for automated translation based on Baidu Translate.
```

#### Instructions

```js
How to use:
1. Register a Baidu Translate developer account and obtain an appid and secret key.
2. Configure the translation object and the file path to be translated. Set the target language according to the Baidu Translate documentation (e.g., it, en, zh).
3. Insert the appid and key into the HTML file and run the program (using the Live Server plugin in VSCode to open the HTML file is recommended).
4. Click the start translation button in the browser to download the translated file.
5. After translation is complete, the corresponding target translation file will be automatically downloaded (e.g., en.js).

```

#### Overview

```js
Automatically reads the fields to be translated from en.js and generates the corresponding translation files.
Automatically iterates over the translation object, translates in batches, and downloads the files automatically.

```

#### Two Different File Format Handling

```js
1. The uni-trans method is used in modular development, where each language folder represents a language, and each module's language is stored in a separate JS file within that folder.
2. The www-trans method consolidates all content for a single language into one JS file, where each file represents a different language.
```

### Notes

- For Asian countries, use Chinese as the source language for more accurate translations.
- For other regions, English provides more accurate translations.