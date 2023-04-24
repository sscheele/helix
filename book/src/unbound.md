In addition to the typable commands which can be run with `:cmd` in normal mode and the commands with keybindindings listed in the [keymap page](./keymap.md), Helix offers a number of commands which cannot be run unless they receive keybindings via the process explained in the [remapping page](./remapping.md). A few of these commands will recieve in-depth explanation in the next section, but currently the only way to view a complete list is to look for the `static_commands!` macro in [`helix_term/src/commands.rs`](https://github.com/sscheele/helix/blob/master/helix-term/src/commands.rs).

## Unbound Commands
| Command               | Description                                          |
|---------              |------------                                          |
| `move_visual_line_up` | Moves the cursor up one _visual_ line, respecting softwrapping rather than the actual line breaks in the file |
| `move_visual_line_down` | Moves the cursor down one _visual_ line, respecting softwrapping rather than the actual line breaks in the file |
