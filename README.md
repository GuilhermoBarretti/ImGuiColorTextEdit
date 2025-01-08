# About this fork

This is a *fork* of a [fork](https://github.com/santaclose/ImGuiColorTextEdit) of [ImGuiColorTextEdit](https://github.com/BalazsJako/ImGuiColorTextEdit).

[ImGuiColorTextEdit](https://github.com/BalazsJako/ImGuiColorTextEdit) (made by [BalazsJako](https://github.com/BalazsJako/)) is a simple widget that provides text editing functionality with syntax highlighting for [Dear ImGui](https://github.com/ocornut/imgui). It provides features found on code editors like undo/redo, syntax highlighting, identifier declarations, error markers, color palettes, etc.

[santaclose](https://github.com/santaclose)'s [fork](https://github.com/santaclose/ImGuiColorTextEdit) implemented a lot of nice new features:
- Ctrl + Click: Multicursor 
- Ctrl + D: Select next match (Multicursor)
- Ctrl + /: Toggle comment
- Ctrl + [ or ]: Identation
- More Language Definitions
- Uses boost regex
- Ctrl + Backspace or Ctrl + Delete: delete entire word
- Middle mouse button: panning

However there are some features from the original repository missing which I restored with this fork:
- Highlight current lines
- Blinking cursors
- Tooltip for identifiers
- SetPalette and SetLanguageDefinition using reference instead of enums ids 
- ErrorMarkers

Some other changes I made:
- AlignCursorToCenter()
- Ctrl+S: Sets Save Request var
- Ctrl+F: Sets Find Request var

![Screenshot](https://github.com/BalazsJako/ImGuiColorTextEdit/wiki/ImGuiTextEdit.png "Screenshot")
