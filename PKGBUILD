# Maintainer: Phorcys <aur@phorcys.net>
pkgname=coder-bin
pkgver=2.21.3
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
sha256sums_x86_64=('9f94415e38e351f828d71613d5ab6223733ae7f91024d1e443cab48cf89f4458')
sha256sums_aarch64=('202230932bb89555e5b03cddd2eaef770eeef7c3cb3c2967667dbba81333e20b')
sha256sums_armv7h=('42ef62cf52999ea8e2b42d26320938595df6878b4b1bb7c4448d5f58e7dcee7c')
