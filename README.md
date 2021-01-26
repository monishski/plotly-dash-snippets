# Plotly Dash Snippets Plugin 

This is a snippets extension plugin for Visual Studio Code for the Plotly Dash microframework.

[Plotly Dash](https://plotly.com/dash/) is a great Open Source/Enterprise tool for technical business/data analysts to share their data within their organisations. Plotly Dash in Python can be considered as the equivalent of what the React framework is in JavaScript.

## Features

The snippets in this pluggin cover components from the Dash HTML Components & Dash Core Components Python packages.

All snippets start with the prefix `dash`. 

For example, predefined Dash HTML Components start with the prefix `dashhtml`, Dash Core Component start with the prefix `dashcore` .

In addition, abstractions such as callbacks live on their own (e.g. for an uncontrolled callback, you would call `dashcb`, while for a controlled stateful callback, you would call `dashcbstate`)

## To do

- Create snippets for Dash Bootstrap Components (developed by [faculty.ai](https://faculty.ai)) & Plotly packages. Ideally, Plotly objects should start with `dashplotly` & Dash Bootstrap Components should start with the prefix `dashboot` 

- Create snippets for other abstractions (e.g. importing, creating the application etc.) [?] 

### Dash Generic Snippets: 

- `dashcb` - Uncontrolled Stateless Callback
- `dashcbstate` - Controlled Stateful Callback
- `dashinlinestyle` - Inline Styling 

### Dash HTML Component Snippets:

- `dashhtmla` - HTML Anchor - Tag
- `dashhtmla` - HTML Component - Anchor
- `dashhtmlbr` - HTML Component - Break 
- `dashhtmlbtn` - HTML Component - Button 
- `dashhtmldiv` - HTML Component - Div 
- `dashhtmlfig` - HTML Component - Figure 
- `dashhtmlform` - HTML Component - Form 
- `dashhtmlframe` - HTML Component - Frame 
- `dashhtmlh1` - HTML Component - H1 
- `dashhtmlh2` - HTML Component - H2 
- `dashhtmlh3` - HTML Component - H3 
- `dashhtmlh4` - HTML Component - H4 
- `dashhtmlh5` - HTML Component - H5 
- `dashhtmlh6` - HTML Component - H6 
- `dashhtmlheader` - HTML Component - Header 
- `dashhtmlhr` - HTML Component - Hr 
- `dashhtmli` - HTML Component - I 
- `dashhtmliframe` - HTML Component - Iframe 
- `dashhtmlimg` - HTML Component - Img 
- `dashhtmllabel` - HTML Component - Label 
- `dashhtmlli` - HTML Component - Li 
- `dashhtmllink` - HTML Component - Link 
- `dashhtmlnav` - HTML Component - Strong 
- `dashhtmlspan` - HTML Component - Span 
- `dashhtmltable` - HTML Component - Table 
- `dashhtmltbody` - HTML Component - Tbody 
- `dashhtmltd` - HTML Component - Td 
- `dashhtmltextarea` - HTML Component - Textarea 
- `dashhtmlth` - HTML Component - Th 
- `dashhtmlthead` - HTML Component - Thead 
- `dashhtmltr` - HTML Component - Tr 
- `dashhtmlul` - HTML Component - Ul

### Dash Core Component Snippets:

- `dashcorechecklist` - Core Component - Checklist
- `dashcoredatepickerrange` - Core Component - Date Picker Range
- `dashcoredatepickersingle` - Core Component - Date Picker Single
- `dashcoredropdown` - Core Component - Dropdown
- `dashcoregraph` - Core Component - Graph
- `dashcoreinput` - Core Component - Input
- `dashcoreinterval` - Core Component - Interval
- `dashcorelink` - Core Component - Link
- `dashcoreloading` - Core Component - Loading
- `dashcorelocation` - Core Component - Location
- `dashcoremarkdown` - Core Component - Markdown
- `dashcoreradioitems` - Core Component - Radio Items
- `dashcorerangeslider` - Core Component - RangeSlider
- `dashcoreslider` - Core Component - Slider
- `dashcoretab` - Core Component - Tab
- `dashcoretabs` - Core Component - Tabs
- `dashcoretextarea` - Core Component - Textarea

## Known Issues

Please add known issues here. 

## Release Notes

### 0.0.1
- Dash HTML Component Snippets Added
- Dash Core Component Snippets Added
