

include $(TOPDIR)/rules.mk

PKG_VERSION:=1.0.12-20250428
PKG_RELEASE:=9

LUCI_TITLE:=LuCI support for SysTools
LUCI_PKGARCH:=all
LUCI_DEPENDS:=+lsblk +docker +dockerd +luci-lib-iform +luci-lib-taskd +speedtestcli
LUCI_EXTRA_DEPENDS:=luci-lib-iform (>=1.1)

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature

