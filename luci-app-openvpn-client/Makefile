# Copyright (C) 2021-2025 Lienol <lawlienol@gmail.com>

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-openvpn-client
PKG_VERSION:=20250227
PKG_RELEASE:=5

LUCI_TITLE:=LuCI support for OpenVPN Client
LUCI_DEPENDS:=+openvpn-openssl +kmod-tun
LUCI_PKGARCH:=all

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
