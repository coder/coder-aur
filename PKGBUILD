# Maintainer: Phorcys <aur@phorcys.net>
pkgname=coder-bin
pkgver=2.16.1
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
sha256sums_x86_64=('32ffb8c45ba2973194e1c70385cf97864e7e70df22c40f00a62e72389b50db16')
sha256sums_aarch64=('1f34bb34a9da825cdcb4414b9e630357a3f804f34eaaa0af4f563a88effe6b6b')
sha256sums_armv7h=('513b78e341a5062cf281dc8bc501a36101857767e9ba161f4197a0b31d542a5f')
