# Maintainer: MyHa-RX
pkgname=ercf
pkgver=1.0.0
pkgrel=1
pkgdesc="Easy Config Editor for Hyprland"
arch=('any')
url="https://github.com/MyHa-RX/ERCF"
license=('GPL3')
depends=('python' 'python-pyqt6' 'hyprpaper' 'git' 'hyprland')

package() {
    cd "$srcdir/../.."
    
    install -Dm755 ERCF/ERCF "$pkgdir/usr/bin/ERCF"
    install -Dm644 ERCF/ercf.desktop "$pkgdir/usr/share/applications/ercf.desktop"
    
    if [ -f "ERCF/ERCF.png" ]; then
        install -Dm644 ERCF/ERCF.png "$pkgdir/usr/share/icons/ERCF.png"
    fi
}
