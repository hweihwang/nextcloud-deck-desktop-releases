# Deckloud Translations

These files hold every piece of text in Deckloud for Mac, iPhone, iPad, and Android. There is one file per language, named by its locale code, for example `da.json` for Danish or `pt_BR.json` for Brazilian Portuguese.

Each line maps the English text to the text the app shows in that language:

```json
"Deleted cards": "Slettede kort",
```

Some strings come from the official Nextcloud Deck translations. Most were machine translated, so many can be improved. Corrections from people who use the app in their language are welcome.

## How to contribute

1. Open the file for your language and select the edit (pencil) button. GitHub creates a fork for you.
2. Change the text on the right side of the colon.
3. Select **Propose changes** and open a pull request. Mention the language and any context that helps review.

You can fix a single string or the whole file. Small pull requests are fine.

If you prefer not to use pull requests, open an [issue](https://github.com/hweihwang/nextcloud-deck-desktop-releases/issues) with the English text, the current translation, and your suggestion.

## Rules

- Keep the English text on the left side unchanged. The app uses it to find the translation.
- Keep placeholders like `{{count}}`, `{{name}}`, and `{0}` exactly as written. You can move them within the sentence.
- Keep product names unchanged, for example Deckloud, Nextcloud, Nextcloud Deck, App Store, and Google Play.
- Keep the file valid JSON: each line ends with a comma except the last one, and quotes inside text need a backslash (`\"`).

Merged changes ship in the next Deckloud release. The files are refreshed from the app on each release, so new strings appear here in English or as machine translations until someone reviews them.

By opening a pull request, you agree that Deckloud may use, change, and distribute your translation in its apps.
