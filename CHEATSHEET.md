## Create sessions

```bash
tmux new                      # Create a new tmux session
```

```bash
tmux new-session name-session # Create a named session
```

```bash
tmux new -s name-session      # Shortcut for new-session
```

## Detaching and attaching sessions

```bash
tmux attach                   # Attach to most recent session
```

```bash
tmux attach -t name-session   # Attach to a specific session
```
