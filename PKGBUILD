# Maintainer: Thibault Suzanne <thi [DOT] suzanne [AT] gmail [DOT] com>
pkgname=emacs-graphviz-dot-mode
pkgver=0.3.3
pkgrel=5
pkgdesc="Mode for the dot-language used by graphviz"
url="http://www.graphviz.org/Misc/graphviz-dot-mode.el"
source=${url}
arch=('any')
license=('GPL')
depends=('emacs')
md5sums=('e6d18201cf4b343df0537f8a415d9717')
install=emacs-graphviz-dot-mode.install

build() {
  cd ${startdir}/src
  install -Dm644 $srcdir/graphviz-dot-mode.el $pkgdir/usr/share/emacs/site-lisp/graphviz-dot-mode.el
}
