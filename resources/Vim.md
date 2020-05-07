# Vim 

## Global
| Command | Description |
|---------|-------------|
| `:help keyword` | Open help for keyword |
| `:saveas file` | Save file as |
| `:close` | Close current pane |
| `K` | Open man page for word under the cursor |

## Exiting
| Command | Description |
|---------|-------------|
| `:w`  | Write (save) the file, bud don't exit |
| `:w !sudo tee %` | Write out the current file using sudo |
| `:q` | Quit (fails if there are unsaved changes) |
| `:q!` or `ZQ` | Quit and throw away unsaved changes |
| `:wqa` | Write (save) and quit on all tabs |