pkgname=semantic-release
pkgver=1.1.1
pkgrel=0
pkgdesc='poor mans semantic-release'
arch=('any')
url='https://github.com/arlac77/poor-mans-semantic-release.git'
license=('MIT')
depends=(perl)
public=true

package() {
    install -dm755 "$pkgdir/usr/bin"
    install -Dm755 $srcdir/../semantic-release "$pkgdir/usr/bin"
}