#
# Makefile.am for devtools/devtools/bin
#

pkgdatadir = @YAST2DEVTOOLS@/bin

dist_bin_SCRIPTS = y2tool
dist_pkgdata_SCRIPTS = 				\
	y2autoconf 				\
	y2automake 				\
	y2makepot

# This file should have 0644 perms, since it gets
# sourced by 'check-textdomain' and 'y2makepot'.
dist_pkgdata_DATA = gettextdomains

dist_control_DATA = control_to_glade.xsl
