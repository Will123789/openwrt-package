# Copyright (C) 2018-2020 Lienol <lawlienol@gmail.com>
#
# This is free software, licensed under the GNU General Public License v3.
#

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-v2ray-server
LUCI_TITLE:=LuCI support for V2ray Server
LUCI_DEPENDS:=+unzip +v2ray 
LUCI_PKGARCH:=all
PKG_VERSION:=11
PKG_DATE:=20200625

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
