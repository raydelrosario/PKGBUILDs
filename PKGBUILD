# Maintainer: Michael Del Rosario <m@delrosariomichael.com>
pkgname='kubecolor'
pkgver=0.0.11
pkgrel=1
pkgdesc='Colorize your kubectl output'
url='https://github.com/dty1er/kubecolor'
arch=('x86_64')
license=('MIT')
depends=('kubectl')
source=("https://github.com/dty1er/kubecolor/releases/download/v${pkgver}/kubecolor_${pkgver}_Linux_${arch}.tar.gz")
md5sums=('8458d15752ecdc1611e823fbd2c4fd1d')

package() {
	cd "$srcdir/"
	install -Dm755 ${pkgname} -t ${pkgdir}/usr/bin/
}
md5sums=('8458d15752ecdc1611e823fbd2c4fd1d')
