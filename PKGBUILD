pkgname=yart
pkgver=1.$(date '+%Y.%m.%d_%H.%M.%S')
pkgrel=1
pkgdesc="images etc"
arch=(any)
license=('Unknown')

package() {
	 mkdir -p ${pkgdir}/usr/share/ppz/art
	 cp -a ${startdir}/{icons,wallpaper} ${pkgdir}/usr/share/ppz/art/
}
