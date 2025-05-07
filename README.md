---
label: Home
icon: home
---
# Retype Translations

This repository contains the translation files of all system strings for [Retype](http://retype.com).

See the `/src` folder of this repository for the source translation files.

Please submit a [Pull Request](https://github.com/retypeapp/translations/pulls) with a revision or a new `.resx` file to add a new language.

Accepted changes will be included in the next release of Retype.

View this page [online](https://retypeapp.github.io/retype-translations/).

## The &lt;value&gt; node

The following sample from the French translation file is a typical `<data>` node:

```xml
  <data name="Callout_Caution_Title" xml:space="preserve">
    <value>ATTENTION</value>
    <comment>CAUTION</comment>
  </data>
```

Only the `<value>` nodes contain the strings to be translated.

The `name` attribute is the key used to reference the string with the Retype app.

The `<comment>` node is the English translation of the string and is used to understand the context.

!!!
Only revise the `<value>` nodes.
!!!

## Visual Studio

Directly editing the `.resx` XML files can be aggrevating, so we recommend using [Visual Studio Code](https://code.visualstudio.com/) and installing one of the RESX editor extensions. The extensions will automatically convert the file into a table that is easy to review and edit.

Any text editor will work or editing directly within GitHub is fine too.

Code | Language | Native name {class="compact"}
---  | --- | ---
`ar` | [Arabic](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.ar.resx) | العربية
`da` | [Danish](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.da.resx) | Dansk
`de` | [German](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.de.resx) | Deutsch
`el` [!badge variant="info" size="xs" text="as of v3.8"]| [Greek](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.el.resx) | Ελληνικά (Elliniká)
`en` [!badge variant="info" size="xs" text="default"] | [English](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.resx) | English
`es` | [Spanish](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.es.resx) | Español
`fi` | [Finnish](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.fi.resx) | Suomalainen
`fr` | [French](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.fr.resx) | Français
`he` [!badge variant="info" size="xs" text="as of v3.8"] | [Hebrew](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.he.resx) | עברית
`hi` | [Hindi](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.hi.resx) | हिन्दी
`hu` | [Hungarian](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.hu.resx) | Magyar
`hy` [!badge variant="info" size="xs" text="as of v3.1"] | [Armenian](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.hy.resx) | Հայերեն
`it` | [Italian](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.it.resx) | Italiano
`ja` | [Japanese](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.ja.resx) | 日本語
`kn` [!badge variant="info" size="xs" text="as of v3.1"] | [Kannada](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.kn.resx) | ಕನ್ನಡ
`ko` | [Korean](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.ko.resx) | 한국어
`nb` | [Norwegian (Bokmål)](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.nb.resx) | Norsk (Bokmål)
`nl` | [Dutch](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.nl.resx) | Nederlands
`pt` | [Portuguese (Brazil)](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.pt.resx) | Português (Brasil)
`pt-PT` | [Portuguese (Portugal)](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.pt-PT.resx) | Português (Portugal)
`ro` | [Romanian](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.ro.resx) | Română
`ru` | [Russian](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.ru.resx) | Русский
`sa` [!badge variant="info" size="xs" text="as of v3.1"] | [Sanskrit](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.sa.resx) | संस्कृतम्
`sv` | [Swedish](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.sv.resx) | Svenska
`ta` | [Tamil](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.ta.resx) | தமிழ்
`te` [!badge variant="info" size="xs" text="as of v3.1"] | [Telugu](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.te.resx) | తెలుగు
`th` | [Thai](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.th.resx) | ไทย
`tr` | [Turkish](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.tr.resx) | Türkçe
`vi` | [Vietnamese](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.vi.resx) | Tiếng Việt
`zh` | [Chinese](https://github.com/retypeapp/retype-translations/blob/main/src/UserInterface.zh.resx) | 中文

## Support

For technical support questions, it is best to start a new [Issue](https://github.com/retypeapp/retype/issues) and we will investigate right away.

Do you have a general inquiry? Please feel free to contact us at hello@retype.com.
