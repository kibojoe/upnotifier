# Maintainer: Holmes <holmes_holmes [at] live [dot] com>

pkgname=('jwm-documentation')
pkgver=16.06
pkgrel=1
pkgdesc='User Orientation Guide for Manjaro-JWM'
license=('CC-BY-SA 4.0')
arch=('any')
url="https://github.com/holmeslinux/$pkgname"
makedepends=('git')
source=("git+$url.git")
sha256sums=('SKIP')

package() {
  cd $srcdir/$pkgname
  install -Dm644 User_Orientation_Guide.pdf $pkgdir/usr/share/doc/livecd/User_Orientation_Guide.pdf
}