# Maintainer: Phorcys <aur@phorcys.net>
pkgname=coder-bin
pkgver=2.19.1
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
sha256sums_x86_64=('c3cc844f88e9b8d9ff0ecc05949f10a4a4b962323d82cd0e4e64340f57f92591')
sha256sums_aarch64=('f0126b323d2cd8cce00ae796956b062a7b44901c16eeb058645fb93b79552cdd')
sha256sums_armv7h=('aa289415ef531a9f2e35fd55cfb772844cc50aabf3f6350b80421a339742f4d6')
