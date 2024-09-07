# Maintainer: José Gabriel Gruber <development at jgabrielgruber dot dev>
# Contributor: thdxr (original PKGBUILD)
# Contributor: Noel Jacob (bun-bin PKGBUILD)
pkgname=templ-bin
pkgver=0.2.648
pkgrel=2
pkgdesc="A language for writing HTML user interfaces in Go."
arch=('x86_64')
url="https://github.com/a-h/templ"
license=('MIT')
provides=('templ')
conflicts=('templ')
sha256sums_x86_64=("3abad775c8ef0ff42181158e58b6d8746be7d3e2e194974345d97556ad668259")
source_x86_64=("templ-x86-x64-${pkgver}.tar.gz::https://github.com/a-h/templ/releases/download/v${pkgver}/templ_Linux_x86_64.tar.gz")

package() {
  install -Dm755 "./templ" "${pkgdir}/usr/bin/templ"
}

