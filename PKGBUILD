# Maintainer: Phorcys <aur@phorcys.net>
pkgname=coder-bin
pkgver=2.20.2
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
sha256sums_x86_64=('414210b9a9541dbd18522d8973237566639fe143bac13deb039ded973aba58a2')
sha256sums_aarch64=('22b9d31a6bdc5f80bd72f7623db9a1c4b758145f8224eac7b3c77d21f8087f39')
sha256sums_armv7h=('2ceabbbe3d6be444366f8b292377be0f908010f04d9d1bb8bdd1f3d40d84e916')
