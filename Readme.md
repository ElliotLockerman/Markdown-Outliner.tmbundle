# Readme  

## General  

A TextMate bundle to aid in creating and editing of [Markdown](http://daringfireball.net/projects/markdown/) outlines.
A regular Markdown bundle (such as [this one](https://github.com/textmate/markdown.tmbundle)) is required. 

## Installation  

Download and unzip. 
Erase everything after "tmbundle" in the name.
Double click.

## Menu Items (Shortcuts) 

Note that these are only active when the cursor is currently in an outline item. 

### Add Item to Outline (⏎/Enter)  
Create a new outline item on the next line, at the same level. To begin outlining, type a minus followed by a space ("- "). To stop outlining, press ⇧⏎/shift enter or enter and backspace over the minus. Currently, only minuses are supported as outline-markers. 

### Indent Outline Item(⇥/Tab)

Indents the (entire) current outline item, without displacing the cursor. 

### Move Outline Item Down(⌘↓/Command-DownArrow)

Swaps the current outline item with the one beneath it. Currently, the cursor is displaced to the beginning of the line. This does not function properly on the second-to-last line, so leave a few blank lines beneath your text. 

### Move Outline Item Up(⌘↑/Command-UpArrow)

Swaps the current outline item with the one above it. Currently, the cursor is displaced to the beginning of the line.

### Un-Indent Outline Item(⇧⇥/Shift-Tab)

Un-Indents the (entire) current outline item, without displacing the cursor. 


