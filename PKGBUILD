# Maintainer: Mark Phillip <thelioncape(at)gmail(dot)com>
pkgname=otf-san-francisco-full
pkgver=1.0
pkgrel=1
pkgdesc='The San Francisco font family (SF family)' 
arch=('any')
license=('custom')
url='https://developer.apple.com/fonts/'
depends=('fontconfig' 
		 'xorg-font-utils'
		 'fakeroot')


source=(git+https://github.com/thelioncape/San-Francisco-family.git)

sha256sums=('SKIP')

package() {
  cd "$srcdir/San-Francisco-family"

  install -d $pkgdir/usr/share/fonts/OTF/SF
  install -d $pkgdir/usr/share/fonts/OTF/SF/Compact
  install -d $pkgdir/usr/share/fonts/OTF/SF/Hello
  install -d $pkgdir/usr/share/fonts/OTF/SF/Mono
  install -d $pkgdir/usr/share/fonts/OTF/SF/Pro
  install -d $pkgdir/usr/share/fonts/OTF/SF/Serif

  install -m644 SF\ Compact/*.otf $pkgdir/usr/share/fonts/OTF/SF/Compact
  install -m644 SF\ Hello/*.otf $pkgdir/usr/share/fonts/OTF/SF/Hello
  install -m644 SF\ Mono/*.otf $pkgdir/usr/share/fonts/OTF/SF/Mono
  install -m644 SF\ Pro/*.otf $pkgdir/usr/share/fonts/OTF/SF/Pro
  install -m644 SF\ Serif/*.otf $pkgdir/usr/share/fonts/OTF/SF/Serif
}

