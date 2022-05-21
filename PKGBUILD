pkgname=dloader
pkgver=1.0
pkgrel=1
verdir=1.0
pkgdesc="update tool for unisoc chipset "
arch=('x86_64')
license=('MIT')
source=(
	"git+https://github.com/topwuther/dloader.git"
)

prepare() {
    cd "${srcdir}"
}

package() {
	cd dloader
	make
	install -D -m755 dloader "${pkgdir}/usr/bin/dloader"
}
sha256sums=('SKIP')
