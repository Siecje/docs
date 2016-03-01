getSelectArea
=============


@short:
	returns the object of the select area

@params:
- area_name			string			optional, the name of the select area 


@returns:

- area		object			the object of the select area

@example:

var area = $$("dtable").getSelectArea();

@template:	api_method
@descr:
if the area_name parameter isn't passed, the method returns the last selected area

The returned object of the select area contains the following parameters:

- start	- (object) the id object of the left top cell, contains two parameters: the row id and the column id
- end - (object) the id object of the right cell, contains two parameters: the row id and the column id
- preserve - (boolean)	defines, if the previous select area should be saved, false by default
- area_name - (string)	optional, the name used to address to an area to change or to delete it; by default it's generated by webix.uid() method
- css - (string) the css style (classname) for the border of an area. By default, the border of area selection is black
- handle - (boolean) optional, enables/disables a handle for selection area resize (enabled by default)

@relatedapi:
- api/ui.datatable_addselectarea.md
- api/ui.datatable_removeselectarea.md
- api/ui.datatable_getallselectareas.md

@related:
datatable/area_selection.md