# Maintainer: Ben Standerline <standerlineben(at)g(mail)(dot)c(o)m>
pkgname=otf-san-francisco-full
pkgver=1.1
pkgrel=2
pkgdesc='The San Francisco font family (SF family)' 
arch=('any')
license=('custom')
url='https://developer.apple.com/fonts/'
depends=('fontconfig' 
		 'xorg-font-util')


source=(https://github.com/thelioncape/San-Francisco-family/archive/1.1.zip)

sha256sums=('c14ac36696a475f013968a7c844083605a3dbdec24b5db15737357c98d74a9c2')

package() {
  cd "$srcdir/San-Francisco-family-1.1"
  install -d $pkgdir/usr/share/fonts/OTF/SF
  install -d $pkgdir/usr/share/fonts/OTF/SF/CompactRounded
  install -d $pkgdir/usr/share/fonts/OTF/SF/Compact
  install -d $pkgdir/usr/share/fonts/OTF/SF/Hello
  install -d $pkgdir/usr/share/fonts/OTF/SF/Mono
  install -d $pkgdir/usr/share/fonts/OTF/SF/Pro
  install -d $pkgdir/usr/share/fonts/OTF/SF/Serif

  install -m644 SF\ Compact\ Rounded/*.otf $pkgdir/usr/share/fonts/OTF/SF/CompactRounded
  install -m644 SF\ Compact/*.otf $pkgdir/usr/share/fonts/OTF/SF/Compact
  install -m644 SF\ Hello/*.otf $pkgdir/usr/share/fonts/OTF/SF/Hello
  install -m644 SF\ Mono/*.otf $pkgdir/usr/share/fonts/OTF/SF/Mono
  install -m644 SF\ Pro/*.otf $pkgdir/usr/share/fonts/OTF/SF/Pro
  install -m644 SF\ Serif/*.otf $pkgdir/usr/share/fonts/OTF/SF/Serif
}

