# Infinity Theming Engine Languages

Getting Infinity to display in your preferred language is easy!

## Using an existing translation

See [Installing WordPress in Your Language](http://codex.wordpress.org/Installing_WordPress_in_Your_Language)
for an overview of how to enable WordPress translations.

1. Download the branch of this repository which matches the version of Infinity you have installed.
1. Create the `wp-content/languages/` folder if it does not already exist.
1. Copy or move the downloaded file to that folder
1. Extract the package and rename the extracted folder to `infinity`
1. Make sure to properly define the `WP_LANG` constant in wp-config.php.

## Creating a new translation

See [Translating WordPress](http://codex.wordpress.org/Translating_WordPress)
for an overview of how to create translations for WordPress.

1. Complete the steps for using an existing translation above.
1. Load the `infinity.pot` file into the translation tool of your choice and put the
   generated "po" and "mo" into the `languages/infinity/` folder.

## Contributing your translation

1. Fork this repository.
1. Commit your translation to the correct branch of *your fork*.
1. Push your changes to GitHub.
1. Submit a pull request from your fork's branch to the same branch of this repository.

## String errors, omissions, misspellings or other inaccuracies

1. Submit a new issue to *this* repository.
1. Be patient.

> Any translation related issues created on the
> main Infinity repository will not be answered and more than likely deleted.