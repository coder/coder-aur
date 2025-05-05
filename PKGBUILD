# Maintainer: Phorcys <aur@phorcys.net>
pkgname=coder-bin
pkgver=2.20.1
pkgrel=2
pkgdesc='Remote development environments on your infrastructure provisioned with Terraform'
arch=('x86_64' 'aarch64' 'armv7h')
url='https://coder.com'
license=('Proprietary' 'AGPL3')
provides=('coder' 'coder-client')
conflicts=()

source_x86_64=("https://github.com/coder/coder/releases/download/v${pkgver}/coder_${pkgver}_linux_amd64.tar.gz")
source_aarch64=("https://github.com/coder/coder/releases/download/v${pkgver}/coder_${pkgver}_linux_arm64.tar.gz")
source_armv7h=("https://github.com/coder/coder/releases/download/v${pkgver}/coder_${pkgver}_linux_armv7.tar.gz")

package() {
	cd "$srcdir"

	install -Dm755 coder "${pkgdir}/usr/bin/coder"
}
sha256sums_x86_64=('a6d256500f93e8bf1f1fd5564f83124a6bab94258d697f96d3178caa95b9c80f')
sha256sums_aarch64=('126ba5c80f5fbb61e100bf2deb2507cf3770398500eff0b51de1d92ce62003f5')
sha256sums_armv7h=('d3f5749f1b722f8465983c87b4b3aced3d2abc8f355b2e419807f2d1230ab149')
