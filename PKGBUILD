# Maintainer: archtux <antonio dot arias99999 at gmail.com>

pkgname=plasmoid-webcamoid
pkgver=2.2.0
pkgrel=1
pkgdesc="Plasmoid to take photos with your webcam."
arch=('any')
url="http://kde-apps.org/content/show.php/Webcamoid?content=144796"
license=('GPL3')
depends=('ffmpeg' 'kdebindings-python2' 'python2')
source=(http://kde-apps.org/CONTENT/content-files/144796-webcamoid.plasmoid)
md5sums=('01e2ff998f5fa246e1863f0ea612459e')

package() {
  cd $srcdir/Webcamoid
  install -dm755 $pkgdir/usr/share/apps/plasma/plasmoids/webcamoid
  cp -R * $pkgdir/usr/share/apps/plasma/plasmoids/webcamoid
  install -Dm644 metadata.desktop $pkgdir/usr/share/kde4/services/plasmoid-webcamoid.desktop
}