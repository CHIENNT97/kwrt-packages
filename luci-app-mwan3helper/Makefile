# Copyright (C) 2016 Openwrt.org
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI support for MWAN3 Helper
LUCI_DEPENDS:=+luci-app-mwan3 +pdnsd-alt +dnsmasq-full +ipset
LUCI_PKGARCH:=all

PKG_NAME:=luci-app-mwan3helper
PKG_VERSION:=1
PKG_RELEASE:=11

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
