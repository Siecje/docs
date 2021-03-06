Segmented Button
===============

##API Reference

- [Methods, properties and events](api/refs/ui.segmented.md) 
- [Shared functionality](desktop/controls_guide.md)

##Overview

Segmented is an integral button with as many segments as you like. Can be used for switching between [MultiView](desktop/multiview.md) cells.

<img src="desktop/segmented.png"/>

##Initialization 

~~~js
{view:"segmented", multiview:true, value:1, options:[
	{ id:"1", value:"Section A" }, // the initially selected segment
	{ id:"2", value:"Section B" }, 
	{ id:"3", value:"Section C" }]
}

//short form for options array
{ view:"segmented", options:["Section A", "Section B", "Section C"]}
~~~

{{sample 13_form/01_controls/07_segmented.html }}

####Main properties

- **multiview** (boolean) - connects the control to the MultiView cells, enables switching between these cells;
- **options** (array, object) - defines the buttons (segments) within the control. [Details](desktop/controls_guide.md#defininginitialvalues);
- **value** (string, number) 
	- within **options** array it sets titles for button segments;
 	- within Segmented constructor it defines the initially selected item for the control;
- **label** (string) - text label of a control. It can be customized by:
	- **labelAlign** (string) - label alignment towards its container. Possible values are "left" and "right".  In any way, it's placed left to the control; 
    - **labelWidth** (number) - width of the label container; 
- **selected** (string) - defines the tab that will be visible initially.

##Showing and Hiding Options

Segmented Button provides the possibility to hide and show segments with the help of the corresponding methods: api/ui.segmented_showoption.md and 
api/ui.segmented_hideoption.md.

You need to pass the id of the view that should be hidden as a parameter.

~~~js
// hiding view
$$("segmented").hideOption("viewId");

// showing view
$$("segmented").showOption("viewId");
~~~



##Working with Segmented Button

[Adding and Deleting Segments (Options) on the Go](desktop/tabs_options.md)



@metadescr:  Segmented is an integral button with as many segments as you like. Can be used for switching between MultiView desktop multiview cells. Initialization js view segmented