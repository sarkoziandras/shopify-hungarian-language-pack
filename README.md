# shopify-hungarian-language-pack
Hungarian Language pack for Shopify

#What's a locale file?
A locale file is a .json file that contains a set of translations for the text strings used in a theme template file. A separate locale file is used for every language that's available in the theme. Locale files are stored in the Locales section of the theme editor.

Instead of hard-coded text strings, theme template files use translation keys and pass them to the translation filter (or t filter.)

The translation filter retrieves the appropriate translated string from the locale file for the active language.


#How to create locale files

You can generate a locale file in a number of ways:

by clicking Add a new locale from the theme template editor
by creating a new locale file manually.
A new locale file is also produced when a new translation is created using the language editor.

#Adding a new locale from the theme template editor

To add a new locale from the Edit HTML/CSS page:
 
1.) From your Shopify admin, go to Online Store > Themes.
2.) Find the theme you want to edit, and then click Actions > Edit code.
3.) Scroll down the sidebar and click Locales, then click Add a new locale.
4.) From the drop-down, choose an existing locale file as a starting point or create a new one from scratch.
5.) Enter a name for the locale file (without the .json extension), then click Create locale.

#Creating a new locale file manually
If you create a locale file manually (that's outside the theme editor), be sure to use the correct IETF language tag for the filename.

#Where to save your locale files
Save your locale files in the /locales folder, which is accessible from the Template Editor.
