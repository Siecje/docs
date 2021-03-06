removeSelectArea
=============


@short:
	removes a select area

@params:
- area_name		string		optional, the name of the select area that should be removed


@example:

$$("dtable").removeSelectArea();

@template:	api_method
@descr:
if the *area_name* parameter isn't passed, the method removes the last unnamed selected area.

@relatedapi:
- api/ui.datatable_addselectarea.md
- api/ui.datatable_getselectarea.md
- api/ui.datatable_getallselectareas.md
- api/ui.datatable_onafterarearemove_event.md
- api/ui.datatable_onbeforearearemove_event.md

@related:
datatable/area_selection.md

@relatedsample: 60_pro/01_datatable/06_api/14_area_selection.html

@edition:pro

@seolinktop: [html5 framework](https://webix.com)
@seolink: [data table](https://webix.com/widget/datatable/)