
# Maintainer: Eshan Roy <src.eshan@gmail.com>

pkgname=snigdhaos-chromium-settings
org=eshanizedos
pkgver=1.0.0
pkgrel=1
pkgdesc="Snigdha OS Chrome Config!"
arch=('any')
url="https://github.com/$org/$pkgname"
license=("GPL3")
depends=('gnome-keyring')
source=("psd.conf"
        "$pkgname.tar.gz")

package() {
  install -dm 755 "${pkgdir}/etc/skel/.config/chromium/"
  install -dm 755 "${pkgdir}/etc/skel/.config/psd"

  cp -rf "${srcdir}/chromium" "${pkgdir}/etc/skel/.config/"
  cp -rf "${srcdir}/psd.conf" "${pkgdir}/etc/skel/.config/psd/"  
  
}
sha512sums=('SKIP'
            'SKIP')
