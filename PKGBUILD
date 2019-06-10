pkgname=synergy
pkgver=4.2.0
_anotherpkgver=bf71f9af401e97d24fbc342cc746ac803ae53b7e
pkgrel=1
pkgdesc="Share one buggy mouse and one buggy keyboard between multiple buggy computers."
arch=('x86_64')
url="https://github.com/yupi2/synergy"
license=('GPLv2')
depends=()
source=("https://github.com/yupi2/synergy/releases/download/${pkgver}_master_${_anotherpkgver}/synergy_${pkgver}_master_${_anotherpkgver}.deb")
md5sums=('9fcc8a17e1e24ec51cdf576d9b845b3b')

package() {
    tar -xf data.tar.xz -C ${pkgdir}
    install -dm755 ${pkgdir}/usr/share/applications
    chmod -R go-w ${pkgdir}/usr
}
