# This module is borked
## The Ajax calls interfere with Drupal Core - don't use this.

This was a proof of concept - which failed.  The https://www.npmjs.com/package/cascading-dropdown was successfully integrated, but the AJAX prevents saving. 
It is designed to be used in Panelizer, but you have to go into the module and turn off the function ryans_cascade_select_cascading_dropdown() before you can save this in the panelizer layout to add it to the page.
After that, you can switch the function ryans_cascade_select_cascading_dropdown() back on.

This requries jQuery 2x - you might be able to forego the jqmulti module by adding the jQuery 2X in the modules info file.
jqmulti needs the jquery library to live in the libraries/jquery folder
