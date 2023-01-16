# Maintainer: Ben Standerline <standerlineben(at)g(mail)(dot)c(o)m>
pkgname=otf-san-francisco-full
pkgver=1.3
pkgrel=1
pkgdesc='The San Francisco font family (SF family)' 
arch=('any')
license=('custom')
url='https://developer.apple.com/fonts/'
depends=('fontconfig' 
		 'xorg-font-util')


source=(https://github.com/thelioncape/San-Francisco-family/archive/1.3.zip)

sha256sums=('133112553d4775175e08418afbd56833a80c02a140741ac77e72216b8323be62')

package() {
  cd "$srcdir/San-Francisco-family-1.3"
  install -d $pkgdir/usr/share/fonts/OTF/SF
  install -d $pkgdir/usr/share/fonts/OTF/SF/Cash
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

