onPaste
=============


@short:
 fires when the <a href="api/copypaste_clipboard_config.md">clipboard</a> is enabled and the user presses CTRL+V keys combination
	

@params:
- text	string	the text to paste

@example: 

tree.attachEvent("onPaste", function(text) {
	webix.message("Node is pasted: " + text);
});

@template:	api_event
@descr:

@relatedsample:
	05_list/09_copypaste.html
	17_datatree/19_copypaste/04_paste_custom.html
    15_datatable/06_clipboard/09_paste_custom.html
@related:
	desktop/clipboard.md
