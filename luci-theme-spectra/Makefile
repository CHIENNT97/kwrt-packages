#
# Copyright (C) 2008-2019 Jerrykuku
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=Spectra Theme
LUCI_DEPENDS:=+curl +jq +php8 +php8-cgi +php8-fastcgi +php8-mod-curl +ffmpeg
PKG_VERSION:=27.468.58239~3a4b5c6
PKG_RELEASE:=85

LUCI_MINIFY_CSS:=0

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
