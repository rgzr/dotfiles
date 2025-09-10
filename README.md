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

Add a new file:

```bash
chezmoi add $FILE
```

Edit the file:

```bash
chezmoi edit $FILE
```

Check changes:

```bash
chezmoi status
chezmoi diff
```

Apply them:

```bash
chezmoi apply
```

Push to repo:

```bash
chezmoi cd
git status
git add .
git commit -m $MESSAGE
git push
```

## Daily usage: removing files

Remove file:

```bash
chezmoi remove $FILE
```

Check changes:

```bash
chezmoi status
chezmoi diff
```

Apply them:

```bash
chezmoi apply
```

Push to repo.
