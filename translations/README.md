# Translate Deckloud

Here is all of the text in Deckloud for iPhone, iPad, Mac, Windows, and Linux. Each language has one file, named by its language code: `da.json` is Danish, `de.json` is German, and `pt_BR.json` is Brazilian Portuguese.

Each line pairs the English text with what the app shows in your language:

```json
"Deleted cards": "Slettede kort",
```

A few strings come from the official Nextcloud Deck translations. Most were machine translated, so they can sound stiff or simply wrong. A fix from someone who uses the app in their own language makes Deckloud better for everyone who speaks it. Thank you for helping.

## How to send a fix

1. Open the file for your language, then select the pencil icon to edit it. GitHub makes a copy for you.
2. Change the text on the right side of the colon.
3. Select **Commit changes**, then open a pull request.

One fixed word is welcome, and so is a whole file. If you'd rather not use pull requests, [open an issue](https://github.com/hweihwang/nextcloud-deck-desktop-releases/issues/new) with the English text, the current translation, and your suggestion.

## Keep these as they are

- **The English text on the left.** Deckloud uses it to find your translation.
- **Placeholders** such as `{{count}}` and `{{name}}`. You can move them within the sentence.
- **Product names** such as Deckloud, Nextcloud, Nextcloud Deck, App Store, and Google Play.
- **The JSON format.** Each line ends with a comma except the last one, and a quote inside the text needs a backslash: `\"`.

Your fix ships in the next Deckloud release. These files are refreshed on each release, so new strings appear here as soon as they are in the app.

By opening a pull request, you agree that Deckloud may use, change, and distribute your translation in its apps.
