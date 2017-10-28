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

* 2017.10

* Updated monthly by nxadm, a member of the perl6 github organization

* Centos and Fedora RPMs and Debian and Ubuntu .deb are available

* One single package used for rakudo, nqp and moarvm

## OpenSUSE packages

<https://build.opensuse.org/project/show/devel:languages:perl6>

* 2017.08

* Updated frequently by nine, a rakudo core developer

* Separate OpenSUSE RPMs available for rakudo, nqp and moarvm

* perl6-Inline-Perl5 is also available

## pkgsrc (Work in Progress)

<http://pkgsrc.se/wip/rakudo>

* pkgsrc is a cross-platform (UNIX-like) source build system. Binaries are
  available for some systems (including NetBSD). WIP is the experimental
  sub-system of pkgsrc.

* 2017.09

* Separate packages for rakudo, nqp and moarvm

## archlinux

<https://aur.archlinux.org/packages/rakudo/>

* 2017.09

* Separate packages for rakudo, nqp and moarvm

## OpenBSD Ports

<http://cvsweb.openbsd.org/cgi-bin/cvsweb/ports/lang/rakudo/>

* 2017.02

## Mac Homebrew

<https://github.com/Homebrew/homebrew-core/blob/master/Formula/rakudo-star.rb>

* Rakudo Star 2017.07

## Chocolately Rakudo Star (Windows)

<https://chocolatey.org/packages/rakudostar>

* 2017.07

* This is a packaging of Rakudo itself, moar, nqp and the modules of Rakudo Star

* It's built straight from the Rakudo Star Windows MSI usually released quarterly

## Rakudo Star Docker

* 2017.07

<https://hub.docker.com/_/rakudo-star/>

## AppImages of Rakudo and Rakudo Star

<https://github.com/samcv/rakudo-appimage-module-test-automation>

* AppImage is a cross-disto Linux packaging format which doesn't need root

* It's unclear which versions are available but they are several months old

