# dot-spacemacs


User configulation file `.spacemace` of Spacemacs, where

- The editing style is set to `emacs`.
    - You can switch between emacs mode and vim normal mode (or vim motion mode for a read-only buffer) by pressing C-z, After executing the M-x holy-mode command (which disables the holy-mode).
- The configulation layers are set up for the following languages:
    - C-C++, Java, JavaScript, TypeScript, Rust, python and R (ESS)
    - markdown, html

## Install

The installation procedure of Spacemacs is described in the official repository : https://github.com/syl20bnr/spacemacs

```
cd ~
mv .emacs.d .emacs.d.bak
mv .emacs .emacs.bak

git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d
```

Then replace the user setting file (`.spacemacs`) to this one.

```
mv .spacemacs .spacemacs.bak
git clone https://github.com/oogasawa/dot-spacemacs
mv dot-spacemacs/.spacemacs ~/.spacemacs
```


# References

- https://github.com/syl20bnr/spacemacs
- https://dev.to/viglioni/how-i-set-up-my-emacs-for-typescript-3eeh
    - ""How I set up my emacs for TypeScript + React" (2020)
- https://nasum.dev/2020/02/08/spacemacs-input-japanies/

