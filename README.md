# ipmiview
ipmiview for supermicro

# Instalation
follow instruction on https://forums.servethehome.com/index.php?resources/install-ipmiview-2-on-debian-ubuntu.30/

change `dpkg-buildpackage -us -uc -sa` -> `dpkg-buildpackage -b -rfakeroot -us -uc -sa`

OR install from .deb
`cat ipmiview_2.12.0+build160804-1~all_amd64.deb.part1 ipmiview_2.12.0+build160804-1~all_amd64.deb.part.2 > ipmiview_2.12.0+build160804-1~all_amd64.deb`
`dpkg -i ipmiview_2.12.0+build160804-1~all_amd64.deb`
