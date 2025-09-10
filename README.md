# dotfiles

## Installation

Install [chezmoi](https://www.chezmoi.io/):

```bash
sh -c "$(curl -fsLS get.chezmoi.io)"
```

Apply config:

```bash
chezmoi init https://github.com/rgzr/dotfiles.git
chezmoi apply
```

## Daily usage: syncing

Get updates from remote:

```bash
chezmoi update
```

See changes to be applied:

```bash
chezmoi diff
```

Apply changes:

```bash
chezmoi apply
```

## Daily usage: adding changes

