![Theme preview](img/theme.png)

A theme for [Obsidian](https://obsidian.md/) based on computer consoles depicted in popular '80s sci-fi films.

"Starlit Abyss" is based on Satchelmouth's [WYConsole Theme](https://github.com/Satchelmouth/Obsidian-Theme-WYConsole).

This theme requires the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin. While the theme _should_ work without it, several features listed below require the plugin in order to be switched on.

## Installation
> [!WARNING]
> This theme is still a work in progress. Issues and PRs are welcome.

To install, download this repo folder, extract, then place the folder into your Obsidian's themes folder. According to Obsidian docs, the containing folder **must** be named "Starlit Abyss" for it to work.

## Features
### Color themes
|                                                        |                                                       |
|:------------------------------------------------------:|:-----------------------------------------------------:|
|  ![Terminal Green](img/theme.png)<br>*Terminal Green*  |     ![CyberPink](img/col-pink.png)<br>*CyberPink*     |
|   ![Rogue AI Red](img/col-red.png)<br>*Rogue AI Red*   | ![Ominous Orange](img/col-or.png)<br>*Ominous Orange* |
| ![Ypsilon Yellow](img/col-yel.png)<br>*Ypsilon Yellow* |  ![Moonbase Blue](img/col-bl.png)<br>*Moonbase Blue*  |

### Multiple fonts:
- [ ] TODO: Screenshot here

### OLED mode (pure black background):

![](img/ft-oled.png)

### Additional "inverted table" style:

| Normal table | Inverted table |
|:---:|:---:|
| ![](img/ft-table-normal.png) | ![](img/ft-table-invert.png) |

## Supported Plugins
* Style Settings *(required)*
* Advanced Tables
* Kanban
* Calendar
* File Tree Alternative Plugin

## Wishlist & Known Issues

- Custom caret *- unfortunately, without some JS coding I'm SOL on this one until CSS 4 drops and Obsidian integrates it. The general idea is to make the caret a box caret, like on old computer terminals. If anyone knows a way to accomplish this, a PR is more than welcome.*
- Canvas 
	- Changing a connection's arrowhead's color is not currently possible. It's just not a selectable object.
	- Some borders will show in a table header row in Canvas, but not Reading or Editing views of those notes.
