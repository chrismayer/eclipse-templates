Eclipse Autocompletion Templates
=================

Templates to be used for autocompletion in [Eclipse IDE](http://www.eclipse.org/)

## javascript-templates.xml

Offers autocomplete templates for native JavaScript and ExtJS commands

### How To use

As normal in Eclipse type a shortcut and press `CTRL + SPACE` to get the autocompletion.

#### Examples

`log` -> gives `console.log(whatToLog);`

`edef` -> will give you a stub for an ExtJS class definition (`Ext.define(...)`)

`ajax` -> will give you a stub for an ExtJS AJAX request (`Ext.Ajax.request(...)`)

...

### Import

  - Open the Preferences dialog in Eclipse by clicking `Window > Prefrences`
  - Select `JavaScript > Editor > Templates` on the left panel
  - Click the `Import...` button on the right and select the `javascript-templates.xml` of this repo
