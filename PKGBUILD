# Maintainer: Andrea Diamantini <adjam@proton.me>

pkgname=nautilus-open-in-foot
pkgver=1.0.0
pkgrel=1
pkgdesc="Open current directory in foot from Nautilus context menu (forked from nautilus-open-in-ptyxis)"
arch=('any')
url="https://github.com/adjamhub/nautilus-open-in-foot"
license=('GPL3')
depends=('python-nautilus>=4.0')
makedepends=('git')

source=("$pkgname-latest.tar.gz::https://github.com/adjamhub/nautilus-open-in-foot/archive/refs/heads/main.tar.gz")

sha256sums=('SKIP')

package() {
    cd "$pkgname-main"
    install -Dm644 -t "$pkgdir/usr/share/nautilus-python/extensions" nautilus-open-in-foot.py
}
