# Plotly Dash Snippets Plugin 

This is a snippets extension plugin for Visual Studio Code for the Plotly Dash microframework.

[Plotly Dash](https://plotly.com/dash/) is a great Open Source/Enterprise tool for technical business/data analysts to share their data within their organisations. Plotly Dash in Python can be considered as the equivalent of what the React framework is in JavaScript.

## Features

The snippets in this pluggin cover components from the Dash HTML Components, Dash Core Components & some from the Dash Bootstrap Componens Python packages.

For example, predefined Dash HTML Components start with the prefix `html`, Dash Core Component start with the prefix `dcc` .

In addition, abstractions such as callbacks live on their own (e.g. for an uncontrolled callback, you would call `dashcb`, while for a controlled stateful callback, you would call `dashcbstate`)

## To do

- Create snippets for Dash Bootstrap Components (developed by [faculty.ai](https://faculty.ai)) & Plotly packages. Ideally, Plotly objects should start with `plotly` & Dash Bootstrap Components should start with the prefix `dbc` 

- Create snippets for other abstractions [?] 

### Dash Generic Snippets: 

- `imdash` - Import Dash
- `iminoutstate` - Import Dash Dependencies
- `imdcc` - Import Dash Core Components
- `imhtml` - Import Dash HTML Components
- `imdbc` - Import Dash Boostrap Components
- `imflask` - Import Flask
- `imflaskcache` - Import Flask Cache
- `dashcb` - Uncontrolled State Callback
- `dashcbstate` - Controlled State Callback
- `dashapp` - Create Dash App Instace
- `dashrunserver` - Run Dash App
- `dashencodeimg` - Image Encoding Function
- `dashhtmltemplate` - Customize Dash's HTML Index Template
- `dashinlinestyle` - Dash Inline Styling
- `flaskserver` - Create Flask Server Instace
- `cacheredis` - Create Flask Cache Redis
- `cachefilesystem` - Create Flask Cache File System
- `memoize` - Create Flask Cache Memoize Function

### Dash HTML Component Snippets:

- `htmla` - HTML Anchor - Tag
- `htmla` - HTML Component - Anchor
- `htmlbr` - HTML Component - Break 
- `htmlbtn` - HTML Component - Button 
- `htmldiv` - HTML Component - Div 
- `htmlfig` - HTML Component - Figure 
- `htmlform` - HTML Component - Form 
- `htmlframe` - HTML Component - Frame 
- `htmlh1` - HTML Component - H1 
- `htmlh2` - HTML Component - H2 
- `htmlh3` - HTML Component - H3 
- `htmlh4` - HTML Component - H4 
- `htmlh5` - HTML Component - H5 
- `htmlh6` - HTML Component - H6 
- `htmlheader` - HTML Component - Header 
- `htmlhr` - HTML Component - Hr 
- `htmli` - HTML Component - I 
- `htmliframe` - HTML Component - Iframe 
- `htmlimg` - HTML Component - Img 
- `htmllabel` - HTML Component - Label 
- `htmlli` - HTML Component - Li 
- `htmllink` - HTML Component - Link 
- `htmlnav` - HTML Component - Strong 
- `htmlspan` - HTML Component - Span 
- `htmltable` - HTML Component - Table 
- `htmltbody` - HTML Component - Tbody 
- `htmltd` - HTML Component - Td 
- `htmltextarea` - HTML Component - Textarea 
- `htmlth` - HTML Component - Th 
- `htmlthead` - HTML Component - Thead 
- `htmltr` - HTML Component - Tr 
- `htmlul` - HTML Component - Ul

### Dash Core Component Snippets:

- `dccchecklist` - Core Component - Checklist
- `dccdatepickerrange` - Core Component - Date Picker Range
- `dccdatepickersingle` - Core Component - Date Picker Single
- `dccdropdown` - Core Component - Dropdown
- `dccgraph` - Core Component - Graph
- `dccinput` - Core Component - Input
- `dccinterval` - Core Component - Interval
- `dcclink` - Core Component - Link
- `dccloading` - Core Component - Loading
- `dcclocation` - Core Component - Location
- `dccmarkdown` - Core Component - Markdown
- `dccradioitems` - Core Component - Radio Items
- `dccrangeslider` - Core Component - RangeSlider
- `dccslider` - Core Component - Slider
- `dcctab` - Core Component - Tab
- `dcctabs` - Core Component - Tabs
- `dcctextarea` - Core Component - Textarea

### Dash Boostrap Component Snippets:

- `dbcalert` - Dash Bootstrap Components - Alert
- `dbcbadge` - Dash Bootstrap Components - Badge
- `dbcbtn` - Dash Bootstrap Components - Button
- `dbccol` - Dash Bootstrap Components - Col
- `dbcrow` -  Dash Bootstrap Components - Row

## Known Issues

Please add known issues here. 

## Release Notes

### 0.0.1
- Dash HTML Component Snippets Added
- Dash Core Component Snippets Added

### 0.0.3
- Some Dash Bootstrap Component Snippets Added
- Further Generic Snippets Added (imports/applications generation)
- Dash HTML Components prefix has been changed from `dashhtml` to `html`, Dash Core Components prefix has been changed from `dashcore` for `dcc` & similarly Dash Bootstrap Components will start with `dbc`

