``` Bash
less [OPTIONS] filename
less -N filename # Display line numbers
less -X filename # By default, when exiting the command, the text disapear. -X will keep the text displayed
less +F filename # Follow mode to monitor any changes to the file
```


| Action | Key | Example | Comments |
|---|---|---|---|
| Search | `/text_to_search` | - |  |
| Next occurence of the search | `n` | - |  |
| Previous occurence of the search | `N` | - |  |
|---|---|---|---|
| Next Page | `f` or `Space bar` | - |  |
| Previous Page | `b` | - |  |
| Go x lines forward | `xf` | `50f` |  |
| Go x lines backward | `xb` | `50b` |  |
| Go to the top | `g` | - |  |
| Go to the bottom | `G` | - |  |
| Go to line x | `xg` | - |  |
| Go to the top | `p` | - |  |
| Go to x percent of the file | `xp` | - |  |
| Help | `h` | - |  |
| Quit | `q` | - |  |
