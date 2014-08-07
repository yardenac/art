pkgname=yart
pkgver=1.$(date '+%Y.%m.%d_%H.%M.%S')
pkgrel=1
pkgdesc="images etc"
arch=(any)
license=('Unknown')

package() {

	 mkdir -p ${pkgdir}/usr/share/ppz/art
	 cp -a ${startdir}/wallpaper ${pkgdir}/usr/share/ppz/art/wallpaper

	 mkdir -p ${pkgdir}/usr/share/icons/hicolor/48x48/apps
	 cp -a ${startdir}/icons/xfce-terminal.png ${pkgdir}/usr/share/icons/hicolor/48x48/apps/

}
