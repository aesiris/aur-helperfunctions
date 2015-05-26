# Maintainer: aesiris

_pkgname='aur-helperfunctions'
pkgname='aur-helperfunctions'
pkgver=1.2.5
pkgrel=1
pkgdesc='Collection of bash functions that help managing a local repo of AUR packages'
arch=('any')
license=('GPL')
depends=('jshon' 'wget')
makedepends=('git')
backup=('etc/aur-helperfunctions.conf')
source=("git://github.com/aesiris/${_pkgname}#tag=${pkgver}")
sha256sums=('SKIP')

package() {
	cd "$srcdir/${_pkgname}"
	install -Dm644 "$pkgname" "$pkgdir/usr/bin/$pkgname"
	install -Dm644 "aur-helperfunctions.conf" "$pkgdir/etc/aur-helperfunctions.conf"

	#gzip -9 man.manpage
	#install -Dm 0644 man.manpage.gz "$pkgdir/usr/share/man/man1/$pkgname.1.gz"
}
