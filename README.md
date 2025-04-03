# Learning Vim/Vi console text editor
* This is just a dump / experimental repository to write some stuff using vim & merging via CLI

### Opening a File in Vi
- To open a file (or create one if it doesn’t exist), type:
  ```bash
  vi filename
  ```
- Once inside Vi, you’ll be in **normal mode** by default.

### Basic Modes in Vi
1. **Normal Mode** (default) – Used for navigation and commands.
2. **Insert Mode** – Used for editing text. Press `i` to enter.
3. **Command Mode** – Used for saving, quitting, and searching. Press `:` to enter.

### Basic Navigation (Normal Mode)
- `h` → move left  
- `l` → move right  
- `j` → move down  
- `k` → move up  
- `w` → jump to next word  
- `b` → jump to previous word  
- `G` → go to the last line  
- `gg` → go to the first line  

### Editing Text
- `i` → Insert before the cursor  
- `a` → Append after the cursor  
- `o` → Open a new line below  
- `O` → Open a new line above  
- `x` → Delete a character  
- `dd` → Delete an entire line  
- `yy` → Copy a line  
- `p` → Paste copied text  

### Saving and Exiting
- `:w` → Save the file  
- `:q` → Quit  
- `:wq` → Save and quit  
- `:q!` → Quit without saving  
