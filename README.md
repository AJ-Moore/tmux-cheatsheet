# tmux-cheatsheet
tmux cheatsheet &amp; shortcuts

### Commands 
|Command|Description|
|---|---|
|`tmux`|create new session|
|`tmux new -s session_name`|create new session with specified name|
|`tmux ls `|list current opened sessions|
|`tmux a -t session_name`|attach to exist session|
|`tmux rename-session -t session_name new_name`|rename session|
|`tmux kill-session -t session_name`|kill specified session|
|`tmux kill-session -a`|kill all sessions except current opened|

### Sessions
|Shortcut|Description|
|---|---|
|`Ctrl+b $`|rename session|
|`Ctrl+b s`|list sessions|
|`Ctrl+b d`|detach from current session|
|`Ctrl+b )`|move to the next session|
|`Ctrl+b (`|back to the previous session|

### Window
|Shortcut|Description|
|---|---|
|`Ctrl+b c`|create new window|
|`Ctrl+b ,`|rename window|
|`Ctrl+b &`|kill window|
|`Ctrl+b n`|move to the next window|
|`Ctrl+b n`|back to the previous window|

### Panes
|Shortcut|Description|
|---|---|
|`Ctrl+b %`|split pane vertically|
|`Ctrl+b "`|split pane horizontal|
|`Ctrl+b x`|kill pane|
|`Ctrl+b up|down|left|righ`|switch between panes|
