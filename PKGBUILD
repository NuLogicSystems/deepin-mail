# $Id$
# Maintainer: James Kittsmiller (AJSlye) <james@nulogicsystems.com>
# Contributor: Sukanka <su975853527 [AT] gmail.com>

pkgname=deepin-mail
pkgver=5.1.0.45
pkgrel=1
pkgdesc="Deepin mail"
arch=("x86_64")
url="https://www.deepin.com/"
license=("GPL3")
groups=('deepin-manjaro')
depends=( 'qt5-webengine'  'liblockfile'  'dtkwidget')
source=("https://community-packages.deepin.com/deepin/pool/main/d/deepin-mail/deepin-mail_${pkgver}-1_amd64.deb")
sha512sums=('642a2e41883489f6606bdc3801e1f1419c928884994bad0e438e730fe58cde2ef2cf0b72c2f5b34835b586ac8ba8c7ec44743871ebb7e266159b20a14a390978')

package(){
    cd ${srcdir}
    tar -xJvf data.tar.xz -C "${pkgdir}"
    cp -f ../deepin-mail.desktop "$pkgdir"/usr/share/applications/deepin-mail.desktop
}
