$cssName
=============

@short: name of the widget the CSS of which you want to inherit for a custom widget
	

@type:string

@example:

webix.protoUI({
	name:"mymulticombo",
    $cssName:"text",
    //other properties and methods
}, webix.ui.richselect);

webix.ui({ view:"mymulticombo"});

@related:
- desktop/extending_components.md

@template:	api_config
@descr:


By default, a custom widget inherits API of the widgets and mixins that are used for it, but not CSS. 
