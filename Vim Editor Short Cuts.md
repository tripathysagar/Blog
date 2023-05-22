## Vim commands

In most of the unix system vim editor comes by default. Writing code or editing files with the vim editors is a must desired.
The editor has three modes 
1. insert mode : writing into a file
2. command mode : executing commmand
3. c : for making cut, copy, paste 
In this note we will be discussing the above functionalities along with serching in the file as it is the most important functionality of a text editor.


---
### insert mode
|Syntax|Description|
|------|-----------|
|`i`    | for entering into insert mode|
|`<ESC>:w`| to write into the file|
|`<ESC>:q`|to quit o the file without writing into the file|
|`<ESC>:q!`| to quit the file without writing into the file and exiting ungracefully|
|`<ESC>:wq!`| to write and quit the file, exiting ungracefully|

---
  ### command mode
    During oping file using `vi <file>` the <file> is oppened in command mode. To enter command mode from insetmode can be done via entering `<ESC>` command.

|Syntax|Description|
|------|-----------|
| `<shift>g` |goto last line of a file|
|`gg`| goto the first line of a file|
|`A` or `g _` |  goto end of a line|
|`set number` or `se nu`|for showing the line number in a file|
|`set nonumber` or `se nonu` |  for removing line number in a file|
|`:n`| for jumping into line number n|
|`dd` | for deleting a line|
| `ndd`|for removing n lines at the cursor pointing|
|`$`| for traversing to the end of a line|
|`u`| for doing undo the operation|
  
---
   ### visual mode
Can be enter like command mode. Below are some  useage
  
|Syntax|Description|
|------|-----------|
| `v` |  char mode selection|
| `V` | line mode selection|
| `ctrl + v`|  block mode selection|
| `y` | for copy to clipboard|
|`d` | for cut to clipboard|
|`p`  |for pasting |
   
----
### searching
Use `/<string-to-search>` and `?<string-to-search>` for searching in forward and backward mode respectively. To iterating over the next finding can be done `<esc>n` and `n` after that. 
Simalarly to iterate backward `<esc>N` and `N`.







    
