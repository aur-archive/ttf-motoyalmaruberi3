# Maintainer: woegjiub <woegjiub@woegjiub.com>

pkgname=ttf-motoyalmaruberi3
pkgver=20140816
pkgrel=1
pkgdesc="A Round Gothic font by Motoya Corporation, Android's Japanese font."
arch=('any')
license=('Apache')
url="http://android.googlesource.com"
depends=('fontconfig' 'xorg-font-utils')
source=(https://github.com/android/platform_frameworks_base/raw/master/data/fonts/MTLmr3m.ttf)
md5sums=('fa41f2cdecf512b52f7d673252fb1632')
install=ttf.install

build() {
	cd ${srcdir}
}

package(){
	install -d ${pkgdir}/usr/share/fonts/TTF
	install -m655 *.ttf ${pkgdir}/usr/share/fonts/TTF
}

