# Contributor:
# Maintainer:
pkgname=MathJax
pkgver=3.2.2
pkgrel=2
pkgdesc="JavaScript display engine for LaTeX, MathML, and AsciiMath"
url="https://www.mathjax.org"
arch="all"
license="Apache-2.0"
source="$pkgname-$pkgver.tar.gz::https://github.com/mathjax/MathJax/archive/$pkgver.tar.gz"

package() {
	mkdir -p "$pkgdir"/usr/share
	cp -a es5 "$pkgdir"/usr/share/mathjax
	install -Dm644 LICENSE -t "pkgdir"/usr/share/licenses/$pkgname
}
