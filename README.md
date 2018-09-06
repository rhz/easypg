# EasyPG (fork)

Fork of EasyPG (GnuPG interface for Emacs)
that signs when encrypting and verifies signatures when decrypting
by default in auto encryption mode.

The original code can be found at
https://git.savannah.gnu.org/cgit/emacs.git/.
In particular, the file that was modified is
https://git.savannah.gnu.org/cgit/emacs.git/tree/lisp/epa-file.el.

Documentation for EasyPG is available at
https://www.emacswiki.org/emacs/EasyPG and
https://www.gnu.org/software/emacs/manual/html_node/epa/index.html.

## How to use it
Clone the repo and add the following line to your `.emacs` file.
```
(add-to-list 'load-path (expand-file-name "~/path/to/repo/"))
```
