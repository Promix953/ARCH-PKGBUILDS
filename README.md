## paru config

```shell
cp /etc/paru.conf ~/.config/paru/paru.conf
```

``` toml
#
# $PARU_CONF
# /etc/paru.conf
# ~/.config/paru/paru.conf
#
# See the paru.conf(5) manpage for options

#
# GENERAL OPTIONS
#
[options]
PgpFetch
Devel
Provides
DevelSuffixes = -git -cvs -svn -bzr -darcs -always -hg -fossil
#AurOnly
#BottomUp
#RemoveMake
#SudoLoop
#UseAsk
#SaveChanges
#CombinedUpgrade
#CleanAfter
#UpgradeMenu
#NewsOnUpgrade

#LocalRepo
#Chroot
#Sign
#SignDb
#KeepRepoCache

#
# Binary OPTIONS
#
#[bin]
#FileManager = vifm
#MFlags = --skippgpcheck
#Sudo = doas

[custom]
Url = https://github.com/Promix953/ARCH-PKGBUILDS
GenerateSrcinfo
```