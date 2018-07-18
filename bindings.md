### lightning-widgets

binding | extends
--- | ---
lightning-notification-bar | xul:hbox

### gdata-list-tree-bindings

binding | extends
--- | ---
gdata-list-tree | chrome://calendar/content/widgets/calendar-list-tree.xml#calendar-list-tree

### xulDatePicker

binding | extends
--- | ---
panellist | chrome://global/content/bindings/menulist.xml#menulist-editable
datetextpicker | chrome://calendar/content/datetimepickers/datetimepickers.xml#datetimepicker-base
datepicker | chrome://calendar/content/datetimepickers/datetimepickers.xml#datetimepicker-base
datepicker-forever | chrome://calendar/content/datetimepickers/datetimepickers.xml#datepicker
timepicker | chrome://calendar/content/datetimepickers/datetimepickers.xml#datetimepicker-base
timepicker-hour | does not extend any binding/element
timepicker-minute | does not extend any binding/element
timepicker-grids | xul:box
datetimepicker | chrome://calendar/content/datetimepickers/datetimepickers.xml#datetimepicker-base
datetimepicker-base | chrome://global/content/bindings/general.xml#basecontrol

### calendar-task-tree-bindings

binding | extends
--- | ---
calendar-task-tree | does not extend any binding/element
calendar-task-tree-todaypane | chrome://calendar/content/calendar-task-tree.xml#calendar-task-tree

### calendar-specific-view-bindings

binding | extends
--- | ---
calendar-day-view | chrome://calendar/content/calendar-multiday-view.xml#calendar-multiday-view
calendar-week-view | chrome://calendar/content/calendar-multiday-view.xml#calendar-multiday-view
calendar-multiweek-view | chrome://calendar/content/calendar-month-view.xml#calendar-month-base-view
calendar-month-view | chrome://calendar/content/calendar-month-view.xml#calendar-month-base-view

### calendar-multiday-view-bindings

binding | extends
--- | ---
calendar-time-bar | does not extend any binding/element
calendar-event-gripbar | does not extend any binding/element
calendar-event-column | does not extend any binding/element
calendar-header-container | chrome://calendar/content/widgets/calendar-widgets.xml#dragndropContainer
calendar-event-box | chrome://calendar/content/calendar-view-core.xml#calendar-editable-item
calendar-multiday-view | chrome://calendar/content/calendar-base-view.xml#calendar-base-view

### calendar-daypicker.xml

binding | extends
--- | ---
daypicker | chrome://global/content/bindings/button.xml#button-base
daypicker-weekday | xul:box
daypicker-monthday | xul:box

### calendar-month-view-bindings

binding | extends
--- | ---
calendar-month-day-box-item | chrome://calendar/content/calendar-view-core.xml#calendar-editable-item
calendar-month-day-box | chrome://calendar/content/widgets/calendar-widgets.xml#dragndropContainer
calendar-month-base-view | chrome://calendar/content/calendar-base-view.xml#calendar-base-view

### calendar-menu-bindings

binding | extends
--- | ---
task-menupopup | xul:menupopup
task-progress-menupopup | chrome://calendar/content/calendar-menus.xml#task-menupopup
task-priority-menupopup | chrome://calendar/content/calendar-menus.xml#task-menupopup

### agenda-list-bindings

binding | extends
--- | ---
agenda-base-richlist-item | chrome://global/content/bindings/richlistbox.xml#richlistitem
agenda-checkbox-richlist-item | chrome://global/content/bindings/richlistbox.xml#richlistitem
agenda-allday-richlist-item | chrome://calendar/content/agenda-listbox.xml#agenda-base-richlist-item
agenda-richlist-item | chrome://calendar/content/agenda-listbox.xml#agenda-base-richlist-item

### calendar-event-dialog-attendees.xml

binding | extends
--- | ---
attendees-list | does not extend any binding/element
selection-bar | does not extend any binding/element

### calendar-event-dialog-recurrence-preview.xml

binding | extends
--- | ---
recurrence-preview | xul:box

### calendar-event-dialog-freebusy.xml

binding | extends
--- | ---
scroll-container | xul:box
freebusy-day | xul:box
freebusy-timebar | xul:box
freebusy-row | xul:box
freebusy-grid | does not extend any binding/element

### calendar-invitations-list-bindings

binding | extends
--- | ---
calendar-invitations-richlistbox | chrome://global/content/bindings/richlistbox.xml#richlistbox
calendar-invitations-richlistitem | chrome://global/content/bindings/richlistbox.xml#richlistitem

### calendar-core-view-bindings

binding | extends
--- | ---
calendar-editable-item | does not extend any binding/element
calendar-category-box | does not extend any binding/element

### calendar-item-bindings

binding | extends
--- | ---
calendar-caption | xul:hbox
item-date-row | xul:row

### calendar-subscriptions-list-bindings

binding | extends
--- | ---
calendar-subscriptions-richlistbox | chrome://global/content/bindings/richlistbox.xml#richlistbox
calendar-subscriptions-richlistitem | chrome://global/content/bindings/richlistbox.xml#richlistitem

### calendar-alarms

binding | extends
--- | ---
calendar-alarm-widget | chrome://global/content/bindings/richlistbox.xml#richlistitem
calendar-snooze-popup | does not extend any binding/element

### calendar-widgets

binding | extends
--- | ---
panel-menulist | chrome://global/content/bindings/menulist.xml#menulist
category-panel | chrome://global/content/bindings/popup.xml#panel
doubleimage-toolbarbutton | chrome://global/content/bindings/toolbarbutton.xml#toolbarbutton
todaypane-toolbarbutton | chrome://calendar/content/widgets/calendar-widgets.xml#doubleimage-toolbarbutton
treenode-checkbox | chrome://global/content/bindings/checkbox.xml#checkbox
modevbox | chrome://calendar/content/widgets/calendar-widgets.xml#modebox
modehbox | chrome://calendar/content/widgets/calendar-widgets.xml#modebox
modebox | xul:box
dragndropContainer | does not extend any binding/element
view-tab | chrome://global/content/bindings/tabbox.xml#tab

### xulMiniMonth

binding | extends
--- | ---
minimonth-header | xul:box
active-minimonth-header | chrome://calendar/content/widgets/minimonth.xml#minimonth-header
minimonth | xul:box

### calendar-list-tree-bindings

binding | extends
--- | ---
full-calendar-list-tree | #calendar-list-tree
calendar-list-tree | does not extend any binding/element

### calendar-multiday-view-bindings

binding | extends
--- | ---
calendar-base-view | does not extend any binding/element
calendar-day-label | xul:box

### accountBindings

binding | extends
--- | ---
account | chrome://global/content/bindings/richlistbox.xml#richlistitem
buttons | xul:hbox
nobuttons | xul:hbox

### imTooltipBindings

binding | extends
--- | ---
tooltip | chrome://global/content/bindings/popup.xml#tooltip

### browserBindings

binding | extends
--- | ---
browser | does not extend any binding/element

### preferencesBindings

binding | extends
--- | ---
preftab | chrome://messenger/content/preferences/preferences.xml#prefwindow

### handlerBindings

binding | extends
--- | ---
handler | chrome://global/content/bindings/richlistbox.xml#richlistitem

### activityBindings

binding | extends
--- | ---
activity-group | chrome://global/content/bindings/richlistbox.xml#richlistitem
activity-base | chrome://global/content/bindings/richlistbox.xml#richlistitem
activity-process | chrome://messenger/content/activity.xml#activity-base
activity-event | chrome://messenger/content/activity.xml#activity-base
activity-warning | chrome://messenger/content/activity.xml#activity-base

### contactBindings

binding | extends
--- | ---
contact | chrome://global/content/bindings/richlistbox.xml#richlistitem

### convBindings

binding | extends
--- | ---
conv | chrome://global/content/bindings/richlistbox.xml#richlistitem

### conversationBindings

binding | extends
--- | ---
conversation | does not extend any binding/element
conv-info-large | chrome://messenger/content/toolbar.xml#toolbar

### badgebuttonBindings

binding | extends
--- | ---
badgebutton | chrome://global/content/bindings/toolbarbutton.xml#toolbarbutton

### groupBindings

binding | extends
--- | ---
group | chrome://global/content/bindings/richlistbox.xml#richlistitem

### downloadBindings

binding | extends
--- | ---
download | chrome://global/content/bindings/richlistbox.xml#richlistitem

### SearchBindings

binding | extends
--- | ---
glodaSearch | chrome://global/content/bindings/autocomplete.xml#autocomplete
searchBarDropMarker | does not extend any binding/element

### threadPaneColumnPickerBindings

binding | extends
--- | ---
threadPaneColumnPicker | chrome://global/content/bindings/tree.xml#tree-base

### glodaFacetBindings

binding | extends
--- | ---
query-explanation | does not extend any binding/element
facets | does not extend any binding/element
facet-base | does not extend any binding/element
facet-boolean | chrome://messenger/content/glodaFacetBindings.xml#facet-base
facet-boolean-filtered | chrome://messenger/content/glodaFacetBindings.xml#facet-boolean
popup-menu | does not extend any binding/element
facet-discrete | does not extend any binding/element
facet-date | does not extend any binding/element
results-message | does not extend any binding/element
result-message | does not extend any binding/element

### mailBindings

binding | extends
--- | ---
dummy | xul:box
attachmentlist-base | chrome://global/content/bindings/listbox.xml#listbox-base
attachmentlist-horizontal | chrome://messenger/content/mailWidgets.xml#attachmentlist-base
attachmentlist-vertical | chrome://messenger/content/mailWidgets.xml#attachmentlist-base
attachmentitem | chrome://global/content/bindings/listbox.xml#listitem
mail-toggle-headerfield | does not extend any binding/element
mail-headerfield | does not extend any binding/element
mail-urlfield | chrome://messenger/content/mailWidgets.xml#mail-headerfield
mail-emailheaderfield | does not extend any binding/element
mail-multi-emailHeaderField | does not extend any binding/element
mail-emailaddress | does not extend any binding/element
mail-newsgroup | does not extend any binding/element
mail-newsgroups-headerfield | does not extend any binding/element
mail-messageids-headerfield | does not extend any binding/element
mail-messageid | does not extend any binding/element
mail-headerfield-tags | does not extend any binding/element
search-menulist-abstract | xul:box
searchattribute | chrome://messenger/content/mailWidgets.xml#search-menulist-abstract
searchoperator | chrome://messenger/content/mailWidgets.xml#search-menulist-abstract
searchvalue | does not extend any binding/element
popup-base | chrome://global/content/bindings/popup.xml#popup
folderSummary-popup | chrome://global/content/bindings/popup.xml#tooltip
folderSummary | does not extend any binding/element
folderSummary-location | does not extend any binding/element
folderSummary-subfoldersSummary | does not extend any binding/element
folderSummary-message | does not extend any binding/element
splitmenu | does not extend any binding/element
appmenu-vertical | chrome://messenger/content/generalBindings.xml#menu-vertical
menulist-description | chrome://global/content/bindings/menulist.xml#menulist
menuitem-iconic-desc-noaccel | chrome://global/content/bindings/menu.xml#menuitem

### tabmailBindings

binding | extends
--- | ---
tabmail | does not extend any binding/element
tabmail-tab | chrome://global/content/bindings/tabbox.xml#tab
tabmail-tabbox | chrome://global/content/bindings/tabbox.xml#tabbox
tabmail-arrowscrollbox | chrome://global/content/bindings/scrollbox.xml#arrowscrollbox-clicktoscroll
tabmail-tabs | chrome://global/content/bindings/tabbox.xml#tabs
tabmail-alltabs-popup | chrome://global/content/bindings/popup.xml#popup
tabmail-close-tab-button | chrome://global/content/bindings/toolbarbutton.xml#toolbarbutton
statuspanel | does not extend any binding/element

### listboxBindings

binding | extends
--- | ---
listitem-iconic | chrome://global/content/bindings/listbox.xml#listitem
listcell-iconic | chrome://global/content/bindings/listbox.xml#listcell

### textboxBindings

binding | extends
--- | ---
textbox | xul:box

### numberboxBindings

binding | extends
--- | ---
numberbox | chrome://messenger/content/textbox.xml#textbox

### spinbuttonsBindings

binding | extends
--- | ---
spinbuttons | chrome://global/content/bindings/general.xml#basecontrol

### timepickerBindings

binding | extends
--- | ---
datetimepicker-base | chrome://global/content/bindings/general.xml#basecontrol
timepicker | chrome://communicator/content/bindings/datetimepicker.xml#datetimepicker-base
datepicker | chrome://communicator/content/bindings/datetimepicker.xml#datetimepicker-base
datepicker-grid | chrome://communicator/content/bindings/datetimepicker.xml#datepicker
datepicker-popup | chrome://communicator/content/bindings/datetimepicker.xml#datepicker

### toolbarBindings

binding | extends
--- | ---
toolbar-base | does not extend any binding/element
toolbox | chrome://communicator/content/bindings/toolbar.xml#toolbar-base
toolbar | chrome://communicator/content/bindings/toolbar.xml#toolbar-base
toolbar-menubar-autohide | chrome://communicator/content/bindings/toolbar.xml#toolbar
toolbar-drag | chrome://communicator/content/bindings/toolbar.xml#toolbar
menubar | chrome://communicator/content/bindings/toolbar.xml#toolbar-base
toolbardecoration | chrome://communicator/content/bindings/toolbar.xml#toolbar-base
toolbarpaletteitem | chrome://communicator/content/bindings/toolbar.xml#toolbar-base
toolbarpaletteitem-palette | chrome://communicator/content/bindings/toolbar.xml#toolbarpaletteitem
toolbarpaletteitem-palette-wrapping-label | chrome://communicator/content/bindings/toolbar.xml#toolbarpaletteitem
menu-button | chrome://global/content/bindings/button.xml#menu-button-base

### generalBindings

binding | extends
--- | ---
statusbar | does not extend any binding/element
statusbarpanel | does not extend any binding/element
dialogheader | does not extend any binding/element
menu-vertical | chrome://global/content/bindings/toolbarbutton.xml#toolbarbutton

### preferencesBindings

binding | extends
--- | ---
preferences | does not extend any binding/element
preference | does not extend any binding/element
prefwindow | chrome://global/content/bindings/dialog.xml#dialog
prefpane | does not extend any binding/element
panebutton | chrome://global/content/bindings/radio.xml#radio

### menulistCompactBindings

binding | extends
--- | ---
menulist-compact | chrome://global/content/bindings/menulist.xml#menulist

### addrbookBindings

binding | extends
--- | ---
addrbooks-menupopup | chrome://global/content/bindings/popup.xml#popup
map-list | chrome://global/content/bindings/popup.xml#popup

### autocompleteBindings

binding | extends
--- | ---
glodacomplete-rich-result-popup | chrome://global/content/bindings/autocomplete.xml#autocomplete-rich-result-popup
glodacomplete-base-richlistitem | chrome://global/content/bindings/richlistbox.xml#richlistitem
gloda-single-tag-item | chrome://gloda/content/glodacomplete.xml#glodacomplete-base-richlistitem
gloda-fulltext-single-item | chrome://gloda/content/glodacomplete.xml#glodacomplete-base-richlistitem
gloda-fulltext-all-item | chrome://gloda/content/glodacomplete.xml#glodacomplete-base-richlistitem
gloda-single-identity-item | chrome://gloda/content/glodacomplete.xml#glodacomplete-base-richlistitem
gloda-contact-chunk | chrome://gloda/content/glodacomplete.xml#glodacomplete-base-richlistitem
gloda-multi-item | chrome://gloda/content/glodacomplete.xml#glodacomplete-base-richlistitem

### charsetListBinding

binding | extends
--- | ---
charsetpicker | chrome://global/content/bindings/menulist.xml#menulist

### mailFolderBindings

binding | extends
--- | ---
folder-menupopup | chrome://global/content/bindings/popup.xml#popup

### filterBindings

binding | extends
--- | ---
ruleactiontype-menulist | does not extend any binding/element
listitem | does not extend any binding/element
ruleaction | #listitem
ruleactiontarget-base | does not extend any binding/element
ruleactiontarget-tag | chrome://messenger/content/searchWidgets.xml#ruleactiontarget-base
ruleactiontarget-priority | chrome://messenger/content/searchWidgets.xml#ruleactiontarget-base
ruleactiontarget-junkscore | chrome://messenger/content/searchWidgets.xml#ruleactiontarget-base
ruleactiontarget-replyto | chrome://messenger/content/searchWidgets.xml#ruleactiontarget-base
ruleactiontarget-forwardto | chrome://messenger/content/searchWidgets.xml#ruleactiontarget-base
ruleactiontarget-folder | chrome://messenger/content/searchWidgets.xml#ruleactiontarget-base