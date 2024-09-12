# Maintainer: José Gabriel Gruber <development at jgabrielgruber dot dev>
# Contributor: thdxr (original PKGBUILD)
# Contributor: Noel Jacob (bun-bin PKGBUILD)
pkgname=templ-bin
pkgver=0.2.778
pkgrel=1
pkgdesc="A language for writing HTML user interfaces in Go."
arch=('x86_64')
url="https://github.com/a-h/templ"
license=('MIT')
provides=('templ')
conflicts=('templ')
sha256sums_x86_64=('2cb042475d8bb215b4a7b586d069f74f05ae2709266208aaf83e6d8d3fc73eff')
source_x86_64=("templ-x86-x64-${pkgver}.tar.gz::https://github.com/a-h/templ/releases/download/v${pkgver}/templ_Linux_x86_64.tar.gz")

package() {
  install -Dm755 "./templ" "${pkgdir}/usr/bin/templ"

  install -Dm0644 README.md "${pkgdir}/usr/share/doc/templ/README.md"
  install -Dm0644 LICENSE "${pkgdir}/usr/share/licenses/templ/LICENSE"
}

