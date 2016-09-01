Methods
=======

{{api
- api/link/ui.filetable_add.md - adds an item to the store
- api/link/ui.filetable_addcellcss.md - adds a css class to the cell
- api/link/ui.filetable_addcss.md - applied CSS class to a component item
- api/link/ui.filetable_addrowcss.md - adds a css class to the row
- api/link/ui.filetable_addselectarea.md - adds a select area
- api/link/ui.filetable_addspan.md - adds colspan or rowspan to the datatable
- api/link/ui.filetable_adjust.md - adjusts the component to the size of the parent HTML container
- api/link/ui.filetable_adjustcolumn.md - adjusts a column to the width of the content
- api/link/ui.filetable_adjustrowheight.md - autodetect height of rows in datatable
- api/link/ui.filetable_attachevent.md - attaches the handler to an inner event of the component (allows behaviour customizations)
- api/link/ui.filetable_bind.md - binds components
- api/link/ui.filetable_blockevent.md - temporarily blocks triggering of ALL events of the calling object
- api/link/ui.filetable_callevent.md - calls an inner event
- api/link/ui.filetable_clearall.md - removes all items from the component
- api/link/ui.filetable_clearcss.md - removes css class from all items
- api/link/ui.filetable_clearvalidation.md - removes all validation marks from the component
- api/link/ui.filetable_closesub.md - closes subrow or subview for an item with the given id
- api/link/ui.filetable_collectvalues.md - returns an array of unique values of the specified column
- api/link/ui.filetable_columnid.md - returns the id of the column at the specified index
- api/link/ui.filetable_copy.md - copies an item to the same or another object
- api/link/ui.filetable_count.md - returns the number of currently visible items
- api/link/ui.filetable_define.md - redefines a single configuration property (or a hash of properties)
- api/link/ui.filetable_destructor.md - destructs the calling object
- api/link/ui.filetable_detachevent.md - detaches a handler from an event (which was attached before by the attachEvent method)
- api/link/ui.filetable_disable.md - disables the calling view (makes it dimmed and unclickable)
- api/link/ui.filetable_eachcolumn.md - iterates over all visible columns in the table
- api/link/ui.filetable_eachrow.md - iterates over all rows in the table
- api/link/ui.filetable_edit.md - enables the edit mode for the specified item
- api/link/ui.filetable_editcancel.md - cancels the edit mode and closes all opened editors. The component is still editable
- api/link/ui.filetable_editcell.md - enables the edit mode for the specified cell
- api/link/ui.filetable_editcolumn.md - enables the edit mode for the specified column
- api/link/ui.filetable_editnext.md - closes the current editor and opens one in the next cell of the row
- api/link/ui.filetable_editrow.md - enables the edit mode for the specified row
- api/link/ui.filetable_editstop.md - stops the edit mode and closes all opened editors. The component is still editable
- api/link/ui.filetable_enable.md - enables the calling view that was disabled by the 'disable' method
- api/link/ui.filetable_exists.md - checks whether an item with the specified id exists
- api/link/ui.filetable_filter.md - filters the component
- api/link/ui.filetable_filterbyall.md - refilters DataTable by all specified filters
- api/link/ui.filetable_find.md - returns rows that match the criterion
- api/link/ui.filetable_focuseditor.md - moves focus to the active editor
- api/link/ui.filetable_freezerow.md - fixes a row at the top of the datatable "on the fly"
- api/link/ui.filetable_getallselectareas.md - returns an object that contains configuration objects of all select areas in the datatable
- api/link/ui.filetable_getchildviews.md - returns child views of the calling component
- api/link/ui.filetable_getcolumnconfig.md - returns the configuration object of the specified column
- api/link/ui.filetable_getcolumnindex.md - returns the index of the column with the specified id
- api/link/ui.filetable_geteditstate.md - returns info about active editor object
- api/link/ui.filetable_geteditor.md - returns editor object
- api/link/ui.filetable_geteditorvalue.md - returns the value of the active (currently open) editor
- api/link/ui.filetable_getfilter.md - returns the filter object that the component uses to filter the values of the specified column
- api/link/ui.filetable_getfirstid.md - returns the ID of the first item
- api/link/ui.filetable_getformview.md - returns master form for the input
- api/link/ui.filetable_getheadercontent.md - returns set of helpers for header content manipulation
- api/link/ui.filetable_getheadernode.md - returns HTML element of the column's header
- api/link/ui.filetable_getidbyindex.md - returns the id of the item with the specified index
- api/link/ui.filetable_getindexbyid.md - returns the index of the item with the specified id
- api/link/ui.filetable_getitem.md - gets the object of the data item with the specified id
- api/link/ui.filetable_getitemnode.md - returns HTML element of the item
- api/link/ui.filetable_getlastid.md - returns the id of the last item
- api/link/ui.filetable_getnextid.md - returns the ID of an item which is positioned the specified step after the specified item
- api/link/ui.filetable_getnode.md - returns the main HTML container for the calling object
- api/link/ui.filetable_getpage.md - returns the currently visible page in case of paged view
- api/link/ui.filetable_getpager.md - returns the pager object associated with the component
- api/link/ui.filetable_getparentview.md - returns the parent view of the component
- api/link/ui.filetable_getprevid.md - returns the ID of an item which is positioned the specified step before the specified item
- api/link/ui.filetable_getscrollstate.md - returns the current position of scrolls
- api/link/ui.filetable_getselectarea.md - returns the object of the select area
- api/link/ui.filetable_getselectedid.md - returns the selected elements' ids
- api/link/ui.filetable_getselecteditem.md - gets an object of the selected data item
- api/link/ui.filetable_getspan.md - returns the config array for a span or null, if there are no spans
- api/link/ui.filetable_getstate.md - returns the current state of the view
- api/link/ui.filetable_getsubview.md - returns subview of the item with the given id
- api/link/ui.filetable_gettext.md - returns text value of a cell
- api/link/ui.filetable_gettopparentview.md - returns top parent view
- api/link/ui.filetable_getvisiblecount.md - returns count of visible rows
- api/link/ui.filetable_group.md - groups data by the specified data property
- api/link/ui.filetable_hascss.md - checks if item has specific css class
- api/link/ui.filetable_hasevent.md - checks whether the component has the specified event
- api/link/ui.filetable_hide.md - hides the view
- api/link/ui.filetable_hidecolumn.md - hides the specified column
- api/link/ui.filetable_hideoverlay.md - hides previously defined overlay
- api/link/ui.filetable_iscolumnvisible.md - returns true if column is visible
- api/link/ui.filetable_isenabled.md - checks whether the view is enabled
- api/link/ui.filetable_isvisible.md - checks whether the view is visible
- api/link/ui.filetable_load.md - loads data from an external data source.
- api/link/ui.filetable_loadnext.md - sends a request to load the specified number of records to the end of the clientside dataset or to the specified position
- api/link/ui.filetable_locate.md - converts an HTML node or event object to in-table position
- api/link/ui.filetable_mapcells.md - applies the callback to a range of cells
- api/link/ui.filetable_mapevent.md - routes events from one object to another
- api/link/ui.filetable_marksorting.md - marks the sorted column with a dedicated sign (asc/desc) in the header
- api/link/ui.filetable_move.md - moves the specified item to a new position
- api/link/ui.filetable_movebottom.md - moves the specified item to the last position
- api/link/ui.filetable_movecolumn.md - moves column to different position
- api/link/ui.filetable_movedown.md - increases the item index and moves the item to the new position
- api/link/ui.filetable_moveselection.md - moves selection in the specified direction
- api/link/ui.filetable_movetop.md - moves the specified item to the first position
- api/link/ui.filetable_moveup.md - decreases the item index and moves the item to the new position
- api/link/ui.filetable_opensub.md - opens subrow or subview for an item with the given id
- api/link/ui.filetable_parse.md - loads data to the component from an inline data source
- api/link/ui.filetable_refresh.md - repaints the whole view or a certain item
- api/link/ui.filetable_refreshcolumns.md - refreshes the structure of DataTable
- api/link/ui.filetable_refreshfilter.md - rebuilds list of options in select filter
- api/link/ui.filetable_refreshheadercontent.md - refreshes the header row of DataTable
- api/link/ui.filetable_registerfilter.md - registers a filter element
- api/link/ui.filetable_remove.md - removes the specified item/items from datastore
- api/link/ui.filetable_removecellcss.md - remove css class from the cell of datatable
- api/link/ui.filetable_removecss.md - removes CSS class from a component item
- api/link/ui.filetable_removerowcss.md - remove css class from the row
- api/link/ui.filetable_removeselectarea.md - removes a select area
- api/link/ui.filetable_removespan.md - removes a rowspan/colspan from the datatable
- api/link/ui.filetable_render.md - renders the specified item or the whole component
- api/link/ui.filetable_resize.md - adjusts the view to a new size
- api/link/ui.filetable_resizesubview.md - adjusts the row's size to the size of a subview
- api/link/ui.filetable_scrollto.md - scrolls the view to the defined position
- api/link/ui.filetable_serialize.md - serializes data to a JSON object
- api/link/ui.filetable_setcolumnwidth.md - sets the width of the specified column
- api/link/ui.filetable_setpage.md - makes the specified page visible (assuming that the pager was defined )
- api/link/ui.filetable_setrowheight.md - sets the height of the specified row
- api/link/ui.filetable_setstate.md - restores the specified state
- api/link/ui.filetable_show.md - makes the component visible
- api/link/ui.filetable_showcell.md - scrolls the table (if needed) to make the specified cell visible
- api/link/ui.filetable_showcolumn.md - shows the column which was previously hidden by method 'hidecolumn'
- api/link/ui.filetable_showcolumnbatch.md - shows or hides a group of columns
- api/link/ui.filetable_showitem.md - 'scrolls' the table to make the specified row visible
- api/link/ui.filetable_showitembyindex.md - 'scrolls' the table to make the specified row visible
- api/link/ui.filetable_showoverlay.md - shows the overlay message over the body of DataTable
- api/link/ui.filetable_sort.md - sorts datastore
- api/link/ui.filetable_sync.md - allows syncing two copies of data (all or just a part of it) from one DataCollection to another
- api/link/ui.filetable_unbind.md - breaks "bind" link
- api/link/ui.filetable_unblockevent.md - cancels blocking events that was enabled by the 'blockEvent' command
- api/link/ui.filetable_ungroup.md - ungroups data
- api/link/ui.filetable_updateitem.md - sets properties of the data item
- api/link/ui.filetable_validate.md - validates one record or all dataset against validation rules
- api/link/ui.filetable_validateeditor.md - validates data in currently active editor
}}

@index:
- api/link/ui.filetable_add.md
- api/link/ui.filetable_addcellcss.md
- api/link/ui.filetable_addcss.md
- api/link/ui.filetable_addrowcss.md
- api/link/ui.filetable_addselectarea.md
- api/link/ui.filetable_addspan.md
- api/link/ui.filetable_adjust.md
- api/link/ui.filetable_adjustcolumn.md
- api/link/ui.filetable_adjustrowheight.md
- api/link/ui.filetable_attachevent.md
- api/link/ui.filetable_bind.md
- api/link/ui.filetable_blockevent.md
- api/link/ui.filetable_callevent.md
- api/link/ui.filetable_clearall.md
- api/link/ui.filetable_clearcss.md
- api/link/ui.filetable_clearvalidation.md
- api/link/ui.filetable_closesub.md
- api/link/ui.filetable_collectvalues.md
- api/link/ui.filetable_columnid.md
- api/link/ui.filetable_copy.md
- api/link/ui.filetable_count.md
- api/link/ui.filetable_define.md
- api/link/ui.filetable_destructor.md
- api/link/ui.filetable_detachevent.md
- api/link/ui.filetable_disable.md
- api/link/ui.filetable_eachcolumn.md
- api/link/ui.filetable_eachrow.md
- api/link/ui.filetable_edit.md
- api/link/ui.filetable_editcancel.md
- api/link/ui.filetable_editcell.md
- api/link/ui.filetable_editcolumn.md
- api/link/ui.filetable_editnext.md
- api/link/ui.filetable_editrow.md
- api/link/ui.filetable_editstop.md
- api/link/ui.filetable_enable.md
- api/link/ui.filetable_exists.md
- api/link/ui.filetable_filter.md
- api/link/ui.filetable_filterbyall.md
- api/link/ui.filetable_find.md
- api/link/ui.filetable_focuseditor.md
- api/link/ui.filetable_freezerow.md
- api/link/ui.filetable_getallselectareas.md
- api/link/ui.filetable_getchildviews.md
- api/link/ui.filetable_getcolumnconfig.md
- api/link/ui.filetable_getcolumnindex.md
- api/link/ui.filetable_geteditstate.md
- api/link/ui.filetable_geteditor.md
- api/link/ui.filetable_geteditorvalue.md
- api/link/ui.filetable_getfilter.md
- api/link/ui.filetable_getfirstid.md
- api/link/ui.filetable_getformview.md
- api/link/ui.filetable_getheadercontent.md
- api/link/ui.filetable_getheadernode.md
- api/link/ui.filetable_getidbyindex.md
- api/link/ui.filetable_getindexbyid.md
- api/link/ui.filetable_getitem.md
- api/link/ui.filetable_getitemnode.md
- api/link/ui.filetable_getlastid.md
- api/link/ui.filetable_getnextid.md
- api/link/ui.filetable_getnode.md
- api/link/ui.filetable_getpage.md
- api/link/ui.filetable_getpager.md
- api/link/ui.filetable_getparentview.md
- api/link/ui.filetable_getprevid.md
- api/link/ui.filetable_getscrollstate.md
- api/link/ui.filetable_getselectarea.md
- api/link/ui.filetable_getselectedid.md
- api/link/ui.filetable_getselecteditem.md
- api/link/ui.filetable_getspan.md
- api/link/ui.filetable_getstate.md
- api/link/ui.filetable_getsubview.md
- api/link/ui.filetable_gettext.md
- api/link/ui.filetable_gettopparentview.md
- api/link/ui.filetable_getvisiblecount.md
- api/link/ui.filetable_group.md
- api/link/ui.filetable_hascss.md
- api/link/ui.filetable_hasevent.md
- api/link/ui.filetable_hide.md
- api/link/ui.filetable_hidecolumn.md
- api/link/ui.filetable_hideoverlay.md
- api/link/ui.filetable_iscolumnvisible.md
- api/link/ui.filetable_isenabled.md
- api/link/ui.filetable_isvisible.md
- api/link/ui.filetable_load.md
- api/link/ui.filetable_loadnext.md
- api/link/ui.filetable_locate.md
- api/link/ui.filetable_mapcells.md
- api/link/ui.filetable_mapevent.md
- api/link/ui.filetable_marksorting.md
- api/link/ui.filetable_move.md
- api/link/ui.filetable_movebottom.md
- api/link/ui.filetable_movecolumn.md
- api/link/ui.filetable_movedown.md
- api/link/ui.filetable_moveselection.md
- api/link/ui.filetable_movetop.md
- api/link/ui.filetable_moveup.md
- api/link/ui.filetable_opensub.md
- api/link/ui.filetable_parse.md
- api/link/ui.filetable_refresh.md
- api/link/ui.filetable_refreshcolumns.md
- api/link/ui.filetable_refreshfilter.md
- api/link/ui.filetable_refreshheadercontent.md
- api/link/ui.filetable_registerfilter.md
- api/link/ui.filetable_remove.md
- api/link/ui.filetable_removecellcss.md
- api/link/ui.filetable_removecss.md
- api/link/ui.filetable_removerowcss.md
- api/link/ui.filetable_removeselectarea.md
- api/link/ui.filetable_removespan.md
- api/link/ui.filetable_render.md
- api/link/ui.filetable_resize.md
- api/link/ui.filetable_resizesubview.md
- api/link/ui.filetable_scrollto.md
- api/link/ui.filetable_serialize.md
- api/link/ui.filetable_setcolumnwidth.md
- api/link/ui.filetable_setpage.md
- api/link/ui.filetable_setrowheight.md
- api/link/ui.filetable_setstate.md
- api/link/ui.filetable_show.md
- api/link/ui.filetable_showcell.md
- api/link/ui.filetable_showcolumn.md
- api/link/ui.filetable_showcolumnbatch.md
- api/link/ui.filetable_showitem.md
- api/link/ui.filetable_showitembyindex.md
- api/link/ui.filetable_showoverlay.md
- api/link/ui.filetable_sort.md
- api/link/ui.filetable_sync.md
- api/link/ui.filetable_unbind.md
- api/link/ui.filetable_unblockevent.md
- api/link/ui.filetable_ungroup.md
- api/link/ui.filetable_updateitem.md
- api/link/ui.filetable_validate.md
- api/link/ui.filetable_validateeditor.md

