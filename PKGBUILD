# Maintainer: Oliver Sherouse <oliver DOT sherouse AT gmail DOT com>
_pkgname=us
pkgname=python2-$_pkgname
pkgver=0.7
pkgrel=1
pkgdesc="A module for fetching information about US states"
arch=("any")
url="http://pypi.python.org/pypi/us"
license=('BSD')
depends=('python2')
options=(!emptydirs)
install=
source=(http://pypi.python.org/packages/source/u/$_pkgname/$_pkgname-$pkgver.tar.gz)
md5sums=('a2ae2b09a5beb1a5f279e544ba1c4a76')
package() {
  cd "$srcdir/$_pkgname-$pkgver"
  python setup.py install --root="$pkgdir/" --optimize=1
}

# vim:set ts=2 sw=2 et:
