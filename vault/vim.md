---
id: gvnuhlu7dd3zr4pkgshz8dw
title: Vim
desc: ''
updated: 1651962836577
created: 1650961843586
---

# Vim - The Personal man

Author: Misc
Itreration: 2
Status: Ongoing
Type: Misc, Productivity, Tech

**Opening**

| vim <fileName>  | open a file |
| --- | --- |

- **Exiting 👻**

    |     |                                 |
    |-----|---------------------------------|
    | :q  | to quit the file                |
    | :e! | to trash all changes and reload |
    | :q! | to trash all changes and quit   |
    | :wq | to save the changes and quit    |
    | ZZ  | to save the changes and quit    |

    
    
- **Navigation**

    | h j k l                           |  left down up right                                       |
    | --------------------------------- | --------------------------------------------------------- |
    | 0                                 | to start of the line                                      |
    | $ (shift + 4)                     | to end of the line                                        |
    | e                                 | to end of Word                                            |
    | w                                 | forward one word (alphanumeric characters make up words)  |
    | W                                 | forward one Word (whitespace separates words)             |
    | b                                 | backward one word (alphanumeric characters make up words) |
    | B                                 | backward one Word (whitespace separates words)            |
    | <number> wW / e / bB / h j k l \* | Move <number> times <text objects>                        |
    | <num> G (shift + g)               | to specific line                                          |
    | % (shift + 5)                     | to matching parenthesis {} [] ()                          |

- **Text Manipulation [...](https://www.notion.so/References-20392176b5824d55ad72d5a3c57cb6e3)**
    
    
    | x | delete at the cursor (→ in normal mode still) |
    | --- | --- |
    | i | insert before the cursor |
    | I | insert  beginning of the line |
    | a | insert after the cursor |
    | A | append after the line |
    | o | open line above |
    | O | open line below |
    | s | delete character and insert |
    | S | delete line and insert |
    | R overstrike mode | replace text character by character (max 1 line) |
    | c <movement> wW / bB / 2j / $/ 0 | change till (→ in insert mode now) | cc - change one line |
    | d <movement> wW / bB / 2j / $/ 0 | delete till (→ in normal mode still) | dd - delete one line ... |
    | r  | replace single character (→ don’t have to press ESC) |
    | <number> ~  | change letter case  |
    
    > Remember - **(command)*(number)(text object)****
    > 
    
    **<movement>*
    
- **Edits**
    
    
    | u | undo the most recent command |
    | --- | --- |
    | U | undo all changes on a line |
    | Ctrl + R | redo an undone operation |
    | p | put or paste copied (yanked) or deleted contents | put below |
    | P | put above |
    | y <movement> | copy content till movement | yy - yank one line ... |
    | . | repeat previous command |
- **Shell**
    
    
    | Ctrl + z | Suspend vim and return to shell |
    | --- | --- |
    | fg | Bring suspended vim to foreground |
    | :sh | Create new shell |
    | Ctrl + d | Terminate shell |
    | :! | Run shell command from within vim |
- **Options**
    
    ```bash
    :set wm=10  //wrapmargin
    :set nu //show line numbers
    
    ```
    

---


