# Maintainer: Ben Standerline <standerlineben(at)g(mail)(dot)c(o)m>
pkgname=otf-san-francisco-full
pkgver=1.4
pkgrel=1
pkgdesc='The San Francisco font family (SF family)' 
arch=('any')
license=('custom')
url='https://developer.apple.com/fonts/'
depends=('fontconfig' 
		 'xorg-font-util')


source=(https://github.com/thelioncape/San-Francisco-family/archive/1.4.zip)

sha256sums=('30ef6b4460c4a20a20c6b3bf88e39d7ae43d59b75bc9c664688e70d4fbb36c5e')

package() {
  cd "$srcdir/San-Francisco-family-1.3"
  install -d $pkgdir/usr/share/fonts/OTF/SF
  install -d $pkgdir/usr/share/fonts/OTF/SF/Cash
  install -d $pkgdir/usr/share/fonts/OTF/SF/Camera
  install -d $pkgdir/usr/share/fonts/OTF/SF/CompactRounded
  install -d $pkgdir/usr/share/fonts/OTF/SF/Compact
  install -d $pkgdir/usr/share/fonts/OTF/SF/Condensed
  install -d $pkgdir/usr/share/fonts/OTF/SF/Hello
  install -d $pkgdir/usr/share/fonts/OTF/SF/Mono
  install -d $pkgdir/usr/share/fonts/OTF/SF/Pro
  install -d $pkgdir/usr/share/fonts/OTF/SF/Rounded
  install -d $pkgdir/usr/share/fonts/OTF/SF/Serif
  install -d $pkgdir/usr/share/fonts/OTF/SF/Shields
  install -d $pkgdir/usr/share/fonts/OTF/NY

  install -m644 SF\ Cash/*.otf $pkgdir/usr/share/fonts/OTF/SF/Cash
  install -m644 SF\ Camera/*.otf $pkgdir/usr/share/fonts/OTF/SF/Camera
  install -m644 SF\ Compact\ Rounded/*.otf $pkgdir/usr/share/fonts/OTF/SF/CompactRounded
  install -m644 SF\ Compact/*.otf $pkgdir/usr/share/fonts/OTF/SF/Compact
  install -m644 SF\ Condensed/*.otf $pkgdir/usr/share/fonts/OTF/SF/Condensed
  install -m644 SF\ Hello/*.otf $pkgdir/usr/share/fonts/OTF/SF/Hello
  install -m644 SF\ Mono/*.otf $pkgdir/usr/share/fonts/OTF/SF/Mono
  install -m644 SF\ Pro/*.otf $pkgdir/usr/share/fonts/OTF/SF/Pro
  install -m644 SF\ Rounded/*.otf $pkgdir/usr/share/fonts/OTF/SF/Rounded
  install -m644 SF\ Serif/*.otf $pkgdir/usr/share/fonts/OTF/SF/Serif
  install -m644 SF\ Shields/*.otf $pkgdir/usr/share/fonts/OTF/SF/Shields
  install -m644 New\ York/*.otf $pkgdir/usr/share/fonts/OTF/NY
}

