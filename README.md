# rakudo-packages

A list of actively maintained packaged binary (and third party source)
distributions for Rakudo Perl 6. 

Rakudo itself comprises of rakudo, NQP and MoarVM. Potentially other backends
can replace MoarVM.  Rakudo Star comprises of rakudo, third party modules and
documentation.

Most UNIX-like packaging systems probably should look at packaging Rakudo as
its three components plus modules.  Rakudo Star might often be a meta package
although packaging systems often differ.

Versions available accurate as of 20171028 but check for updates.

## nxadm's packages

<https://github.com/nxadm/rakudo-pkg/releases>

* Updated monthly by nxadm, a member of the perl6 github organization

* Centos and Fedora RPMs and Debian and Ubuntu .deb are available

* One single package used for rakudo, nqp and moarvm

## OpenSUSE packages

<https://build.opensuse.org/project/show/devel:languages:perl6>

* Updated by nine, a rakudo core developer

* Separate OpenSUSE RPMs available for rakudo, nqp and moarvm

* perl6-Inline-Perl5 is also available

## pkgsrc (Work in Progress)

<http://pkgsrc.se/wip/rakudo>

* pkgsrc is a cross-platform (UNIX-like) source build system. Binaries are
  available for some systems (including NetBSD). WIP is the experimental
  sub-system of pkgsrc.

* Separate packages for rakudo, nqp and moarvm

## archlinux

<https://aur.archlinux.org/packages/rakudo/>

* Separate packages for rakudo, nqp and moarvm

## Debian packages
<https://packages.debian.org/search?keywords=rakudo>

* stretch (stable) 2016.12

* buster (testing) 2017.06

* sid (unstable) 2018.01 (amd64 etc.)

## OpenBSD Ports

<http://cvsweb.openbsd.org/cgi-bin/cvsweb/ports/lang/rakudo/>

## Mac Homebrew

<https://github.com/Homebrew/homebrew-core/blob/master/Formula/rakudo-star.rb>

* Rakudo Star 2017.07

## Chocolately Rakudo Star (Windows)

<https://chocolatey.org/packages/rakudostar>

* This is a packaging of Rakudo itself, moar, nqp and the modules of Rakudo Star

* It's built straight from the Rakudo Star Windows MSI usually released quarterly

## Rakudo Star Docker

<https://hub.docker.com/_/rakudo-star/>

## AppImages of Rakudo and Rakudo Star

<https://github.com/samcv/rakudo-appimage-module-test-automation>

* AppImage is a cross-disto Linux packaging format which doesn't need root
