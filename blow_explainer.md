The conversions below use native Windows GNU Emacs’s default color map. Numbered names such as `darkseagreen2` and `gray16` are approximated by removing the number.

| Line | Setting | Function |
|---|---|---|
| [6](blow.txt:6) | `default` | Ordinary text: foreground `#d3b58d`, background `#041818`. |
| [7](blow.txt:7) | `custom-group-tag-face` | Underlined group headings in `lightblue` (`#add8e6`). |
| [8](blow.txt:8) | `custom-variable-tag-face` | Underlined variable headings in `lightblue` (`#add8e6`). |
| [9](blow.txt:9) | `font-lock-builtin-face` | Initially defines no attributes. Line 33 later sets `lightgreen` (`#90ee90`). |
| [10](blow.txt:10) | Comment alternative | Inactive. Would make comments `yellow` (`#ffff00`). |
| [11](home/alex/Work/omacom/omarchy-theme-naysayer/blow.txt:11) | `font-lock-comment-face` | Attempts to use `#3fdflf`, which is invalid; likely intended `#3fdf1f`. |
| [12](blow.txt:12) | `font-lock-function-name-face` | Function names use `white` (`#ffffff`) on dark color displays. |
| [13](blow.txt:13) | `font-lock-keyword-face` | Keywords use `white` (`#ffffff`). |
| [14](blow.txt:14) | String alternative | Inactive. On native Windows Emacs, both `gray160` and `gray16` fall back to `gray` (`#bebebe`). On X11, `gray16` is `#292929`; `gray160` is not a standard numbered grayscale name. |
| [15](blow.txt:15) | `font-lock-string-face` | Strings use turquoise `#0fdfaf`. |
| [16](blow.txt:16) | `font-lock-variable-name-face` | Variable names use pale blue `#c8d4ec`. |
| [17](blow.txt:17) | Warning alternative | Inactive. Would use `#695a46`. |
| [18](blow.txt:18) | `font-lock-warning-face` | Warning text uses `#504038`. |
| [19](blow.txt:19) | `highlight` | Foreground `navyblue` (`#000080`), background `darkseagreen2`—approximated as `DarkSeaGreen` (`#8fbc8f`) on Windows. Canonical X11 `DarkSeaGreen2` is `#b4eeb4`. |
| [20](blow.txt:20) | `mode-line` | Uses inverse video, swapping inherited foreground and background colors. |
| [21](blow.txt:21) | `region` | Selected text gets a `blue` (`#0000ff`) background. |
| [22](blow.txt:22) | `widget-field-face` | Widget-field text uses `white` (`#ffffff`). |
| [23](blow.txt:23) | `widget-single-line-field-face` | Widget fields use a `darkgray` (`#a9a9a9`) background. |
| [25](blow.txt:25) | `global-font-lock-mode` | Enables syntax highlighting globally. |
| [26](blow.txt:26) | `set-cursor-color` | Selected-frame cursor uses `lightgreen` (`#90ee90`). |
| [27](blow.txt:27) | `set-background-color` | Changes the selected frame’s effective background to `#072626`. |
| [28](blow.txt:28) | `global-set-key` | Binds `Ctrl+Return` to save the current buffer. |
| [30](blow.txt:30) | Font alternative | Inactive `Anonymous Pro-14` font selection. |
| [31](blow.txt:31) | `set-face-attribute` | Selects the `Consolas-174` font pattern for the default face. |
| [33](blow.txt:33) | `set-face-foreground` | Makes built-ins `lightgreen` (`#90ee90`). |
