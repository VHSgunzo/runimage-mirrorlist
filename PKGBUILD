# Maintainer: VHSgunzo <vhsgunzo.github.io>

pkgname='runimage-mirrorlist'
pkgver='0.6'
pkgrel='1'
pkgdesc='Pacman mirrorlist for RunImage container'
url="https://github.com/VHSgunzo/runimage-mirrorlist"
arch=('any')
license=('MIT')
source=('runimage-mirrorlist')
sha256sums=('SKIP')
install='mirrorlist.install'

package() {
  install -Dm644 'runimage-mirrorlist' "${pkgdir}/etc/pacman.d/runimage-mirrorlist"
}
