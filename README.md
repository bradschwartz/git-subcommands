# git-subcommands

Some helpful commands that interface cleanly with git as subcommands.

## Tools

### git-home

Inspired by Homebrew's `home` command. Takes either a remote name or defaults
to `origin` and opens it in your default browser.

```bash
git home # opens `origin` URL
git home fork # opens `fork` URL
```

### git-org-clone

Helps keep code all in one place. No matter where you're at, clones provided
repo to `$HOME/code/${org}/{repo}`.

```bash
git org-clone https://github.com/bradschwartz/git-subcommands.git
cd $HOME/code/bradschwartz/git-subcommands # now created
```

## Installation

Tap my personal Homebrew Tap

```bash
brew tap bradschwartz/bradschwartz
brew install bradschwartz/bradschwartz/git-subcommands
```

Or manually clone this repo and add to your `PATH`