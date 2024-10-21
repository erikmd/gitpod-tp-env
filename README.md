# gitpod-tp-env

## Using Emacs in Gitpod (Cloud dev. env.) for OCaml/Coq

1. Fork this repository (or use GitHub's template feature) so that it includes this [.gitpod.yml](./.gitpod.yml) file.
2. Log in [Gitpod Classic](https://gitpod.io/login/) using your **GitHub** account.
3. Open your [Gitpod **Preferences**](https://gitpod.io/user/preferences)
   * Set your **Dotfiles Repository URL**: `https://github.com/erikmd/gitpod-workspace-emacs-nw`
4. Open [the **Gitpod URL** `https://gitpod.io/new/?autostart=false&editor=xterm`](https://gitpod.io/new/?autostart=false&editor=xterm)
   * Fill the form with **the URL of your own GitHub repository**
   * Select the **`Terminal` editor** and click on `Continue`
   * If ever the loading takes too much time, try to reload the tab once (<kbd>Ctrl+R</kbd>)
5. Run `emacs` in the workspace shell (based on [`tmux`](https://github.com/tmux/tmux/wiki))
6. Note the existence of the `(?)` special menu in Emacs, also:
   * type <kbd>Alt+F1</kbd> or <kbd>Ctrl+F1</kbd> to get some help on the main key bindings;
   * type <kbd>F7</kbd> to disable xterm-mouse-mode and thus allow copy-and-paste with the mouse.
7. Open an OCaml (<kbd>C-x C-f code.ml RET</kbd>) or Coq (<kbd>C-x C-f code.v RET</kbd>) file.

> [!TIP]
> You may also be interested in the [Gitpod **Browser Extension**](https://www.gitpod.io/docs/configure/user-settings/browser-extension) to create workspaces more easily from other repositories/PRs.

## At the end of the session

* You can save your work by using Git commands, for example:  
  `git commit -a -m "WIP" && git push`
* Otherwise, you might want to `Pin` the workspace in <https://gitpod.io/workspaces>.

## Screenshots

### `tmux` session at startup

<a href="https://github.com/erikmd/gitpod-tp-env/raw/master/images/2024_Screenshot_Gitpod_1.png"><img alt="gitpod-classic + terminal-browser + tmux" width="754px" src="https://github.com/erikmd/gitpod-tp-env/raw/master/images/2024_Screenshot_Gitpod_1.png"></a>

### `emacs` in tty mode with mouse enabled

<a href="https://github.com/erikmd/gitpod-tp-env/raw/master/images/2024_Screenshot_Gitpod_2.png"><img alt="gitpod-classic + terminal-browser + emacs" width="754px" src="https://github.com/erikmd/gitpod-tp-env/raw/master/images/2024_Screenshot_Gitpod_2.png"></a>

## Limitation

This approach relies on the Gitpod Classic plans which are intended to
be replaced with [Gitpod Flex](https://www.gitpod.io/pricing) after
April 2025.
