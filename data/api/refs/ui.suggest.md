ui.suggest 
=============


{{memo A suggest control. }}

Can be used standalone or as an editor for other components. Check [suggest](desktop/suggest.md) documentation for more detailed description.


### Constructor

~~~js
webix.ui({
	view:"text", 
  	width: 300,
  	name:"country", 
  	label:"Country", 
  	value:"Belarus", suggest:[
  		{id:1, value: "Albania"},
		{id:2, value: "Bhutan"},
		{id:3, value: "Colombia"},
		{id:4, value: "Denmark"},
		{id:5, value: "Germany"},
		{id:6, value: "Moldova"}
    ]         
});
~~~

### Where to start

- [Overview of Suggest List](desktop/suggest.md)
- [Samples](http://docs.webix.com/samples/13_form/01_controls/)

<div class='webixdoc_parents'><span>Based on: </span>
<a href="api/refs/ui.popup.md">ui.popup</a>, <a href="api/refs/ui.window.md">ui.window</a>, <a href="api/refs/ui.view.md">ui.view</a>, <a href="api/refs/ui.baseview.md">ui.baseview</a>, <a href="api/refs/settings.md">Settings</a>, <a href="api/refs/destruction.md">Destruction</a>, <a href="api/refs/basebind.md">BaseBind</a>, <a href="api/refs/uiextension.md">UIExtension</a>, <a href="api/refs/movable.md">Movable</a>, <a href="api/refs/modality.md">Modality</a>, <a href="api/refs/eventsystem.md">EventSystem</a></div>


<div class='h2'>Methods</div>

{{api
- api/link/ui.suggest_adjust.md - adjusts the component to the size of the parent HTML container
- api/link/ui.suggest_attachevent.md - attaches the handler to an inner event of the component (allows behavior customizations)
- api/link/ui.suggest_bind.md - binds components
- api/link/ui.suggest_blockevent.md - temporarily blocks triggering of ALL events of the calling object
- api/link/ui.suggest_callevent.md - calls an inner event
- api/link/ui.suggest_close.md - removes a window
- api/link/ui.suggest_define.md - redefines a single configuration property (or a hash of properties)
- api/link/ui.suggest_destructor.md - destructs the calling object
- api/link/ui.suggest_detachevent.md - detaches a handler from an event (which was attached before by the attachEvent method)
- api/link/ui.suggest_disable.md - disables the calling view (makes it dimmed and unclickable)
- api/link/ui.suggest_enable.md - enables the calling view that was disabled by the 'disable' method
- api/link/ui.suggest_getbody.md - gets the UI view of the window body
- api/link/ui.suggest_getchildviews.md - returns child views of the calling component
- api/link/ui.suggest_getformview.md - returns master form for the input
- api/link/ui.suggest_gethead.md - gets the ui view of the window header
- api/ui.suggest_getitemid.md - returns the id of the suggest's item
- api/ui.suggest_getitemtext.md - returns the rendered text of the suggest's item
- api/ui.suggest_getlist.md - returns inner data control from suggest
- api/ui.suggest_getmastervalue.md - returns current value of master control
- api/link/ui.suggest_getnode.md - returns the main HTML container for the calling object
- api/link/ui.suggest_getparentview.md - returns the parent view of the component
- api/ui.suggest_getsuggestion.md - returns id of top suggestion from the suggest list
- api/link/ui.suggest_gettopparentview.md - returns top parent view
- api/ui.suggest_getvalue.md - gets the ID of a selected item in the option list
- api/link/ui.suggest_hasevent.md - checks whether the component has the specified event
- api/link/ui.suggest_hide.md - hides the view
- api/link/ui.suggest_isenabled.md - checks whether the view is enabled
- api/link/ui.suggest_isvisible.md - checks whether the view is visible
- api/ui.suggest_linkinput.md - links a suggest list to an input field
- api/link/ui.suggest_mapevent.md - routes events from one object to another
- api/link/ui.suggest_resize.md - adjusts the view to a new size
- api/link/ui.suggest_resizechildren.md - resizes all children of the calling component
- api/ui.suggest_setmastervalue.md - set value in master control
- api/link/ui.suggest_setposition.md - sets window's position
- api/ui.suggest_setvalue.md - selects an item in the option list
- api/link/ui.suggest_show.md - makes the component visible
- api/link/ui.suggest_unbind.md - breaks "bind" link
- api/link/ui.suggest_unblockevent.md - cancels blocking events that was enabled by the 'blockEvent' command
}}


<div class='h2'>Events</div>


{{api
- api/link/ui.suggest_onafterscroll_event.md - occurs when some webix view has been scrolled
- api/link/ui.suggest_onbeforeshow_event.md - fires right after show() method is called for the window (popup) and before the window is shown
- api/link/ui.suggest_onbindrequest_event.md - fires when the component is ready to receive data from the master component
- api/link/ui.suggest_onblur_event.md - fires when focus is moved out of the view
- api/link/ui.suggest_ondestruct_event.md - occurs when component destroyed
- api/link/ui.suggest_onfocus_event.md - fires when a view gets focus
- api/link/ui.suggest_onhide_event.md - fires when window is hidden
- api/link/ui.suggest_onkeypress_event.md - occurs when keyboard key is pressed for the control in focus
- api/link/ui.suggest_onlongtouch_event.md - fires on holding finger in some position for a certain period of time
- api/link/ui.suggest_onshow_event.md - fires when window is shown
- api/link/ui.suggest_onswipex_event.md - occurs on a horizontal swipe movement
- api/link/ui.suggest_onswipey_event.md - occurs on a vertical swipe movement
- api/link/ui.suggest_ontimedkeypress_event.md - fires after typing has been finished in the field
- api/link/ui.suggest_ontouchend_event.md - occurs when the touch event is ended
- api/link/ui.suggest_ontouchmove_event.md - occurs during touch movement
- api/link/ui.suggest_ontouchstart_event.md - when some webix view has been touched
- api/ui.suggest_onvaluesuggest_event.md - some item selected in the suggest control
- api/link/ui.suggest_onviewmove_event.md - fires while view is moving
- api/link/ui.suggest_onviewmoveend_event.md - fires when view has stopped moving
- api/link/ui.suggest_onviewresize_event.md - view size was changed by resizer
}}


<div class='h2'>Properties</div>

{{api
- api/link/ui.suggest_animate_config.md - defines or disables view change animation.
- api/link/ui.suggest_autofit_config.md - adjusts window size to the size of an html node it is initiated in
- api/link/ui.suggest_autofocus_config.md - sets focus on the window the moment it appears on the page
- api/link/ui.suggest_body_config.md - the content of window body: template or view
- api/link/ui.suggest_borderless_config.md - used to hide the component borders
- api/link/ui.suggest_container_config.md - an HTML container (or its id) where the component should be initialized
- api/link/ui.suggest_css_config.md - the name of a css class that will be applied to the view container
- api/ui.suggest_data_config.md - JavaScript array containing data for the component
- api/link/ui.suggest_disabled_config.md - indicates whether an item is enabled
- api/ui.suggest_filter_config.md - custom filtering function
- api/ui.suggest_fitmaster_config.md - size suggest box to the master control
- api/link/ui.suggest_gravity_config.md - sets the view gravity (1 by default)
- api/link/ui.suggest_head_config.md - sets the view header
- api/link/ui.suggest_headheight_config.md - defines the header height (43 by default)
- api/link/ui.suggest_height_config.md - sets the height of the component
- api/link/ui.suggest_hidden_config.md - defines whether the view will be hidden initially
- api/link/ui.suggest_id_config.md - the component ID
- api/ui.suggest_input_config.md - points to an  HTML input field that houses the suggest list
- api/ui.suggest_keypresstimeout_config.md - time between key pressing and filtering start
- api/link/ui.suggest_left_config.md - the left offset of the window
- api/ui.suggest_master_config.md - reference to the master view
- api/link/ui.suggest_maxheight_config.md - sets the maximum height for the view
- api/link/ui.suggest_maxwidth_config.md - sets the maximum width for the view
- api/link/ui.suggest_minheight_config.md - sets the minimal height for the view
- api/link/ui.suggest_minwidth_config.md - sets the minimal width for the view
- api/link/ui.suggest_modal_config.md - switches window modality
- api/link/ui.suggest_move_config.md - makes view movable
- api/link/ui.suggest_on_config.md - allows attaching custom handlers to inner events of the component
- api/link/ui.suggest_padding_config.md - sets paddings of the chart content
- api/link/ui.suggest_position_config.md - sets position of the window relative to the the screen
- api/link/ui.suggest_relative_config.md - positions a popup window relative to the component it's connected with
- api/link/ui.suggest_resize_config.md - enables/disables window resizing
- api/ui.suggest_template_config.md - template which will be used to fill parent input from selected record
- api/ui.suggest_textvalue_config.md - defines which field from suggest list will be used as text after selecting an option
- api/link/ui.suggest_tofront_config.md - places window above other windows on clicking it
- api/link/ui.suggest_top_config.md - the top offset of a window
- api/ui.suggest_type_config.md - defines type of suggest control
- api/ui.suggest_url_config.md - the URL which the component will use to load data after its initialization
- api/link/ui.suggest_width_config.md - sets the width of the component
- api/link/ui.suggest_zindex_config.md - stack order of the component
}}





<div class='h2'>Other</div>


{{api
- api/ui.suggest_$enterkey_other.md - the method that will be called when the Enter key is pressed
- api/link/ui.suggest_$getsize_other.md - returns the current size of the component
- api/link/ui.suggest_$height_other.md - current height of the view
- api/link/ui.suggest_$scope_other.md - scope for resolving event and method names
- api/link/ui.suggest_$setsize_other.md - sets the component size
- api/link/ui.suggest_$skin_other.md - the method which will be called when skin is defined
- api/link/ui.suggest_$view_other.md - reference to top html element of the view
- api/link/ui.suggest_$width_other.md - current width of the view
- api/link/ui.suggest_config_other.md - all options from initial component configuration
- api/link/ui.suggest_name_other.md - indicates the name of the component (a read-only property)
}}


@index:
- api/refs/ui.suggest_methods.md
- api/refs/ui.suggest_props.md
- api/refs/ui.suggest_events.md
- api/refs/ui.suggest_others.md

