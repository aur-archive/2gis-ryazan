pkgname=2gis-ryazan
pkgver=41
pkgrel=1
pkgdesc="Map of Ryazan for 2GIS, September 2014"
arch=('i686' 'x86_64')
url="http://info.2gis.ru/ryazan/products/download#linux"
license=('custom')
depends=('2gis>=3.14.7.0')
source=("http://download.2gis.com/arhives/2GISData_Ryazan-41.orig.zip")
md5sums=('ae3b07c47398780a16a98334094d21a6')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Ryazan.dgdat" "${pkgdir}/opt/2gis/2gis-ryazan.dgdat" || return 1
  
}
