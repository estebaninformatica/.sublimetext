# .sublimetext
Configuration sublime text
preferencias / settings user

{
	"color_scheme": "Packages/User/SublimeLinter/Monokai (SL).tmTheme",
	"folder_exclude_patterns":
	[
		"node_modules"
	],
	"font_size": 9,
	"highlight_modified_tabs": true,
	"ignored_packages":
	[
		"Vintage"
	],
	"tab_size": 2,
	"theme": "SoDaReloaded Dark.sublime-theme",
	"theme_primer_sidebar_font_large": true,
	"theme_primer_sidebar_tree_small": true,
	"translate_tabs_to_spaces": true,
	"hot_exit": false
}

keybinding default user

[
  { "keys": ["f1"], "command": "reveal_in_side_bar"},
  { "keys": ["f2"], "command": "toggle_comment"},
  { "keys": ["ctrl+i"], "command": "reindent" },
  { "keys": ["f3"], "command": "expand_tabs" },
  {
    "keys": ["f4"], "command": "align_tab",
    "args" : {"live_preview" : true}
  },
  { "keys": ["f5+up"], "command": "select_lines", "args": {"forward": false} },
  { "keys": ["f5+down"], "command": "select_lines", "args": {"forward": true} },
]

