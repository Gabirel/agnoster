# agnoster for FISH

A fish theme optimized for people who use:

- Solarized
- Git

For Mac users, I highly recommend `iTerm2` + `Solarized Dark`

# Compatibility

**NOTE:** In all likelihood, you will need to install a [Powerline-patched font](https://github.com/Lokaltog/powerline-fonts) for this theme to render correctly.

To test if your terminal and font support it, check that all the necessary characters are supported by copying the following command to your terminal: 

Fish user:
`echo \ue0b0 \u00b1 \ue0a0 \u27a6 \u2718 \u2621 \u2699`.

Bash or Zsh user:
`echo "\ue0b0 \u00b1 \ue0a0 \u27a6 \u2718 \u2621 \u2699"`.

The result should look like this:

![Character Example](https://gist.githubusercontent.com/Gabirel/df85f42bbf992ff40335eac07cdf09bf/raw/fbeea64d843bd5a8ce124220c23582b844bec90e/character-example.png)

## What does it show?

- If the previous command failed (✘)
- User @ Hostname (if user is not DEFAULT_USER, which can then be set in your profile)
- Git status
  - Branch (![branch-symbol](https://gist.githubusercontent.com/Gabirel/df85f42bbf992ff40335eac07cdf09bf/raw/c0b869c634a1fe5aff7f4794f5ba1af126a96111/branch-symbol.png)) or detached head (➦)
  - Current branch / SHA1 in detached head state
  - Dirty working directory (±, color change)
- Working directory
- Elevated (root) privileges (☡ )
    (NOTE: This is different from upstream because it may cause some issues. So I replaced it.)
- Background jobs hints(⚙)
- Time hints on the right
- Square status

![Screenshot](https://gist.githubusercontent.com/agnoster/3712874/raw/screenshot.png)
