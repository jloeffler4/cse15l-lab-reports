## Week 7 Lab Report

### Part 1

**Selected Task**: Adding a new line to print directory names before `File[] paths = f.listfiles()` in `DocSearchServer.java`

My group's sequence (9 `vim` command keystrokes):

- **`1` `7` `G`**
- **`<Shift>`** + **`O`**
- *`System.out.println("Found directory: " +  f.toString());`*
- **`<Esc>`**
- **`:` `w` `<Enter>`**

### Part 2

#### VS Code + `scp`

| Time Taken | Difficulties Encountered |
| - | - |
| 21 seconds | The major difficulties I encountered were setting up the `scp` + `ssh` commands in the history since it's very long to type in. |

#### SSH + `vim`

| Time Taken | Difficulties Encountered |
| - | - |
| 26 seconds | Using `vim` went much smoother than I thought it would. I can't say that I encountered any difficulties, but it did take a bit longer to move the cursor, save, etc. since it required more precision in keyboard inputs. |

#### Conclusion

I would definitely use VS Code or any IDE over `vim` for working on real-world programs because they often involve working across multiple files and VCS. It does take a bit longer to set everything up, however, once everything is working, it makes complex edits way easier than in a plaintext editor.

For one-line edits and things like config files that only live on the remote server, I would prefer to use a terminal-based editor (preferably `nano` instead of `vim`). It's definitely a question of tradeoffs and complexity. The biggest factors are where the files are vs. where they need to run, complexity of edits, and size/amount of files.