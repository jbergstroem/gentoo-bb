### gentoobb/jdk-icedtea:20141204
Built: Sun Dec  7 17:44:05 CET 2014

Image Size: 256.1 MB
#### Installed
Package | USE Flags
--------|----------
app-admin/eselect-java-0.1.0 | ``
app-portage/portage-utils-0.53 | `nls -static`
dev-java/icedtea-bin-6.1.13.5 | `-`
dev-java/java-config-2.2.0 | ` `
dev-java/java-config-wrapper-0.16 | ``
dev-lang/python-exec-2.0.1-r1 | ` `
media-libs/giflib-4.1.6-r3 | `-`
media-libs/lcms-2.6-r1 | `threads zlib -doc -jpeg -static-libs {-test} -tiff`
media-libs/libjpeg-turbo-1.3.1 | `-java -static-libs`
media-libs/libpng-1.6.12 | `-apng (-neon) -static-libs`
sys-apps/baselayout-java-0.1.0 | ``
#### Inherited
Package | USE Flags
--------|----------
**FROM gcc** |
dev-libs/gmp-5.1.3-r1 | `cxx -doc -pgo -static-libs`
dev-libs/mpc-1.0.1 | `-static-libs`
dev-libs/mpfr-3.1.2-r1 | `-static-libs`
sys-devel/binutils-2.24-r3 | `cxx nls zlib (-multislot) -multitarget -static-libs {-test} -vanilla`
sys-devel/binutils-config-3-r3 | ``
sys-devel/gcc-4.8.3 | `cxx fortran nls nptl openmp sanitize (-altivec) -awt -doc (-fixed-point) -gcj -go -graphite (-hardened) (-libssp) -mudflap (-multilib) (-multislot) -nopie -nossp -objc -objc`
sys-devel/gcc-config-1.7.3 | ``
sys-devel/make-4.0-r1 | `nls -guile -static`
sys-kernel/linux-headers-3.16 | ``
**FROM bash** |
app-admin/eselect-1.4.3 | `-doc -emacs -vim-syntax`
app-shells/bash-4.2_p53 | `net nls (readline) -afs -bashlogger -examples -mem-scramble -plugins -vanilla`
net-misc/curl-7.39.0 | `ipv6 ssl threads -adns -idn -kerberos -ldap -metalink -rtmp -ssh -static-libs {-test}`
sys-apps/file-5.19 | `zlib -python -static-libs`
sys-apps/sed-4.2.1-r1 | `acl nls (-selinux) -static`
sys-libs/ncurses-5.9-r3 | `cxx unicode -ada -debug -doc -gpm -minimal -profile -static-libs -tinfo -trace`
sys-libs/readline-6.2_p5-r1 | `-static-libs`
**FROM openssl** |
app-misc/ca-certificates-20130906-r1 | ``
dev-libs/openssl-1.0.1j | `bindist (sse2) tls-heartbeat zlib -gmp -kerberos -rfc3779 -static-libs {-test} -vanilla`
sys-apps/acl-2.2.52-r1 | `nls -static-libs`
sys-apps/attr-2.4.47-r1 | `nls -static-libs`
sys-apps/coreutils-8.21 | `acl nls -caps -gmp (-selinux) -static -vanilla -xattr`
sys-apps/debianutils-4.4 | `-static`
**FROM s6** |
dev-lang/execline-1.3.1.1 | `-static-libs`
dev-libs/skalibs-1.6.0.0 | `-doc -static-libs`
sys-apps/s6-1.1.3.2 | ``
*manual install*: entr-2.9 | http://entrproject.org/
**FROM busybox** |
sys-apps/busybox-1.21.0 | `ipv6 make-symlinks pam -livecd -math -mdev -savedconfig (-selinux) -sep-usr -static -syslog -systemd`
sys-auth/pambase-20120417-r3 | `cracklib sha512 -consolekit -debug -gnome-keyring -minimal -mktemp -pam`
sys-libs/cracklib-2.9.1-r1 | `nls zlib -python -static-libs {-test}`
sys-libs/db-4.8.30-r1 | `cxx -doc -examples -java -tcl {-test}`
sys-libs/glibc-2.19-r1 | `-debug -gd (-hardened) (-multilib) -nscd -profile (-selinux) -suid -systemtap -vanilla`
sys-libs/pam-1.1.8-r2 | `berkdb cracklib nls -audit -debug -nis (-selinux) {-test} -vim-syntax`
sys-libs/timezone-data-2014i-r1 | `nls -right`
sys-libs/zlib-1.2.8-r1 | `-minizip -static-libs`
#### Purged
- [x] Headers
- [x] Static Libs
