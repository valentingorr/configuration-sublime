# configuration-sublime

## Packages
1. AdvancedNewFile
2. BracketHighlighter
3. Browser Refresh
4. Build Next
5. ChangeQuotes
6. CMD
7. Color Highlight
8. ColorSchemeEditor
9. Discord Rich Presence
10. DotENV
11. EJS 2
12. Emmet
13. Emmet Css Snippets
14. ExtJs Snippets
15. FileIcons
16. JavaScript Completions
17. jQuery
18. JsonTree
19. PackageResourceViewer
20. Sass
21. SideBarEnhancements
22. SideBarMenuAdvanced
23. SidebarSeparator
24. SublimeOnSaveBuild
25. SublimeREPL
26. Terminus

## Key Bindings

```json
[
	{ "keys": ["ctrl+alt+o"], "command": "open_dir", "args": {"dir": "$file_path", "file": "$file_name"} },
	{ "keys": ["alt+f4"], "command": "close_window" },
	{ "keys": ["ctrl+alt+w"], "command": "close_all" },
	{ "keys": ["ctrl+shift+o"], "command": "prompt_open_folder" },
	{ "keys": ["ctrl+w"], "command": "close_file" },
	{ "keys": ["ctrl+r"], "command": "browser_refresh", "args": {"auto_save": true,"delay": 0.0,"activate": true,"browsers" : ["chrome"]}},
	{ "keys": ["ctrl+alt+shift+v"], "command": "clone_file" },
	{ "keys": ["ctrl+t"], "command": "change_quotes" },
	{ "keys": ["ctrl+shift+w"], "command": "toggle_setting", "args": { "setting": "word_wrap" } },
	{ "keys": ["alt+c"], "command": "terminus_open", "args" : { "cmd": "cmd.exe", "cwd": "${file_path:${folder}}", "title": "Command Prompt", "panel_name": "Terminus" } },
	{ "keys": ["alt+b"], "command": "terminus_open", "args" : { "cmd": ["C:\\Program Files\\Git\\bin\\bash.exe", "-i", "-l"], "cwd": "${file_path:${folder}}", "title": "Git Bash", "panel_name": "Terminus" } },
	{ "keys": ["ctrl+space"], "command": "cmd"}
]
```

## Settings

```json
{
	"auto_hide_menu": true,
	"bold_folder_labels": true,
	"file_exclude_patterns":
	[
		"*.css.map",
		"reportWebVitals.js"
	],
	"folder_exclude_patterns": [
		".svn",
		".hg",
		"CVS",
		".Trash",
		".Trash-*",
		"node_modules",
		".git"
	],
	"font_size": 8,
	"highlight_line": true,
	"highlight_modified_tabs": true,
	"ignored_packages":
	[
		"SaneSnippets",
		"Vintage",
	],
	"line_padding_bottom": 1,
	"line_padding_top": 1,
	"margin": 0,
	"material_theme_arrow_folders": true,
	"material_theme_big_fileicons": true,
	"material_theme_bright_scrollbars": true,
	"material_theme_small_tab": true,
	"material_theme_tabs_separator": true,
	"preview_on_click": false,
	"shift_tab_unindent": false,
	"show_panel_on_build": false,
	"tabSize": 6,
	"theme": "Adaptive.sublime-theme",
	"translateTabsToSpaces": false,
	"useTabStops": false,
	"dark_theme": "Adaptive.sublime-theme",
	"light_theme": "Default Dark.sublime-theme",
	"word_separators": "./\\()\"'-:,.;<>~!@#$%^&*|+=[]{}`~?",
	"color_scheme": "Mariana.sublime-color-scheme",
}
```
