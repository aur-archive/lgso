# Maintainer: WorMzy Tykashi <wormzy.tykashi@gmail.com>

pkgname=lgso
_gitname=LGSO
pkgver=1.41
pkgrel=1
pkgdesc="A utility to gather save games into a single sane location"
arch=(any)
url="https://github.com/Tux1c/LGSO"
license=('GPL2')
depends=('bash')
makedepends=('git')
source=("git+https://github.com/Tux1c/LGSO.git#tag=v$pkgver")
md5sums=("SKIP")

package() {
  cd "$srcdir/$_gitname"

  install -Dm755 lgso.sh "$pkgdir/usr/bin/lgso.sh"
  ln -s lgso.sh "$pkgdir/usr/bin/lgso"
}
