# Maintainer: Georg Lehmann
pkgname=gtksourceview-vulkan-glsl
pkgver=1.0.3
pkgrel=1
pkgdesc="Syntax highlighting for Vulkan GLSL"
url="https://github.com/DadSchoorse/vulkan-glsl-highlighting"
arch=('any')
license=('LGPL2.1')
source=("vulkan-glsl.lang")
sha512sums=('SKIP')

package() {
        mkdir -p "${pkgdir}/usr/share/gtksourceview-3.0/language-specs"
        cp vulkan-glsl.lang "${pkgdir}/usr/share/gtksourceview-3.0/language-specs"
}
