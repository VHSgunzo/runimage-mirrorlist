# Maintainer: VHSgunzo <vhsgunzo.github.io>

pkgname='runimage-mirrorlist'
pkgver='0.1'
pkgrel='1'
pkgbase="$pkgname"
pkgdesc='Pacman mirrorlist for RunImage container'
url="https://github.com/VHSgunzo/runimage-mirrorlist"
arch=('any')
license=('MIT')
source=('runimage-mirrorlist')
sha256sums=('SKIP')

package() {
  install -Dm644 runimage-mirrorlist "${pkgdir}/etc/pacman.d/runimage-mirrorlist"
}
