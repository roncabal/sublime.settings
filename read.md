## Install Package Control
	1. https://packagecontrol.io/installation
	2. cmd+shift+p to show preferences
	3. Search for Package Control: Install Package
## Install Boxy Theme
	* Search for Boxy Theme on Package Control

	Other things to install for boxy:

	- Boxy Theme
	- Boxy Theme - Add On (Font Face)
	- Boxy Theme - Add On (Widget Font XS)
	- Boxy Theme - Add On (Linter Theme)

	Additional settings for Boxy Theme - Tomorrow
	```
	// Additional for Boxy Tomorrow
	"theme_accent_green": true,
	"theme_font_md": true,
	"theme_scrollbar_colored": true,
	"theme_scrollbar_line": true,
	"theme_sidebar_folder_monochrome": true,
	"theme_tab_line_size_lg": true,
	"theme_tab_selected_transparent": true,
	"theme_tab_selected_underlined": true,
	"theme_tab_size_sm": true,
	"theme_sidebar_size_xs": true,
	```
## Install GitGutter
	* Search for GitGutter on Package Control
## Install BracketHighlighter
	* Search for BracketHighlighter on Package Control
## Install PHPCompanion
	* Search for PHPCompanion on Package Control

	- Add this on Key Bind - User
	```
	[
       ...
        { "keys": ["f9"], "command": "expand_fqcn" },
        { "keys": ["shift+f9"], "command": "expand_fqcn", "args": {"leading_separator": true} },
        { "keys": ["f10"], "command": "find_use" },
        { "keys": ["f8"], "command": "import_namespace" },
        { "keys": ["shift+f12"], "command": "goto_definition_scope" }
        ...
	]
	```
## Install AllAutoComplete
	* Search fo AllAutoComplete on Package Control
## Ctrl+Click go to definition
	(Mac)
	Create Default (OSX).sublime-mousemap in ~/Library/Application Support/Sublime Text 3/Packages/User

	```
	[
    {
        "button": "button1", 
        "count": 1, 
        "modifiers": ["ctrl"],
        "press_command": "drag_select",
        "command": "goto_definition"
    }
]	```
## Install DocBlockr
	* Search for DocBlockr on Package Control
## Install CodeIntel
	* Search for CodeIntel on Package Control
