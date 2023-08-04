# VIM and Neovim: Text Editors for Power Users

![VIM Logo](https://linuxhandbook.com/content/images/2023/01/neovim-vs-vim.png)

## Introduction

### Origins

VIM's story begins with the "Vi" text editor, which was created by Bill Joy in the 1970s for the Unix operating system.

![VIM Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/Bill_Joy_at_World_Economic_Forum_%28Davos%29%2C_2003-01_%28cropped%29.jpg/220px-Bill_Joy_at_World_Economic_Forum_%28Davos%29%2C_2003-01_%28cropped%29.jpg)

Vi revolutionized text editing with its modal approach, separating different editing modes for navigation and text manipulation. Vi quickly became a staple tool for programmers and system administrators.

VIM and Neovim are powerful text editors designed for efficient text manipulation and code editing. They offer a unique modal editing approach and a rich ecosystem of plugins and customization options.

### Birth of VIM

In the early 1990s, Bram Moolenaar sought to enhance Vi's capabilities by creating a more feature-rich and extensible version. In 1991, VIM was born, introducing a multitude of improvements while staying true to Vi's core modal editing concept. VIM's extensibility and customization features set it apart from its predecessor.

![VIM Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/f/ff/Bram_Moolenaar_in_2007.jpg/220px-Bram_Moolenaar_in_2007.jpg)

## Modal Editing

VIM and Neovim use a modal editing approach, allowing you to switch between different modes for various tasks:

- **Normal Mode**: Navigate and manipulate text.
- **Insert Mode**: Enter and edit text.
- **Visual Mode**: Select and manipulate text visually.

### Key Features

#### VIM

- Lightweight and highly customizable.
- Efficient text navigation and manipulation using keybindings.
- Wide range of plugins and community-contributed scripts.

#### Neovim

- Built for extensibility and compatibility.
- Asynchronous plugin system for improved performance.
- Better support for modern development workflows.

### VIM in VS CODE

![vim+vscode](https://i.ytimg.com/vi/h-epcklOC_g/hqdefault.jpg)

- Efficiency and Speed: VIM's modal editing philosophy promotes a keyboard-centric methodology, curtailing the necessity for incessant toggling between the keyboard and mouse. This engenders accelerated coding, as fundamental tasks like navigation, selection, and text manipulation can be accomplished with minimal keystrokes.

- Customization: Analogous to standalone VIM, the VS Code extension affords unparalleled customization options. You wield the authority to configure keybindings, plugins, and settings, sculpting an editing environment tailored to your workflow and coding predilections.

- Universality: Mastering VIM keybindings bestows a valuable aptitude, as it transcends the confines of a singular text editor. Through the VIM extension for VS Code, you not only enrich your productivity within VS Code but also cultivate proficiencies that can be wielded in terminal environments or while working on remote servers.

- Potent Text Manipulation: VIM boasts a renowned repertoire of text manipulation capabilities encompassing macros, text objects, and global substitutions. By seamlessly incorporating these attributes into VS Code, the VIM extension furnishes an opulent toolkit for deftly metamorphosing your code.

- Cognitive Harmony: Proficiency in VIM engenders an almost instinctive alignment of commands with actions. This augmented cognitive coordination heightens your overall coding experience by alleviating mental strain, permitting you to focus more intently on problem-solving rather than grappling with your text editor.

- Community and Resources: The VIM community stands expansive and supportive, dispensing a plethora of tutorials, guides, and plugins. By adopting the VIM extension for VS Code, you gain entree to this vast knowledge repository, continuously honing your coding prowess.

## Normal Mode Commands

### Navigation

- `h`, `j`, `k`, `l`: Navigate left, down, up, and right respectively.
- `w`: Move to the beginning of the next word.
- `b`: Move to the beginning of the previous word.
- `gg`: Move to the start of the document.
- `G`: Move to the end of the document.
- `0`: Move to the beginning of the line.
- `$`: Move to the end of the line.
- `%`: Jump to matching brackets/parentheses.

### Editing

- `i`: Enter Insert mode before the cursor.
- `a`: Enter Insert mode after the cursor.
- `A`: Enter Insert mode at the end of the line.
- `o`: Open a new line below and enter Insert mode.
- `O`: Open a new line above and enter Insert mode.
- `x`: Delete the character under the cursor.
- `dd`: Delete the current line.
- `yy`: Yank (copy) the current line.
- `p`: Paste the yanked text after the cursor.
- `u`: Undo the last action.
- `Ctrl + r`: Redo the last undone action.

### Searching and Substitution

- `/pattern`: Search forward for "pattern".
- `?pattern`: Search backward for "pattern".
- `n`: Move to the next search result.
- `N`: Move to the previous search result.
- `:s/old/new/g`: Replace "old" with "new" globally in the current line.
- `:%s/old/new/g`: Replace "old" with "new" globally in the entire document.

### Copying, Cutting, and Pasting

- `yw`: Yank (copy) from the cursor to the end of the word.
- `yy`: Yank (copy) the current line.
- `p`: Paste the yanked/cut text after the cursor.

## Conclusion

VIM and Neovim stand as enduring testaments to the power of modal editing.

Their efficient workflows, extensibility, and rich histories have solidified their roles as beloved tools among power users, programmers, and text enthusiasts.

By embracing these editors, you open the door to a world of efficient text manipulation and a vibrant community of users.

Whether you choose VIM's tried-and-true path or Neovim's modernized approach, you're sure to find yourself navigating and crafting code with unparalleled precision and speed.

So dive into the world of modal editing, explore the depths of your creativity, and harness the potential of VIM and Neovim to become a true text-editing virtuoso.
