# Maintainer: MyHa-RX <github@myha-rx>
pkgname=ercf
pkgver=1.0.0
pkgrel=1
pkgdesc="Easy Config Editor for Hyprland - графический редактор конфигов"
arch=('any')
url="https://github.com/MyHa-RX/ERCF"
license=('GPL3')
depends=('python' 'python-pyqt6' 'hyprpaper' 'git' 'hyprland')
source=("file://ERCF"
        "file://ercf.desktop"
        "file://ERCF.png"
        "file://README.md"
        "file://LICENSE")
sha256sums=('SKIP' 'SKIP' 'SKIP' 'SKIP' 'SKIP')

package() {
    
    install -Dm755 "$srcdir/ERCF" "$pkgdir/usr/bin/ERCF"
    
    
    install -Dm644 "$srcdir/ercf.desktop" "$pkgdir/usr/share/applications/ercf.desktop"
    
    
    install -Dm644 "$srcdir/ERCF.png" "$pkgdir/usr/share/icons/ERCF.png"
    
    
    install -Dm644 "$srcdir/README.md" "$pkgdir/usr/share/doc/$pkgname/README.md"
}
