# GiveWP add-on Translations

## How Translation works for GiveWP and its add-ons 

Translation for GiveWP is handled in two different ways: one is for the main plugin (and any others hosted in the official plugin directory) and the other for premium add-ons.

The main GiveWP plugin available on the wordpress.org plugin directory is translated by the (largely volunteer) team at the official translation page for the WordPress project. Here's the specific page for GiveWP: https://translate.wordpress.org/projects/wp-plugins/give

We as a company don't have control over those translation files, though we can make suggestions and contributions there just like anyone else. We'd encourage you to get involved there to make GiveWP translations the best they can be.

The premium add-ons, because they are not on the official WordPress directory, have to handle translations differently. A handful of our add-ons ship with translation files (PO and MO files) but as most of our team is not multilingual enough to manage translations, we rely on others to provide translations for GiveWP add-ons. The most established way to do that is with a program called Poedit: https://poedit.net/download

If you want to translate the files just for your site, you can also use a plugin called Loco Translate: https://wordpress.org/plugins/loco-translate/

We have documentation about how you can do that here https://givewp.com/documentation/resources/translating-give/translating-givewp-with-loco-translate/

This repository is a place for folks to share their translations with the world!

## Using this Repository

### Adding translation files to your site

In this repository, each add-on that has translations available has its own directory where user-contributed PO and MO files live. To use those files, you can download them and add them to the language folder in your WordPress installation.

We provide this space for polyglots to upload their translations in a way that all users can benefit from, but make no guarantees as to the accuracy of translations or the functionality of the files here. 

### Contributing translations for others to use

To add your own translation files, please clone this repository and submit a Pull Request to the master branch where you have added the files, and if necessary the directory, for our team to evaluate. Make sure to name the directory exactly as you see the slug in your plugin filesystem. `give-stripe` is shown as an example.