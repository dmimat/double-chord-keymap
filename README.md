# Double Chord Keymap

A keymap for all IntelliJ-based IDEs where most shortcuts have two keystrokes:
the first one defines a group and the second one defines an action in this group
(e.g. `Ctrl/Cmd+D, A` for **Debug > Attach to Process** or
`Ctrl/Cmd+N, U` for **Navigate > Find Usages**).

You may want to try this keymap out if some of the following features are important to you:

- Easy-to-remember mnemonic mappings
- Same shortcuts across different operating systems
- Fewer modifier keys
- No conflicts with system shortcuts
- No conflicts on non-English Latin keyboards

Specific key bindings are listed below by category.

Single-chord shortcuts:

- [Standard editor shortcuts](#standard-editor-shortcuts)
- [Standard macOS application shortcuts](#standard-macos-application-shortcuts)
- [Shortcuts for sequential actions](#shortcuts-for-sequential-actions)

Double-chord shortcuts:
- [Ctrl/Cmd+B (Block). Manipulations with code blocks](#b)

> **NOTE:**  Availability of the actions listed below depends on your IDE and installed plugins

##Single-chord shortcuts
###Standard editor shortcuts
| Windows/Linux    | macOS   | Action         |
|------------------|---------|----------------|
| `Ctrl+A`         | `Cmd+A` | **Select All** |
| `Ctrl+C`         | `Cmd+C` | **Copy**  |
| `Ctrl+F`         | `Cmd+F` | **Find**  |
| `Ctrl+S`| `Cmd+S` | **Save** |
| `Ctrl+V`         | `Cmd+V` | **Paste** |
| `Ctrl+X`         | `Cmd+X` | **Cut**  |
| `Ctrl+Y`         | `Cmd+Y` | **Redo** |
| `Ctrl+Z`| `Cmd+Z` | **Undo** |

###Standard macOS application shortcuts 
|      |                                   |
|--------------|-----------------------------------------|
|`Cmd+H`| **Hide Front Application** | 
|`Cmd+M`| **Minimize**| 
|`Cmd+Q`| **Quit** |
|`Cmd+,`| **Preferences** |

###Shortcuts for sequential actions
| Windows/Linux        | macOS                | Action                                                       |
|----------------------|----------------------|--------------------------------------------------------------|
| `F1`                 | `F1`                 | **Back**                                                     |
| `Shift+F1`           | `Shift+F1`           | **Forward**                                                  |
||||
| `F2`                 | `F2`                 | **Last Edit Location**                                       |
| `Shift+F2`           | `Shift+F2`           | **Next Edit Location**                                       |
||||
| `Ctrl+F2`            | `Cmd+F2`             | **Next Method**                                              |
| `Ctrl+F1`            | `Cmd+F1`             | **Previous Method**                                          |
||||
| `F3`                 | `F3`                 | **Find Next**                                                |
| `Shift+F3`           | `Shift+F3`           | **Find Previous**                                            |
||||
| `F4`                 | `F4`                 | **Next Occurrence of the Word at Caret**                     |
| `Shift+F4`           | `Shift+F4`           | **Previous Occurrence of the Word at Caret**                 |
||||
| `Ctrl+F4`            | `Cmd+F4`             | **Next Highlighted Error**                                   |
| `Ctrl+F3`            | `Cmnd+F3`            | **Previous Highlighted Error**                               |
||||
| `F5`                 | `F5`                 | **Next Change** / **Next Difference in Diff viewer**         |
| `Shift+F5`           | `Shift+F5`           | **Previous Change** / **Previous Difference in Diff viewer** |
|||
| `F6`                 | `F6`                 | **Next Emmet Edit Point**                                    |
| `Shift+F6`           | `Shift+F6`           | **Previous Emmet Edit Point**                                |
|||
| `F7`                 | `F7`                 | **Move Caret to Code Block Start**                           |
| `F8`                 | `F8`                 | **Move Caret to Code Block End**                             |
| `Shift+F7`           | `Shift+F7`           | **Move Caret to Code Block Start with Selection**            |
| `Shift+F8`           | `Shift+F8`           | **Move Caret to Code Block End with Selection**              |
||||
| `Ctrl+Shift+F7`      | `Cmd+Shift+F7`       | **Go to Containing Declaration**                             |
| `Ctrl+Shift+F8`      | `Cmd+Shift+F8`       | **Select Containing Declaration**                            |
||||
| `Ctrl+F6`            | `Cmd+F6`             | **Unselect Occurrence**                                      |
| `Ctrl+F7`            | `Cmd+F7`             | **Add selection for Next Occurrence**                        |
||||
| `F10`                | `F10`                | **Extend Selection**                                         |
| `F9`                 | `F9`                 | **Shrink Selection**                                         |
||||
| `Ctrl+F8`            | `Cmd+F8`             | **Step Into**                                                |
| `Ctrl+F9`            | `Cmd+F9`             | **Step Over**                                                |
| `Ctrl+F10`           | `Cmd+F10`            | **Force Step Over**                                          |
| `Ctrl+F11`           | `Cmd+F11`            | **Force Step Into**                                          |
| `Shift+F11`          | `Shift+F11`          | **Smart Step Into**                                          |
| `Ctrl+F12`           | `Cmd+F12`            | **Step Out**                                                 |
||||
| `Alt+Shift+Down`     | `Alt+Shift+Down`     | **Move Statement Down**                                      |
| `Alt+Shift+Up`       | `Alt+Shift+Up`       | **Move Statement Up**                                        |
| `Alt+Shift+Left`     | `Alt+Shift+Left`     | **Move Element Left**                                        |
| `Alt+Shift+Right`    | `Alt+Shift+Right`    | **Move Statement Right**                                     |
||||
| `Alt+Down`           | `Alt+Down`           | **Move Line Down**                                           |
| `Alt+Up`             | `Alt+Up`             | **Move Line Up**                                             |
||||
| `Alt+Left`           | `Alt+Left`           | **Select Previous Tab**                                      |
| `Alt+Right`          | `Alt+Right`          | **Select Next Tab**                                          |
||||
| `Ctrl+[digit]`       | `Ctrl+[digit]`       | **Go to bookmark X**                                         |
| `Ctrl+Shift+[digit]` | `Ctrl+Shift+[digit]` | **Toggle bookmark X**                                        |
||||
| `Ctrl+Space`         | `Ctrl+Space`         | **Basic Completion**                                         |
| `Ctrl+Alt+Space`     | `Ctrl+Alt+Space`     | **Second Basic Completion**                                  |
| `Ctrl+Shift+Space`   | `Ctrl+Shift+Space`   | **Type-Matching Completion**                                 |
||||
| `Ctrl+Tab`           | `Ctrl+Tab`           | **Basic Completion**                                         |

## Double-chord shortcuts

<a id="b"></a>
### First chord: Ctrl/Cmd+B (block) - manipulations with code blocks

| Second Chord | Mnemonic | Action         |
|-----------------|----------|----------------|
|`A`|as|**Save as Template**|
|`C`|comment|**Comment/Uncomment with Block Comment**|
|`G`|generate|**Generate**|
|`H`|history|**Paste from History**|
|`I`|implement|**Implement Methods**|
|`O`|override|**Override Methods**|
| `P`             | paste    | **Paste as Plain Text** |
|`R`| rearrange|**Rearrange**|
|`S`|surround|**Surround With...**|
|`T`|template|**Insert Live Template**|
|`U`|unwrap|**Unwrap / Remove**|


<a id="d"></a>
### First chord: Ctrl/Cmd+D (debug) - running and debugging

| Second Chord | Mnemonic    | Action                               |
|--------------|-------------|--------------------------------------|
| `A`          | attach      | **Attach to Process**                |
| `B`          | breakpoints | **View Breakpoints**                 |
| `C`          | cursor      | **Run to Cursor**                    |
| `D`          | debug       | **Debug Selected Configuration**     |
| `E`          | evaluate    | **Evaluate Expression**              |
| `F`          | find        | **Show Execution Point**             |
| `G`          | go on       | **Resume Program**                   |
| `H`          |             | **Run Context Configuration**        |
| `I`          | immediate   | **Navigate to Immediate Window**     |
| `J`          | jump        | **Jump to Statement**                |
| `K`          | konfig      | **Edit Configurations**              |
| `L`          | line        | **Toggle Line Breakpoint**           |
| `N`          | new         | **Rerun**                            |
| `O`          | over        | **Stop**                             |
| `P`          | pause       | **Pause Program**                    |
| `Q`          | quick       | **Quick Evaluate Expression**        |
| `R`          | run         | **Run Selected Configuration**       |
| `S`          | skip        | **Force Run to Cursor**              |
| `T`          | temporary   | **Toggle Temporary Line Breakpoint** |
| `U`          | update      | **Update Running Application**       |
| `V`          | value       | **Set Value**                        |
| `W`          | watch       | **Add to Watches**                   |
| `X`          |             | **Toggle Breakpoint Enabled**        |
| `Y`          |             | **Run... (select configuration)**    |
| `Z`          |             | **Debug... (select configuration)**  |
