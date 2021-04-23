# Maintainer: Georg Lehmann
pkgname=gtksourceview-vulkan-glsl
pkgver=1.0
pkgrel=1
pkgdesc="Syntax highlighting for Vulkan GLSL"
url="TODO"
arch=('any')
license=('GPL')
source=("vulkan-glsl.lang")
sha512sums=('SKIP')

package() {
        mkdir -p "${pkgdir}/usr/share/gtksourceview-3.0/language-specs"
        cp vulkan-glsl.lang "${pkgdir}/usr/share/gtksourceview-3.0/language-specs"
}
