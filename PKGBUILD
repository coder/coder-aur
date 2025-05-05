# Maintainer: Phorcys <aur@phorcys.net>
pkgname=coder-bin
pkgver=2.17.0
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
sha256sums_x86_64=('e3cfe8c661b42237204b3ec3f3e41bf854db96ea3fb6ddf70c4ca1afb685feee')
sha256sums_aarch64=('b2e2e36ec3d7ecf1c2090c457da0555489c3ff3330d92f893a5f7b955c8781d8')
sha256sums_armv7h=('826c6cf7b2dc23eeb503e9aa6db5a21e34c40504ef0f710504a5417e16da76b1')
