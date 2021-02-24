### 0.6.2
##### Bug Fixes
- Datagrid: Expandable row toggle affects the row selection state ([#109](https://github.com/karan-kang/blazority/issues/109))
- Datagrid: Inline combox and radiobox control do not receive click event (Refactored for stability) ([S#3](https://github.com/blazority/support/issues/#3))

### 0.6.1
##### Updates
- Datagrid: Auto inject column name (built using Title propery) as classes to cells for identification purposes
- Dropdown: Adding on click handler for ease of use

##### Bug Fixes
- Datagrid: Inline combox and radiobox control do not receive click event ([S#3](https://github.com/blazority/support/issues/#3))

### 0.6.0
##### Features
- Framework: Support for .NET 5 framework ([#103](https://github.com/karan-kang/blazority/issues/103))
- Dropdown: Adding new dropdown menu control [Dropdown](/dropdown) ([#9](https://github.com/karan-kang/blazority/issues/9))

##### Bug Fixes
- Datepicker: value binding not working ([#104](https://github.com/karan-kang/blazority/issues/104))
- Datagrid: SelectedItem cannot be unselected by setting the bound property to null ([S#2](https://github.com/blazority/support/issues/2))

### 0.5.0
##### Features
- Date picker: Adding new date picker control [Date Picker](/datepicker) ([#8](https://github.com/karan-kang/blazority/issues/8))
- Calendar: Adding new calendar control to support picking dates in embedded or inline mode [Calendar](/calendar) ([#8](https://github.com/karan-kang/blazority/issues/8))
- Range: Adding new range input control [Range](/range) ([#48](https://github.com/karan-kang/blazority/issues/48))
- Button group: Adding new button group component ([Button Group](/buttongroup)) ([#7](https://github.com/karan-kang/blazority/issues/7))

##### Bug Fixes
- Combobox: Selection via up/down arrow keys is not working ([#95](https://github.com/karan-kang/blazority/issues/95))
- Combobox: Showing 'no matches' when there should be some ([#94](https://github.com/karan-kang/blazority/issues/94))

##### Misc
- Theming improvements for up/down arrow keys for the number input control 
- Performance improvements to base CSS class and style mapping classes

### 0.4.24
##### Features
- Datagrid: Support for expandable rows ([Datagrid](/datagrid/expandable-rows)) ([#92](https://github.com/karan-kang/blazority/issues/92))

### 0.4.23
##### Features
- Combobox: Refactored core for stability improvements ([Combobox](/combobox))
- Combobox: Adding support for Editable mode, i.e. ability to add new item ([Editable Combobox](/combobox/editable))
- Combobox: Adding support for Complex item type ([Complex Item Combobox](/combobox/complex))

### 0.4.22
##### Features
- Datagrid: Sync selection behavior between control and row selection mode ([Datagrid](/datagrid/multi-selection)) ([#89](https://github.com/karan-kang/blazority/issues/89))

### 0.4.21
##### Features
- Datagrid: Added support for grouping ([Datagrid](/datagrid/grouping)) ([#84](https://github.com/karan-kang/blazority/issues/84))
##### Bug Fixes
- Datagrid: Column span for empty rows does not work n fixed table-layout mode ([#83](https://github.com/karan-kang/blazority/issues/83))

### 0.4.20
##### Bug Fixes
- Datagrid: Updated fix for pagination count mismatch during filtering ([#67](https://github.com/karan-kang/blazority/issues/67))

### 0.4.19
##### Bug Fixes
- Datagrid: Null values are not getting filtered by built-in filter logic ([#82](https://github.com/karan-kang/blazority/issues/82))

### 0.4.18
##### Features
- Datagrid: Added support for method expression bindings to column field parameter ([Datagrid](/datagrid/compact)) ([#77](https://github.com/karan-kang/blazority/issues/77))

##### Bug Fixes
- Combobox: Down chevron does not work  ([#78](https://github.com/karan-kang/blazority/issues/78))
- Combobox: Options stay filtered after selecting an option in multi select mode ([#80](https://github.com/karan-kang/blazority/issues/80))

### 0.4.17
##### Features
- Combobox: Ported combobox control with support for both standalone and form-based usage ([Combobox](/combobox))
- Checkbox: Ported checkbox control with support for both standalong and form-based usage ([Checkboxes](/checkboxes))
- Tree: Ported tree view control with support for vertical and horizontal trees ([Tree](/tree))
- Datagrid: Added support for clearing filters programatically ([Datagrid Filtering](/datagrid/filtering))

##### Bug Fixes
- Form Control: All controls in form report validation error if one is invalid ([#62](https://github.com/karan-kang/blazority/issues/62))
- Datagrid: User can select unselectable rows using Shift selection ([#61](https://github.com/karan-kang/blazority/issues/61))
- Datagrid: Placeholder image is not showing since v0.4.16 ([#64](https://github.com/karan-kang/blazority/issues/64))
- Datagrid: Unable to deselect previously selected row in single selection mode ([#65](https://github.com/karan-kang/blazority/issues/65))
- Datagrid: Pagination count does not update on filtering ([#67](https://github.com/karan-kang/blazority/issues/67))
- Datagrid: Select all during multi selection is selecting filtered rows ([#69](https://github.com/karan-kang/blazority/issues/69))

### 0.4.16
##### Features
- Datagrid: Support for fixed height with optional sticky header and/or footer  ([Fixed mode](/datagrid/fixed))
- Packaging: Providing minified CSS and JS files as part of generated package ([See updated getting started])(/getting-started) 

##### Bug Fixes
- Datagrid: Fixed an issue where selected item or items does not get clear when items are filtered ([#59](https://github.com/karan-kang/blazority/issues/59))
- Datagrid: Reduced top margin, and made it compatiable with Clarity styling
- Datagrid: Placeholder styling update to span across all columns when control based selection is enabled

### 0.4.15
##### Features
- Datagrid: Built in support for row selection without need for seperate column control ([Row Selection](/datagrid/row-selection))
- Datagrid: Ability to perform range selection using SHIFT key with checkbox selction ([Multi Selection](/datagrid/multi-selection))

##### Bug Fixes
- Fixing datagrid filtering does not work when filter template is used with child content  ([#56](https://github.com/karan-kang/blazority/issues/56))

##### Breaking Changes:
- Datagrid: RowClicked Event callback now provides access to MouseEventArgs and Row item data as custom object. Target developers should look at the revised 
usage at ([Basic Structure](/datagrid/structure))

### 0.4.14
##### Bug Fixes
- Fixing style issue for datagrid row selector column ([#55](https://github.com/karan-kang/blazority/issues/55))
- Fixing focus and input with action sizing

### 0.4.13
##### Features
- Added Form component with Vertical, Horizontal and Compact layouts
- Added Form control components: Text, Number, Password, Select, Textarea, Radio buttons
- Tree view: Support for master-detail view, and listening to node selection event via OnNodeSelect callback

### 0.4.12
##### Features
- Datagrid: Added support for compact code
- Datagrid: Added support for row click via RowClicked parameter
- Modal: Updates to support proper two way binding on Open parameter
- Tree view: Support for three modes: Basic, selection tree, dynamic tree using definition

##### Miscellaneous
- Refactoring to reduce clutter in core namespace 'Blazority'
- Updated Clarity and Clarity icons depdency to 4.0.6
- Updated custom-elements dependency to 1.4.3

##### Bug Fixes:
- Better fix for datagrid issue where Inline filters break column layout when used with single or multi selection  ([#27](https://github.com/karan-kang/blazority/issues/27))
- Fixing datagrid placeholder value not getting applied issue ([#32](https://github.com/karan-kang/blazority/issues/32))


### 0.4.11
##### Features
- Datalist: Added a bare implementation 'DatalistControl' for use without clarity form control
- Datagrid: Adding support for custom column header via HeaderTemplate

##### Bug Fixes:
- Fixes datagrid issue where Inline filters break column layout when used with single or multi selection  ([#27](https://github.com/karan-kang/blazority/issues/27))


### 0.4.10
##### Features
- Datagrid: Added ability to conditionally select rows in single and multi selection mode using CanSelect function parameter
- Datagrid: Added ability to conditionally apply CSS classes to rows using RowClass function parameter
- Datagrid: Added unique row identifier to generated rows

### 0.4.9
##### Features
- Added badges
- Added labels
- Datagrid: Added row hover style
- Datagrid: Added single and multi row selection support

##### Bug Fixes:
- Fixes datagrid column hover style for sortable columns ([#17](https://github.com/karan-kang/blazority/issues/17))

### 0.4.8
##### Features
- Added initial version of progress bar
- Added a datalist control
- Added spinner control

##### Bug Fixes:
- Fixes datagrid does not scroll with lot of columns ([#15](https://github.com/karan-kang/blazority/issues/15))

### 0.4.7
##### Features
- Card: Added support for Basic, Media Block, and Clickable cards

### 0.4.6
##### Features
- Datagrid: Added support for custom filter templates
- Datagrid: Autofocus improvements for floating filters

### 0.4.5
##### Bug Fixes:
- Fixing sorting and filtering functionality when item collection is changed ([#2](https://github.com/karan-kang/blazority/issues/2))

### 0.4.4
##### Features
- Datagrid: Added validation rule to detect invalid filter value and provide visual clues
- Datagrid: Added autofocus implementatio to column filter component
- Datagrid: Added support for custom filter placeholder via FilterPlaceholder parameter
- Misc: Added new blazority.js file which should be referenced in script imports, see getting started guide for details.

##### Breaking Changes:
- Changed path for blazority.css to _content/Blazority/blazority.css, see getting started guide for updates

### 0.4.3
- Datagrid: Added support for client side filtering
- Datagrid: Replaced and unified "Expression" and "SortBy" parameter to "Field" parameter

### 0.4.2
- Added support for loading butons
- Added demo for flat buttons

### 0.4.1
- Inital public version of Blazority based on Clarity v4.0.2
- Includes Accordion, Alerts, Button component
