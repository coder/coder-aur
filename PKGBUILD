# Maintainer: Phorcys <aur@phorcys.net>
pkgname=coder-bin
pkgver=2.21.0
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
sha256sums_x86_64=('092651d2f648f44c8ab8e5f3bb16364c4941ac563ae74711eeb776b2447fbf7b')
sha256sums_aarch64=('8e925a691515460d6dfcf0b8ce7ccd08a7d6779763a95db1e3ac625e04c4d026')
sha256sums_armv7h=('98cae0a3fd056eba7511c6897e2c7ce244b5d3dd1ab244dc196d5ba478d76b71')
