# Maintainer: José Gabriel Gruber <development at jgabrielgruber dot dev>
# Contributor: thdxr (original PKGBUILD)
# Contributor: Noel Jacob (bun-bin PKGBUILD)
pkgname=templ-bin
pkgver=0.2.771
pkgrel=2
pkgdesc="A language for writing HTML user interfaces in Go."
arch=('x86_64')
url="https://github.com/a-h/templ"
license=('MIT')
provides=('templ')
conflicts=('templ')
sha256sums_x86_64=('216aff42df8a7eb8855a0ee8f9b500069fb8e509157fc2aa5fad0f48e9a6d53e')
source_x86_64=("templ-x86-x64-${pkgver}.tar.gz::https://github.com/a-h/templ/releases/download/v${pkgver}/templ_Linux_x86_64.tar.gz")

package() {
  install -Dm755 "./templ" "${pkgdir}/usr/bin/templ"

  install -Dm0644 README.md "${pkgdir}/usr/share/doc/templ/README.md"
  install -Dm0644 LICENSE "${pkgdir}/usr/share/licenses/templ/LICENSE"
}

