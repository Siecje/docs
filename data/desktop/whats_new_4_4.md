Version 4.4
======================

<span class="release_date">released on June 27, 2017</span>

Breaking Changes
---------

To avoid ambiguity, Google-map  has been completely removed from the [Components repository](https://github.com/webix-hub/components), 
but its [advanced version](desktop/googlemap.md) stays in package and is available in both GPL and PRO editions.  

New Features 
---------

- [webix.print() API](desktop/printing.md) for smart printing of widgets
- [Query Builder](desktop/query_builder.md) widget for data source configuration and filtering
- [Samples on interaction with the server side](desktop/serverside.md#examplesofintegrationwithserversideplatforms) for PHP, Node.js and .Net platforms
- [serverMultiComboFilter](datatable/filtering.md#servermulticombo) for Datatable

Updates
---------

- ability to [use relative elements in abslayout](desktop/absolute_layout.md#usingrelativeelementsinabsolutelayout)
- ability to [define disabled items in menu from JSON](desktop/menu.md#disable_item)
- [templateCopy](api/link/ui.datatable_templatecopy_config.md) for Datatable and Treetable
- [scale and origin options](datatable/sparklines.md#customizingsparklines) for Datatable "line" and "bar" sparklines
- auto-detection of the sorting mode for options based on their data in [Datatable filters](datatable/filtering.md)
- ["raw" sorting](desktop/filter_sort.md#sorting) mode
- [getRaw](api/storage.cookie_getraw.md) method for cookie storage
- [addView()](api/ui.carousel_addview.md) and [removeView()](api/ui.carousel_addview.md) methods for Carousel
- [webix.history.track](desktop/history_track.md#disablinghistorytracking) can be disabled
- Datatable's [adjustRowHeight()](api/ui.datatable_adjustrowheight.md) can adjust the row to the highest cell if column id is not specified
- ability to create [rejected](api/promise_reject.md) and [resolved](api/promise_resolve.md) promises with webix.promise interface
- advanced settings for exporting hierarchical components to [Excel](desktop/data_components_export.md#customizingexporttoexcel) 
and [CSV](desktop/export_csv.md#customizingexporttocsv)
- extended touch auto-detection and enhancements for Datatable and Treetable on touch devices

Fixes
---------

- changeId for top items in the Tree sometimes doesn't work
- parsing date from %c format
- using setColumnWidths against a hidden column in DataTable
- %c options in date conversion break for dates with timezone info
- webix.extend ignores false values
- active content destruction from click handler
- preventing extra click events in Uploader
- selecting not loaded yet records in the Datatable
- regression in dynamic loading during scrolling
- Datatable onBefore/AfterUnSelect events fire only for CTRL+click unselecting
- Datatable colspan in footer and columnGroup in header result in crash on collapsing
- Multicombo getText returns empty data
- Datatable with editMath: editor opens the formula only once
- prevent from an attempt to locate item in a destructed view
- Google-map: prevent from multiple including of api files into the document
- Tooltip does not fit into screen size
- Window with fixed header width
- asynchronous data with richSelectFilter and column fillspace in Datatable
- hidden series in Chart preserve active areas
- soft clearAll for TreeStore and Google-map
- Portlet inside Scrollview
- animate:false in Carousel view
- get formatted date for ExcelViewer instead of raw number
- Datatable scroll position after hiding columns on touch devices
- Datatable scroll with rowspan and leftsplit on touch devices 
- clearing Colorboard value does not work
- check for readonly options in plain HTML input as suggest master
- Datatable activeContent: calling locate() returns null
- grouped columns In Datatable: expanding also triggers sorting in the first column
- Form Input can display validation messages
- locate dragged item over empty area
- drag-n-drop fails when mouse leaves document body
- loading subviews using Webix Jet menu on touch devices
- incorrect auto-loading calls for datatable with custom row height
- dynamic loading may ignore second call for the same data range
- add tag when separator is entered in Multicombo input
- deleting tags on Backspace in Multicombo 
- keepText property lets the data stay in input with newValues enabled in Multicombo
- hide columns in a fully x-scrolled Datatable
- i18n translation for Calendar and Richtext
- toggle's ambiguity with string values
- returning false from onBeforeLoad doesn't prevent loading data
- encoding fix in CSV export
- text controls should display numeric 0 value
- regression in built-in editors on touch devices
- Datatable subrows  cause row rendering issue during scrolling
- readonly Combo: keydown invokes a suggest popup
- incorrect escape template in strict mode
- overflow CSS for modal Window
- Datatable shift+key multiselection fails in case of string row ids
- text of header menu items for grouped columns in Datatable
- bar-sparklines with origin lesser than values
- correct scroll after column size changing in Datatable
- remove space prefix for CSV export of hierarchical components
- saving state for Datatable with fillspace
- duplicate generation of the empty option for richSelectFilter with custom options
- loadBranch method ignores url parameter
- CSV export regression: the output file has two header lines
- Sidemenu positioning: wrong padding value
- call to a non-existent $init method in Select filter
- style for editable Datepicker as a filter

