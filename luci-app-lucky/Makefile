# SPDX-License-Identifier: GPL-3.0-only
#
# Copyright (C) 2021-2022  sirpdboy  <herboy2008@gmail.com> https://github.com/sirpdboy/luci-app-lucky
# 
# This is free software, licensed under the Apache License, Version 2.0 .
#
include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-lucky
PKG_VERSION:=1.2.0
PKG_RELEASE:=11

LUCI_TITLE:=LuCI Support for Dynamic lucky Client
LUCI_DEPENDS:=+lucky
LUCI_PKGARCH:=all

define Package/$(PKG_NAME)/conffiles
/etc/config/lucky
/etc/lucky/lucky.conf
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
