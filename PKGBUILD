# Maintainer: MyHa-RX
pkgname=ercf
pkgver=0.5.0
pkgrel=1
pkgdesc="Config Editor for Hyprland"
arch=('any')
url="https://github.com/MyHa-RX/ERCF"
license=('GPL3')
depends=('python' 'python-pyqt6' 'hyprpaper' 'git' 'hyprland')

package() {
    cd "$srcdir/.."
    
    install -Dm755 ERCF "$pkgdir/usr/bin/ERCF"
    install -Dm644 ercf.desktop "$pkgdir/usr/share/applications/ercf.desktop"
    
    if [ -f "ERCF.png" ]; then
        install -Dm644 ERCF.png "$pkgdir/usr/share/icons/ERCF.png"
    fi
}
