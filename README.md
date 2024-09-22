# gitpod-tp-env

## Using Emacs in Gitpod (Cloud dev. env.) for OCaml/Coq

* Fork this repository (or use the template feature of GitHub)
* Login in [Gitpod](https://gitpod.io/login/) using your **GitHub** account
* Open your [Gitpod **Preferences**](https://gitpod.io/user/preferences)
  * Set your **Dotfiles Repository URL**: `https://github.com/erikmd/gitpod-workspace-emacs-nw`
* Open [the **Gitpod URL** `https://gitpod.io/new/?autostart=false&editor=xterm`](https://gitpod.io/new/?autostart=false&editor=xterm)
  * Fill the form with **the URL of your own GitHub repository**
  * Select the **`Terminal` editor** and click on `Continue`
* If ever the loading takes too much time, try to reload the tab once (<kbd>Ctrl+R</kbd>)
* Run `emacs` in the workspace shell (based on [`tmux`](https://github.com/tmux/tmux/wiki))
* Note the existence of the `(?)` special menu in Emacs, also:
   * type <kbd>Alt+F1</kbd> or <kbd>Ctrl+F1</kbd> to get some help on the main key bindings;
   * type <kbd>F7</kbd> to disable xterm-mouse-mode and thus allow copy-and-paste with the mouse.
* You may also be interested in the [Gitpod **Browser Extension**](https://www.gitpod.io/docs/configure/user-settings/browser-extension) to create workspaces more easily from other repositories/PRs.

## At the end of the session

* You can save your work by using Git commands, for example:  
  `git commit -a -m "WIP" && git push`
* Otherwise, you might want to `Pin` the workspace in <https://gitpod.io/workspaces>.
