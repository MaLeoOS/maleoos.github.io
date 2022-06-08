## MaLeo OS

This is not only a desktop, this is a new operating system.
The MaLeo OS is about develop soon.

### About MaLeo OS

MaLeo OS will be based on Arch Linux. This operating system is made only for fun.
More information soon.


### Installation Guide

The OS is based on Arch Linux, so installation will be the same as a Arch Linux.
MaLeo OS can be installed from USB flash.

Verify signature
It is recommended to verify the image signature before use, especially when downloading from an HTTP mirror, where downloads are generally prone to be intercepted to serve malicious images.

On a system with GnuPG installed, do this by downloading the PGP signature (under Checksums in the Download page) to the ISO directory, and verifying it with:

```markdown
$ gpg --keyserver-options auto-key-retrieve --verify archlinux-version-x86_64.iso.sig
```

Alternatively, from an existing Arch Linux installation run:

```markdown
$ pacman-key -v archlinux-version-x86_64.iso.sig
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/MaLeoOS/maleoos.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
