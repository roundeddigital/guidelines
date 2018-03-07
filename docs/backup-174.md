## Backup/Update Procedures ![](https://img.shields.io/badge/Uncode-1.7.4+-blue.svg) ![](https://img.shields.io/badge/Date-2017.12.12-brightgreen.svg)

[back to index](../README.md)

----

### Instructions

- **Step 1:** Use Rounded Digital > Options Utils > Layouts to generate & save new layout
  - (a) Use consistent naming convention (clientname-YYYY-MM-DD)


- **Step 2:** Use Rounded Digital > Options Utils > Export:
  - (a) Theme Options (save in a TXT File)
  - (b) Layouts (save in a TXT File)


- **Step 3:** Use Appearance > Editor to save a record of the following:
  - (a) Stylesheet (style.css)
  - (b) Theme Functions (functions.php)


- **Step 4:** Use All in one WP Migration to Generate backup web files
  - (a) Use auto-generated naming convention (domainexample.com-YYYYMMDD-######-###.wpress)


----

### MORE HELP
**Rounded Digital > Options Utils > Export**

* Settings PHP File:
    Export your Settings into a fully functional theme-options.php file.
    If you want to add your own custom [I18n](https://codex.wordpress.org/I18n_for_WordPress_Developers) text domain to the file, enter it into the text field before exporting.
    For more information on how to use this file read the documentation on Theme Mode.
    Remember, you should always check the file for errors before including it in your theme.

* Settings TXT File:
    Export your Settings by highlighting this text and doing a copy/paste into a blank .txt file.
    Then save the file for importing into another install of WordPress later.
    Alternatively, you could just paste it into the Options Utils->Settings->Import Settings textarea on another web site.

* Theme Options TXT File:
    Export your Theme Options data by highlighting this text and doing a copy/paste into a blank .txt file.
    Then save the file for importing into another install of WordPress later.
    Alternatively, you could just paste it into the Options Utils->Settings->Import Theme Options textarea on another web site.

* Layouts TXT File:
    Export your Layouts by highlighting this text and doing a copy/paste into a blank .txt file.
    Then save the file for importing into another install of WordPress later.
    Alternatively, you could just paste it into the Options Utils->Settings->Import Layouts textarea on another web site.


**Rounded Digital > Options Utils > Layout**

* Layout Management:
    To add a new layout enter a unique lower case alphanumeric string (dashes allowed) in the text field and click "Save Layouts".
    As well, you can activate, remove, and drag & drop the order; all situations require you to click "Save Layouts" for the changes to be applied.

    When you create a new layout it will become active and any changes made to the Theme Options will be applied to it.
    If you switch back to a different layout immediately after creating a new layout that new layout will have a snapshot of the current Theme Options data attached to it.
