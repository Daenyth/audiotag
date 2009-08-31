# Maintainer: Daenyth <Daenyth+Arch [at] gmail [dot] com>
# Contributor: Jarosla Lichtblau <dragonlord@aur.archlinux.org>

pkgname=audiotag
pkgver=0.19
pkgrel=1
pkgdesc="A command-line tool for mass tagging/renaming of audio files."
arch=('i686' 'x86_64')
url="http://github.com/Daenyth/audiotag/"
license=('GPL')
depends=('flac' 'vorbis-tools' 'id3lib' 'perl' 'atomicparsley')
source=(http://github.com/Daenyth/audiotag/tarball/v$pkgver)

md5sums=('4682cfe01c89dc0b7fc14aef61344579')

build() {
  cd "${srcdir}/$pkgname-$pkgver"

  install -D -m755 "${pkgname}" "${pkgdir}/usr/bin/${pkgname}"
}
