template
=============

@short:
	returns HTML string for sparklines in a cell 

@params:

- item			object			the data item
- common		string			the datatable type
- data			array			an array with sparklines data
- column		object			the column configuration
- index			number			the item index

@returns:

- sparklines		string			HTML string for sparklines in a cell 

@example:
var html = webix.Sparklines.template(item,common,data,column,index);


@template:	api_method
@descr:

@related:
	datatable/sparklines.md
@relatedsample:
	60_pro/01_datatable/08_sparklines/01_init.html