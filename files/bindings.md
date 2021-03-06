### gdata-list-tree-bindings

binding | extends
--- | ---
gdata-list-tree | chrome://calendar/content/widgets/calendar-list-tree.xml#calendar-list-tree

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

### calendar-month-view-bindings

binding | extends
--- | ---
calendar-month-day-box-item | chrome://calendar/content/calendar-view-core.xml#calendar-editable-item
calendar-month-day-box | chrome://calendar/content/widgets/calendar-widgets.xml#dragndropContainer
calendar-month-base-view | chrome://calendar/content/calendar-base-view.xml#calendar-base-view

### calendar-menu-bindings

binding | extends
--- | ---
task-menupopup | does not extend any binding/element
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
attendees-list | chrome://messenger/content/richlistbox.xml#xbl-richlistbox
selection-bar | does not extend any binding/element

### calendar-event-dialog-freebusy.xml

binding | extends
--- | ---
scroll-container | does not extend any binding/element
freebusy-day | does not extend any binding/element
freebusy-row | does not extend any binding/element
freebusy-grid | chrome://messenger/content/richlistbox.xml#xbl-richlistbox

### calendar-invitations-list-bindings

binding | extends
--- | ---
calendar-invitations-richlistitem | chrome://global/content/bindings/richlistbox.xml#richlistitem

### calendar-core-view-bindings

binding | extends
--- | ---
calendar-editable-item | does not extend any binding/element
calendar-category-box | does not extend any binding/element

### calendar-item-bindings

binding | extends
--- | ---
item-date-row | does not extend any binding/element

### calendar-subscriptions-list-bindings

binding | extends
--- | ---
calendar-subscriptions-richlistitem | chrome://global/content/bindings/richlistbox.xml#richlistitem

### calendar-alarms

binding | extends
--- | ---
calendar-alarm-widget | chrome://global/content/bindings/richlistbox.xml#richlistitem
calendar-snooze-popup | does not extend any binding/element

### calendar-widgets

binding | extends
--- | ---
doubleimage-toolbarbutton | chrome://global/content/bindings/toolbarbutton.xml#toolbarbutton
todaypane-toolbarbutton | chrome://calendar/content/widgets/calendar-widgets.xml#doubleimage-toolbarbutton
modebox | does not extend any binding/element
dragndropContainer | does not extend any binding/element
view-tab | does not extend any binding/element

### xulMiniMonth

binding | extends
--- | ---
minimonth-header | does not extend any binding/element
minimonth | does not extend any binding/element

### calendar-list-tree-bindings

binding | extends
--- | ---
full-calendar-list-tree | #calendar-list-tree
calendar-list-tree | does not extend any binding/element

### calendar-multiday-view-bindings

binding | extends
--- | ---
calendar-base-view | does not extend any binding/element

### imTooltipBindings

binding | extends
--- | ---
tooltip | chrome://global/content/bindings/popup.xml#panel

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

### badgebuttonBindings

binding | extends
--- | ---
badgebutton | chrome://global/content/bindings/toolbarbutton.xml#toolbarbutton

### groupBindings

binding | extends
--- | ---
group | chrome://global/content/bindings/richlistbox.xml#richlistitem

### SearchBindings

binding | extends
--- | ---
glodaSearch | chrome://global/content/bindings/autocomplete.xml#autocomplete

### mailBindings

binding | extends
--- | ---
attachmentlist-base | chrome://messenger/content/richlistbox.xml#xbl-richlistbox
attachmentlist-horizontal | chrome://messenger/content/mailWidgets.xml#attachmentlist-base
attachmentlist-vertical | chrome://messenger/content/mailWidgets.xml#attachmentlist-base
attachmentitem | chrome://global/content/bindings/richlistbox.xml#richlistitem
mail-multi-emailHeaderField | does not extend any binding/element
search-menulist-abstract | does not extend any binding/element
searchattribute | chrome://messenger/content/mailWidgets.xml#search-menulist-abstract
searchoperator | chrome://messenger/content/mailWidgets.xml#search-menulist-abstract
searchvalue | does not extend any binding/element
popup-base | chrome://global/content/bindings/popup.xml#popup
splitmenu | does not extend any binding/element
appmenu-vertical | chrome://messenger/content/generalBindings.xml#menu-vertical
menuitem-iconic-desc-noaccel | chrome://global/content/bindings/menu.xml#menuitem

### tabmailBindings

binding | extends
--- | ---
tabmail | does not extend any binding/element
tabmail-tab | chrome://global/content/bindings/tabbox.xml#tab
tabmail-arrowscrollbox | chrome://global/content/bindings/scrollbox.xml#arrowscrollbox
tabmail-tabs | chrome://global/content/bindings/tabbox.xml#tabs
tabmail-alltabs-popup | chrome://global/content/bindings/popup.xml#popup
tabmail-close-tab-button | chrome://global/content/bindings/toolbarbutton.xml#toolbarbutton

### thunderbird-addon-bindings

binding | extends
--- | ---
thunderbird-addon-generic | chrome://mozapps/content/extensions/extensions.xml#addon-generic

### overlay-bindings

binding | extends
--- | ---
overlayTrigger | does not extend any binding/element

### menubuttonBindings

binding | extends
--- | ---
menu-button-base | chrome://global/content/bindings/button.xml#button-base
menu-button | chrome://messenger/content/menubutton.xml#menu-button-base

### notificationboxBindings

binding | extends
--- | ---
notificationbox | does not extend any binding/element
notification | does not extend any binding/element

### toolbarBindings

binding | extends
--- | ---
toolbox | does not extend any binding/element
toolbar | does not extend any binding/element
toolbar-menubar-autohide | chrome://communicator/content/bindings/toolbar.xml#toolbar
menubar | does not extend any binding/element
toolbarpaletteitem | does not extend any binding/element
toolbarpaletteitem-palette | chrome://communicator/content/bindings/toolbar.xml#toolbarpaletteitem
toolbarpaletteitem-palette-wrapping-label | chrome://communicator/content/bindings/toolbar.xml#toolbarpaletteitem
menu-button | chrome://global/content/bindings/button.xml#button-base

### generalBindings

binding | extends
--- | ---
menu-vertical | chrome://global/content/bindings/toolbarbutton.xml#toolbarbutton

### richlistboxBindings

binding | extends
--- | ---
xbl-richlistbox | chrome://global/content/bindings/general.xml#basecontrol

### addrbookBindings

binding | extends
--- | ---
addrbooks-menupopup | chrome://global/content/bindings/popup.xml#popup
map-list | chrome://global/content/bindings/popup.xml#popup

### autocompleteBindings

binding | extends
--- | ---
glodacomplete-rich-result-popup | chrome://global/content/bindings/autocomplete.xml#autocomplete-rich-result-popup

### mailFolderBindings

binding | extends
--- | ---
folder-menupopup | chrome://global/content/bindings/popup.xml#popup

### filterBindings

binding | extends
--- | ---
ruleactiontype-menulist | does not extend any binding/element
filterlistitem | chrome://global/content/bindings/richlistbox.xml#richlistitem
ruleaction | #filterlistitem
