

include $(TOPDIR)/rules.mk

PKG_VERSION:=1.1.2-20240822
PKG_RELEASE:=5

LUCI_TITLE:=LuCI support for heimdall
LUCI_PKGARCH:=all
LUCI_DEPENDS:=+docker +dockerd +luci-lib-taskd

define Package/luci-app-heimdall/conffiles
/etc/config/heimdall
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
