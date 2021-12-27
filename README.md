# yasnippet-lean

Lean snippets for the `yasnippet` package.

![yasnippet-lean demo](yasnippet-lean-test.gif "Typing Lean code fast")

# New

 * snippets for Lean 4

# How to install

## From melpa

You can install this package from melpa, by first ensuring that you have the melpa source in your package-archives.

```lisp
(require 'package)
(add-to-list 'package-archives
             '("melpa" . "http://melpa.milkbox.net/packages/") t)
(package-initialize)
```

Once that is done, then just refresh the packages and install it with.

* <kbd>M-x package-refresh-contents</kbd>
* <kbd>M-x package-install yasnippet-snippets</kbd>

Now all the snippets will load automatically, as soon as yasnippet loads.

## Using `use-package`

(use-package yasnippet
  :ensure t)

# Contributing

If you have any useful snippets for Lean, then please feel free to contribute, by opening a PR or an issue if you have any suggestions.

To study the current snippets, I suggest that you use `M-x yas-describe-tables`,
which will show a table representation of all the snippets that are available in the current mode.
