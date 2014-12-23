#Sublime Text 3 Settings
This is my Sublime Text 3 configuration. 

###Installation
First you need to manually install [Package Control](https://sublime.wbond.net/installation).

After that clone my repository.
```
git clone https://github.com/janekkkk/sublime-settings.git
```
**Close Sublime Text!**

This will **destroy** your previously installed packages so back them (~/.config/sublime-text-3/Packages/User) up first if you need to! Change PATH to where you put my repo.
```
cd ~/.config/sublime-text-3/Packages/
rm -r User
ln -s ~/PATH/User
```

###User settings
```json
{
    "auto_id_class": true,
    "auto_indent": true,
    "bold_folder_labels": true,
    "caret_extra_bottom": 2,
    "caret_extra_top": 2,
    "caret_extra_width": 2,
    "caret_style": "phase",
    "close_windows_when_empty": true,
    "color_scheme": "Packages/Colorcoder/Clouds_Midnight (Colorcoded).tmTheme",
    "draw_white_space": "all",
    "ensure_newline_at_eof_on_save": true,
    "find_selected_text": true,
    "fold_buttons": false,
    "font_face": "Ubuntu Mono",
    "font_options":
    [
        "subpixel_antialias",
        "no_bold"
    ],
    "font_size": 12,
    "highlight_line": true,
    "highlight_modified_tabs": true,
    "ignored_packages":
    [
        "Vintage",
        "Markdown"
    ],
    "line_padding_bottom": 1,
    "line_padding_top": 1,
    "match_brackets_angle": true,
    "original_color_scheme": "Packages/Colorsublime - Themes/Clouds_Midnight.tmTheme",
    "scroll_past_end": false,
    "show_full_path": true,
    "show_minimap": true,
    "tab_size": 4,
    "tabs_small": true,
    "theme": "itg.flat.light.sublime-theme",
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true,
    "wide_caret": true,
    "word_wrap": "true"
}

```
