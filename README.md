# Localisations
Localisation files used within the apps

### Base Localisations
The base locations have been translated using Google Translate and DeepL. Some localisations may be incorrect. If you find any inaccuracies or incorrect translations, please submit a PR with the corrections or open an issue. 

### Localisations
- [x] English (en-US)
- [ ] Chinese Simplified (zh-Hans)
- [ ] Chinese Traditional (zh-Hant)
- [ ] Korean (ko)
- [ ] Italian (it)
- [ ] Spanish (es)
- [ ] German (de)
- [ ] French (fr)
- [ ] Japanese (ja)
- [ ] Dutch (nl)

A languge is marked with a checkmark once it has been fully verified and up-to-date. If updates are issued with incompleted or unverified translations, the checkmark is removed. 

### New Languages
If you'd like to help add new language/s to the repository, please follow the instructions mentioned below. All help with translations and languages are always appreciated. If you'd like privately submit translations, please get in touch with me at [support@elytra.app](support@elytra.app).

## Instructions for Adding New Langauges 
1. Create a folder named `{LanguageCode}.lproj`
2. Copy the files from the `en.lproj` project into this folder. 
3. Edit the two files namely: `Localizable.strings` and `LaunchScreen.strings` with translations in this language. 
4. Optionally edit the `Localizable.stringsdict` file using a Plist editor like TextMate.app or Xcode.app. Instructions for editing this file are available [here](https://developer.apple.com/library/archive/documentation/MacOSX/Conceptual/BPInternational/StringsdictFileFormat/StringsdictFileFormat.html) and [here](https://developer.apple.com/documentation/xcode/localizing-strings-that-contain-plurals). This file specifically contains translations for plural items. 
5. Commit your changes and open a PR with your changes. 

## Instructions for Corrections
**A. Open an issue** 
1. Open an issue and mention the line number and file in which the incorrect translation appears.
2. Mention the correct translation string. 

**B. Submit a PR**
Follow steps 3-5 from *Instructions for Adding New Langauges* 

## License
The contents of this repository are licensed under the MIT license. (Will evaluate if Creative Commons License is more appropriate shortly). 
This means if you find any translations useful for your own apps, please feel free to use them.
