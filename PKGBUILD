# Maintainer: archcrack <johndoe.arch@outlook.com>

pkgname=2fa
pkgver=0.2.3
pkgrel=1
pkgdesc="A little OTP keys manager written in Bash"
arch=(any)
url="https://github.com/leo-arch/2fa"
license=(GPL2)
depends=('bash' 'coreutils' 'oathtools')
optdepends=('qrencode: Generate QR code images' 'feh: Display QR code images')
makedepends=('git')
source=("git+${url}.git")
sha256sums=('SKIP')

package() {
  cd "${srcdir}/${pkgname}"
  install -Dm755 $pkgname "${pkgdir}/usr/bin/$pkgname"
}
