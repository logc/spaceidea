# A configuration for IdeaVim that makes it work like Spacemacs

## Installation

```
git clone https://github.com/logc/spaceidea.git ./spaceidea
ln -s ./spaceidea/.ideavimrc ~/.ideavimrc
```

In IntelliJ Idea (not needed if starting or restarting):

```
:source ~/.ideavimrc
```

## Available Keymaps

### Search
| Keymap           | Action           | Notes                                                       |
|------------------|------------------|-------------------------------------------------------------|
| `<space>`/       | FindInPath       | Similar to grepping over the whole project                  |
| `<space><space>` | SearchEverywhere | Already mapped to double right `<shift>` but this is faster |

### Files
| Keymap      | Action  | Notes                                          |
|-------------|---------|------------------------------------------------|
| `<space>`fs | SaveAll | There is no save for a single file, apparently |

### Go Places
| Keymap | Action                             | Notes                                                 |
|--------|------------------------------------|-------------------------------------------------------|
| gd     | go to definition, already built-in |                                                       |
| gT     | GotoTest                           |                                                       |
| gi     | GotoImplementation                 |                                                       |
| gn     | GotoNextError                      | Next compilation error within file                    |
| gp     | GotoPreviousError                  | Prev  compilation error within file                   |
| gr     | PreviousTab                        | This is a personal choice, because 'r' is 'left of t' |
| gt     | NextTab                            |                                                       |
| gu     | ShowUsages                         |                                                       |

### Git
| Keymap      | Action               | Notes |
|-------------|----------------------|-------|
| `<space>`gC | Git.ResolveConflicts |       |

### Open
| Keymap      | Action                       |
|-------------|------------------------------|
| `<space>`oo | MoveEditorToOppositeTabGroup |

### Windows (Tabs)
| Keymap      | Action            | Notes                                   |
|-------------|-------------------|-----------------------------------------|
| `<space>`wd | CloseContent      | 'Window delete', closes the current tab |
| `<space>`wj | VimWindowDown     |                                         |
| `<space>`ws | SplitHorizontally |                                         |
| `<space>`wu | Unsplit           |                                         |
| `<space>`wv | SplitVertically   |                                         |
| `<space>`ww | VimWindowNext     | Nice to cycle through windows           |
| `<space>`wl | VimWindowRight    |                                         |
| `<space>`wh | VimWindowLeft     |                                         |
| `<space>`wk | VimWindowUp       |                                         |
| `<space>`wj | VimWindowDown     |                                         |

### Comments
| Keymap      | Action               |
|-------------|----------------------|
| `<space>`cl | CommentByLineComment |

### Refactor
| Keymap      | Action                            | Notes                        |
|-------------|-----------------------------------|------------------------------|
| `<space>`rr | Refactorings.QuickListPopupAction |                              |
| `<space>`ri | ShowIntentionActions              | Does the same as 'alt-Enter' |


