pkgname=semantic-release
pkgver=1.1.0
pkgrel=0
pkgdesc='poor mans semantic-release'
arch=('any')
url='https://github.com/arlac77/poor-mans-semantic-release.git'
license=('CUSTOM')
depends=(perl)
public=true

package() {
    install -dm755 "$pkgdir/usr/bin"
    install -Dm644 $srcdir/../semantic-release "$pkgdir/usr/bin"
}