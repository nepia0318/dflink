# dflink

CLI tool for manage symbolic link for dotfiles.

`yq` is requirement (only `yq-go` is confirmed).

## Environment Value

| Name | Description | example |
| ---- | ---- | ---- |
| `DFLIST_YAML` | Path to YAML file in which link list described. | `${XDG_DATA_HOME}/dflist/dflist.yaml` |
| `DFLINK_DOTFILES_ROOT` | Path to original repository for dotfiles | `${HOME}/.dflink` |

## Usage

### Add

``` zsh
    dflink add [-r] [package] [file]
```

### Remove

``` zsh
    dflink rm [-r] [package] [file]
```
