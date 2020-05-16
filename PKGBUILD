# Maintainer: Aditya Shakya <adi1090x@gmail.com>
# Contributor: Devin Collins <me@imdevinc.com>

pkgname=slim-themes-1090x
pkgver=$PKGVER
pkgrel=$PKGREL
pkgdesc="SLiM Themes desiged by adi1090x"
arch=('any')
url="https://github.com/adi1090x/slim_themes"
license=('GPL3')
makedepends=('git')
optdepends=('slim: login manager providing theme support')
source=('git+https://github.com/adi1090x/slim_themes.git#branch=master')
sha256sums=('SKIP')

package() {
  cd 'slim_themes/themes'
  install -d "$pkgdir/usr/share/slim/themes"
  cp -a * "$pkgdir/usr/share/slim/themes/"
}

# vim:set ts=2 sw=2 et:
