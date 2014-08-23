Seti Theme (for Emacs)
======================

Dark theme ispired by [Atom Seti](https://github.com/jesseweed/seti-ui).

This theme tries to also give the [Atom](https://github.com/atom/atom) feel.

Installation
-----------
#### From Package (Melpa)

**M-x** `package-install` RET `seti-theme`.

#### Manual

Download `seti-theme.el` to the directory `~/.emacs.d/themes/`. Add this to your
`.emacs`:

```elisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")
```

You can load the theme now with:

`M-x load-theme RET seti`

To make it the default theme add to your `.emacs` file:

```elisp
(load-theme 'seti t)
```

Screenshots
-----------

#### General
![General](/img/seti-general.png)
#### C
![C](/img/seti-c.png)
#### Web (HTML JS)
![Web](/img/seti-web.png)
#### Elisp
![Elisp](/img/seti-elisp.png)
#### Dired
![Dired](/img/seti-dired.png)
#### Shell
![Shell](/img/seti-shell.png)
#### Org
![Org](/img/seti-org.png)
