# Maintainer: MyHa-RX <github@myha-rx>
pkgname=ercf
pkgver=0.5.0
pkgrel=1
pkgdesc="Config Editor for Hyprland"
arch=('any')
url="https://github.com/MyHa-RX/ERCF"
license=('GPL3')
depends=('python' 'python-pyqt6' 'hyprpaper' 'git' 'hyprland')
source=("file://ERCF"
        "file://ercf.desktop"
        "file://ERCF.png"
        "file://README.md"
sha256sums=('SKIP' 'SKIP' 'SKIP' 'SKIP' 'SKIP')

package() {
    
    install -Dm755 "$srcdir/ERCF" "$pkgdir/usr/bin/ERCF"
    
    
    install -Dm644 "$srcdir/ercf.desktop" "$pkgdir/usr/share/applications/ercf.desktop"
    
    
    install -Dm644 "$srcdir/ERCF.png" "$pkgdir/usr/share/icons/ERCF.png"
    
    
    install -Dm644 "$srcdir/README.md" "$pkgdir/usr/share/doc/$pkgname/README.md"
}
