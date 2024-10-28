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
  <data name="Alert_Caution_Title" xml:space="preserve">
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
`ar` | Arabic | العربية
`da` | Danish | Dansk
`de` | German | Deutsch
`en` [!badge variant="info" size="xs" text="default"] | English | English
`es` | Spanish | Español
`fi` | Finnish | Suomalainen
`fr` | French | Français
`hi` | Hindi | हिन्दी
`hu` | Hungarian | Magyar
`hy` [!badge variant="info" size="xs" text="as of v3.1"] | Armenian (Hayeren) | Հայերեն
`it` | Italian | Italiano
`ja` | Japanese | 日本語
`kn` [!badge variant="info" size="xs" text="as of v3.1"] | Kannada | ಕನ್ನಡ
`ko` | Korean | 한국어
`nl` | Dutch | Nederlands
`no` | Norwegian | Norsk
`pl` | Polish | Polski
`pt` | Portuguese | Português
`pt-BR` | Brazilian Portuguese | Portuguese do Brasil
`ro` | Romanian | Română
`ru` | Russian | Русский
`sa` [!badge variant="info" size="xs" text="as of v3.1"] | Sankrit (Saṁskṛtam) | संस्कृतम्
`sv` | Swedish | Svenska
`ta` | Tamil | தமிழ்
`te` [!badge variant="info" size="xs" text="as of v3.1"] | Telugu | తెలుగు
`th` | Thai | ไทย
`tr` | Turkish | Türkçe
`vi` | Vietnamese | Tiếng Việt
`zh` | Chinese | 中文

## Support

For technical support questions, it is best to start a new [Issue](https://github.com/retypeapp/retype/issues) and we will investigate right away.

Do you have a general inquiry? Please feel free to contact us at hello@retype.com.
