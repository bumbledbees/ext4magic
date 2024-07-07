# ext4magic

A fork of the popular Linux admin tool that can help recover deleted or overwritten files on ext3 and ext4 filesystems, which fixes a few new problems that have been introduced/discovered since the project was seemingly abandoned.

This repo is using ext4magic v0.3.2 as a base, which can be downloaded from [here](https://sourceforge.net/projects/ext4magic/files/ext4magic-0.3.2.tar.gz/download).


## Included patches:

- [This patch](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=854497;msg=10) from Markus, fixes [Debian bug report #854497](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=854497)
- [This patch](https://gitweb.gentoo.org/repo/gentoo.git/commit/?id=9d427990c39a9ab3cf97b6feb243e9f28620f79c) from Göktürk Yüksek, fixes [Gentoo bug report #650074](https://bugs.gentoo.org/650074)
- [This patch](https://gitweb.gentoo.org/repo/gentoo.git/commit/?id=029e17b98f838bdf8d1c6c1b89946db6dd63d2fe) from Mike Frysinger, fixes [Gentoo bug report #580192](https://bugs.gentoo.org/580192)
