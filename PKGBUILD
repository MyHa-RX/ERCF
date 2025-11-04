pkgname=ercf
pkgver=1.0.0
pkgrel=1
pkgdesc="Easy Config Editor for Hyprland - графический редактор конфигов"
arch=('any')
url="https://github.com/MyHa-RX/ERCF"
license=('GPL3')
depends=('python' 'python-pyqt6' 'hyprpaper' 'git' 'hyprland')
source=("$pkgname-$pkgver.tar.gz::https://github.com/MyHa-RX/ERCF/archive/$pkgver.tar.gz")
sha256sums=('SKIP')

package() {
    cd "$srcdir/ERCF-$pkgver"
    
    
    install -Dm755 ERCF "$pkgdir/usr/bin/ERCF"
    
    
    install -Dm644 ercf.desktop "$pkgdir/usr/share/applications/ercf.desktop"
    
    
    if [ -f "ERCF.png" ]; then
        install -Dm644 ERCF.png "$pkgdir/usr/share/icons/ERCF.png"
    fi
    
    
    if [ -f "README.md" ]; then
        install -Dm644 README.md "$pkgdir/usr/share/doc/$pkgname/README.md"
    fi
    if [ -f "LICENSE" ]; then
        install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
    fi
}